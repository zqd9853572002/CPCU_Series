casualty XOL loss treaty

# 一、Casualty XOL 概述

- ==casualty XOL（CXOL）承保直保公司的underlying casualty insurance policy==
  
  - ==casualty insurance是承保被保险人因negligence导致的第三方的bodily injury或property damage==
  
  - ==casualty insurance包括liability insurance和其他不能归为marine or fire insurance的保险==
  
    > 如automobile liability
    >
    > general liability
    >
    > employer liability
    >
    > professional liability
    >
    > worker compensation
    >
    > crime insurance
- 直保公司购买casualty XOL以保护其excessive liability
  
  - casualty XOL可基于facultative basis或treaty basis

## 1. CXOL operation

- CXOL的operation和PPR类似，但由于underlying policy主要为liability policy导致其和PPR有明显区别
  - liability loss是underlying insured要对第三方的bodily injury/ property damage负责
    - ==liability loss通常需要更多时间来manifest(显示)和settle，导致claim resolution会发生严重的delay==
    - property loss通常涉及被保险人property的damage/ destruction/ theft/ loss of use
      - ==first-party loss通常会较快settle（因为被保险人通常会知道loss occurred，且property loss value通常较易确定）==
- underlying policy的区别导致CXOL和PPR的clause和pricing差别巨大

## 2. CXOL function

- CXOL的function包括
  - 提供large line capacity
  - 稳定loss experience
  - 提供catastrophe protection

### （1）提供large line capacity

- ==CXOL可让直保公司承保超过其自身possible/ acceptable liability limit==
- large line capacity可让直保公司在limited financial resource的情况下，为underlying insured提供更多的coverage limit，继而能在市场上更有效的竞争

### （2）稳定loss experience

- ==CXOL通过限制直保公司的loss amount，帮助直保公司减少loss experience fluctuation==
- ==稳定的loss experience可帮助直保公司进行==
  - ==financial planning==
  - ==支持growth（support growth）==
  - ==加强投资者对直保公司的confidence==

### （3）提供catastrophe protection

- ==clash cover（或有high attachment point的CXOL）可保护直保公司不会因single occurrence而发生多个policy的multiple loss，进而遭受financial consequence==
- catastrophe protection可保护直保公司的earning和policyholder surplus

## 3. ri program中的CXOL

- ==CXOL可提供per policy basis或Per occurrence basis==

  |                  | Per policy CXOL             | Per occurrence CXOL (大多数CXOL都为per occurrence basis)     |
  | ---------------- | --------------------------- | ------------------------------------------------------------ |
  | attachment point | ==适用于each policy的loss== | ==适用于任何one occurrence的loss（不管insured/ policy/ coverage的number）== |
  | ri limit         | ==适用于each policy的loss== | ==适用于任何one occurrence的loss（不管insured/ policy/ coverage的number）== |

  

- ==CXOL通常按层（layer）承保，以增加再保公司在直保公司ri program中的participation==

  - 直保公司的ri program中可有multiple layer

  - 直保公司通常会有大额retention，使得first layer的再保公司基本没有损失

    - 但有些XOL会设定一个low attachment point（会导致treaty会遭受损失）

    - working cover是指承保frequent loss的ri layer，working cover layer的价格通常会反映expected loss frequency

      > 如直保公司会设定一个50 xs 50 和一个 100 xs 100的layer

    - policy-exposed layer是working cover和直保公司可提供的largest liability coverage limit之间的layer

- ==clash cover可在policy-exposed layer之上提供ri coverage==

  - ==clash cover可在如下情况时提供coverage==
    - ==single occurrence会影响多个insured或多种insurance type时==
    - ==Extra-contractual obligation (ECO)==
    - ==excess of policy limit (XPL) losses==
    - ==excessive loss adjustment expense (ELAE)==

# 二、CXOL中的common clause

- 有些common clause进行了修改，以为CXOL提供clarification
- CXOL中涉及修改的common clause主要为Reinsuring Clause和Definitions Clause

