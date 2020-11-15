Big Data Analytics for Managing Risk

# 一、大数据的特点和来源
- 保险公司的传统数据一般都放在有defined field的database中，保险专业人员可通过这些数据生成报告，显示结果。风管人员也可方位保险公司的数据已生成其管理的claim报告。big data（无法使用传统方法收集和分析的data set）引入了异于传统的数据类型和数据源。
- 数据的variety, volume, source都在快速增长，如风管人员可通过sensor获取员工的安全数据，承保人可从drone和社交媒体获取风险数据，claim adjuster可通过内外部数据的pattern来更好的识别fraud。风管人员和保险人员开始和data scientist一起工作，以确定那些数据有助于business decision。

## 1. 数据的特点
- big data 隐含大量数据的意思。大数据和传统数据的区别在于volume，variety，velociy，veracity，value。
	- volume：有很多数据会available，且amount会继续增长。
	- variety：传统的保险公司使用structured data（数据可整合到有defined field的数据库中，也包括数据库间的连接），大数据也包括structured data，但大数据也可来源于多个source，其中大部分都是unstructured data（无法整合到predetermined format的数据库中，通常包括text/ image/ non-traditional media）。
	- velocity：数据到达保险公司的速度不断提高，velocity还包括数据类型变化速度的增加。
	- veracity（真实性）：指数据的完整性和准确性。unstructured big data比structured big data的准确性要低（但传统的structured data也并不完美）。但即使准确性较低，保险公司也经常可以从大数据中获取有用信息。
	- value：从数据分析中获取的价值可帮助保险公司更好做出business decision。大数据拥有add value的潜力，但必须使用能提供有意义结果的技术来进行分析（这也数data science的目标）。

## 2. 内部数据和外部数据
- data science（inter-disciplinary field，设计并使用技术来处理各种来源的大量数据，并基于数据提供knowledge）让保险公司可访问larger和more varied数据（也就是大数据）。有些数据是保险公司或风管机构直接获得的，有些是从outside source获得的。

### （1）internal data
- 保险公司拥有很多数据，也一直依赖数据。有些数据（如risk factor, loss, premium, rating factor, rate, customer information）在传统上用于做出商业决策，这些数据也会报给各州的state rating bureau。风管人员也会依赖loss和premium数据，他们也会向Occupational Safety and Health Administration（OSHA）报送safety statistics。
- 风管人员和保险人有很多未使用的内部数据（internal data，由企业拥有的数据），未使用的原因为volume或缺乏access technique。如保险公司可能不分析claimant preexisting medical condition的computer claim codes，但如果使用data science 技术分析，可能会有用。
- data science会为使用 non-traditional internal data提供技术。
	> 如voice analysis可用于识别frand相关的vocal characteristic，
	>
	> 承保人获取property photo，claim adjuster获取accident scene photo。Artificial intelligence（AI）可分析这些图片已找到human analysis忽略的信息（如建筑周围潜在的environment hazard，通过facial recognition识别accident的目击者）。

### （2） external data
- 外部数据（external data）是非企业所有的数据，企业希望获取或使用它。有时内部数据和外部数据的边界（boundary）会很模糊（blur）。
	- telematics上报的驾驶习惯信息应属于external data
	- 雇主发给员工的wearable sensor手机的信息可属于internal data（用于workplace），也可属于external data（收集的是员工个人信息）。
- 其他external data还包括
	- 顾客home或commercial building中的sensor
		
	> 若保险公司要访问顾客property的信息，必须先取得customer的同意
	
	- 无人机拍摄的catastrophe photo
		
	> regulator已同意保险公司可使用drone检查catastrphe scene，但有其他regulation要求可使用什么信息，以及如何使用
	
	- internet（social media）
		> privacy issue是从public resource（如social media）获取信息时，需要关注的legal / regulatory问题，对于data science来说尤其如此（因为data science可用于发现并分析previously unknown data relationship）。如保险公司可从内外部访问claimant的个人信息，尽管每个source自身都不违反claimant privacy，但将所有数据combining有可能会导致损害claimant privacy（这种方式是claimant not anticipated）。
		>
		>各国和各州都通过了privacy regulation，如National Association of Insurance Commissioner' Insurance Consumer 'Cybersecurity Bill of Right'
	
	- statistical plan data, aggregated insurance industry data, competitor rate filing, third-party data
		
		> 最常见的第三方数据为economic data（有关interest rate，asset price，exchange rate，consumer price index及有关全球，国家或地区经济的其他信息的数据）和geodemographic data（有关population classification的数据，属于structured data）
	- 保险公司在personal line和commercial line中还可使用credit rating（需要permitted by law）

