经营连续性管理 Business Continuity Management（BCM）
# 一、简介
- ==企业可使用业务连续性管理（Business Continuity Management, BCM）解决危害事件对业务的潜在威胁。==
- ==BCM包括检视各项危险，建立发生业务中断后可继续运营核心功能的计划。==
- 企业认为Business continuity management可帮助企业抵抗各项危险事件，所以该管理计划也被称为business resiliency（弹性计划 ）。

## 1. business continuity management历史
- emergency preparedness/ disaster recovery/ business continuity之间经常混用，三者概念相关，但强调的范围和重点不同，BCM的历史代表着企业从surviving a catastrophe逐渐进化到responding to resilience。
	- BCM的源头是emergency preparedness和responding plan。这两种计划的目标是在灾难过后，提供紧急救援物资和训练有素的人员，以确保企业人员和财产安全。虽然适用性仅限于disaster，但emergency preparedness确实帮助建立了全面规划。
	- ==disaster recovery plan源于企业对技术的使用和依赖。==
		> 企业在数据管理和存储，库存管理，通信及关键系统方面变得更加脆弱。IT部门制定了数据和设备保护，及数据恢复的计划。==disaster recovery仍被视为IT部门的职责==。
		>
		> ==随着技术普及，disaster recovery计划已扩展到制定灾难发生过程中的protection plan。在更广的范围内，disaster recovery plan希望在灾害事件中的混乱和emotional distraction时提供有效帮助。==
		>	
		> 该计划通常聚焦灾害发生前和刚发生后的计划。
- 随着BCM发展，企业逐渐开始关注其依赖的其他企业（如供应和分销系统），进而保证企业自身的运营。
- emergency preparedness, disaster revocery plan, BCM的区别
	> emergency preparedness关注灾害过后的人员/建筑/设备恢复
	>
	> disaster recovery plan关注保护数据和技术系统
	>
	>BCM关注企业的持续经营, 包括任何严重interruption

## ==2. BCM与Risk Management==
- ==bcm和rm都会对企业的资源/活动/进行planning, organizing, leading and controlling以达到最终结果。==
	- ==BCM主要处理disruption的结果（旨在减少灾害对运营的影响，所以更偏重operational risk）；==
	- ==RM处理operational risk，hazard risk（property/ liability/ personnel loss），financial risk（market force effect on financial asset or liability）和strategic risk（economic和societal trends导致的effect）==
- ==企业应当将BCM和RM视为complementary（互补关系）而非竞争关系。企业应当对两种职能，权责和汇报机制进行清晰定位。==

## 3. business continuity的certification和standard
- 911之后，DHS已采取三项国际认证用于disaster/ emergency/ business continuity管理。
- ==这些认证鼓励美国企业为emergency做好准备，因为其提供了评估风险以及制定恢复和连续性计划的准则，企业可根据自身情况确定使用哪一个标准。==
- ==遵守这些标准是自愿的，但选择执行的企业必须投入资源来完成==（企业需向DHS提交执行标准并获取DHS颁发的certification，获得certification的企业需要定期审计已确定其满足标准）。
	> ASIS SPC.1-2009（Organizational Resilience: Security, Preparedness and Continuity Management Systems）: 强调企业在emergency中的resilience。提供了policy/ objective/ program guideline，旨在加强通过BCM加强企业的resilience。
	>
	> Britishi Standard 25999-2:2007（Business Continuity Management）: 定义了用于BCM的management system requirement
	>
	> National Fire Protection Association 1600:2010（Standard on Disaster/ Emergency Management and Business Continuity Programs): 主要关注prevention，mitigation，preparedness，response和recovery，与rm/ security/ loss prevention相关。

# 二、Business Continuity Planning及其步骤
- 不管外部内部环境如何，企业应当设定详细的减小风险的计划并实施。遇到disaster后，即使企业不会迅速破产，灾害带来的effectiveness和mission reassessment以及领导层的变更有可能会导致进一步混乱。
- 开发business continuity plan（BCP）是BCM中的重要一步。==BCP会分析所有可能的事件，为使得企业继续生存，BCP会评估业务中断时，企业必须继续履行的关键职责。==
- BCP和BCM中的business均指代保证企业继续运行，同时这种business的延续也要考虑企业的mission, vision and strategy。
- BCP的开发和实施需要七个步骤。

