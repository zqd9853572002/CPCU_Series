# 一、使用sensor data来prevent Employee Injury

- 在WC claim中，past accident data会显示accident causation只关注single unsafe act/ condition，但是simplest accident通常是multiple action和condition的complex interaction的byproduct

- workplace accident和cause是data analytics的ideal application subject，因为workplace accident analysis的traditional method只依赖于human对limited information的interpretation（这无法说明contributing factor如何combine to cause an accident）

- ==wearable sensor是一种powerful way（其属于most prevalent data analytics sensor），其可用于collect worker biological condition和workplace environment physical condition的data==

  - 此类data可帮助advance predictive modeling/ machine learning，以improve forecast accident的accuracy
  - ==将sensor data categorize后，可帮助开发predict workplace accident的attribute，这些attribute会和traditional workplace accident attribute混合（combine）在一起，进而用于independently analyze information gain==

- safety program可以combine accident analysis technique element

  > 如FTA和 RCA，FTA混合 (combine) 后，可用于识别potential accident，进而predict the most likely system failures 

## 1. 传统的Workplace Accident Analysis Techniques

- traditional workplace accident analysis technique category包括system safety，root cause analysis (RCA)，Failure Mode and Effects analysis (FMEA) ，Criticality Analysis，Fault Tree Analysis (FTA)

### （1）system safety analysis

- system safety由US Department of Defense开发，最初用于minuteman导弹研发和部署，后用于所有航空航天工业和实话和电力企业
- 企业可认为是一个system，企业内部也由各种system组成，风管人员需要让这些系统安全有效运转

#### 1）system safety的定义

- system safety是一种engineering technique，其会在throughout system life cycle中，考虑system中interrelated element的mutual effect
  - system safety适用于accident causation approach
- system safety做的事情
  - 分析hazard和hazard cause
  - 估计特定类型breakdown的probability
  - 建议cost-effective way，以prevent或避免system failure
- system safety把企业看成整体（whole），并依赖specif才technique来确定how hazard lead to system failure and accident（也为occurred accident提供investigation framework）

- system safety依赖identify和分析hazard的各种技术，也依赖确定这些hazard如何导致系统failure/ accident的技术。这些技术可预估特定损失的可能性，并提出成本可控且有效的预防方式
- 该方法和其他关注unsafe act or condition的传统方法有区别（传统方法中，一旦unsafe事件确定，就会提出相应的控制）。

#### 2）system的概念：所有系统均有四个特点

- 所有system均由component，purpose，environment，life cycle。

- component
  - component属于system physical element。
    - 由于其可危害整个系统的可用性，所以需要特别关注，此项通常由传统风管或safety部门负责。
    - 其他形式的impairment（包括deterioration或technical obsolescence）通常由其他部门负责。
    - 但system approach消除了其中的分界，风管人员需要考虑all system physical elements impairment。
  - 所有系统均有sub-system（不管这种sub-system与system的层级差距有多深）
    - 某个sub-system出问题都会导致system的损伤。
    - 风管人员需要知道system及其所有subsystem，了解其相互关联关系，以及某个subsystem的失效如何影响其他subsystem或整体system。
  - system一般由energy source驱动，所以energy也会成为一种潜在的风险。风管人员需确保energy的合理控制和system physical movement来保证system的完整性，同时确保energy持续可用以及整体系统按计划执行。
- purpose
  
- 每个系统都会至少有一个目标且需要支持system目标，风管人员必须知晓这些。
  
- environment
  - 所有system均运行在一个大的environment中，对于大environment来说，system其实都是subsystem。environment分为三部分

    |                                    | 解释                                                         | mark                                                         |
    | ---------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | physical environment               | 在极端条件下，系统可能无法正产完成其工作                     | 包括温度，illumination，pressure，working surface等          |
    | organizational environment         | 系统运行须遵守的policy和流程。这些决定了组织内的授权和责任是否清晰，管理层对安全的责任以及员工提问的empowerment | -                                                            |
    | social-economic/ legal environment | -                                                            | 包括社会标准（norm）和convention（习俗），安全/environment和各种法规，以及local/ national/ global经济考量 |