## 1. Reinsuring Clause

- ==CXOL的reinsuring clause说明了承保何种insurance type==
- ==CXOL主要用于承保underlying casualty policy==
  - 大部分的casualty policy都是liability policy（主要承保第三方的bodily injury和property damage）
  - underlying liability insurance可以是occurrence basis或claim-made basis

### （1）occurrence basis

- ==occurrence basis是bodily injury和property damage必须发生在policy period内==
- occurrence trigger会明确哪些直保公司的policy可适用于claim

### （2）claim-made basis

- ==claim-made basis是对underlying insured的first claim（bodily injury/ property damage）必须发生在policy period内==
  - claim-made basis通常用于claim reporting和settlement之间有很长delay的情况（long-tail liability，如professional liability或D&O liability）
  - claim-made basis会使确定那张保单适用于claim更简单（因为applicable policy是first made claim时生效的保单）
  - ==claim-made basis保单的特点使得其必须使用CXOL处理==
- ==claim-made basis的特点==
  - ==retroactive date==
    - ==retroactive date是只有bodily injury/ property damage的occurrence date在retroactive date之后，保单才承保（retroactive date在policy inception date之前）==
    - 有的claim-made policy不包括retroactive date，此时保单承保policy period之内发生的claim（不管occurrence date）
    - claim-made policy会限制直保公司的long-tail liability
    - 若claim-made policy已生效多年，且还有original retroactive date，则可承保prior policy period发生的，但在current policy period提出的claim
  - ==prior act coverage==
    - ==prior act coverage是扩大claim coverage，其承保发生在现有保单的retroactive date之前的，且prior policy不承保的事故==
    - ==claim-made保单可通过增加prior act coverage endorsement，来承保prior act==
    - 若无prior act coverage，被保险人从一个直保公司转到另一个直保公司时，后一个保单可能无法提供之前保单的retroactive date，从而出现coverage gap（new retroactive date之前发生的事件，新旧保单军无法承保）
  - ==extended reporting period（ERP，tail）==
    - ==extended reporting period（ERP，tail）是claim-made policy expiration之后的一段时间，expired policy可承保retroactive date之后，policy expiration之前发生的，但在extended reporting period之内报告的claim==
    - ==ERP的长度可跨越数月到数年（有时甚至是unlimited ERP）==
    - 如果underlying policy中有prior act coverage或extended reporting period，则CXOL也可承保相关损失（会在treaty中说明）

## 2. Definitions Clause

- ==CXOL中的重要定义是occurrence（其取决于insured underlying coverage）==

- ==occurrence的定义会根据如下情况进行tailored/ modify（修改）==

  | 具体产品                                                     | occurrence定义                                               |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ==Products and Completed Operations Coverage（产品和完工责任）== | ==policy period之内，single cause of loss导致的对same insured的所有injury和damage的accumulation算作one occurrence== |
  | ==Occupational Disease Coverage（职业病coverage）==          | ==occurrence definition会明确每个affected employee是属于单独的occurrence，还是same occupational exposure导致所有的affected employee的combined loss同属一个occurrence== |
  | ==Other Losses Coverage==                                    | ==允许直保公司将same event之后continuous 12-month period（连续12个月内）的所有injury/ damage定义为one occurrence，使得直保公司和再保公司避免关于occurrence number的argument== |

### （1）Products and Completed Operations Coverage中的occurrence定义

- ==对于product and completed operation coverage，直保公司对occurrence的定义为：policy period之内，single cause of loss导致的对same insured的所有injury和damage的accumulation算作one occurrence==

- occurrence的定义假定，single cause of loss是由manufacturing product/ performing operation时的error导致的injury/ damage