## 1. Understanding the Business(了解业务)
- ==企业必须了解其业务的每一方面，包括key objective，如何实现以及涉及的内外部环境。==
- ==企业还应了解如何使用facility，供应链，人力，沟通方式，信息系统，流程，分销渠道以及客户等。这些会组成Business Impact Analysis(BIA)的基础。==
## 2. 进行Business Impact Analysis（BIA）
- ==企业进行Business Impact Analysis（BIA）以识别并评估可能的风险。==
	- ==分析包括可能发生的事件，发生时间以及如何影响关键目标实现。==
	- ==BIA还会分析衡量风险对财务和非财务的影响，探讨企业vulnerability（制定保护企业战略资源的关键问题）。==
	- ==BIA会区分critical process和non-critical process（让企业用BIA确定恢复时间的目标，critical process中的recovery time必须优先恢复，以让企业继续维持运营）。==
- ISO 31000：2009及其他国际标准对BIA制定了不同的方法或术语。
	> 在某些标准中，BIA和risk assessment相结合
	>
	> 其他标准中，BIA超出了传统风险评估的范围（传统risk assessment通常只关注hazard risk，而无法评估风险对运营的全面影响）。

## 3. 风险评估（Risk Assessment）
- 企业identify并评估潜在的风险及发生率 (体现企业对特定事件的敏感度)，有助于企业对business continuity management战略进行优先级排序，并根据risk appetite进行risk control管理。全面的风险评估可帮助企业找出所有可能的危险并提出改进建议。
- 可在不同层次执行risk assessment：
	- ==enterprise assessment: 影响企业所有商业目标的global层面评估==
	- ==site assessment: 特定位置和场所层面的评估==
	- ==program/ project assessment: 项目capability/ resources层面的评估==

## 4. 开发business continuity plan (BCP), business impact analysis (BIA)和recovery time
- ==风险评估后，企业开始评估disruption时需要继续进行的关键运营。企业可使用如下一项或几项进行。==
	> ==active backup model：在其他地点建立和主要生产地一样的设备，主要生产地运营中断后，staff可relocate to second place。==
	>
	> ==split operation model：企业有两处或以上的生产地（通常是分散的），每个地点都有支持完整生产的能力。==
	>
	> ==alternative site model：维护一个生产站点和一个备份站点，备份将根据需要成为主站点。==
	>
	> ==contingency model：开发备用方法以维持生产（可能是手动流程）。==
- 上述几种方法均需有几个层次的planning（BCM ornaizational strategy, process level strategy, resource recovery strategy）。
- 具体的strategy包括
	> 保险: 可保范围内的损失发生后，企业可获得财务补偿
	>
	> transfer process: 与另一家公司达成互惠安排（reciprocal），在业务中断时履行职能，
	>
	> termination: 停止生产或提供受影响的产品或服务 
	>
	> ==loss mitigation: 实施risk control, 减少/最小化/转移损失==
	>
	>do nothing: 企业自留风险,会导致企业risk appetite增加

## 5. 执行continuity plan
- business continuity coordinator（BCC）协助并指导每个部门形成自身的部门计划，从而保证企业的每个部分都能有效工作。BCC把drafted BCP提交高层审核，审核通过后，BCC和高管开始按照BCP执行。
- 每个部门的计划必须包括：
	> 可接受的functioning level/ recovery time目标
	>
	> 需要的资源以及潜在的失败点/required task and activity/流程/支持文档/supporting structure/ division team描述（purpose, team member, mission）/ 各部门间的关系（interdependence）

## 6. 建立BCM/ BCP 企业文化
- ==高管层需为中层管理者提供目标，员工需要了解BCP的重要性其中一种方式为举行semi-annual exercise（使用plan应对虚拟的disaster，此过程可发现plan的漏洞并进行修改）。==
- 上下游公司也应当知道该企业具有BCP，其与企业的关系也会得到改善。

## 7. 维护和更新计划BCP
- Business Continuity Plan（BCP）必须随时更新才能有效，企业应在条件允许下，对BCP进行review。
- 企业需要每半年回顾一次written BCP（或在产品/流程等发生重大时进行回顾）。
- 可将BCP电子版保存在服务器上，纸质版需要专门人员维护。
- BCP并非在任何情况下都有效，当企业生存面临挑战时，需要进行 strategic redeployment planning。

