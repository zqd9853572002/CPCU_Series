Root Cause Analysis
# 一、Root Cause Analysis简介：
- ==root cause（直接导致事件的根本原因）可让企业知晓风险事件的最初原因，并可据此引以为戒。==
- ==root cause analysis（RCA，使用其他分析技术来鉴别意外根本原因的系统流程）可用于了解有害事件的深层原因。==
- 风管人员应关注影响企业workplace安全的事件。==harmful event通常和basic cause（physical/ human/ organizational）中的一个有关。==
	> ==physical cause是tangible或material物体导致的损失。==
	>
	> ==human cause是人的error或inaction导致的损失。==
	>
	> ==organizational cause是faulty system/ process/ policy有问题（如流程和责任人不清）导致的损失。==

## ==1. root cause的特点==
- ==root cause是详细和具体的根本原因（specific underlying cause），而非只是概括的描述。==
- ==root cause可reasonable identified，找到问题根源。==
- ==root cause必须是可改进的东西。==
- ==root cause提供可有效预防未来同类事故发生的方案。==


##	2. root cause analysis（RCA）
- 通常在事件发生后才会进行，但其也可预测可能妨害企业的事件（此时企业可进行提前预防，而非等事件发生后再面对）。
- ==root cause analysis的approach包括：safety-based, production-based (industrial manufacturing), process-based, failure-based, system-based.==
- ==RCA的流程包括：==
	- ==（1）收集数据==
	需要circumstance，fact，cause的所有数据
	- ==（2）causal factors（起因） charting==
		为企业提供并分析数据结构框架（画出事件顺序图，并列明root cause问题），并提供调查阶段的gap和deficiency。
	- ==（3）root cause identification==
使用mapping或flow charting可找出causal factor的每一个原因。
	- ==（4）推荐解决方案并实施==
推荐的解决方案需要实施并进行跟踪。

# 二、failure mode and effects analysis （FMEA）
- ==与从事件触发相反，FMEA从原因开始分析，推出其如何助推事件发生。==
- 该分析从产品开发和运营开始分析，目标为鉴别==failure mode（产品/ 流程/ 设计方面的缺陷==）并完成==effect analysis（研究failure结果，决定root cause）==。
## 1. 概述

### （1）FMEA需要确定系统的indenture level
- ==indenture level指某个item的relative complexity within assembly/ system or function（即整个系统从大到小的级别），确定failure effect时需要鉴别effect在整个系统中的地位。==
- ==effect分为local effect（某个failure影响同级别indenture），next-higher-level effect（影响上一层级的情况）, end effect（影响最高级indenture系统的情况）。==
### （2）FMEA的主要目标
- 保证customer safety + 生产出quality的产品。
- ==FMEA的输出结包括：强化流程设计，最小化或消除产品设计方面的问题，研发减少failure发生率的系统，identify human error mode及其影响，研发追踪potential future design问题的系统。==

### ==（3）FEMA也可用于其他服务==
- ==可用于concept（设计早期阶段分析系统及subsystem），design（生产之前分析产品），process，equipment，service，system，software。==

## 2. FEMA的流程
- FEMA最好由团队一起完成，在早期设计中用于减少损失的发生率或降低severity。

### ==（1）FEMA流程==
- ==确定范围和目标==
- ==组织团队研讨==
- ==定义components及其功能==
- ==找出每个部分的潜在问题和影响==
- ==提出改进措施（预防或减少风险）==

### （2）使用criticality analysis进行FEMA流程
==criticality analysis会识别系统关键部分，并对失去某部分后造成的结果进行优先级排序。==
- ==criticality analysis将failure分成4类==
	- 导致unscheduled maintenance的failure
	- 导致delay or loss of operational availability的failure
	- 会导致整个mission failure的failure
	- 会导致potential life loss的failure。

### （3）risk priority number （RPN）
- ==评估风险时对每一种critical failure的后果进行评分，此项分数决定每一个FEMA item的风险级别。==
- ==RPN由consequence ranking（C，评估severity），occurrence ranking（O，评估发生率/可能性），detection ranking（D，评估无法检测到failure的可能性）三项共同决定。==
- 每项得分为1-5或1-10（分数越高问题越严重），三项得分相乘得出RPN，每项failure的RPN得出后，相互之间进行比较。
- ==分数最高的问题需要优先解决，但分数最高并不意味问题最严重（criticality）。一般来说，C (consequence ranking) 较高的应当最优先处理，C*O高的第二处理（C * O = criticality score, 代表对整个系统failure的可能）。==

### ==（4）FEMA的优点==
- ==适用于多种系统==
- ==在设计阶段即采用FEMA，可有效降低equipment modification的成本。==
- ==增加quality/ reliability/ safety/ 企业形象/ 竞争力，减少生产废弃物（scrap）==
- ==关注loss prevention，消除潜在failure==

### ==（5）FEMA的缺点==
- ==属于top-down工具，只能关注major failure==
- ==其他分析工具可能会做得更好==
- ==FEMA可与其他工具一起发现top level中更多的问题==
- ==分析复杂多层系统时，FEMA方法会很复杂和冗长，时间和金钱成本较高==

# 三、Fault Tree Analysis（FTA）
==故障树分析，从最终事件出发，按时间从后向前倒推导致损失的原因。使用deductive method（演绎法），从general出发逐渐发现具体原因，找出一系列的问题所在，通过阻止事件的顺序（interrupt event sequence）来防止最终事件发生。==

## 1. Fault Tree Analysis （FTA）的本质