### （3）structured和unstructured数据
- underwriter和claim用的传统数据都是structured data（在数据库中organized，且和其他数据库相连），telematic也提供structured数据（数据库中有pre-determined field来接收需要的信息，如distance traveled, braking, left turn）。
- unstructured data是not organized的，没有database可对此类data categorize，如adjuster的note（没有database可对其contained data进行分类），外部的unstructured 数据包括从网络（社交媒体）获取的数据。
- data science可用于structured和unstructured数据，但对unstructured数据更为有用。data scientist使用多种方式gather, categorize, 并analyse unstructured data（但缺点在于分析unstructured时，不知道是否会产生有用的结果）。保险公司的数据库中有众多客户数据，潜在的监管问题在于客户社交媒体信息的privacy

	| Big Data Category | structured | unstructured |
	|-----|-----|-------| ----- |
	| external | telematic<br>financial data<br>labor statistics |social media<br>news report<br>internet video|
	|internal data|policy information<br>claim history<br>customer data|adjuster notes<br>customer voice record<br>surveillance video|

# 二、Data-Driven Decision Making
- 保险人和风管人员窜同上使用数据来作决策（保险人使用自身及行业loss data来给保险产品定价，风管人员使用accident data降低loss）。data analytics可增加data type，analysis method，和使用data-driven decision making（收集和分析relevant和verifiable data，评估结果以指导business strategy的过程）的结果。
- 风管和保险人员之前依赖human analysis，computer可更多的提供loss和premium等数据（这些数据可根据business need进行细分）。data science为aggregating和analyze 数据提供了更多先进方法（advanced method）。

## 1. data science和data-driven decision making
- data science可通过data-driven decision making帮助风管和保险人员提升business result。有多种方式可实现这种improvement：
	- automating decision making（自动化decision making），以提升accuracy和efficiency
		
	> 如保险公司提供基于计算机算法（computer algorithm）的在线个人车险报价；
	
	- organize大量的新数据：保险公司可根据多种characteristic组织数据
		
	> 如telematics给出的speed/ braking pattern/ left turn/ distance traveled数据）
	
	- 发现数据中的new relationship
		
	> 可分析从没有发生workplace accident的员工的特点，并使用该信息识别如何提高所有员工的safety
	
	- 发现新数据源（data source）
		
		> 保险公司可使用text mining来分析claim adjuster note，以预测理赔severity并对其分配合适的资源。
	
- 针对所有企业，使用了大数据的公司的improvement有26%（并在未来几年会达到41%）。现在保险公司只能处理10%-15%的structured data。
- 保险公司和风险人员可获得大量他们未使用的现有数据。此外，各种来源的external data的数量也在迅速增长（如Internet of Things，IoT，向计算机传输数据的object network）。
- 保险公司和其他公司进行data-driven decision making的过程
	- 1. 使用data engineering和processing technique来管理大数据（对于conventional system too large）。
	- 2. model可在保险公司感兴趣的领域gather/ analyze数据，从而为data analytics team或需要data analysis的manager 提供结果。
	- 3. 让合适的人作出data-driven decision。
- data-driven decision making可跨领域解决多种business问题/ 增加efficiency/ 提供competitive advantage。
- data-driven decision making有两种方法：descriptive and predictive。

### （1）descriptive approach
- 当保险公司或风管人员有特定问题（sepcific problem）时，使用descriptive approach。data science使用数据以帮助解决问题，保险和风管人员在问题解决后，不会继续使用data-driven decision making（即解决一次性的问题，而不会被重复使用）。