- 发生可造成injury/ damage的single act后，bodily injury/ property damage可能随时发生

  > 如动物饲料制造商的饲料变质，其将变质饲料运到养牛场，牛因饲料有问题而生病或死亡
  >
  > 进行CXOL claim时，饲料制造商的直保公司会认为饲料导致的所有损失均属于one occurrence（一次事件）
  >
  > single act（变质饲料）在wide geographic area上造成了多个individual loss，但仍属于one occurrence

- 有的definition clause会规定“same policy period内，由same causative agency导致的所有的product/ completed operation都属于one occurrence”，loss date是policy period的开始时间

### （2）Occupational Disease Coverage中的occurrence定义

- 再保公司承保worker compensation（WC）时，occurrence definition会强调occupational disease
- ==occupational disease通常涉及多个employee和employer，所以occurrence definition会明确每个affected employee是属于单独的occurrence，还是same occupational exposure导致所有的affected employee的combined loss同属一个occurrence==
  - ==有的definition会定义每个employee都是单独的occurrence（每个employee都会有separate retention和limit）==
  - ==有的definition会将same occupational exposure导致的所有employee的loss定义为一个occurrence==
- employee的injury loss date依据employment course。injury loss date可以为
  - 若受WC保护，loss date为应向其支付compensation的日期
  - 若不受WC保护，则loss date为actually disability的开始时间
  - 如果在employment结束后才提出claim，则loss date为终止（cessation）employment的时间

- 如果将所有affected employee的loss定义为one occurrence，则会将same policy且same policy period内发生的所有occupational disease定义为one occurrence。occurrence的loss date是policy period开始的第一天

### （3）Other Losses Coverage中的occurrence定义

- ==对于Other Losses Coverage，CXOL允许直保公司将same event之后continuous 12-month period（连续12个月内）的所有injury/ damage定义为one occurrence，由此，直保公司和再保公司可避免关于occurrence number的argument/ dispute==

  > 如一个砂石坑操作人员连续使用了几个月的炸药，导致nearby building的foundation（地基）出现crack（裂缝）。此时，如果occurrence definition包括accumulated damage，则无需确定是哪次爆炸造成了伤害

# 三、CXOL的专门条款

- 由于主要处理liability claim（需处理第三方claimant），CXOL比PPR更复杂。所以有些条款需要specific enough（general enough的条款会导致coverage distortion，进而导致再保公司错误的承保not intend的coverage）
- 专门为CXOL design/ adapt的条款包括
  - Retention and limits clause
  - Reinstatement clause
  - Claims and loss adjustment expense clause
  - Declaratory judgment expense clause
  - Sunset and sunrise clause
  - Commutation clause 

## 1. Retention and limits clause

- ==Retention and limits clause明确了直保公司的rentention amount和再保公司的liability limit==

- ==CXOL的Retention and limits clause强调single occurrence会影响multiple insured/ policy/ coverage的possibility==

  | situation                              | 案例                                                         |
  | -------------------------------------- | ------------------------------------------------------------ |
  | single occurrence影响multiple insured  | 一家保险公司为building的general contractor和architect同时提供保险，building在construction过程中倒塌，则single occurrence会影响多个insured |
  | single occurrence影响multiple policy   | 一家保险公司承保same accident中的多辆汽车，即one accident会影响多个policy<br><br>被保险人长时间使用defective cement来修建dam，dam倒塌。dam建造期间，保险公司为被保险人出具了多张renewed policy，则此事故涉及多张in effect的多个policy |
  | single occurrence影响multiple coverage | 被保险人开车，发生车祸（撞车+撞人），涉及at-fault accident，导致bodily injury和property damage，则single occurrence涉及多个coverage |

- ==Retention and limits clause对retention and ri limit的定义包括one occurrence导致的直保公司的所有loss，这种方式可让直保公司轻松确定其在single occurrence的maximum loss（不必分别确定每个policy/ coverage的retention/ limit）==

## 2. Reinstatement clause（复效条款）