- ==最终事件在树顶（top event）==
- ==树的枝叶（方块）用以描述具体事件。==
- ==枝叶（具体事件）通过or gate（表示某些原因单独出现即可导致损失事件）或and gate（表示必须所有原因同时出现，才会导致损失事件）联系（表明原因与最终事件间的关联）。==
	- or gate: 必须保证所有原因都不发生，才能避免最终的损失事件；
	- and gate: 只要保证其中一个原因不发生，即可避免最终的损失事件。

## 2. 在fault tree中增加发生率（probability）
- 如果每项原因的发生率已知，则可计算最终事件的发生率。
	- ==or gate = p（a）+ p（b）-p（a）* p（b）==
	- ==and gate = p（a）* p（b）==

## 3. loss control方面的应用
- ==Fault Tree Analysis (FTA) 通常会建议loss prevention==
- ==or gate和and gate的loss control方法不一致。==
- ==为保证loss control的效果，fault tree需要尽可能完整和准确。不完整的fault tree可能会omit整条原因链。==

## 4. fault tree analysis（FTA）的步骤
（1）确定最终的harmful event以构建fault tree树顶，事件需要详细描述
（2）从最终事件出发，逐级找出原因
（3）确定原因相互之间的关系（对最终事件）: 属于or gate或and gate
（4）评估fault tree, 确定可能的改进方案
（5）向管理层进行推荐风控手段

## 5. falty tree analysis的假设与限制
### （1）假设
- 所有的部分（原因）只存在两种可能：成功/ 失败（operational/ not operational）
- 每种failure都与其他部分相互独立
- 每种failure的发生率不变。
- 为便于管理，fault tree一般会限制failure的数量（可能会忽视某些原因），但依然能为评估harmful event提供帮助

### （2）缺点
- ==如果各原因的发生率不知道，那么top event的发生率也无法预估==
- ==只有知晓所有原因后，才能知道top event的发生轨迹==
- ==fault tree属于静态（static）分析，若环境或流程改变，fault tree需要重建==
- ==难以描述human error==
- ==难以描述domino effect或conditional failure==

# 四、5 whys分析和fishbone diagram
- 风管人员先进行brainstorming找出导致最终事件的各种原因，分类，并追踪到最原始的问题。
- 鱼骨图的结果是找出风险事件的underlying cause，消除它以防后患。
- 鱼骨图也被称为herring-bone diagram/ cause-and-effect diagram/ fishikawa diagram
## 1. 5 whys analysis: 
- ==属于鱼骨图的重要组成部分，主要用于解决human factor（通常是流程和管理实践导致root cause）。==
- 确定某个问题后，持续问why（通常问5次，但不限于5次），继而找到ultimate cause。
- ==5 whys分析可以防止风管人员依赖错误的假设，并设法追踪到问题的源头。==

### ==（1）5 whys分析的步骤==
- ==明确描述需要调查的具体问题==
- ==对问题持续问为什么，找到答案==
- ==若依然无法揭示问题的root cause，调查为何出现第二步中的问题==
- ==重复2-3步，了解最终的原因==

### ==（2）5 whys分析的优点和缺点==
- ==优点：==
	- ==确定问题的root cause==
	- ==当发现多个root cause时，可帮助寻找其中的关系==
	- ==通常不需要统计分析或收集数据。==

- ==缺点：==
	- ==风管人员可能在找到真正原因之前就停止深入调查==
	- ==有可能每个问题只关注某一个答案==
	- ==企业有时不会帮助风管人员了解到真正的原因==
	- ==uninformed人员可能无法问出相关的问题==
	- ==不同风管人员对于同一个问题可能会找出不同的答案（但对于多种原因导致同一个事件的，这条属于优势）。==

## 2. 鱼骨图（fishbone diagram）
- 5 whys分析是最为流行的在头脑风暴中找到所有原因的分析方法。这些原因在鱼骨图中通过鱼骨和鱼骨髓连接，骨髓指向最终的事件。	
- 鱼骨图最常用于industry或流程方面的问题。制造业中通常使用6M来检视问题原因。	
	> ==6M包括Machine（technology，任何机器或技术）,Method（process，具体执行过程），Material（任何用于生产最终产品的物品，包括信息），Manpower（Phisical work/ Mindpower/ brain work，任何参与的人）/ ，Measurement（inspection，流程中产生的用于判断product quality的数据），Milieu/ Mother Nature (Environment，当地因素，包括天气，温度，习俗，文化等)。==

	> 4M只包含前四项，属于简化版。
	>
	> 8M在6M基础上增加Management/ money power和Maintenance。	
	>
	> 其他类型企业有时使用8S（Product/ Service, Price, Place, Promotion/ Environment, People, Process, Physical Evidence, Productivity & Quality）或5S (Surroundings, Suppliers, Systems, Skills, Safety)

### ==（1）鱼骨图的步骤==
- ==画鱼骨图时，风管人员应一同在场，以确认所有问题原因都在头脑风暴阶段体现出来。==
	- ==团队同意问题的陈述==
	- ==沿着最终的effect画出横线（作为骨髓）==
	- ==通过头脑风暴列出原因的主要类别（类别取决于企业类型，组织架构和系统）==
	- ==将各类别通过鱼骨与骨髓链接==
	- ==可通过5 whys写出每个问题的原因==
	- ==写出上一步中问题的具体原因，可以进行归类==
	- ==对每个具体原因继续进行5 whys分析==
	- ==团队应关注问题最少的分类==
	- ==确定root cause后，应拿出补救措施（remedy）并执行，以防再次发生==