### （2）predictive approach
- predictive approach涉及多次重复使用同一种方法，从而为data-driven decision making提供信息。
	
	> 如用计算机给每个保险申请报价，风管人员使用sensor监控员工使用safety equipment的情况，以及预测如何分配claim给adjuster。

## 2. 风管和保险的data-driven decision making model
- 遵循decision making model可帮助确保best result。
	- 第一步是define problem（这是整个data-driven decision making过程中最重要的部分，若未能clearly defined，则很可能无法make data-driven decision）。没有business context，modeling和analyzing data会无效。这一步通常会从相关business area地方工作的人员中获得信息。
	- 第二步是data（收集quality data）并确保quality，包括data selection，提高data quality，data preparation，如去掉missing/ inaccurate data，选择合适的变量。
	- 第三步是analysis and modeling。涉及big data analysis technique，descriptive model/ predictive model。风管人员和data analytics team讨论可能对分析有用的correlation或pattern。分析人员可使用cluster technique来发现数据中的pattern。
	- 第四步是insight，包括trend, relationship, behavior, event。这一步要为第二步data提供feedback。
	- 第五步是actionable decision，风管人员基于分析作出多个决策。
		
		> 具体包括risk prcing, risk selection, claim fraud detection, claim assignment, product development, risk identification, risk assessment, loss control. 

# 三、predictive model的训练和评估
- 很多公司使用predictive model（通过defined target variable来predict unknown outcome）来指导未来的business decision，如predictive modeling可帮助保险公司增加marketing（准确定位market）/ underwriting（增加policy price point的数量）/ claim（减少claim fraud）方面的consistency和efficiency。但企业对predictive model也应持谨慎态度（caution），在开发predictive model过程中，企业必须评估model的effictiveness和reliability。
- 保险和风管人员可使用predictive model来预测behavior
	> 企业可预测哪些员工可能会在工作中受伤，它就可以制定相应的策略来提高这些雇员的安全。企业可使用其拥有的过去和现在员工的数据，创建一个predictive model，该模型根据对这些员工的了解，来确定现在和未来员工发生工伤的可能性。
	> 
	>>第一步：为给出受伤和没受伤的员工的数据，如只是用过去一年的数据，同时每个员工只有15个attribute。
	>>
	>>第二步：建立模型（基于上述15个attribute），然后将该模型用于training data（用于训练predictive model的数据，所以必须是target variable的known value），从而让model更加准确。将模型投入生产环境，进而对员工进行真实预测。此时要找出为什么在培训环境中有效的模型，在生产环境中不再有效。
	>>
	>> 第三步：有可能是model was tailored too closely to the training data. 这种错误可通过重新评估最初保存的一些训练数据，或通过applying performance metrics to model before moving into production 来避免。

## 1. training the model
- 可使用target variable（在分析模型中中需要预测的某些predefined attribute）的known value来训练predictive model，同时也要确定class label（模型中target variable的value）。
### （1）training data
- attribute（用于描述model中instance（也称为sample，data set中一组描述数据点）特点的变量）的选择决定了predictive model是否能成功，且这种selection必须微调几次（fine-tuned several times）。模型必须足够复杂以保证准确性（过少attribute无法准确描述，过多使用attribute会导致模型overfit）。
- 当model过于tailored to training data时，会发生overfit（fitting model too closely to training data，导致model对其他数据无效）。

### （2）holdout data
- holdout数据可用于检验两个变量间的correlation是否显著（significant）或异常（anomaly）。
- holdout data是training data中保留的数据（与training data一样，holdout data也有model target variable的known class label）
  - holdout data适用于test predictive model，以确保其在未用于model development的data上依然表现良好，从而帮助确保model没有overfitted to training data
- 若holdout data 可展示出predictive model中两个变量的相关性，则说明model可以generalization（模型可在training data外使用）。
- 模型必须具有一定的复杂性才能准确，但如果模型过于复杂(即overfitt)，则其准确性将无法用于training data之外。