- life cycle
  - system会经历五个阶段

    |                                       | 解释                          | mark                                                         |
    | ------------------------------------- | ----------------------------- | ------------------------------------------------------------ |
    | conceptual phase                      | 明确系统基本目的和初步设计    | 此阶段对hazard考虑的越多，后期运营时对其他保护设备的依赖及对人员错误的考虑越少 |
    | engineering phase:                    | 设定系统design，测试prototype | 使用同样规格创建prototype（原型），测试系统所有功能          |
    | production phase/ developmental phase | 生产实际system                | 采用和prototype同样的规格生产                                |
    | operational phase/ deployment phase   | 系统实施阶段                  | 系统实际使用阶段，此阶段不太会增加新的安全措施（与之前步骤相比，此时系统已定型，很难改变） |
    | disposal phase/ termination phase     | 系统使用寿命到期              | 需要处理此时需要多考虑environment因素                        |

#### 4）system safety的案例

- 某个时间可以从小到大分成多个角度考虑，每个角度都有相应的风险处置方式。

#### 5） system safety的优点

- 可按顺序提出loss control方式以增强相关系统的稳定性
- 由于系统规模逐层上升，可从内到外进行系统安全分析
- 可从发生率和损失严重程度方面减少特定原因导致的损失

### （2）root cause analysis (RCA)

- ==RCA是使用其他analysis technique的result，来识别accident的predominant cause的systematic procedure==
- ==RCA适用于识别（discern）accident的root cause（深层原因），进而通过mitigate future action/ inaction/ condition/ behavior的方式，来prevent harmful event==

  - ==root cause是直接导致事件的根本原因，可让企业知晓accident event的最初原因，并可据此引以为戒==

- 风管人员应关注影响企业workplace安全的事件

- harmful event通常和basic cause（physical/ human/ organizational）中的一个有关

  |                      | 定义                                                         |
  | -------------------- | ------------------------------------------------------------ |
  | physical cause       | physical cause是tangible或material物体导致的损失             |
  | human cause          | human cause是人的error或inaction导致的损失                   |
  | organizational cause | organizational cause是faulty system/ process/ policy有问题（如流程和责任人不清）导致的损失 |

#### 1）root cause的特点

- root cause是详细和具体的根本原因（specific underlying cause），而非只是概括的描述。
- root cause可reasonable identified，找到问题根源。
- root cause必须是可改进的东西。
- root cause提供可有效预防未来同类事故发生的方案。

#### 2）root cause analysis（RCA）

- 通常在事件发生后才会进行，但其也可预测可能妨害企业的事件（此时企业可进行提前预防，而非等事件发生后再面对）。

- RCA的approach包括：safety-based, production-based (industrial manufacturing), process-based, failure-based, system-based

- RCA的流程

  |                           | 解释                                                         |
  | ------------------------- | ------------------------------------------------------------ |
  | collect data              | 需要circumstance，fact，cause的所有数据                      |
  | causal factors charting   | 为企业提供并分析数据结构框架（画出事件顺序图，并列明root cause问题），并提供调查阶段的gap和deficiency。 |
  | root cause identification | 使用mapping或flow charting可找出causal factor的每一个原因    |
  | 推荐解决方案并实施        | 推荐的解决方案需要实施并进行跟踪                             |

### （3）Failure Mode and Effects analysis (FMEA)

- ==FMEA是一种analysis technique，与从accident开始相反，FMEA从accident cause/ reason开始分析，进而branch out to consequence（推出其如何助推事件发生）==
- FMEA的的目标是通过识别critical failure的order，来prevent/ reduce harmful event的severity，并根据priority来address event（处理事件）
- FMEA的specific action（consequence）包括
  - eliminate failure mode
  - minimize severity (consequences)
  - reduce occurrence
  - improve detection

- FMEA从产品开发和运营开始分析，目标为鉴别failure mode（产品/ 流程/ 设计方面的缺陷）并完成effect analysis（研究failure结果，决定root cause）

#### 1）FMEA需要确定系统的indenture level

- indenture level指某个item的relative complexity within assembly/ system or function（即整个系统从大到小的级别），确定failure effect时需要鉴别effect在整个系统中的地位。
- effect分为local effect（某个failure影响同级别indenture），next-higher-level effect（影响上一层级的情况）, end effect（影响最高级indenture系统的情况）。

#### 2）FMEA的主要目标

- 保证customer safety + 生产出quality的产品。
- FMEA的输出结包括：强化流程设计，最小化或消除产品设计方面的问题，研发减少failure发生率的系统，identify human error mode及其影响，研发追踪potential future design问题的系统。

#### 3）FMEA也可用于其他服务

- 可用于concept（设计早期阶段分析系统及subsystem），design（生产之前分析产品），process，equipment，service，system，software。

#### 4）FMEA的流程

