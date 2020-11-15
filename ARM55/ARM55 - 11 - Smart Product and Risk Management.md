Smart Product and Risk Management
# 一、Smart Product 如何应用于风管
- 现在更多imperceptible risk factor（难以察觉的风险事件，如空气中的有害化学成分，seemingly disconnected financial transaction）都被纳入risk management decision making。
- ==smart product (使用sensor的创新产品；wireless sensor network；用以收集、传输和分析数据。使项目faster，useful，improved) 可感知环境、处理数据，并与其他smart product和smart operation通信。==
- ==interaction可产生big data（数据量巨大而无法使用传统方法分析的data set），此时可使用advanced analytics以减少预测未来事件时的不确定性（uncertainty）。==
- ==随技术发展，smart product的availability和sophistication可改进风险管理技术，如wearable or wristwatch，drone(无人机)，robot。==
- ==smart product为传统risk assessment and control提供了new dimension of depth and precision.== 

## 1. 财产管理
- property manager可使用wireless sensor networks（==WSN，由放置在不同区域的individual sensor组成的wireless network，用于exchange data==）来detect或respond to leak and malfunction 以及 prevent on-site fall and injury. 
	> 水传感器可检测leakage（在tenant遭受water damage之前）。
	>
	> ==temperature sensor (温度传感器) 可检测温度异常（before pipe freeze, 这条在vacant或暂时没人occupied的建筑中特别有用）。==
	>
	> ==light sensor可在需要时提供光，以减少可导致liability claim和诉讼的危险。==
	>
	> ==motion sensor和surveillance camera可在犯罪发生前即阻止（deter）犯罪。==
	>
	> ==thermal sensor/ current sensor/ smoke detector会评估impending（即将）fire condition，以让first responder在火灾发生之前就能知晓，或完成必要措施以减少cost of damage。==
	
- 可通过Wireless sensor network中连接的个传感器对建筑进行远程管理（产生数据，显示实时和历史维护报告和服务记录，并对各楼层或部门进行对比）。有些传感器只要放置好并激活即可，有的传感器需要further monitoring or interaction. surveillance camera（需要computer vision辅助）可捕捉图像并用于额外分析，用于loss prevention and reduction，并用于continuous climate control，power consumption，compliance with building code.
## 2. 供应链管理
- 供应链管理不仅包括unforeseen event引起的product/ service/ shipment disruption，还包括interruption对product, service, shipment引起的downstream effect。
- risk assessment（包括identify potential or actual distuption）和risk control（包括preventing or reducing disruption）可使用多项技术来管控supply chain risk。
	- radio frequency identification (RFID，使用radio frequency来identify object)，wireless protocol和Global Positioning System (GPS) 在供应链风险管理中至关重要。
		>==传统货物追踪使用barcode（需要靠近reader才能读取），RFID可在无人工介入情况下完成identify和compile characteristics。==
		>
		>RFID技术属于wireless，支持自动化流程，无需靠近reader，并可提供每件物品的信息（用于logistic and transport），其与GPS结合后可进行mixed shipment without external wrapping。
		>
		>当shipment incomplete or damaged, RFID可用于assess risk，自动呼叫replacement并管理replacement流程。
		>
		> RFID可提供实时和准确的储存和检索（retrieval）记录，企业可快速知晓discrepancy和interruption，并prevent和reduce供应链风险。RFID也可为接收方或remediation（修复）自动发送real-time alert。
	- 其他传感器可empower更准确（precise）的供应链管理，如sensor data可通知weather condition interrupted production of part或货物被盗. 
	