### （3）cross-validation
- 有时，使用holdout data也无法确保model能很好地用于生产环境（导致的原因包括可用的training data非常有限，或model developer认为不需使用某些数据）。此时可使用cross-validation解决这个问题。
- cross-validation是将available data split into multiple fold，然后使用不同的data fold训练模型并完成holdout test。所有的数据都以两种方式使用，predictive model也可使用多种方式开发，从而允许开发人员选择perform best的version。之后再用全部dataset对selected model进行训练。

## 2. evaluating the model
- 在开始使用predictive model前，应使用未训练的数据对其effectiveness进行评估。在training和test步骤后，应进行evaluation。

### （1）performance metrics
- 很多metrics可用于评估model performance。performance metrics可通过confusion matrix（该矩阵表示predictive model在dataset上的结果）理解。
- 具体的评估方法包括：
	- accuracy：简化的方法，评估多久会有一次正确的model predict。
		
> accuracy = model correct prediction/ total prediction = 预测准确且positive + 预测准确且negative / 总预测数

	- precision：不看model的total result，precision只衡量 positive result，通常比accuracy更能衡量模型的成功率。
	
	> precision = correct positive prediction / total positive prediction = 预测positive且正确 / 预测为positive的总数字
		
	- recall: 用于衡量模型在catch positive result 方面做得有多好（how well）
		
	> recall = correct positive / (correct positive + incorect negative) = 预测准确且positive / (预测准确且positive + 预测错误且negative)
		
	- F-score：较流行的方式，考虑了precision和recall两种方法，要先计算precision和recall。
		
		> F-score = 2 * [(precision * recall) / (precision + recall)]

### （2）将model放进生产环境
- predictive model放入生产环境（用于日常运营），training process仍会继续（只是证明了model的价值）。若model无法知道好的business decision，则要对model重新进行评估。
- 保险和风管人员应使用专业经验检查model result。
	- 若model result看起来没意义，则模型有可能overfit或不够复杂。
	- 但情况也有可能变化，没有一种predictive model能无限期地做出准确预测（make accurate prediction indefinitely）。
	- 当发生重大的经济/技术/文化变化时，应与data scientist或精算师合作，更新prediction model并对其进行re-train，从而提供最佳结果。

# 四、Big Data Analysis技术简介
- 大部分保险和风管人员不会直接使用data analysis技术，但underwriter/ claim/ risk manager应对这些技术有基本了解。大数据和新技术正在扰乱保险业，保险和风管人员应熟悉大数据的概念及分析方法。了解大数据如何与技术interact，及如何提供新信息，将为保险公司和希望提升职业素质的专业人士带来竞争优势。
- 传统的data analysis仍很重要（这些技术对现有的保险和风管仍然有效，这些技术也会用于分析大量数据，以及来自非传统来源的数据（如social media的数据））。保险和风险管理专业人员应对传统技术有了解，原因如下：
	- 首先，这些技术在提供信息和解决业务问题方面仍然很重要。
	- 其次，它们是新技术的基础。对于专业人员来说，了解一些更新的技术，以便能够在团队中与data analyst一起工作，并更好地理解保险的真实情况。

## 1. data analysis技术简介
- 在data analysis中，有两种主要的方法：supervised learning和unsupervised learning
	- supervised learning是machine learning中派生出的一种model creation，其定义了attribute和target variable
		
		> 计算个人车险保费时，使用defined variable（age, driving experience, accident record等）来决定defined target variable（车险保费）
		
	- unsupervised learning是machine learning中派生出的一种model creation，其未定义target variable
	
	  > 在开发新产品中使用社交网络的数据，就要用到无监督学习（attribute未知，也没有target variable，model会寻找relationship，之后在进行分析）
	
- 各种技术通常会有inter-relationship

  > 通过unsupervised learning获得信息后，可开发predictive model，用获取的信息来进行supervised learning
