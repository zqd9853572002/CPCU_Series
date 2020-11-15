Risk Analysis

# 一、risk analysis简介
- risk analysis可为understanding risk以及为risk treatment decision提供信息。==risk analysis考虑identified risk的source和consequence，在考虑consequence时，企业需知晓风险的potential effectiveness，每种consequence的可能性，以及现有control的effectiveness。有了这新信息后，企业可以决定risk level。==

## 1. risk analysis的本质
- 作为overall risk analysis approach的一部分，企业应分析potential event/ product line/ project/ process的risk。对于已识别的风险，企业应注意可能的consequence（风险如何影响企业实现其目标，包括积极和消极方面）和对应的probability。
- 不太可能或不重要（unlikely or insignificant）的identified consequence，不需要进行太多分析。相反，single event可能引发多个far-reaching (深远) 的后果，这些后果可能会影响企业的多个目标。对于更复杂的结果，可使用多个分析方法来确定其risk level。
- 有些risk analysis聚焦于特定事件的consequence（如hurricane/ power failure），有些risk analysis聚焦于process（product manufacture，关注流程中的每一步）或system（automated inventory tracking，关注系统中的每个component）。

## 2. qualitative assessment和quantitative analysis
- risk analysis可以是qualitative，quantitative（取决于risk type，data available和企业需求），也可以两者合并在一起。
	- ==qualitative assessment（定性评估）：测量风险consequence的严重程度（high/ medium/ low）==，在qualitative assessment中，应包括对定性的基础 (agreed-on basis) 进行明确的书面解释（clear and written explanation）
	- ==quantitative analysis: 通过历史数据，为每个consequence和probability分配value，从而给出risk level的indication。这种方法对缺少历史信息或数据的风险或有其他uncertainty的风险无效==。这种情况下，企业可使用定性+定量结合的方式。
- 定性和定量分析均需对风险的probability进行估计。==probability可基于与所分析风险类型相关的历史数据。若类似事件很少发生，或缺乏历史数据，则由此产生的probability estimate是不准确的（uncertain）。这种情况下，企业可使用prediction（估计）或expert opinion来估计probability。predictive technique（如decision tree analysis和event tree analysis），会将数值赋给风险相关的各种component，并将它们combined来生成probability estimate==。有些structured process会和expert opinion结合来进行风险的probability estimation。

## 3. assessing control
- ==为准确确定 risk level，企业必须检查现有risk control measure的有效性（effectiveness），即所有用于控制特定风险的方式。企业应确认每种风控方式可达到其intend level，以及是否有效。verification取决于相关风险control performance的record和document。==
- control assessment可以是quantitative和/或qualitative。此类信息尽管不是detailed，但仍能帮助企业决定是否继续维持现有的control/ improve control/ 或用其他方式替代它。

# 二、Probability Analysis
- ==Probability Analysis是研究某事件的probability，即该事件在长期稳定环境（long run in stable environment）中发生的相对可能性(relative likelihood, frequency)，需要有大量数据做基础。==
- 事件会导致一系列后果(consequence，severity)，每个后果都具有probability of occuring。概率相关的概念包括：theoretical probability（理论概率），empirical probability (经验概率)，law of large number（大数法则）。
- probability distribution可建立theoretical probability和empirical probability。==probability distribution提供的信息可帮助分析loss exposure，评估风险positive/ negative consequence，并做出risk managment decision. ==

## 1. probability的本质
- ==任何probability都可以表示为fraction (1/2) / percentage (50%)/ decimal (0.5)。==
	
	> 不可能事件的概率为0，确定时间的概率为1，所以==概率的范围为 0<p<1==. 

### （1）theoretical probability和empirical probability
- 概率可用theoretical data distribution或用historical data得到。
	- ==theoretical probability是基于theoretical principle（理论原理），而非基于经验的概率，其值保持不变，如抛硬币。==

	- ==empirical probability（posteriori probability）是基于historical data或fact observation的实际经验得到的概率。==
		> ==该probability无法从理论获得，而只能从研究sample loss experience获得==
		>
		> ==这种从历史获得的概率，可能会随着新数据的发现或产生，以及事件环境的变化而变化）。==