## 3. 交通管理
- 可使用IoT（==Internet to Things, network中的物体相互传输数据 without human interaction==）连接汽车/司机，开发出awareness/ safety/ efficiency/ reliability的解决方案。该技术也可用于管理vehicle fleet。有些IoT技术科提供驾驶辅助（driver assistance），如crash avoidance, self-parking, lane changing assistance, 借助摄像机和computer vision的自动驾驶（可辨别人和其他物体，辨别pavement type或施工区的abrupt lane）。
- smart transportation（integration of strategic vehicle management solution with innovative tech）对运输管理至关重要. 可分成如下几个层次
	- ==sensing layer: 使用各项传感器，相机及数据收集能力，协助或自主进行correction并提供信息。==
	- ==communication layer：使用wireless protocol和其他司机或manager传输数据，以确保necessary capability（recording, data uploading, navigating, video recording, 集中监管sensing layer and service layer）==
	- ==service layer：使用data processing，cloud computing, 存储并分析sensor收集的及driver提供的大数据。==
- 各层间的interaction可增强remote diagnotics，对实时驾驶习，physical condition，维修状况，preventive maintenance alert，定制化产品和服务进行分析，让驾驶员easier并让乘客enjoyable。
- ==sensing layer创建图像、诊断、trip log。service layer用于分析。communication layer提供数据传输支持。resulting data用于monitor performance并further refine the process。==
- accelerometer（加速度计）可测量加速度（acceleration）、运动（motion）和倾斜（tilt），与软件结合来检测直线运动（linear motion）。==通过telematics（使用技术设备和wireless communication及GPS间来传输数据），accelerometer技术可生成vehicle fleet information，如驾驶员的加速和刹车==。telematics也可以用于其他行业，如检测过度的震动(excessive vibration)，预防爆炸about to explode。
- 增强现实技术（augmented reality）可将数字体验融入到用户的physical环境中。如head-up display（平视显示）可在风挡玻璃上显示速度和警告信号等，减少驾驶员distraction。
## 4. 巨灾管理
- sensor和WSN（wireless sensor network）可用于巨灾管理（sensor需承受harsh environment，sensor可用于持续监测某地区的灯光，温度，特定气体等）。sensor和WSN还可在巨灾发生前后监测local change。通过持续监测，sensor和WSN可发现并分析变化，以帮助预测巨灾和做好准备工作。
- ==Lidar（使用infrared light来监测nearby object），用于增强auto vehicle的performance和accuracy。lidar可和optical sensor结合进行图像分析（不管有无阴影或blinding sunshine）==. Lidar在巨灾发生前后都有用：
	> 不管天气如何，均可提供图像，提供三维mapping技术，相较2D技术，可提供更多信息
	>
	> 可捕捉或产生accurate elevation data（海拔信息），增强洪水多发地区的mapping能力，有助于确定周围河流触发洪水的水位。它还可帮助识别需evacuated区域（有时可具体到某个建筑）。
	>
	> 洪水后的lidar图像，及其收集的气压，温度，wind turbulence and location等，有助于安排rescue和remediation的优先级。该信息还可以用于分析和比较各洪水事件。
	>
	> 灾难中断cell or internet service后，Lidar可帮助决策emergency communication equipment的最好位置（确定何处放置wifi终端）。发生tsunami或earthquake后，Lidar可对街道或建筑的风险进行排序，以帮助救援和分配remediation resources。
	
## 5. workplace safety管理
- ==wearable设备: 可让工人以舒适的方式穿戴sensor并能完成日常工作==
- ==drone无人机: 可替代人进入未知或有潜在危险的区域，来提供信息或评估并控制风险。drone可on the ground, in the air, or underwater.==
- ==robot: 可使用机器人完成更多repetitive和heavy-lifting工作。worker可更好利用自身技能，并将机器和人更好的在workplace中合作。==

## 6. construction and engineering管理
- mechanical sensor可检测并测量physical质量，并产生可读取的信号和数据.
	> montion sensor可用于surveillance和security
	
	> pressure sensor类似于strain sensor，将pressure或tension转换成electrical resistance并进行测量
	
	> current sensor 可用于保护电子设备和电池过热
	
	> position sensor在其处于特定位置时才会激活，如洗车中的传感器可感知汽车大小和清洗流程
	
	> proximity sensor在物体进入范围内激活，手机听筒传感器可感知presence of an ear并关闭背光灯和触摸屏以节电
	
	> inertial measurement unit（IMU）可使用accelerometer and gyroscope（陀螺仪）追踪物体位置，IMU用于导航系统，可用于fitness tracker 或 gaming system，这中也是autonomous vehicle（自动驾驶汽车）的关键传感器。
	
