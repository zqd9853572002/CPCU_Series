# 一、data & cyber security laws

## 1. 现状

- US Government执行data law很慢，只在相关领域应用了data law
- 很多州对federal level未覆盖的gap进行了立法

## 2. 重要的federal law

- Federal Trade Commission Act (FTCA) - 1914
  - 禁止unfair或deceptive practice
  - 已经应用于禁止使用非法获取的consumer data
- Family Educational Rights & Privacy Act (FERPA) - 1974
  - 限制access学生educational record的时间
- Computer Fraud and Abuse Act (CFAA) - 1986
  - 禁止unauthorized to access computer
  - 第一个涉及hacking的regulation
- ==Health Insurance Portability and Accountability Act (HIPAA) - 1996==
  - ==规定了medical info如何store/ shared的情况，以及如果发生breach，需要做什么==
  - ==适用于healthcare provider, insurer等（因为这些人会处理medical info）==
    - ==特别适用于保险公司的claim部门==
- Children's Online Protection Act (COPA) - 1998
  - 对于受众是13岁以下kid的网站，实行 data collection & privacy requirement
- ==Gramm-Leach-Bliley Act /Financial Modernization Act (GLBA, FMA) - 1999==
  - ==主要监管financial data（财务数据）的collection, use, disclosure==
  - ==用于金融机构（银行，保险公司等）==
- Homeland Security Act (HSA) - 2002
  - 创建了Department of Homeland Security (DHS)
  - DHS Privacy Office
    - 强调和homeland security相关的privacy issue
    - 回应privacy violation相关的complaint
- Federal Information Security Management Act (FISMA)  - 2002
  - 为federal agency提供框架（用于develop/ implement information security program）
- Cybersecurity Information Sharing Act (CISA) - 2015
  - 授权公司monitor并defend information system
  - 在有government授权的情况下，保护公司可voluntary share cyber threat方面的信息

## 3. 其他key effort

- ==Payment Card Industry Data Security Standard (PCIDSS)==
  - ==不属于law==
  - ==为credit card公司设定了information policy/ procedure==
  - ==要处理大量credit card transaction的公司，必须采用PCIDSS==
- Executive Order 13636 - Improving Critical Infrastructure Cybersecurity (ICC)
  - 让政府promote/ incentivize 采用cyber security practice和cyber threat information sharing

## 4. 公司需注意law，以确保compliance和customer trust

### （1） data protection law的三个领域

- data privacy
  - 涉及data的appropriate use/ access
  - data privacy的内容
    - 能收集何种信息
    - 如何share data，可以和谁share data
    - 如何dispose data
  - California Consumer Privacy Act (CCPA)
    - 最严格的data privacy law
    - 给consumer的权利
      - consumer可知晓收集了什么data，如何收集的
      - 有权知道data是否sold或disclose，以及卖给谁，提供给谁
      - 有权opt out出卖其data的business
      - 可选择是否要删除info（有些情况例外）
      - 在执行上述right时，不被discrimination
    - CCPA被很多公司作为de facto（default默认）standard
    - 为其他州的privacy law提供了model
- breach notification
  - ==如果personally identifiable info（PII）泄露，所有州均要求公司向个人通知security breach==
	  - PII包括个人的unique info（包括name, address, SSN等），需要safekeeping和confidentiality
	  - ==处理PII信息的公司要遵守所在州的法律==
  - security breach包括: 未授权接入computerized personal info
	  - ==如果州法有breach notification law，并要求为encrypted data提供safe harbor，则企业更有可能encrypt data（此举可减少unauthorized access data的风险）==
	  - safe harbor
	    - ==如果做出了good faith effort 或提供了law要求的intended protection，则可ease/ eliminate penalty或compliance requirement==
	    - ==针对encrypted data（已加密数据），很多州免除了发生breach后，要进行notification 的要求==