# 三、STRATEGIC REDEPLOYMENT PLANNING
- 事件发生后，企业可使用strategic deployment planning确定如何恢复其业务运营。
- BCP有时无法确保企业恢复，管理层需要在重大灾害发生时确认战略是否仍然有效，如无效，则需进行调整。当灾害是由chaotic situation引起时，企业必须调整相关战略。

## 1. Strategic Redeployment Planning (SRP) Stage
- strategic deployment planning (SRP) 是在severe disruption后，用于恢复的全面弹性计划，有效准确及时的沟通在SRP的各步骤中都是必须的。
- ==Strategic Redeployment Planning (SRP) 分为四个阶段：emergency stage，alternate marketing stage，contingency production stage，communication stage==

### （1）emergency stage（disaster recovery）
- ==此阶段从disruption发生和企业的immediate response开始，该阶段的主要目标在于保护人员安全，保护财产，保护reputation。==
- 具体行为包括关闭并清洁facility，召回产品，与员工和媒体会面沟通情况等。

### （2） alternate marketing stage
- ==评估disruption对企业reputation和market share的影响。==
	
	- ==企业此时必须决定是否要采用新的marketing战略，也要考虑consumer loyalty，供应商是否继续愿意和公司合作，竞争者是否会利用此机会侵蚀公司的市场份额，竞争者是否会影响公司现有供应商==
	- 在此阶段，企业需要考虑所有能保住核心业务和资源的行为（包括退出市场等）。
- ==企业应当设定运营中心或data room以测试所有可能的scenario。==
	
- 企业可使用color-coded方法
	- 红黄绿表示，绿色表示现有战略可以保留
	- 新的marketing战略需要决策企业是否仍要延续或保留之前传统业务（此种情况可用黄色表示）。
	- 当现有战略无法维持，需要新战略时，可用红色表示（对业务模式进行彻底改变，有时是完全替换，此时需要考虑如何替换当前产品或服务；需要的资源；最终如何恢复期望目标和果）. 
		
		> 如企业决定不再继续提供某产品或服务，其必须评估discontinuance对企业的影响以及损失的revenue和客户群。

### （3）contingency production stage
- ==此阶段，企业须尽量减少停机时间，公司必须决定在现有情况下提供哪些产品或服务。==
- ==公司必须考虑相应供应链所需的资源和成本，并确定产品包装是否更新。==
- ==公司还需考虑transportation和distribution的可用性。==

### （4）communication stage
- ==沟通阶段的唯一目标是preserve或增强stakeholder的信任和信心。==
	- 此阶段从危机发生即开始（此时成为crisis communication）
	- 生产和声誉回复后，crisis communication变成post-crisis communication，企业需确定并关注内外部stakeholder的关切（stakeholder的安全与保障，管理层所有决策的透明度，沟通的清晰度和一致性，对管理层和组织信任缺失）
- 在混乱时期进行有效沟通的关键，是与危机之前就已建立关系的媒体保持好关系（危机时利用之前的合作）。
- 企业向媒体透露的信息须给员工信息一致。企业需与地方和行业协会有效沟通。员工需要最新的真实信息。危机期间让员工、客户、供应商和stakeholder了解情况，可防止授敌人以柄，还会增强忠诚度和对企业的信任。

## 2. 成功的关键
- strategic redeployment需要内外stakeholder的持续关注。企业必须在disruption发生前就保持好reputation，企业与内外stakeholder的沟通习惯尤为关键，successful redeployment需要全公司的effort。
- Strategic Redeployment Planning (SRP)可能不涉及企业重大变革。但有时该计划会非常激烈，且可能涉及企业的战略方向。

# 四、Crisis Communication
危机中企业与stakeholder的沟通能力至关重要。Crisis management可有效减小企业风险。

## 1. 通过crisis communication减小风险
- 良好的rm应当嵌入到企业中并涉及企业各方面（financial partner/供应商/客户/stakeholder）。
- 企业执行crisis management plan时，首要目标为存活下来（这取决于恢复正常运行的速度（依托continuity/ disaster recovery plan）以及执行strategic redeployment plan是否成功）。
- 企业危机管理包含众多方面，但是危机沟通的质量至关重要。