# 二、Data Analytics如何驱动Smart Product
- smart product and operation可产生大量数据，并可最终通过preventive analytics来improve risk assessment and control。preventive analytics使用大数据等技术寻找root cause and interaction。由于其持续监测各项活动，所以特别有效。
- ==传统风管技术会使用root cause analysis（RCA）分析事故原因并寻求应对措施以防止其再次发生，但RCA属于事后行为（backward）且只会定期进行（有时为一年一次），而且有可能无法identify所有的root cause和相关事件，这都限制了其有效性。==
- 近年来风管人员开始使用analytical model来进行损失预测和predictive analytics（基于各种predictive attributes），而这正可利用smart products在数据方面的优势. 通过大数据，这些方法变得更加有用。
- 以下分析技术的发展使分析方法更加复杂。

## 1. Analysis Claasification
- ==classification analysis（属于supervised learning technique）：根据已知属性（attributes）的值对数据进行细分（segment），确定分类目标变量(categorical target variable)的值 (value)。该方法可用于揭示accumulated data point之间的关系.==
- workplace中的sensor可收集大量信息，但需要将收集的信息关联起来（有时还要关联非传感器数据）才能决定最终的影响。这时就需要进行classification analysis（单独使用或与其他及时combination）。
- ==可使用classification tree来判定是否会出现事故及其概率，方块表示是否会出现事故，并在其中标识出概率，进而可以算出最终事故的概率。==

## 2. Text Mining
- ==text mining可通过language recognition来获取信息==。text analysis model比其他模型更复杂（text属于非结构化数据（unstructured），且可能包含unorganized field或non-numerical value）。
- 各种文字材料对计算机或算法（==algorithm，一系列用于解决数学问题或create computer program的operational sequence==）来说无意义，所以必须对其进行预处理（preprocess）以解决各种语法标点问题，及同义词含义（synonyms）。为将modeling algorithm用于text，text必须以algorithm可识别的方式录入（可将text转换成每个单词出现次数来完成，该过程称为结构化，即将unstructured data（text）转化为structured data（number）），之后再用高级统计技术进行分析。
- ==natural language processing（NLP，自然语言处理，text mining一部分），即使用语言学（linguistics）来理解speech或阅读文档==。可用于获取每个字的意思。==该技术可用于帮助计算机学习context==，对于某些应用非常关键（如==sentiment analysis，情绪分析，用于确定文本要表达的opinion或emotion==）。该技术还可用于robot，以自动执行claim process/ 阅读不同语言的文件/ 挖掘public information（后者在获取公共信息以评估供应链风险方面极其有用）。
- ==text mining还可用于其他风管领域，如从potential fraudulent claim中挖掘worker compensation data，从social media中确定sentiment level以评估声誉风险等。==

## 3. Pattern Matching（模式匹配）
- ==pattern matching指finding matching pattern in data==。 可通过比对来完成风管工作。computer vision已经发展到可对细微差别（nuance）进行区分（可通过不断feed massive number of images和deep learning of neural network）。
- ==该方法可用于寻找金融机构间的欺诈交易（fraud in financial transaction）和网络安全（network security issues）问题 （具体方式为分析transaction data来找出fraudulent pattern，通过对比之前分析过的案件，对可疑的交易进行flag）。如通过图像对比，分析土壤湿度（soil moisture level）==

## 4. Neural Network分析
- ==neural network（一种data analysis技术，由input layer，hidden layer（nonlinear function）和output layer组成。主要用于复杂问题）用于模拟人脑功能==。尽管神经网络无法像人脑一样工作，但其在对input data进行分类时可以类似方式进行，它也可以完成human brain无法完成的工作，如快速解答大量数据的数学计算
- neural network由三层组成
	- input layer: 提供network 分析的数据
	- hidden layer: 介于input layer和output layer之间，其计算过程不透明且难以理解. 该层负责各种数学function来匹配input和output。
		> 通常来看，神经网络由thousands of neurons and links to perform calculation（with large amount of data）
	- output layer 提供分析结果
	