- data security
  - 涉及protection of data from unauthorized access
  - 各州的law不一样
  - 法律要求公司要有的东西
    - 写明的information-security procedures
    - 对wireless communicate或储存在personal device上的personal info进行encryption（加密）
    - 每年review security measures
    - 遵守PCIDSS standard
    - 写明的 cyber security procedures
    - CISO (chief information security officer, 负责protecting data和information system
  - cyber security: 保护data（防止通过互联网，unauthorized access to data）

### （2） General Data Protection Regulation (GDPR)

- 欧盟（European Union (EU)）建立的comprehensive且formal的data protection rules
- 是personal data regulation standard 的global model
  - ==适用于EU的公司，以及处理EU resident数据的公司==
- ==基于的 fundamental premise： individual拥有personal data==
- requirement
  - 只收集需要perform task的data（需为minimum amount）
  - ==只能person consent的情况下，收集并储存data==
  - 只有在需要perform task时，keep data
  - ==如果person提出request，要清除数据（erase data）==
  - ==如果发生breach，必须在72小时内通知authority和 individual==
  - 允许opt out from having machine make decision about them
  - 所做的document必须comply with GDPR
  - ==data move through到另一组织时，data必须可追踪==
  - 执行对ID security vulnerability的assessment

### （3） best practice

- 建立strict security的culture
- 指定专人负责data security（如chief info security officer，CISO）
- 只收集或储存能完成task的minimum data
- 限定access personal data的 employee 数量
- 在personal device上安装security feature
- 对于 unattended/ unlocked devices, 加强 security policy
- ==员工培训（training）==
  - ==在接入public network前，要precaution==
  - ==何时允许工作电脑上使用external device==
  - ==phishing/ malicious email（钓鱼邮件）==
  - ==对于不再需要的personal data，如何properly destroy==
  - ==报告suspicious email/ customer==
- 建立online privacy policy，解释公司如何use/ control personal information
- 如果data 泄露，可用其作为teachable moment，而不需说明who at fault。

# 二、strict liability/ absolute liability

## 1. strict liability/ absolute liability（严格责任）

- ==strict liability/ absolute liability的定义：即使进行了reasonably act，当事人没有fault的情况下，也要负责==
- ==适用于extremely dangerous/ abnormal 的情况==
- ==可扩展至things artificially brought onto land 的情况 和 nonuser（bystanders，旁观者，即不是product的实际使用者受伤的，也可根据strict liability起诉）==

## 2. ultrahazardous activity（特别危险的活动）

- ==ultrahazardous activity的定义：abnormally dangerous activity（非常规的危险活动），即使有reasonable care，也无法perform safely==

  > ==explosive substance（危险物品）的storage或 transportation均属于ultrahazardous activity==

- ==plaintiff负责举证，plaintiff必须证明3种情况==

  - ==很有可能导致serious harm的风险==
  - ==perform时，必然会伴随high risk degree==
  - ==activity不常发生在进行conduct的area中（即unusual risk in community）==

- 如果发生harm result，则performer要负责

- ==根据Ryland vs. Fletcher case, 如果dangerous substance被artificially（人为的）散播到real property上，进而导致escape和damage的，也要负责==

## 3. pets

- ==如果owner知道动物会有propensity harm/ attach，则动物的owner要负责==

  > 自家养的牛跑到别人土地上，引起损失，可使用strict liability（可不适用negligence）

- ==法律对domestic animal（家养动物）和wild animal（野生动物,根据local custom，not devoted to people use的动物）不一样==

  - ==根据 local custom，各地对待这两种动物的法律不一样==

    > ==大部分州不支持对猫狗适用strict liability（因为一般不会引起serious damage），但主人知道可能会引起重大损失（vicious propensity  to cause injury）的除外==

  - ==wild animal 的owner，对该动物引起的任何act/ damage都负strict liability==

## 4. toxic tort

- ==toxic tort的定义：将他人置于toxic substance时，要承担责任==
- ==和其他tort不一样，toxic tort通常基于statute（而不基于common law）来确定toxic tort==

## 5. environmental law

- ==environmental law主要处理environment protection和maintenance==
- ==environmental law 的主要measure==
  - ==prevent damage==
    - environmental-impact statement
    - 分配liability的measure
    - 分配cleanup liability的measure

# 三、product liability

## 1. product liability

- ==product liability的定义：对产品负责任==

## 2. product liability suit的基础

- misrepresentation
	
	- ==产品实际情况和宣传不符==
- breach of warranty
	- ==breach of warranty可以complete defense或partial defense==
  - express warranty
  - ==implied warranty是seller没有express state的情况下，也要warrant的certain fact==

- strict liability和negligence的区别

  - general negligence

    - plaintiff必须证明product引起了损失

    - ==product defect的类型==

      - ==manufacture/ assembly defect（制造或组装defect）==
      
        - ==产品不符合original design或specification==
        - ==使用poor-quality material或 shoddy assembly work（劣质装配），即未能使用reasonable care==
           - ==属于最易证明的strict liability==
      
        - ==design defect (设计fault)==
      
          - 为确定产品是否需要 unreasonable danger waning，或是否failure to warn users（未能warn user），一般包括如下三个因素（此项不是negligence 的主要关注点）
	    
	          - ==danger degree（各产品的degree不同）==
	    
            - ==danger的knowledge==
      
            - ==foreseeability of dangerous use==
      
                > ==知道用wet hand碰faulty switch，会导致burn。==
                >
                > ==根据common law不负责，但根据现在的法律是有责任的==
      
      - 产品离开生产厂家后发生的defect，生产厂不负责
    
  - strict liability
  
    - ==不需证明negligence或intent to harm, 只关注product本身==
    - ==和manufacture的conduct无关==

## 3. defense（抗辩）

- state of art（技术水平）

  - 在生产product时，根据当时的science/ knowledge，产品是安全的
  - 如果没有danger indication，或无法通过技术获得danger knowledge，则生产商无理由停止生产或使用
  - ==state of art defense 不支持 complete defense==

  > 之前在建筑中使用asbestos（石棉），现在知道asbestos危害健康。

- 已经遵守了statutes或regulation，但据此理由无法成为conclusive defense

  - plaintiff的反驳：可引用reasonable manufacture使用了precautions作为证据

- 已经遵守了product specification

  - 如果制造商按照其他人的specification制造，则制造商不负责相关损失

- ==open & obvious danger (user should have known of danger)==

  - ==如果商品很明显属于danger，则制造商没有warning或其他precaution的duty==

  - ==正常使用时，发生unreasonably dangerous（非常规危险）的，制造商要承担strict liability==

    > 如knife, gun, gasoline等

- plaintiff’s knowledge (plaintiff has equal knowledge of risks as manufacturer)（==如果plaintiff和manufacture对商品的knowledge相同，则制造商没有warn duty==）

- comparative negligence (比较过失)

  - ==active negligence和assumption of risk==

    - ==消费者在知道existing defect knowledge的情况下，仍自愿使用product。==

    - ==defendant负责证明 plaintiff知道defect或danger==

      > ==plaintiff 知道物品会burn skin，但操作时不戴protective glove，属于assumption of risk==

  - passive negligence:

    - plaintiff’s failure to discover a product’s defect or to guard against possible defect（==passive negligence的定义：plaintiff未能发现product defect，或未能防范可能的defect，此时可要求赔偿==）

      > 电线明显frayed（磨损），但plaintiff未注意到

- ==misuse of product：错误使用产品导致的损失，制造商不负责==

- ==alteration of product：改造product导致的损失，制造商不负责==

# 四、types of damage that can be awarded（可获得的赔偿）

## 1. compensatory damage

- ==special damage==
  - ==special damage的定义：实际发生的损失==
  - ==special damage包括：medical expense, physical therapy, lost wage, earning loss和out of pocket expense==)