## 2. stakeholder communication
- ==crisis communication在危险到来之前就开始了，其基于所有stakeholder之间的（互信）trust baseline，stakeholder必须相信管理层有能力处理危机。企业的沟通必须坦诚，解决突出问题，让stakeholder参与，以便有效恢复并维护stakeholder的信任==
- ==有效沟通也可以告知stakeholder企业已经考虑到所有的风险。沟通应强调安全方面，表明高管层致力于在透明环境中做决策，且体现企业的integrity和authenticity。==
- ==所有的沟通应当consistency，且对受众量身定制（企业应对内外stakeholder进行不同的沟通（专注于各自关注的问题并给出解决方案））。==

### （1）internal stakeholder
- 企业需要意识到internal stakeholder的需求各不相同
	- ==企业员工需要了解crisis如何影响其工作，有的会提出新的安全问题。可使用meeting, visual aid, hand-on training, intranet实现)==
	- ==unit manager (line manager)/ operational manager 必须知晓ongoing risk，培训(training)和对潜在风险的关注至关重要。==
	- ==line manager对rm负责，其必须对crisis management plan中的某些特定方面负责。==
	- ==internal stakeholder需要知晓manage/ mitigate/ prevention方面的信息==
	- ==需在季报或年报上告知企业健康情况，高管层需要披露趋势（trend）并告知公司resilience情况.==
	- ==企业高层需向board of director告知strategic风险, governance issue, long-term resilience.==

### （2）external stakeholder
- 针对外部利益相关人（stakeholder）
	- ==与供应商维持好关系有助于post-crisis的工作（企业resilience的重要部分）。==
	- ==应告知消费者continuity和safety，好的沟通有助于建立信任并维持loyalty==
	- ==须向政府和local authority告知企业为确保公共安全和健康，社区承诺所作的努力，依法监控并报告合规情况。==
	- ==其他external stakeholder包括local association和special interest group（需要告知这些组织现有情况，以维持后续和他们的关系）==
	- ==可利用媒体向内外部stakeholder传递信息。健康方面/ 安全方面/ 财务方面的报道和采访有助于恢复和保持marketplace confidence。==
	- ==上述每种沟通都必须truthful，risk manager需要清楚且诚实地告知现有情况，已知风险和潜在风险，企业需要管理并监督与stakeholder的沟通。==

## 3.crisis communication的优势
- 危机前和危机后的沟通可改善企业与内外部stakeholder的关系。
	- 创造开放真实的环境，为投资创造机会。
	- 长期来看，有效沟通可吸引并留住最优秀的员工（员工不会因企业reputation受损而蒙受损失），可与现有及新的供应商和客户建立关系。  
- 良好沟通可保护企业声誉，减少开发新市场的障碍（增强市场对产品和服务的信任），获取竞争优势（因为可以很好地管理危机和风险）。
- ==可减少危机事件引发的诉讼（litigation）。==

# 五、supply chain风险管理

- globalization和outsourcing增加了不同区域和行业中事件/货物和服务间的依赖性。某种货物或服务中断可能对企业有深远影响（无法完成合同承诺，继而伤害shareholder value）。  
- ==供应链风险管理需要评估和减少所有可能中断企业运营的风险。==
	- ==在商品生产领域中，供应链风险管理包括生产/运输/存储/以及从原材料到最终销售波动（volatility）的管理，生产中断会导致财务及声誉方面的影响。==
	- ==在服务领域中，供应链风险管理包括最终服务相关的波动性，还有价值链上的所有部分。企业须确定供应链中的风险和机会，并平衡efficiency和best practice。==
		
		>ISO 28000：supply chain security management requirement的引入使供应链风险管理的visibility有所提高。

## 1. supply chain的threat和opportunity
==企业需检视供应链内外部的风险和vulnerability（脆弱性）。==

- ==内部风险包括：==

	> ==production location:可能遭受自然灾害，man-made disaster或terrorism。此项可使用diversify location解决==
	>
	> ==production bottleneck：production依赖key machine or material(如果这些机器发生malfunction或breakdown，会导致生产减缓或停止)。可重新设计产品或流程减少或消除bottleneck。==
	>
	>==information tech: 数据中心有可能受损失，无info backup，或staff fail to follow restoration protocol。可使用backup protocol, redundant system, maintenance抵抗这种风险==。
	>
	>==infrastructure: 基础设施损害会完全停止生产。可使用backup protocol, redundant system, maintenance抵抗这种风险。==
	>
	> ==strike或employment问题：生产可能停止，inventory无法转移，订单也无法执行。==
	>
	> ==machinery breakdown：订购并安装过程中，生产可能停止或产生critical backup。可通过维护spare parts或建立changeover process来减小这种风险==