- 尽管theoretical probability因其不变的性质而更可取，但对于保险和风管人员分析的风险，theoretical probability不适用或不可用。因此，必须使用empirical probability。

### （2）大数法则（law of large number）
- probability analysis：forecast event的技术（如用于accidental/ business loss），其假设不变的probability distribution。
	- ==该方法可有效预测企业的loss或gain的likelihood和consequence，但需要企业拥有大量past loss/ gain的数据，也要有fairly stable operation（即loss/ gain pattern可持续下去）。==
	- ==对于unchanging environment，企业过去的loss/ gain可看作是企业未来所有loss/ gain的sample。==
- ==一个组织过去经历的损失越多，可以用于分析的损失样本就越大。因此，对未来损失的预测更可靠(随时间的推移而一致)，因为预测是基于产生损失的环境的更大样本。这是大数定律的应用，也适用于gain和其他情况。==
- ==大数法则：随着sample size 增加，empirical frequency和theoretical probability之间的差距会下降。==
- ==大数法则的缺点：只有满足如下情况时，大数法则才能用于预测未来事件==
	- ==这些事件在过去是在相同condition (unchanging, basic causal force) 中发生的==
	- ==事件会在未来同样（unchanging condition）的情况下继续发生==
	- ==事件是相互独立的（independent），且有sufficient numerous。==

## 2. Probability distribution
- ==大部分风管人员做的工作都属于empirical probability distribution==（对一组特定情况的probability estimate和每种outcome的概率的展示(表、图表或图形)）。
- ==一个合理probability distribution应该包括所有的结果（即collevtively exhaustive，不会再有其他情况），且各个结果都是mutually exclusive（即所有的概率相加为1）。==
- ==probability distribution分为discrete和continuous。==
	- ==discrete probability distribution：有限个可能的结果，通常可以table或list的方式列出所有的结果和每个结果的可能性==。该类分布会有有限个结果（contable number of outcome）。可用于分析多久时间会发生一次，即frequency distribution。==可用于分析worker compensation的loss frequency==
	- ==continuous probability distribution：有无限多个possible outcome，通常会用line graph表示==。该分布中，outcome显示在水平轴（horizontal axes），结果可能性（probability）显示在垂直轴（vertical axes，具体表示为在结果之上的直线或曲线的高度）。continuous probability distribution的结果称为probability density function（概率密度函数）。continuous probability distribution常用于描述事件的结果（描述损失或收益的值的，而非结果的数量）。==continuous probability distribution有无限个可能的结果，但任何given outcome概率都是0（因为存在无限个其他结果）。风管人员可通过将continuous distribution分成若干个bin来计算结果落在一定范围内的概率。==

# 三、probability distribution的特点

- 在分析probability distribution时，风管人员会考虑expected value, means, standard deviation, coefficient of variation, normal distribution。
- 在确定empirical probability并建立probability distribution后，风管人员应使用central tendency（probability distribution中最能代表所有可能结果的单个结果）和dispersion（分布中，variation of value）来比较概率分布的特点.
	- ==central tendency（probability distribution中最能代表所有可能结果的单个结果）：即对结果最好的猜测==。许多probability distribution围绕一个特定值，这个值可能在distribution的exact center（也可能不在）。==可通过expected value和mean来衡量central tendency。==
	- ==dispersion描述的是分布在expected value周围（而非聚集在expected value周围）分散的程度。可使用standard deviation和coefficient of variation描述dispersion。==
- 有些distribution有正态分布的特点（normal probability distribution），这对预测future loss有用。

## 1. expected value
- ==expected value：概率分布中所有可能结果的加权平均值（weighted average），可通过weighting和average outcome衡量central tendency的程度==。weight是某个结果的概率。可能的结果用$x_n$表示，概率用$p_n$表示==。
	- ==一个分布的expected value等于$\sum_1^n(p_n *x_n)$==
- ==expected value的计算适用于所有theoretical discrete probability distribution（无论其形状或dispersion如何）==。而对于continuous distribution，expeted value也是结果的加权平均值，但较复杂，不做讨论。