## 2. exploratory data analysis
- 可在开发和测试模型前使用exploratory data analysis。exploratory data analysis提供的信息可为data提供基本的理解，analyst也可获得missing/ inaccurate data的信息。
- exploratory data analysis涉及的技术包括可显示data pattern和correlation的chart, graph。
	- exploratory data analysis包括scatter plot（two-dimensional plot），bubble plot，correlation matrix
		> scatter plot（two-dimensional plot）会显示出两个attribute的关系。
		>
		> bubble plot是scatter plot的另一种类型，bubble size代表第三个attribute
		>
		> correlation matrix：可先确定几个attribute，并想知道它们是否和target variable有关。可开发predictive model来识别最有可能给target variable有贡献的attribute。相关性越强，matrix中的cell color越深。matrix中，颜色越深的组合说明这种attribute的组合和结果越相关。

## 3. data analysis技术
- exploratory data analysis完成，并决定开发predictive model后，analyst将为model选择最合适的技术（模型要适合business context，data type和data source）。这些技术在不断发展，有些常用的技术可根据不同情况进行调整，如segmentation（data 被分为不同的category）可用于supervised learning和unsupervised learning。
- 大部分技术都会使用machine learning（随着收到additional data或result，computer会继续refine model）。
	- association rule learning（examining data，以发现attribute间的新关系，进而state as business rule）涉及unsupervised learning（computer使用各种algorithm，以发现large amount data间可能有用的关系，并开发可用于new data的rule）。

		> 当人们在网上购物时，retailer常使用association rule learning推荐其他产品。如有人买了一本关于电脑的书，零售商很可能会给他发邮件，向他推荐更多的电脑书籍。同样，当顾客选择了要购买的商品并在结账时，retailer可能会推荐一个类似的商品。
		> 
		> 客户在网上购买汽车保险和房屋保险时，保险公司可使用association rule learning推荐umbrella policy。

### （1）传统的data analysis技术
- 保险公司和风管人员会依赖传统数据分析技术来解决business problem（如确定保险产品保费和unpaid claim reserve）。这种技术通常用于structured data（如loss cost by claimant, type of injury），有时也使用external structured data（如每月的gross domestic product）。

- 保险公司和风管人员通常想用传统data analysis确定以下结果：
	- 数据属于哪个non-numerical category，
		
	> 保险公司想知道车祸是否涉及人身伤害或只是财产损失，或风管人员想知道雇员是否发生过事故。
	
	- 基于数据的numerical answer
	
	>保险公司想分析在线申请时输入的数据，从而决定保费。
	
- 基于历史数据的probability score
		
	> 风管人员想确定safety solution降低事故frequency的概率，或保险公司想确定被保险人发生catastrophic loss的概率。
	
	- 基于现有及过往数据预测future loss
		
		> 保险公司想知道一条line的ultimate cost，风管人员想预测员工back injury的cost。
	
- 传统的data analysis技术包括classification tree，regression model，cluster analysis。这些技术开始使用machine learning来增加其结果的准确性。
	
	- ==classification tree是使用类似于tree的结构，根据known attribute来segment data，从而确定categorical target variable的value（可用于确定workplace accident的probability）==
		- classification tree：使用data analysis解决问题时，data必须有certain characteristic才能有用
		- ==classification tree属于supervised learning==
		- classification tree包括
		  - nodes（data attribute）
		  - arrow（classification tree中的pathway）
		  - ==leaf nodes（classification tree上的terminal node，可根据attribute classify instance，表示target variable的值）==
		    - 每个sample的attribute将跟随arrow穿过leaf node，这些leaf node根据attribute将数据分割到一个ultimate leaf node（标记为return to work或not return to work）。这些分类并不一定是actual outcome。
	- regression model是当需要知道target variable的numerical value时，需要用到math function创建algorithm
	  - algorithm是用于解决数学问题并创建computer program的operational sequence）。
	  - linear regression是根据explanatory variable来预测target variable值的统计方法
	    - linear regression使用minimize the error（target variable的actual value和forecast value的差）。
	  - generalized linear model/ GLM是将linear regression与non-linear function连接起来，以增加flexibility。该技术需与general linear model（一组不同类型的linear model）区分开来
	    - GLM包括三个部分（random component，systematic component，link function）
	      - random component是response variable的probability distribution
	      - systematic component是描述explanatory variable (attribute)间的linear combination
	      - link function是一种数学函数，描述target variable的random value依赖于explanatory variable linear combination产生的mean value。将random component和systematic component联系起来。
	- cluster analysis是确定previously unknown grouping of data的model
	  - cluster analysis属于unsupervised learning
	  - cluster analysis适用于知晓想解决的问题，但不知道需要分析哪些的variable的情况
	  - 可开发model来分析dataset，结果可能是围绕explanatory variable的某个特定值
	  - cluster analysis获得的信息可用于开发predictive model，model也可使用其他supervised learning技术。