- ==general damage==
  - ==general damage的定义：给受害人的monetary award，用以弥补损失==
  - ==general damage包括: pain and suffering, disfigurement, loss of limb/ sight/ hearing, emotional distress（包括nightmare和phantom pain）==

## 2. punitive damage

- ==发生以下情况时，用以惩罚defendant==
  - ==defendant 故意 cause harm==
  - ==defendant的行为涉及maliciously, fraudulently, outrageously==

## 3. wrongful death action（非正常死亡诉讼）

- wrongful death action: 由deceased party的 survivor提起诉讼
- ==survival statute赋予 deceased person的estate，使其有权索要damage（从injury date到死亡时间的damage==
  - 允许提出compensatory damage（包括general damage）

# 五、和tort相关的liability 概念

## 1. joint tortfeasor (joint & several)

- 当多个negligence act涉及多个人时，会发生joint liability。

- ==joint tortfeasor分为joint和several==

  - ==joint tortfeasor==

    - ==joint tort是两个或以上的人，对第三方负有common duty，并由于common neglect act对第三方造成损害，且很难区分是哪个wrongdoer引起了fault/ harm==

      > 两辆车在路上赛车，发生碰撞后，导致第三人损伤，这种情况属于joint tort

  - ==several tortfeasor==

    - ==several tort是两个或以上的人的separate negligent act聚集在一起，产生single indivisible injury的情况==