## 2. mean
- ==mean是数据和（sum of value）除以数据量(number of value)==。
	- ==在theoretical distribution中，需使用probability计算expected value；==
	- ==在empirical distribution中，需使用mean计算expected value，可通过每个结果的weighting和frequency，之后再除以number of outcome value来计算mean。==
- ==mean = sum of value/ number of value==
- 当underlying condition不变时，mean才能良好估计expected outcome。mean来源于经验，若产生experience的环境（condition）改变，则mean无法准确估计central tendency。尽管如此，风管和保险人员仍会将mean作为single best guess来预测未来事件。
	
	> 企业下年度worker compensation的claim number通常是前几年事件frequency distribution的mean。

## 3. standard deviation
- ==风管人员可通过衡量分布的dispersion来更好地理解loss exposure。standard deviation（通过计算variance的square root，求出value和expected value(或mean)的dispersion）可衡量分布中value的离散程度（how widely dispersed）。==
- ==standard deviation越大，则value越desperse。==

## 4. coefficient variation
- ==coefficient of variation（通过standard deviation除以mean或expected value，来计算dispersion）是另一种衡量分布dispersion的方式。==
	- ==coefficient of variation = standard deviation/ mean (expected value)==
	- ==若两个分布的mean（expected value）相同，则使用standard deviation（standard deviation越大，其variability越大）==
	- ==若两个分布的mean（expected value）不同，则使用coefficient of variation，coefficient of variation越大，则dispersion或variability越大。==
- ==风管人员可使用coefficient of variation确定loss control措施是否让能让损失more predictable或让损失less（即分布是否更variable或less）。coefficient of variation越大表明loss更难以predict。==
- coefficient of viriation可用于比较有不同shape/ mean/ standard deviation的分布的variability。coefficient of variation越大，则dispersion或variability越大，继而会导致准确预测单个结果的难度越大。

## 5. normal distribution
- ==normal distribution画出来后的形状为bell-shaped。其属于theoretical distribution，可精准预测central/ average/ expected value的variability。==
- ==normal distribution的curve永远不会触达水平线（x轴）（即normal distribution中每个结果的概率都大于0，不管这个结果距离mean有多远）。mean左右的概率各为50%==
	- 正态分布可给出一定标准差内（高于或低于分布平均值）的结果的可能性百分比
		> 68.26%的结果会落在1个standard deviation的范围内(above and below the mean)
		> 95.44%的结果会落在2个standard deviation的范围内(above and below the mean)
		> 99.74%的结果会落在3个standard deviation的范围内(above and below the mean)
		>
		> | 左边4标准差 | 左边3标准差 | 左边2标准差 |左边1标准差 | 右边1标准差| 右边2标准差|右边3标准差|右边4标准差
		> |-| -|- | - | - |-|-|-|
		>| 0.13 | 2.15 |13.59|34.13|34.13|13.59|2.15|0.13

## 6. normal distribution的应用

# 四、Trend Analysis
- ==风管人员使用trend analysis来预测loss/ gain, 这种forecast可帮助企业管理层作出cost-effective的风管决策。==
	- ==企业使用trend analysis（识别past data中的pattern，并使用这种pattern投射到未来（project to future））识别环境中的pattern change，并从pattern变化中发展forecast。==
	- ==regression analysis（用以估计variable间的关系）通过衡量影响trend的variable来提高forecast的准确性，如某变量的变化和其他变量相关，可据此来提高对原变量的预测准确性。==
	- ==企业可使用trend analysis和regression analysis来detect和forecast pattern。==
- 企业对面临的风险和gain作出预测。风管人员会研究过往数据，并将这些数据进行probability analysis和/或trend analysis，以预测未来的expected value。预测结果可帮助管理层决定每种alternative的cost and benefit并选择benefit最大（cost最小）的那个。
- trend analysis通常使用inflation rate调整forecast future dollar amount（如通货膨胀会导致physical damage loss的future cost上升）。

## 1. regression analysis
- ==regression analysis假设因变量（dependent variable，被预测的变量）可使用自变量（可预测因变量的变量）进行预测。==
	
	- ==Linear Regression Analysis（假定因变量的变化对于自变量的变化在每个单位都是恒定的）处理constant rate of change，即regression line是直线的（straight, linear），而非弯曲的（curve）。==