- FMEA最好由团队一起完成，在早期设计中用于减少损失的发生率或降低severity

  | 步骤 | 具体流程                       |
  | ---- | ------------------------------ |
  | 1    | 确定范围和目标                 |
  | 2    | 组织团队研讨                   |
  | 3    | 定义components及其功能         |
  | 4    | 找出每个部分的潜在问题和影响   |
  | 5    | 提出改进措施（预防或减少风险） |

#### 5）FMEA的优点和缺点

- FMEA的优点和缺点

  | FMEA的优点                                                   | FMEA的缺点                                                   |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 适用于多种系统                                               | 属于top-down工具，只能关注major failure                      |
  | 在设计阶段即采用FMEA，可有效降低equipment modification的成本 | 其他分析工具可能会做得更好                                   |
  | 增加quality/ reliability/ safety/ 企业形象/ 竞争力，减少生产废弃物（scrap） | FMEA可与其他工具一起发现top level中更多的问题                |
  | 关注loss prevention，消除potential failure                   | 分析复杂多层系统时，FMEA方法会很复杂和冗长，时间和金钱成本较高 |

### （4）Criticality Analysis

- criticality analysis是识别system的critical component，并对lose each component的severity进行rank
- criticality analysis的目标（goal）是prevent/ reduce harmful event的severity，并根据priority（critical failure）来address event
- criticality analysis的specific action（consequence）包括
  - eliminate failure mode
  - minimize severity (consequences)
  - reduce occurrence
  - improve detection

#### 1）使用criticality analysis进行FMEA流程

- criticality analysis会识别系统关键部分，并对失去某部分后造成的结果进行优先级排序

- ==criticality analysis和FMEA混合（combine，paired）后，可通过识别critical failure order的方式，帮助企业prevent harmful event或reduce harmful event severity==

- criticality analysis将failure分成4类

  |      | criticality analysis对failure的分类（category）        |
  | ---- | ------------------------------------------------------ |
  | 1    | 导致unscheduled maintenance的failure                   |
  | 2    | 导致delay or loss of operational availability的failure |
  | 3    | 导致整个mission failure的failure                       |
  | 4    | 导致potential life loss的failure                       |

#### 2）risk priority number （RPN）

- 评估风险时，会对每一种critical failure的后果进行评分，此项分数决定每一个FMEA item的风险级别

- RPN由三项组成

  | RPN                 | 缩写 | 评估内容                      |
  | ------------------- | ---- | ----------------------------- |
  | consequence ranking | C    | 评估severity                  |
  | occurrence ranking  | O    | 评估发生率/可能性             |
  | detection ranking   | D    | 评估无法检测到failure的可能性 |

  - 每项得分为1-5或1-10（分数越高问题越严重），三项相乘得出RPN，每项failure的RPN得出后，相互之间进行比较。
  - 分数最高的问题需要优先解决，但分数最高并不意味问题最严重（criticality）
    - C (consequence ranking) 较高的应当最优先处理
    - C*O高的第二处理（C * O = criticality score, 代表对整个系统failure的可能）

### （5）Fault Tree Analysis (FTA)

- ==fault tree analysis/ FTA是分析particular system failure，进而trace leading to system failure的event（backward in time）==
- ==FTA中，risk manager会examine一些列导致accident的event和condition，进而通过interrupt event sequence的方式，来防止failure occur==
- FTA是从最终事件出发，按时间，从后向前倒推导致损失的原因
  - ==FTA使用deductive method（演绎法），从general出发，逐渐发现具体原因，找出一系列的问题所在，通过interrupt event sequence来prevent accident occur==

#### 1）FTA的本质

- accident在fault tree的top（top event）

- branch是necessary to produce accident的event（具体事件）

- branch通过or gate或and gate联系（表明原因与accident间的relationship）

  |          | 解释                                                 | mark                                               |
  | -------- | ---------------------------------------------------- | -------------------------------------------------- |
  | or gate  | or gate是表示某些原因单独出现即可导致损失事件        | 必须保证所有原因都不发生，才能避免最终的损失事件   |
  | and gate | and gate是表示必须所有原因同时出现，才会导致损失事件 | 只要保证其中一个原因不发生，即可避免最终的损失事件 |

#### 2）在fault tree中增加probability

- 如果已知每个casual event的probability，则可计算accident的probability
  - or gate = p（a）+ p（b）-p（a）* p（b）
  - and gate = p（a）* p（b）

#### 3）FTA在loss control方面的应用