- CXOL会限定每个occurrence的amount limit，但其可承保contract year总的所有occurrence（unlimited number of occurrence）
  - 如果attachment point较高（如clash cover），则通常会约定per occurrence limit和一年中的maximum recovery
  - ==reinstatement clause是在loss occurrence发生后，恢复treaty的original per occurrence limit（但以contract year的maximum recovery为限），reinstatement clause通常会收取predetermined premium==
- reinstatement在CXOL中并不常见（在PPR中较常见）
  - liability loss通常需要更长时间完成develop，所以确定reinstate的per occurrence limit的percentage会更困难
  - reinstatement clause可用于clash cover
- ==reinstatement clause会强调再保公司的==
  - ==maximum liability==
  - ==per occurrence limit的automatic reinstatement==
  - ==Reinstatement premium==

### （1）再保公司的Maximum Liability

- ==contract year limit/ aggregate limit是再保公司承担的，对合同年度内发生的所有occurrence引起的所有loss的最大liability limit（即合同年度内，再保公司要承担的所有liability）==

- ==contract year limit/ aggregate limit通常按per occurrence limit的倍数表示（通常为per occurrence limit的4-5倍）==

  > 如3 full reinstatement treaty是指contract year limit为per occurrence limit的4倍（original limit + 3 full reinstatement）

- 直保公司和再保公司会协商full reinstatement number

### （2）Automatic Reinstatement of the Per Occurrence Limit

- ==如果CXOL同时具有per occurrence limit和contract year limit，则contract year中的每个loss都会减少per occurrence limit和contract year limit==

  > occurrence limit = 3000，contract year limit = 9000，loss = 400
  >
  > 则occurrence limit变为2600，contract year limit变为8600