- regression analysis的目标是找出最符合历史数据的线，并用这条线预测未来的损失。
- regression analysis的步骤为使用plot data point并绘制一条approximate line。草图有助于直观地估计线性回归线的两个决定因素。
	- 第一个决定因素是线与y轴相交的点（y-intercept，x=0时，y的值，即每个点上都会发生的损失）。
	- 第二个决定因素是线的斜率（slope，即 y随x的单位增加而增加或减少的数量，斜率可正可负）。
	- intercept和slope决定直线。这个步骤通常由计算机软件或calculator完成。
	- 线性回归公式为 $y = bx+a$
		
		>y是因变量，x是自变量，a是y上的intercept，b是slope
	- ==需要注意的地方：==
		> ==当回归线与实际使用的数据值相去甚远时，可能变得不准确（使用此趋势线来预测近几年的损失是可行的，但要估计未来20+年的损失则会不准确）==
		>
		> ==对于任何过往数据，线性回归的线计算出的因变量值不会完全等于该年的实际历史值。任何regression line只代表straight或smoothly curved line对过去几年的实际历史数据的“best fit”。任何projected trend value都可能不同于actual outcome，actual value和projected value的差异也有不同。==

## 2. regression analysis案例
- 风管人员可使用多个自变量，并将其应用到线性回归线上。任何reasonable causative measured 的variable都可成为预测因变量的自变量。如可将货运量，天气条件，价格水平等作为自变量，然后预测未来一年的损失。
- 有时会用到curvilinear regression，用于测量自变量和因变量的关系和加速程度（accelerating/ decelerating rate），此时回归线不是直线。
- 只有在underlying assumption valid时，forecast才能被接受。
	- trend analysis在预测未来loss/ gain时很有效，但其结果必须interrupted with reason，而不能直接接收其结果（因为regression属于纯数学方法）。
	- 损失数据稀缺使得对accidental loss的预测更加困难。

# 五、分析event consequence
- 应对occurrence的action会产生多种consequence或payoff。企业可使用decision tree analysis和event tree analysis来预测consequence的likelihood和severity。
	- ==decision tree analysis会检查决策的各种consequence（包括cost, gain），企业可使用decision tree来比较各选项，从而选择最有效的strategy。==
	- ==event tree analysis会检查accident event的所有可能结果（包括probability，现有的预防或control的措施）。企业可使用event tree来检查系统的effectiveness, risk treatment, risk control measure，从而identify, recommend, justify 各项成本（money, time, resource for improvement）。==

## 1. decision tree analysis
- decision tree会分析decision outcome的uncertainty。企业用decision tree，从多个选项中选择最佳行动方案，或管理与项目相关的风险。通过分析各种选项和可能影响它们的事件，从而可以减少决策中的不确定性。
- decision tree可使用定性或定量分析。
	- 定性分析可帮助了解decision可能产生的scenario, progression, consequence。
	- 定量分析可估计各项决定导致的scenario的probability和frequency。
- ==decision tree的起点为正在考虑的initial decision（如要开发两种产品中的哪一种）。从这点出发，为每种选择绘制event sequence（path）；每个path都会有对应的outcome。定量分析中，为每个pathway上的event分配probability，并估算每个结果的expected value（cost或gain）。比较pathway中每个事件的概率与其结果值的乘积，确定能产生最高expected value的pathway。==
- 优点：可对event sequence和outcome提供visual portrayal，可通过计算得出best pathway。
- 缺点：涉及复杂或众多问题的decision tree会非常复杂，从而在information communication方面ineffective。若decision tree过于简单，则会降低resulting decision的有效性（effectiveness）。