- FTA通常会建议loss prevention
- loss control对or gate和and gate的方法不一致
- 为保证loss control的效果，fault tree需要尽可能完整和准确。不完整的fault tree可能会omit整条原因链

#### 4）FTA的步骤

- 确定最终的harmful event以构建fault tree树顶，事件需要详细描述
- 从最终事件出发，逐级找出原因
- 确定原因相互之间的关系（对最终事件）: 属于or gate或and gate
- 评估fault tree, 确定可能的改进方案
- 向管理层进行推荐风控手段

#### 5）FTA的assumption和limitation

- FTA的assumption
  - 所有的部分（原因）只存在两种可能：成功/ 失败（operational/ not operational）
  - 每种failure都与其他部分相互独立
  - 每种failure的发生率不变。
  - 为便于管理，fault tree一般会限制failure的数量（可能会忽视某些原因），但依然能为评估harmful event提供帮助
- FTA的缺点（limitation）
  - 如果不知道underlying event/ base event的probability，则无法预估top event的probability
  - 如果casual event不在fault tree中，则无法探明导致accident的important pathway（即只有知晓所有原因后，才能知道top event的发生轨迹）
  - fault tree属于静态（static）分析，若environment或流程改变，fault tree需要重建
  - 无法描述human error，domino effect或conditional failure（继而会导致one another in succession和culminate accident）
    - ==conditional failure是指traditional analysis无法account for (解释) human error or succession that occurs when one event causes another，进而导致accident culminate==

## 2. Sensor-Generated-Data Analysis Techniques

- ==microprocessor capacity，battery miniaturization和camera clarity的rapid advance已经预示（herald）sensor和wearable technology的revolution==

  > holter monitor属于sensor，其可用于detect cardiac attack/ arrest

- ==sensor的缺点（limitation）是只有找到all sensor的accumulated data point的relationship后（这会解释environmental condition/ worker attribute/ other relevant factor等对accident occurring probability的effect），才能fully realize to use sensor==

- data analytics的步骤（step）

  | 步骤 | 具体步骤                                                     | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 1    | ==collect data and categorize==                              | -                                                            |
  | 2    | 将category发展处similar attribute                            | -                                                            |
  | 3    | ==independently analyze each attribute，以获取information gain== | -                                                            |
  | 4    | 对training data使用supervised learning technique（如classification tree algorithm） | algorithm会execute recursively，进而显示如何使用attribute combination来predict accident occurring的probability |
  | 5    | ==用holdout data来test model，以确定predictive power==       | 使用not used in model development的data                      |

- attribute combination的classification result会通过arrow sequence来连接rectangle，每个rectangle都描述了其connected attribute的actual value

- 使用training data时，会根据model correctly predict specified class的time percentage，在rectangle上增加probability

- classification tree algorithm的目标（goal）是确定accident occur/ not occur的probability

  - ==可通过classification tree，对defined target variable和known attribute进行segment data，进而确定workplace accident的probability==

# 二、使用Text Mining和Social Network Analysis来Assess Reputation Risk

## 1. Reputation Risk

- ==reputation是关系到企业goal and value的intangible asset==
  - ==reputation是企业legitimacy的pillar，也是企业operate/ not to operate的social license==
  - ==reputation源于stakeholder的behavior和opinion，并随时间而增长==
- reputation涉及stakeholder experience和expectation的的comparison
- data analytics为企业提供了一种方式，使其能够跟上service and product的shifting perception
  - 可使用text mining and social network analysis来提出plan of action
- ==reputation risk是negative publicity，不管是否是true，都会damage reputation，进而影响其operate business的ability==
  - reputation risk涉及管理 company and general public/ stakeholder and employee之间的interaction（所以risk manager必须使用systemic approach来管理reputation risk）
- 有时intangible asset可占到企业1/3到3/4的价值，风管人员应好好管理
  - reputation是决定未来商业前景的关键因素，由过去和现在人们对企业的看法形成，这种看法存在于stakeholder的潜意识中，并会随时间增长，是关乎企业目标和价值的无形资产
  - 当满足或超出stakeholder预期时，企业可得到较好的reputation
  - 为维护好reputation，企业必须赢得并保持key stakeholder的信任和自信。好的reputation也可提供竞争优势或提供更高效的服务（此项针对政府部门）
- reputation是长期建立的，但poor decision可瞬间将其变坏
  - 无法满足stakeholder的利益会造成bad reputation
  - bad reputation会造成企业损失，甚至可能威胁企业的长期生存
  - 任何事件或情况都会给企业的reputation造成或好或坏的影响