- ==innocent party可从任何negligent的一方获得100%的damage赔偿（如果innocent party自身也要负责，则要扣除其自身负责的部分）==

	- ==支付了100%赔偿的negligent party，有权向其他negligent party要求赔偿appropriate portion==

  - ==contribution：如果一方支付的damage超过其应承担的damage share，其有权从其他tortfeasor处collect多付的部分==

- ==joint tortfeasor的目的：防止延误对innocent party的赔付（因为negligent party会对分摊多少责任进行dispute）==

- ==大部分jurisdiction会使用Uniform Contribution Among Joint Tortfeasors Act (UCAJTFA)==

## 2. expanded liability的概念

- enterprise liability/ industry-wide liability
  - ==enterprise liability/ industry-wide liability的定义：如果无法确定at fault的specific manufacture，则industry 中的每个成员都要对manufacture harmful/ defective product负责==
    - 每个制造商所负责任按照market share计算
    - 和joint/ several liability类似，plaintiff可从single defendant获得100%赔偿
- ==alternative liability==
	- ==defendant必须证明其未引起harm，或harm是由其他defendant引起的==
  
    - ==将proof burden转移给defendant (即defendant承担proof burden)==
  
  - ==适用于有多个defendant，但不确定哪一个at fault==
  
- ==market share liability==
	- ==defendant的liability根据market share的pro rata确定，但如果defendant能证明未涉及product的除外==
  - 和enterprise liability类似，但每个defendant的maximum exposure为market share（小于100%），而非100%。
- ==concert of action==
	
	- ==适用于多个defendant必须act together或act cooperatively，才能create dangerous product/ event的情况==
	
	  > ==如多人赛车，导致损失==
- ==conspiracy（阴谋）==
	
	- ==2个以上的当事人work together，有目的性的unlawful act==
- ==joint venture==
  - ==2个或以上的当事方形成的business association，用以完成特定project==
  - 为起诉joint venture的所有当事方，plaintiff必须证明如下4个因素
    - 各方同意合作，以完成business activity
    - 各方会分摊 profit/ loss
    - joint control of venture by all parties（所有方控制venture）
    - 各方对venture asset进行出资（contribution）

## 3. vicarious liability（连带责任）

- ==vicarious liability的定义：一方要为其他人的action负责==
  - ==principle和agent==
    - principle（授权方）授权agent（被授权方）代表其act
  - ==employer & employee==
    - ==employer对employee的act负责，但仅限于employment scope之内==
      - 法院有多种方法确定 employment scope，确定liability必须满足一定条件）
  - ==parent & child==
    - parent对minor child的tort不负责任，但有例外
    - 例外情况
      - ==child作为父母的agent或employee时，此时父母责任和principle或employer一样==
      - ==negligent entrustment的情况：父母给孩子dangerous instrument（危险用品，如枪或车），应当预计到孩子可能会cause harm==
      - ==negligent supervision的定义，未能让孩子远离cause harm的行为==
      - ==negligent entrustment和negligent supervision同时适用的情况==
        - ==父母给孩子dangerous article，且知道孩子可能会unreasonably risky use，父母未对孩子进行reasonable control exercise==
      - ==有些jurisdiction会使用 family purpose doctrine（车主对任何驾驶该车的family member造成的损害负责，即使孩子已经成年了也可用）==
      - 有些jurisdiction要求父母对孩子的theft/ vandalism等行为（根据statute要求）负责