## 2. event tree analysis
- event tree analysis分析accident event的consequence（decision tree分析decision的结果）。accidental event是第一个significant deviation from normal situation（第一个偏离正常情况的事件），其会导致unwanted consequence。
- 和decision tree一样，event tree也有定性和定量分析。定性方面，他可帮助产生accidental event导致的scenario, progression, consequence. 定量方面，他可预估各种scenario和outcome的probability和frequency，从而帮助企业确定control和safeguard措施的有效性或必要性。event tree用于确定risk treatment method的需求（neeed）和有效性（effectiveness）。
- ==event tree的起点是识别accidental event。之后决定accidental event会导致什么后续事件（progression）。各种progression会受各种因素（other system, human response, weather, performance, failure of barrier）影响，进而导致各种不同的结果 (alarm/ detection system, emergency procedure, other control measure)。==
	- ==progression的分析会列出initial event会导致的一系列潜在consequence的list，以及每个consequence的barrier，继而发展出event tree diagram。==
	- ==barrier按事件发生后的激活顺序列出，在每条pathway中，每个barrier都会有两种可能（function/ fail），所以pathway会分为两条路，每条路都会有相应的probability（由专家或其他分析给出）。==
	- ==每条pathway的probability是所有事件发生的可能性（乘以每个pathway上事件发生的frequency，且的关系）。所有事件probability的和应该为1。==
- 优点：可对event sequence和outcome提供visual portrayal。特别是其可说明accidental event后control system的有效性（考虑了time, 其他contribution factor，domino effect）。
- ==缺点：只提供了两个可能（成功或失败），从而无法反应有些progression的复杂性。另外，有些对结果有影响的factor可能会被忽视（overlook）。==

## 3. decision tree analysis 和event tree analysis的对比
- decision tree analysis 和event tree analysis有类似的approach, appearance, process，但他们的purpose, information used/ produced, other factor不一样。
- 对比表

# 六、分析loss exposure

- 对loss frequency, severity, total dollar loss, timing进行分析可帮助风管人员完成loss projection，协助他们对loss exposure 进行排序，进而将风管资源放在最需要的地方。
- ==风管流程中的分析步骤包括loss exposure的四个方面：==
	- ==loss frequency：一定时间内的loss number==
	- ==loss severity：某个occurrence导致损失的dollar amount==
	- ==total dollar loss：一定时间内所有occurrence导致的total dollar amount==
	- ==timing： loss occurrence和loss payment之间的时间==
- 如果对上述四个方面的分析需要使用past loss进行empirical distribution，并确定所用数据的可信度（credibility）。data credibility是衡量可用数据是否可用于未来损失预测的level of confidence。

## 1. loss frequency
- loss frequency是一定时间内的loss number。relative loss frequency是特定时间内发生的损失数量除以number of exposure。
	- 风管中最常用的relative frequency是
		> worker compensation中injury per person per hour
		>
		> auto accident per mile driven