- neural network 可用于深度学习数据之间的关系。
- 神经网络的另一特点为可使用incomplete data。
	- 其分析结果基于observation, detected correlations and new concept. 如可通过分析公开数据知晓供应商的供应商（2nd-tier or 3rd-tier supplier），在进行风险分析时，企业即可完成一个更为全面的risk profile。

- ==neural network通常认为属于machine learning==
	- 机器学习从一个模型开始，data scientist 开发并测试模型以完成predictive analysis。当computer使用模型时，其会从结果和new data中学习。
	- ==neural network相较于其他machine learning方法，更少依靠rules，计算机会进行independent observation之后提供intuitive result（直观结果）。==
- ==当neural network可接触到各种smart product提供的数据后，即可用于风管和风控领域。如可对machine failure, catastrophes, financial impropriety, defective product等进行复杂分析以预测风险。==

# 三、使用Smart Product的风险
有些技术太新以至于相关的风险还未揭示出来。企业需衡量新技术带来的好处和风险，风管人员需了解新技术带来的风险，之后再决定保护自己的方式。

## ==1. 财产风险==
- ==cyber attack风险：smart product通常需要使用wifi或其他通信方式，有可能会被cyber attack，导致shut down operation并毁坏equipment和product。==
- ==industrial espionage（商业间谍风险）：使用AI会增加industrial espionage（间谍活动）的风险（特别是corporate spying），使用的智能设备越多，黑客越有更多的机会来监视企业活动并disrupt其运营。若某部分职能处于供应链中，一个business operation的暂停会导致ripple effect（涟漪效应）。==
- ==高额维修费用风险：智能设备较复杂，维修和替代费用也较高，风管人员应确定有specialized skilled 人员来进行维修和运营。==

## 2. 责任风险
新技术会带来一些新的责任风险。

- ==autonomous vehicle（自动驾驶汽车）中，很难确定property damage和bodily injury的责任。将从驾驶员责任转移到产品制造商是可行的。但如果人类驾驶员可选择控制车辆的情况下，这种责任转移是否可行==？随着自动驾驶越来越多，交通事故的责任将转变为产品责任（product liability），保险和风管人员也许对此做出调整。
- ==监控驾驶行为/ 工作习惯和活动/ 日常手机使用习惯的sensor都会导致隐私问题（privacy）。==
- IoT设备的相互连接（inter-connectivity）会增加数据传输量，继而导致attack的可能性上升（一个未受保护的设备可能会导致大量数据泄露）。另外inter-connectivity会导致智能设备受损，继而导致产品责任问题（如冬季温控设备损坏，导致水管破裂和water damage）。
- ==wearable设备可能导致身体受伤，如minor skin irritation（刺激）或无法监测用户medical condition而造成severe injury。如某人患心脏病，通过使用wearable设备监测心率，若其心脏病发作，家人可向可穿戴设备制造商提出索赔。==
- RFID（Radio Frequency Identification）可帮助供应链风险管理，但也会带来privacy和security方面问题。RFID通过wireless传输信息的时候，信息可能会被截取（intercepted by unauthorized party），若企业使用此方式向客户或供应商传输数据，则企业需对数据的错误传输负责。
- ==Drone（无人机）会导致property damage and bodily injury, 如无人机失去GPS连接后，可能会从天上掉下砸到人或物。==
- ==对于poorly designed algorithm，企业面临error and omission liability，继而导致faulty decision，以及对他人的bodily injury or property damage==

## 3. Personnel风险
- ==当企业要求员工使用新技术时，如果私人或医疗信息被获取或不当使用时，企业可能要负责==。
	> 如使用运动员的数据（而非过往比赛表现）来判断其价值，公司通过可穿戴设备控制雇员的时间使用习惯等。
	