- 外部风险包括：

	> ==第三方供应：第三方供应disruption会降低企业生产能力。可通过diversify supplier，小心签署合同，保持和供应商的对话解决此风险。==
	>
	> ==sole-souce supplier: 市场上的供应商只有一家时，供应中断会降低或直接关停企业生产能力。多和供应商沟通或重新设计产品来减少风险。==
	>
	> ==single source supplier:在市场上有多个供应商，但企业只选取了其中一个的情况下，会发生供应中断。==
	>
	> ==change in demand level: 客户taste或竞争变化会导致生产过剩或不足。若无法准确预测需求，会损坏企业market reputation。可通过市场环境监测预测来减小风险==
	>
	> ==financial risk（财务风险）：材料或运输费用增加会导致成本上升。由于消费者偏好/ 已签署的合同/ 竞争，企业可能无法转移增加的成本。汇率波动可能会导致材料成本增加，降低产品在国外市场的吸引力。可通过合同来protect risk（如保险合同），或监测emerging financial trends来减少风险。==
	>
	> ==geopolitical environment(地缘政治环境): 出口和进口受政府regulation或税收影响。不稳定的政府增加了企业在外资产被国有化（nationalization）的风险。可通过了解运营地区的地缘政治环境缓解此风险。==
	>
	> ==natural或manmade catestrophe（自然灾害或人为灾害）：自然灾害可伤害企业设施或影响运输路线。若企业员工过少，流行病（pandemics）也会影响企业运营。恐怖活动会长时间影响供应和分销系统。可定期更新business continuity plan（BCP）来减少风险。==
	>
	> ==key supplier与competitor的合并：关键供应商所有权的变更可影响原料的价格及可用性。可通过diversify supplier, contract carefully，维持和供应商的对话来减少风险。==

- 未发觉的潜在机会有
	- just-in-time delivery and work process，可降低存货和储存价格。
	- 技术升级可增加process efficiency。
	- 通过communication加强与供应商的关系，减小潜在的供应链断裂。

## 2. disruption中efficiency和vulnerability的平衡

- 企业评估完供应链中的潜在风险后，须确定如何保护生产流程，分销渠道和市场声誉。企业还应检查保持高效生产的手段，测试并考虑准确预测材料/人员/销售的能力。供应源及产品设计的灵活性可保证企业在面对灾难时的efficiency。 
- 供应链的所有潜在损失（loss of revenue, increased cost, mitigation cost）都可使用business impact analysis (BIA)进行。
	- 若某些风险事件不会对企业revenue造成损失，则企业不必在business continuity plan中考虑此风险。
- 为保证continuity，企业必须全盘考虑threat和disruption短期/中期/长期结果（如被评级机构降级，或国外法律确保企业的连续性）

## 3. supply chain的实践
- ==企业应定期评估供应链风险，多学科专家组成团队，评估潜在风险优先级/ 中断时间/ 恢复时间，还应考虑应对手段（取决于disruption的可能性和严重性（level/ duration））。==
- ==具体的应对手段包括进行dry-running和根据情况升级business continuity plan（BCP）。==

# 六、减小供应链风险
- 每个企业都应为disruption做好准备，以保证自身货物或服务仍能正常进行。
- 风管人员需要了解的内容包括
	- cascading disruption: 无关紧要的事情引起major disruption
	- supply chain management：多样化supplier，并和supplier发展良好关系
	- business resiliency planning：为respond to disruption做好准备
- 风管人员还应分析和企业有关联的各方的风险，并决策如何降低每种风险带来的直接损失。该分析旨在确定risk exposure及其导致的损失的影响，并分析如何减少损失。	

## 1. case analysis tool
supply chain element, 相互之间的关系，现有合同内容，可用的mitigation tool

## 2. Overview of analysis
- 在disruption来临之前就建立mitigation plan是business continuity plan的重要一步。
- 风险分析的具体步骤包括
	- 识别每个公司的独立风险
	- 确定公司间的co-dependency
	- 分析风险并确定每家公司如何避免或减少损失。