- frequency distribution 通常是基于过往数据的discrete probability distribution（即how often similar event have happened）。
- 大公司可以很高的confidence来进行预测loss frequency (如在预测transit loss方面，每天运送几千个包裹的公司，比每天运送几百个包裹的公司要准确的多）。
- 很多公司没有足够的exposure unit来准确预测low frequency + high severity的事件，但可以估算margin for error（这也比完全没有estimate强，只要能认识到相应的limitation）。

## 2. loss severity

分析loss severity的目的在于确定loss有多严重（如多少建筑会毁于一场火灾，或企业需要多长时间才能从火灾中恢复）。

### （1）Maximum Possible Loss （MPL）

- 有效的风管会识别loss带来的最坏情况（worst possible outcome）。==maximum possible loss（MPL）是在在任何地点或在任何事件中遭受损失的总价值（total value exposed to loss）。==
- 为决定MPL，风管人员需考虑单一event会导致的全部损失。
	- MPL有时无法估计出最大的liability loss：==理论上liability loss的上限为defendant total wealth，MPL在预估责任损失时，必须对liability案件做出一些practical assumption以正确评估损失风险。通常假设为，95%-98%的类似情况下，liability损失的最大金额是MPL，而不是defendant's total wealth。==

### （2）合并考虑 frequency和severity
- ==为全面分析特定损失的严重性，需要综合考虑severity和frequency，以及他们的interact。==
- ==综合考虑的一种方法为Prouty Approach（可识别loss frequency的四种类型和loss severity的三种类型）。==
	- ==loss frequency分为四类：==
		
		> ==almost nil: 非常不可能发生（no possibility）==
		>
		>==slight: 可能发生，但仍未发生==
		>
		> ==moderate：偶尔发生==
		>
		> ==definite：经常发生==
	- ==loss severity 分为三类：==
		> ==slight: 企业可retain这种loss exposure==
		>
		> ==significant：企业无法retain风险，有些exposure必须financing==
		>
		> ==severe：企业必须financing所有loss exposure，否则会危机企业survival==
	
	- ==上述frequency和severity的分类都是主观的（subjective）==，但仍可帮风管人员对loss exposure进行排序。
	- ==风险的frequency和severity倾向于反向相关（inversely related），即严重损失不太可能会发生，或随着frequency增加，loss severity会逐渐减小。==
	- 企业通常会使用budget自留definite but minor loss（high frequency + low severity），极端情况下，企业要avoid能产生intolerably large loss的风险。所以==大部分风管决策都关注让significant/ severe的事故的发生率降为moderate/ slight/ almost nil。==
- 某个loss exposure可能会产生重大的financial significant loss（因为high loss severity, 或high frequency + low severity loss的堆积效应）。企业可能会关注“shock event”（如重大事故，爆炸或巨额liability claim）。但若小损失经常发生（有时会称为routine loss），其最终产生的total loss会远远大于single event loss。minor/ cumulatively significant loss应引起风管人员的注意（和large individual loss一样）。
	
- ==另一种方法为将frequency和severity distribution合并为一个total claim distribution，从而对特定时期内的potential loss提供更多信息==。combining distribution会比较困难，因为随着possible outcome增加，frequency和severity的组合指数增加（increase exponentially）
	
	- total claim distribution可用于计算central tendency和dispersion，可评估各类risk control和risk financing的效果。

## 3. Total Dollar Loss
- 可通过loss frequency和loss severity相乘得到total dollar loss。total dollar loss是frequency和severity混合的简化版，可用于分析有多个possible outcome的情况。
- expected total dollar loss = expected loss frequency * expected loss severity
- ==计算worst case scenario时，worst total dollar loss = highest frequency * highest severity, 其中highest frequency的发生率过低时（如小于等于0.01），则使用倒数第二高的frequency。==
- 这些estimate可用于管理loss exposure，如评估是否购买保险。

## 4. Timing
- ==risk assessment不仅要考虑损失什么时候发生，还要考虑loss什么时候支付。time dimension很重要（用于支付损失的金钱 hold in reserve时可赚取interest，直到其被支付出去）。timing对于accounting 和tax也很重要。==
- 支付property loss的金钱通常在损失发生后很快就会支付出去。但是liability loss通常会有long delay（event occurrence -> occurrence recognized -> period of possible litigation -> payment actually made）。对于涉及environment或health相关的风险，这种delay可能跨越几十年。delay会增加loss amount的不确定性，但它也会让reserve在这段期间内赚取interest或investment income。

## 5. Data Credibility

- 分析完上述loss exposure的维度后，风管人员需评估预测的credibility。==data credibility指available data可准确预测future loss的confidence level。data age和data是否可代表actual loss/ estimate of loss会影响data credibility。==
- 有很多内外部因素会影响data credibility。
	- 内部来看，企业的运营方式的改变（如对制造过程的改进，或data collection方式的改变）会严重减弱过往收集到的数据的credibility。
	- 外部来看，自然灾害，large liability award，恐怖袭击等不仅会改变收集到的数据，还会引起运营环境的改变，进而削弱已收集数据的credibility。
- ==理想状态下，产生数据和预测数据的环境应该相同。但是，大多数情况下环境都会改变（即使这种变化很慢）。与旧数据相比，不断变化的环境会使更多新数据成为future loss更可靠的预测指标。但由于report和paying for claim的延迟，recent data并非是actual loss（而是对最终损失的一个估计）。==
	- ==这使风管人员陷入dilemma，即是使用older data（这些数据是准确的，但可能其生成环境和要预测的环境不一样），还是使用recent data（牺牲掉一些准确性，但能更加保持前后环境一致）？==
- 对loss exposure的四个维度作出预测后，下一步就要确定要使用哪种risk control或risk financing措施。