- 智能产品可能会带来巨大的风险，因为其需要企业在时间和金钱方面大量投资。
- ==工厂，建筑工地，unionized，field personnel会比办公室人员更接收智能产品，年轻人也会更易接受。但人们也会关注智能产品是否会对自身造成伤害的问题。==
- 员工会关注smart product是否会手机隐私数据，企业会关注data safeguard和cyber liability exposure in creating/ collecting/ storing process. 收集医疗数据有可能面临healthcare privacy方面的regulation。
- ==若无合适训练，smart product可能弊大于利。员工过于相信设备而less attentive；因使用drone和robot，员工害怕被替代，而拒绝使用新技术。==

## 4. Net Income风险
- ==新技术可影响企业的net income，IoT会给企业带来潜在的cyber attack（如ransomware，勒索软件），企业运营会因malicious party而暂停。==
- ==企业还应注意potential data breach，这会影响客户，企业修复reputation,告知并协助客户等善后工作的花费会很大。==
- 企业对breach的反应会决定overall loss。
	> 若企业无法采取合适的措施来halt breach并将其告知regulator和消费者，企业会面临罚款（failing to report the breach/ violating privacy statutes）
	>
	> 企业管理人员，如果知道breach行为但未采取合适措施，也会被解雇。如CIO或CEO被解雇，招聘的成本会很巨大。
	>
	> breach后，即使采取了行动，企业也会发生legal fee for counsel in handling the breach/ managing employee termination and hiring/ resolving customer loss. 企业还会为受影响的客户提供credit monitoring。
	>
	> 企业还会经历reputation loss。企业应迅速采取措施阻止攻击并修复任何安全漏洞/ 避免在攻击发生之前就发生攻击/ 制定应对攻击的计划, 这些都可帮助企业减少reputation loss and financial loss。对于中小企业来说，breach可能导致经营失败。
	
## 5. Emerging Tech的风险控制
企业一般都会控制cyber risk（数据落入未授权的一方，或数据未被合理使用（或使用方式对个人或企业有害）的风险）。虽然构建一个secure system比在现有系统上打补丁简单得多，但企业仍可以通过如下方式控制新技术风险。

### （1）physical control
- ==当一组计算机和其他IoT设备被恶意软件（malicious software）感染后，会形成僵尸网络（botnet）。可通过网络和device security（如防火墙firewall和用户授权user authentication）防止形成botnet。==
- 一个unsecured系统组件可让整个网络失效并造成data breach。使设备免受攻击即可让其不造成bodily injury and property damage (未受干扰的设备一般都会可正常运行)。
### （2）Procedural Control
- 提高IoT设备间的inter-operability（相互操作性），强调security standard是控制风险的关键手段。
- 企业应当标准化数据收集方式 
	- 现实中通常无标准化的communication protocol（不同的设备产生数据的方式不同）。
	- standard about data可帮助减小风险，如data governance 可明确收集何种数据以及保存时间
	- 若企业会保留数据（store data），则其也会面临data breach的风险。

### （3）Managerial Control
- ==管理层应为企业设定smart product的使用和运营标准，以及如何控制风险==。Federal Trade Commission（FTC）为企业提供了保护device and network的guideline。
- IoT：Privacy & Security in a Connected World报告提供了IoT的数据收集及使用原则
	> security：FTC推荐在device中建立security，培训员工，retain capable service provider, defending against identified risk, 限制未授权登录，持续监控smart product
	>
	> ==data minimization: 企业应限制收集的数据，储存太多数据会导致attack==
	>
	> ==notice and choice: 当企业收集用户数据或用于unexpected way时，应向用户展示notice，并给出用户选择是否同意==
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMzY0MjE0MTAsNDg2NTA2MDU3LC0xMT
U2NzA1NjA5LDE0NTgzNjc3NzQsLTYzODc0NDA5MCwyMTEzMTQ3
OTIwLC0xNjM0MjgyMTUwLC0xNTY1MzU1MzMsLTEyOTMxOTg1ND
YsMTQxNTUxODE4NSwtMTgwMDA2NzIxNywxODIzOTc2MzI0LC0x
NjQ1NzcwNTU1LDIxMzUxMTEyNDhdfQ==
-->