### （2）新的data analysis技术
- 大数据和新技术的融合让data scientist能分析数据并提供有意义的信息以指导business strategy。data analytics能处理大量的数据，也能快速增加data velocity。另外，也需要新的分析技术来分析textual/ social network data。人工智能（AI，计算机的processing或output模拟human reasoning或knowledge）可对visual image data和auditory source data进行更好的分析。大数据以及通过新技术产生的数据通常是unstructured，所以需要新技术来分析。
- 新的data analysis技术包括text mining，social network analysis，neural network。
	- text mining：从language recognition中获取信息
		
	> text mining随着互联网和social media的增长而变得更加普遍。分析文本的model比分析其他数据的model更为复杂（因为没有organized field，通常也没有numerical value，如对claim adjuster的note进行分析）。一种方法是搜索既不rare也不common的词。 另一种方法是查找adjacent word。
	
	- social network analysis（network analysis）：研究网络中人之间的connection和relationship。
		> 网页中蹦出的广告基于人的兴趣算出（根据社交网络的preference或association）。社交网络分析不知用于社交媒体，也可用于business network setting（如email traffic between people，links between webpage）。
		>
		> social network analysis在识别claim fraud ring中非常有效。有些保险公司会使用社交网络的数据预测fraud probability。
	
	- neural network：用于解决复杂问题。由三层组成，包括input layer，hidden layer（有non-linear function），output layer。
		> neural network属于data mining中的新技术。按人脑的方式从data pattern推断rule，然后构造用于分析的logic。
		> 
		> neural network会产生一个包含layer of node的模型，node之间有weighted link。neural network技术可用于supervised learning和unsupervised learning。
		>
		> neural network可在input和output variable中建立复杂的关系
		>
		>neural network的缺点：
		>> neural algorithm建立的rule和logic是不透明的（opaque）。
		>>
		>>很难解释从weighted link中获取的信息。
		>
		> neural network的无限可能性导致学术界和business努力改进开发和处理相关的计算机软件。
# 五、在claim中使用classification tree analysis
- complex claim：包含一个或多个characteristic，这些characteristic可导致cost大于平均claim cost。
- 保险人想把complex claim(但第一次report的时候很难分辨是否是complex claim)在更短时间内分配给有经验的理赔人员，同时给他们足够的资源。
- information gain：衡量一个或多个attribute的predictive power。
- recursively是Successively applying a model（连续应用模型）
  - computer recursively是为了分析attribute value中的different split
- classification tree中的顺序并非一定按照information gain的顺序，因为information gain的排序是对每个attribute单独进行分析，但classification tree中每个node都要基于其本身和上层的attribute一起分析。
  - root node是classification tree中的第一个node（最重要的information）
  - combination of node是classification tree中的data attribute
- lift是在model performance evaluation中，用于衡量predictive model effectiveness的关键指标。lift基于model的accuracy和precision。
	- lift = (model给出的positive prediction)% / (没有model时（expected by change）的positive prediction)%
- 开发predict complex claim model的步骤
	- 从training data确定complex claim的attribute
	- 对每个attribute的重要性进行排序
	- data science team决定要使用的data analytics技术
	- 根据重要性，确定model中attribute的weight
	- 开发好model后，用holdout data测试。