### （1）reputation属于asset

- 由于intrinsic, intangible及其能对未来价值产生影响的属性，reputation属于企业的重要资产。有些无形资产（如trademark, license）是可以量化的，但reputation在财报上无法作为无形资产进行量化。reputation的价值基于stakeholder的belief（如企业reputation在招聘高潜力员工时会有重要影响）
  - reputation管理包括stakeholder expectation的管理和reputation会面临危机和机会。
  - 企业应当知晓各key stakeholder的关注，并将其排序（因为各stakeholder的预期不一样，每个stakeholder的具体关注点也不一样）。
  - stakeholder可分为internal（如企业管理层，executive board，员工等）和external（shareholder，customer，supplier，regulator， governmental entity等）。

- 可使用power/ interest matrix来确定stakeholder的范围并确定优先级

### （2）主要风险来源

- non-compliance，D&O的unethical behavior，filing of major lawsuit都会威胁reputation。

- 企业通常只考虑不利因素（downside），但也应考虑upside方面的风险（即可增加reputation的机会）。企业应当寻找利用风险的机会以扩大其reputation影响。

- 为保护或利用声誉，必须确定reputation risk的来源。reputation的key driver会成为之后reputation的风险来源。企业应当考虑key driver会如何interact with stakeholder。

- 潜在的风险点如下

  | potential risk             | 具体解释                                                     |
  | -------------------------- | ------------------------------------------------------------ |
  | goal and mission           | 财务表现和长期投资 financial performance/ long-term investment value |
  | rules (law and regulation) | 公司治理和领导力 corporate governance and leadership<br/><br/>社会责任 corporate social responsibility<br/><br/>合规 regulatory and legal compliance |
  | value (internal factor)    | 工作talent和文化 workplace talent and culture<br/><br/>客户的承诺 deliver on customer promise<br/><br/>沟通与危机管理 communications and crisis management |

### （3）管理reputation risk的系统方法

- 企业会和stakeholder，所处environment（internal/ external）及资源产生联系。需从整体考虑相互之间的关系来确定对reputation的影响。可通过essential triangle研究reputation risk及结果。
- 企业由其本身，message和stakeholder expectation三者（这三者就是essential triangle的三个顶点）之间的动态平衡，这种平衡会给reputation造成影响。
  - 企业本身：企业自身即各项资源的混合；
  - Message： stakeholder会对企业有各种预期，企业必须取得stakeholder的信任，并知晓stakeholder假设企业会整合并优化各项资源。很多企业使用transparent business practice和好的governance来达到目标（如企业会及时告知stakeholder其决策）。向stakeholder传递消息非常重要，特别是关于business plan/ value/ goal等信息，这种communication会对reputation有影响（可好可坏）。

- 企业还应管理和general public/ stakeholder/ employee之间的interaction。reputation mechanism, how interact with and communication可围绕三个ethical dimension进行（goal and mission/ rules(law and regulation)/ value (internal force)）这种管理叫做systemic approach。
- 企业高层负责设定清晰的目标，当企业的信息传递不匹配或不及时时，会发生reputation risk。当企业面临reputation risk时，需要快速做出决策，领导层和企业文化会在其中起关键作用。reputation risk management也适用于政府机构等非营利性组织。

### （4）实现reputation risk管理

- 实施reputation risk management需要viewed holistically + implemented actively + monitored

  |                                                   |                                                              |
  | ------------------------------------------------- | ------------------------------------------------------------ |
  | identify, evaluate and prioritize reputation risk | 识别reputation risk的key driver，评估risk 上升或下降的tangible consequence，并进行风险排序。 |
  | develop and implement risk response               | 判定risk是否为偶然（contingent），是否会是威胁或机会，与企业risk appetite的关系（即企业是否可接受这种风险损失），风险是否treatable以及cost of treatment. risk response实施时需关注message在企业和stakeholder传递中的gap。 |
  | monitor and report                                | 管理层需要持续关注风险，尽早作出corrective action。risk的任何变化都要告知相关人员（不管是internal还是external），以便于timely response |

- 在implement reputation risk management时，需要清晰明晰role和responsibility，这要从CEO和Board or Director开始，但最终情况是企业的所有stakeholder都要参与其中。管理reputation risk 的barrier包括lack of clarity, resources or awareness. 企业需要让所有operational level manager在发生disruption时进行有效回应

## 2. Text Mining