## 4. Good Samaritan law

- ==good Samaritan law: 给予他人emergency assistance 的人免于ordinary negligence诉讼，但不免除gross negligence责任==

  > A对B没有duty，但是A还是决定帮助B，A如果发生negligence，则A可根据Good Samaritan Law免责。

## 5. class actions & mass tort litigation

- ==class action定义：single tort有多个victim时，litigation中，1个或几个当事方代表entire class的interest的情况==
  - trial court在认定suit为class action时，需要考虑的consideration
    - ==numerosity（众多）==
  	  - ==plaintiff人数过多，无法分别hear每一个案件==
    - ==commonality（共通性）==
  	  - common legal elements are well-defined （==有共同的legal element==）
    - ==typicality（典型性）==
  	  - ==representative party 的 claim/ defense必须在所有class member中属于typical==
    - ==representation adequacy==
  	  - (named parties must fairly & adequately protect interests of non-named members)（==named party必须能fairly and adequately 保护non-named member的interest==）
- ==mass tort litigation定义：根据tort law（而非contract law）提起的class-action suit==

# 六、影响国际业务的美国法律

- 在美国境内做业务的公司，受international law，各国法律和美国法律的影响
- 以下每个法律都会影响企业国际贸易的earning和practice

## 1. Internal Revenue Code (IRC, tax code)

- foreign tax credits

  - 可帮助或阻碍 international investment and trade

  - Foreign tax credit仅限于美国的corporate tax rate

    > ==当前的IRC允许美国公司在其他国家缴纳的税款抵免其在美国缴纳的税款==
    >
    > 这些credit有助于避免对来自美国的收入双重征税（美国属于worldwide tax system）。

- ==IRC subpart F 编辑了anti-deferral rule（如果母公司未将profit回流到美国，则其国外公司所赚的利润要在当年进行tax）==
	
- ==repatriation of earning的定义：位于美国的母公司，将其海外分支的earning，转移回美国的母公司或stockholder的过程==
	
- corporation tax brackets

## 2. Foreign Corrupt Practices Act（FCPA）

- ==Foreign Corrupt Practices Act（FCPA）： 禁止向foreign official进行payment或bribe，以obtain/ keep business。在外国做生意的公司必须熟悉此法律==
	- ==FCPA要求公司列出美国的security/ stock，保留accounting record（以反映公司的所有transaction），以满足特定的accounting provision==
	- ==国会制定FCPA，用以停止此类贿赂行为，重建public对美国business system的integrity confidence==
	- ==FCPA使美国公司在竞争中处于不利地位==

## 3. Patriot Act in 2001（PA）

- ==Patriot Act目的：用以deter/ punish 在美国的terrorist act==
- ==Patriot Act的作用==
  - ==增强 law enforcement agency的surveillance/ investigate power，可issue subpoenas==
  - ==可在没有wrongdoing evidence的情况下，扩大获取personal/ student financial information（和ongoing criminal investigation相关）==
- Patriot Act如何影响业务
	- Section 215: 扩大了FBI根据court order获取business record的能力
	- Section 351-366: 修改了banking/ finance law, 允许政府从银行获取和terrorism相关的信息
	- Section 351: 允许Secretary of Treasury实施sanction（制裁），包括切断与美国金融机构/银行在外国的所有交易（如果这些国家的bank secrecy law拒绝向美国的agency提供信息）
	- Section 352
	  - prohibits financial institutions from knowingly becoming involved in unlawful transactions w/ suspected terrorists（禁止金融机构在知情的情况下与恐怖分子嫌疑人进行非法交易）
	  - ==公司至少要做到==
	    - ==根据money-laundering risks，实行incorporate internal policies/ procedures/ controls==
	    - ==指定compliance officer==
	    - ==建立ongoing training program，independent audit function==