- ==reinstatement clause规定，只要年度内的损失未超过contract year limit，则可自动恢复per occurrence limit（automatic reinstatement）==

  > 案例
  >
  > ![](https://s1.ax1x.com/2020/07/14/UaUsF1.jpg)

### （3）Reinstatement Premium

- ==clash cover中，直保公司不需为1+ reinstatement支付保费==

  - ==但如果存在reinstatement premium，则reinstatement premium基于再保公司每次reinstate的per occurrence limit的百分比==

  - ==不论remaining time in the contract year，reinstatement premium amount都基于pro rata（在treaty contract中称为pro rata as to amount and 100% as ti time）==

  - 公式

    - ==per occurrence limit reinstated percentage = loss / per occurrence limit==
    - ==reinstatement premium = per occurrence limit reinstated percentage * earned ri premium for the contract year==

    > 如per occurrence limit = 3000，loss = 1800，则需要reinstate 60%的per occurrence limit，此时per occurrence limit reinstated percentage = 60%

- ==再保公司settle loss时，才会支付reinstatement premium（因为只有loss actually settle之后才会知道loss的exact amount，也才能知道需要reinstate的per occurrence limit的exact amount）==

- 如果支付reinstatement premium时还不知道contrat year的final ri premium，则可使用estimated premium或deposit premium计算reinstatement premium

## 3. Claims and loss adjustment expense clause

- ==Claim and loss adjustment expense clause说明了直保公司必须报告的claim的circumstance，再保公司必须支付的liability claim，以及如何处理loss adjustment expense（LAE）==
- Claims and loss adjustment expense clause着重强调
  - reporting claim
  - ==binding/ bound the reinsurer to the primary insurer’s settlement==
  - sharing loss adjustment expense (LAE)

### （1）reporting claim

- 直保公司要想再保公司报告超过retention的claim
  - 有的treaty要求claim reserve超过retention的50%，或发生特定serious injury时，都要报告给再保公司（不管直保公司的loss reserve是多少）
  - 超过XOL一定额度的claim也要报告给再保公司（双方可约定具体的percentage）
- 如果reporting delay属于accident，则delayed notice不会免除再保公司的liability
  - reporting delay不会void ri coverage，但delay可能会导致再保公司利益受损（再保公司无法及时参与到claim defense中），继而可能导致直保公司和再保公司进行arbitration
  - 直保公司发现filed report claim时，就应立即通知再保公司
  - 如果发生initial error且发生further delay，再保公司可deny liability
- 收到claim后，再保公司有权使用其own expense参与到claim defense中
  - 对于complex claim，直保公司claim staff会欢迎再保公司claim staff带来expertise

### （2）binding the reinsurer to the primary insurer’s settlement

- ==如果直保公司已经赔偿了claim并可提供payment proof，则再保公司应尽快赔偿直保公司（respond promptly to primary insurer’s payment request）==
  - ==即再保公司受制于直保公司的claim settlement==
- 该条款可消除双方对于再保公司liability和payment schedule的dispute

### （3）sharing loss adjustment expense (LAE)

- LAE可包含在loss中（以用于retention和ri limit），也可让双方按承担loss的比例承担LAE

## 4. Declaratory judgment expense clause

- ==Declaratory judgment expense clause说明了CXOL是否承保直保公司因declaratory judgment action而发生的legal expense==

- ==declaratory judgment action中，保险公司（或被保险人）向法院提出coverage question，并让法院说明insurance policy中各方的right==

  - coverage question包括是否有occurrence，exclusion是否适用，特定情况下保险公司是否有义务帮助insured defend

- Declaratory judgment expense clause用以解决coverage的问题（但不会enforce contract）

- ==Declaratory judgment expense clause中典型的ri question是ri treaty是否承保直保公司的legal expense==

  - 直保公司的legal expense非常巨大，如果treaty中未写明，很少有case law案例能说明ri treaty是否承保直保公司的legal expense

    | ==支持ri treaty承保直保公司的legal expense的argument==       | ==反对ri treaty承保直保公司的legal expense的argument==       |
    | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | Dcclaratory judgment expense和其他claim-related loss adjustment expense (LAE)一样 | declaratory judgment expense不属于claim handling的结果，而是adversarial proceeding的结果，所以不属于loss adjustment expense（LAE） |
    | 再保公司可从successful declaratory judgment action中获益     | treaty未明确说明要承保declaratory judgment expense           |
    | follow the fortune doctrine要求承保declaratory judgment expense | 不存在的情况下（none exist），无法通过follow the fortune doctrine创建coverage |

- 直保公司和再保公司通常会在treaty negotiation时解决Declaratory judgment expense的问题（ri treaty承保liability insurance时尤其如此，因为declaratory judgment action更常见于liability insurance）
  - 如果要承保declaratory judgment expense，最常见的方法为将费用含在loss adjustment expense中（两者可同等对待）
  - 可单独约定declaratory judgment expense clause，明确在发生发生declaratory judgment action时，treaty承保直保公司的legal expense

## 5. Sunset and sunrise clause

### （1）sunset clause

- ==sunset clause限定了treaty expiration后，向再保公司报告occurrence的time limit==
  - sunset clause的time limit可以是几个月或几年
  - ==sunset clause可控制long-tail liability claim==
    - ==若再保公司在sunset period内未收到reported occurrence，则再保公司可close treaty（即不会再承保additional loss）==
  - 有时，sunset clause可用于ri agreement项下的每个contract year
  - sunset clause可以是单独的clause也可是其他clause（如retention and limit clause/ Claims and loss adjustment expense clause）的一部分
  - ==只有在sunset period过期之前报告给再保公司的claim，ri才会承保==

### （2）sunrise clause

- ==sunrise clause是可恢复sunset clause导致的lost coverage（即如果直保公司未在sunset period报告claim，则其无法获得ri coverage，但如果有sunrise clause，则ri可承保此类损失）==
- sunrise coverage可按两种方法操作
  - 再保公司修订现有treaty中的sunset period，以扩展coverage period，但须直保公司支付additional premium
  - 再保公司在new treaty中增加wording，以承保sunset clause不承保的loss

## 6. Commutation clause（交换条款）

- ==commutation clause是在treaty过期一段时间后，直保公司和再保公司close out claim liability==
  - commutation clause允许再保公司在更短的时间确定ultimate loss cost
  - commutation clause的功能包括
    - 确定了提出commutation request的earliest point（最早时间）
    - 定义了actuary/ appraiser如何确定ultimate cost
    - 确定actuary/ appraiser的recommendation是否属于binding
  - commutation clause可以是general and simple，也有可能specific and complex
- commutation clause通常不需要commutation，也不需明确如何决定claim settlement value
  - ==直保公司和再保公司commute loss时，commutation clause可提供general framework==
  - 谈判settlement时，双方应对reserve level/ claim handling  control/ probable settlement pattern感到comfortable

# 四、CXOL pricing

- CXOL pricing方法和PPR pricing一样
- ==CXOL的pricing method（price treaty）为exposure rating和experience rating，再保公司会同时使用两种方法，并选择一个最合理（appropriate）的结果==

## 1. exposure rating

- exposure rating 使用insurance industry loss data（而非采用直保公司的loss experience）进行定价

- ==exposure rating会考虑underlying policy的inherent liability amount==

- 案例：S公司销售新保险产品，没有loss experience，所以无法建立CXOL

  - background

    ![](https://s1.ax1x.com/2020/07/15/UaIeMD.jpg)

  

  - 计算50 xs 50的indicated exposure rate

    ![](https://s1.ax1x.com/2020/07/15/UaI3JP.jpg)

    - (2) increased limit factor/ ILF是insurance advisory organization开发的，基于basic policy limit的，用于price coverage的factor。increase limit factor (ILF)反映了在basic policy limit之上的industry loss experience
      - 直保公司的给liability policy的定价，取决于basic rate（basic coverage limit）和increased limit factor
        - insurance advisory organization会收集premium和loss data信息，以开发出credible increased limit factor
        - increased limit factor也可用于再保公司计算underlying insurance premium中和ri layer相关的部分
      - increased limit factor增长和policy limit增长的比例不同，因为损失超过basic policy limit的可能性较高（所以要对刚超过basic policy limit的部分多收保费，越往上，增长的速度越慢）
    - (4) premium fraction用于计算premium ceded
    - (6)和(7) premium ceded = [(underlying coverage对应的estimated subject premium - policy limit对应的estimated subject premium) / underlying coverage对应的estimated subject premium] * written premium
    - (8) premium for layer = (6) - (7)
    - 计算premium ceded时，会从written premium扣除各项expense ratio（包括agent commission/ internal expense/ boards, bureaus and taxes/ profit and contingency）
      - 分给再保公司的premium ceded = (8) * (1-expense ratio)

- ==为CXOL定价(exposure rating)时，再保公司的underwriter会考虑以下因素（factor），以修改CXOL ri rate==

  - ==Allocated loss adjustment expense（ALAE）==
  - ==Reinsurer expense（再保公司的费用）==
  - ==Extra-contractual obligations and excess of policy limits coverage==
  - ==Clash cover==
  - ==Policy limit mix==

### （1）Allocated loss adjustment expense（ALAE）

- ri treaty通常会赔偿allocated loss adjustment expense（ALAE），ALAE可基于pro rata basis（依据再保公司的loss indemnity比例），或基于indemnity paid total amount的addition
  - ==increased limit factor/ ILF不包括ALAE loading，而是将ALAE放入到premium的basic limit部分中==
  - ==如果LAE按照paid total amount的addition支付，则再保公司需将ALAE放入ri premium中==

### （2）reinsurer expense（再保公司的费用）

- ==ri rate必须反映再保公司的expense==
- ==再保公司的expense包括==
  - ==ceding commission==
  - ==brokerage==
  - ==再保公司的internal expense==
  - ==profit and contingency loading==
  - ==再保公司的net retrocessional cost==

### （3）Extra-contractual obligation（ECO）和excess of policy limits coverage（EPL）

- ==如果ri treaty提供ECO和EPL，则再保公司需在ri rate中考虑ECO和EPL的费用==

### （4）Clash cover

- ==treaty可能承保single occurrence（会影响multiple insured/ multiple insurance type）导致的net retention accumulation==
- ==再保公司underwriter会调整exposure rate以反映Clash cover的loss potential==

### （5）Policy limit mix

- 如果CXOL按flat rate定价，则再保公司会定期审核sold policy limit mix
  - ==如果actual policy limit distribution和直保公司的projection不一致，则会影响再保公司的potential liability和ri rate accuracy==
    - 短期内，ri loss ratio无法反映此种差异
- 解决方案
  - 基于actual policy limit sold（而非基于estimate policy limit）来确定ceded premium。直保公司每月报告每个policy limit category的actual written premium，并基于separate rate（cession factor）为每个policy limit category支付premium
  - 为low level的ri coverage开发average rate（从而产生predictable loss flow）
    - 此rate可在future date时，根据再保公司的actual loss进行调整
    - 该方法涉及CXOL的experience rating

## 2. Experience Rating

- ==experience rating的目的是根据actual past loss和related subject premium来确定future period的loss cost rate，之后会将experience rate和exposure rate做比较==

- 案例

  - background
    - S公司已经有4年的 loss portfolio（期间发生了很多loss），loss trending中，inflation rate为6％
  - trend factor会用于entire loss amount（而非只用于特定的layer）
    - 如果nominal loss的增长率大于incurred loss的增长率，则再保公司受到inflation的影响要大于直保公司

- reporting loss时，可能会发生delay（liability insurance和WC中很常见），且有些loss ultimate value会被underestimated（低估）

  - 上述两种情况会导致aggregate loss reserve增加（loss development）

    > ![](https://s1.ax1x.com/2020/07/15/UaTga9.jpg)

- 如果直保公司有sufficient loss data以确定credible loss development pattern，下一步就是chart loss development以预测loss reserve的变化和loss ultimate value

  - NAIC annual statement - Schedule P列明了此类chart（triangle），其用来衡量保险公司的loss reserve adequacy，之后会用estimate来预测claim的future value

- 直保公司的historical loss information不足以建立credible projection时，可使用industry loss development information来建立loss development pattern（可达到data credibility的acceptable level），该方法可反映loss exposure和experience rating的combination

- age-to-age development factor是用某个时点上的accident year incurred loss除以该时点前，但属于同一accident year的incurred loss

  - ==age-to-age development factor = incurred loss at age 2 / incurred loss at age 1==
  - age-to-age development factor是average result，应选择某个合适的factor来调整data中的anomaly
    - ==对于final time period，可选择appropriate industry statistics或estimated data做tail factor（如使用一半的previous increment做tail factor，或使用loss development triangle），以确定ultimate loss value==

- age-to-ultimate factor是从final time向前计算（calculate backward）

  - 对于final period，age-to-ultimate factor设定为selected age-to-age factor
  - ==age-to-ultimate factor (years 3-4) = age-to-ultimate factor (Year 4) *selected age-to-age factor (year 3-4)==

- 每年的aggregate loss development反映出probable loss development会发展成ultimate aggregate value

  - ==Year ultimate loss = current loss * age-to-ultimate factor (year 1-2)==

- IBNR reserve是ultimate loss和current loss value之间的差
  
  - ==IBNR reserve = ultimate loss - current loss==
- 用于future period的estimated subject premium必须反映manual rate和exposure unit的变化
  - rate可用于调整past premium for current condition
  - broad economic data可用于调整exposure unit的变化
  - combined effect会导致premium on-level factor（再保公司underwriter可据此预估adjusted subject premium，以用于priced period）

## 3. ri rate的evaluation和selection

- 再保公司的underwriter会考虑每种pricing method的结果，之后选择适合underlying policy insurance risk且符合current ri market condition的ri rate

- ==exposure rating和experience rating会给出不同的ri rate，再保公司会尝试reconcile不同的rate，并确定best ri price==
  
  - ==reconciliation和select没有generally accepted method==
  - 再保公司underwriter会根据特定情况下的factor，使用其judgment对每种方法分配不同的weight（权重）
  
- ==exposure rate factor和experience rate factor需要考虑的factor==

  | ==exposure rate factor==                                     | ==experience rate factor==                   |
  | ------------------------------------------------------------ | -------------------------------------------- |
  | 根据policy limit分类，subject premium projected distribution的accuracy和credibility | 估计claim cost inflation trend的accuracy     |
  | 超过retention的increased limit factor的accuracy              | 估计excess loss development factor的accuracy |
  | 不在increased limit factor（ILF）中的，发生LAE/ ECO loss/ XPL loss/ clash cover loss的可能性（possibility） | subject premium current value的accuracy      |
  | -                                                            | statistical sampling的adequacy               |
  | -                                                            | estimated excess loss cost的stability        |


### （1）Exposure Rate Factor

- ==使用exposure rate时，需要考虑的factor包括==

  - ==根据policy limit分类，subject premium projected distribution的accuracy和credibility==

    - policy limit mix的改变会严重影响ri rate

      > 高额的attachment point中，由于缺少确定factor的credible loss data，increased limit factor无法准确反映loss possibility

  - ==超过retention的increased limit factor（ILF）的accuracy==

  - ==不在increased limit factor（ILF）中的，发生LAE/ ECO loss/ XPL loss/ clash cover loss的可能性（possibility）==

    - ECO/ XPL/ clash cover loss通常不会反映在increased limit factor中，再保公司underwriter必须判断此类loss amount和probability
    - 如果LAE放到indemnity loss中，也会影响ri rate

### （2）Experience Rate Factor

- ==确定experience rate时，需要考虑的factor==

  - ==估计claim cost inflation trend的accuracy==

    - underlying inflation trend assumption必须合适，一个inflation trend index无法适用于所有business class

      > medical service和building cost的inflation trend会有巨大差别

  - ==估计excess loss development factor的accuracy==

    - 从大量loss中获得的excess loss development factor才有statistical credibility
    - layer的attachment point越低，超出attachment point的coverage amount越小，data credibility level越高

  - ==subject premium current value的accuracy==

    - 建立inflation trend的assumption会影响premium on-level factor的准确性
    - 直保公司应有experience period内所有rate-level change 的准确记录（因为有些change比西乡state insurance regulator报备）

  - ==statistical sampling的adequacy==

    - statistical sampling adequacy取决于是entire layer发生损失还是layer的一部分发生loss
    - 如果是layer的一部分发生损失，experience rate无法包括entire layer的charge（但此项目可进行adjustment）

  - ==estimated excess loss cost的stability==

- 每年的experience rate都会fluctuate，再保公司的underwriter必须确定是否要增加additional insurance risk charge（因为loss volatility）。再保公司可使用multiple-year/ retrospectively rated treaty/ large insurance risk charge以解决此问题

## 4. Upper Layers Pricing

- 对于working cover之上的layer，通常使用exposure rating
  
  - ==随着layer size或attachment point增长，layer的loss experience会变得less stable（不稳定），increased limit factor（ILF）会更反映出industry data的loss potential==
  - ==考虑到high layer instability（不稳定），lower loss frequency和underwriting profitability instability（不稳定），再保公司会加入additional insurance risk charge，以平衡发生unexpected loss的possibility==
- clash cover pricing主要基于judgment和market competition（因为很少会发生能够trigger clash cover的损失）
  - clash cover在所有policy limit之上
  - clash cover pricing取决于
    - 再保公司underwriter对ECO或XPL loss possibility的assessment
    - 2+insured涉及one occurrence的possibility
    - high loss adjustment expense（高额LAE）的possibility