- ==text mining的步骤==

  |      | 具体步骤                                                     | mark/ 案例                                                   |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 1    | ==找到进行sentiment analysis的attribute==                    | -                                                            |
  | 2    | clean up                                                     | eliminate space/ punctuation/ 或无法提供information的word（stop word） |
  | 3    | 通过remove prefixes and suffixes (stemming)的方式，减少stem上的word | -                                                            |
  | 4    | 创建2个dictionary                                            | 一个dictionary有favorable word，另一个有unfavorable word     |
  | 5    | ==对certain term执行sentiment analysis (包括term frequency（TF） 和inverse document frequency（IDF）)== | ==term frequency是衡量how often a term appears in a document==<br /><br />若一个term在only one blog post中使用多次，则其具有high TF和high IDF（IDF可用于衡量blog corpus的rarity，和certain term found in an abundance of mention）<br /><br />high TF + high IDF说明该term值得consideration |

## 3. Social Network Analysis

- sociogram是small social network

  - sociogram对分析small social network非常useful

- matrix是very large social network

- ==data scientist会通过examine social network connection through sociogram的方式，来知道一个人或几个人的negative sentiment可以传播多远==

  - ==negative sentiment的influence很大程度上取决于sociogram中的poster metrics（centrality measure）==

    |             | 解释                                                         |
    | ----------- | ------------------------------------------------------------ |
    | closeness   | closeness是衡量network中particular node和其他node之间的average distance或path length |
    | degree      | degree是衡量每个node的connection number                      |
    | betweenness | betweenness是衡量network中，how many times a particular node is part of the shortest path between two other nodes |

  - ==closeness/ degree/ betweenness对衡量one network的centrality measure非常重要，对衡量how one person/ few people can connect multiple social media network也很重要==

- 通过使用text mining和social network analysis，targeted message会发送到more influence和more effectively respond to reputation risk的correct group
- risk manager可通过考虑social network中的local variable和network variable的combination，来better target a response to crisis
- ==企业不能通过combine piece of user information的方式，来specifically identify individual customer（此举属于reputation risk），企业可采用precautions的方式来预防此种行为==
  
  - ==data scientist可以继续开发ensure individual privacy的新方法，从而让企业reap the benefit of network analysis==
- 对social data perform text mining后，可进行network analysis，此举可为how far/ how quickly a sentiment can spread 提供information

# 三、将Clustering和Linear Modeling用于Loss Development

- 对风管人员来说，尽可能准确的确定loss的ultimate value非常重要

  - 尽量准确的确定loss的ultimate value属于保险公司的biggest obligation（最大责任），剩余的money可用于insurance operation

- long-tail claim是loss date到loss closure的duration超过1年的claim（由于multiple factor，long-tail claim很难predict）

- ultimate loss是accident year中，对all loss的final paid amount

  - $ultimate\ loss = paid\ loss + loss\ reserve + loss\ adjustment\ expense\ reserve\ (LAER)$
  - loss development factor是基于过往accident year得到loss development data
    - ultimate loss = each accident year的total incurred loss * loss development factor
  - ==某一accident year的ultimate loss prediction基于total incurred loss==
  - liability loss会在66个月内达到ultimate loss value
  - 对于closed claim，通常假设其已达到ultimate loss value

- adverse development是对inadequate reserve的case，增加claim cost

  - ==如果不知道adverse factor，则可使用unsupervised learning（如k-means，clustering等）的方式寻找pattern==

    > outlier包括在18 month evaluation point上，claim size和incurred loss的比例（$\cfrac{claim\ size}{incurred\ loss}$ ）> 3.5的属于outlier

- excess liability insurance是承保loss超过underlying insurance coverage limit，或超过retention amount的情况

## 1. Procedure Overview

## 2. Collect and Organize Past Data

## 3. 使用Data Analysis Techniques

- ==cluster analysis是一种exploratory technique，其没有predefined variable，所以适用于不知道attribute的情况==

- high severity claim的attribute包括

  |      | high severity claim的attribute/ factor  |
  | ---- | --------------------------------------- |
  | 1    | accident date后，1+ week之后才有respond |
  | 2    | claim rep denied/ deny liability        |
  | 3    | claimant有attorney                      |
  | 4    | large jury award                        |

  - 对于上述high severity claim factor，data scientist可根据attribute，使用Generalized Linear Model (GLM) 来预测average ultimate severity（作为target variable）
  - 相应的，claim reserve也应当基于GLM result

## 4. Develop a More Accurate Method 以 Predict Loss

- ==开发完评估ultimate loss的predictive model后，应当repeat analysis，以确定accuracy==