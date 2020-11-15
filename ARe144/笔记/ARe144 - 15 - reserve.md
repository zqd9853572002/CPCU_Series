loss reserving method

# 一、Loss Reserve

- ==reserve是对已发生已报告但尚未settle/ paid案件的估计金额（即保险公司在未来会赔付多少钱）==
  - loss reserve对确定保险公司financial condition非常重要，准确的reserve practice对保险公司的stability和solvency非常重要
  - 保险公司依赖loss reserve estimate，保险公司难以估计准确的future loss和expense payment
  - loss reserve amount（体现在balance sheet的liability部分）会严重影响保险公司的policyholder surplus和profitability
  - ==实际来看，accident year的incurred loss < accident year结束后ultimate loss amount==

## 1. Loss and Loss Adjustment Expense Reserve

- ==reserve包括loss reserve和loss adjustment expense reserve (LAE reserve)==

  | 针对     | loss的定义                                                   |
  | -------- | ------------------------------------------------------------ |
  | 直保公司 | loss是根据primary insurance policy，要支付给claimant的钱     |
  | 再保公司 | loss是根据reinsurance agreement，要未来（future）支付给直保公司的钱 |

  - ==loss分为paid loss和loss reserve==
  - ==incurred loss是paid loss + loss reserve + LAE reserve==
    - ==incurred loss = paid loss + loss reserve + LAE reserve==

- ==保险公司使用loss reserve承担loss occur，loss settle和paid claim之间的delay==

  - claim报告给保险公司后，保险公司需要调查保单是否属于承保的loss，以及商讨appropriate settlement

    |                             | delay情况                    | 案例                                                         |
    | --------------------------- | ---------------------------- | ------------------------------------------------------------ |
    | property claim              | 较短                         | homeowner policy中，着火导致的loss通常会在几个月内settle     |
    | third-party liability claim | 较长（因为会涉及litigation） | product liability和medical malpractice claim通常会持续多年才能close |

    

- loss reserve还包括loss adjustment expense（LAE）amount

  - loss adjustment expense（LAE）和individual claim file或overall claim operation（此时无法分配到某个specific claim file上）相关

  - NAIC将loss adjustment expense（LAE）分为Defense and Cost Containment（DCC）和Adjusting and Other（AO）

    - 有时也用Allocated loss adjustment expense (ALAE)，Unallocated loss adjustment expense (ULAE)

    | NAIC对LAE分类                                          | 定义                                                         | mark        |
    | ------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
    | ==Defense and Cost Containment（DCC）==                | ==claim defense和litigation相关的费用==                      | -           |
    | ==Adjusting and Other（AO）==                          | ==包括所有其他费用（如adjuster salary，other fee and expense）== | -           |
    | ==Allocated loss adjustment expense (ALAE，已停用)==   | ==用于特定案件的investigate/ defend/ settle claim的费用==    | 可等同于DCC |
    | ==Unallocated loss adjustment expense (ULAE，已停用)== | ==无法分配给specific claim的loss adjustment expense（LAE）== | 可同等于AO  |

  

- ==incurred loss = paid loss +  Loss reserve + Loss adjustment expense reserve (LAER)==

  - ==incurred loss是一段时间内已发生的loss（不管何时支付claim）==
  - ==paid loss是一段时间内已经赔付的loss==
  - ==loss reserve是保险公司total loss amount的一部分==
  - ==Loss adjustment expense reserve是对已发生的claim的expense（包括investigate，defend，settle claim）的预估==
    - LAER和loss reserve相关，代表settling outstanding claim的future expense的estimate

- 保险公司会建立bulk reserve（aggregate reserve，IBNR reserve），用以估计如下

  - 估计reported case reserve growth，对于reserve inadequate的case，估算reported loss
  - 估计已发生未报告的loss
  - 估计已经settled/ closed claim的additional cost

- ==建立IBNR reserve比建立known case reserve更难==

  - ==IBNR reserve estimate主要基于past experience，并根据current condition进行修改（如增加claim cost，增加reported claim的frequency和severity）==

### （1）Incurred Loss的Life Cycle

- 必须定期review/ update loss reserve以反映paid loss和loss expense的变化
  - 保险公司会使用不同method，定期update其过去几年incurred loss的estimate

#### 1）accident-year method

- accident-year method是organizing ratemaking statistics的method，其使用accident year的incurred loss（包括与accident year发生的所有accident导致的claim loss，但不包括过去和未来年份的loss），按照accounting record formula计算earned premium

- ==accident-year method只累积当年度的所有incurred loss==

  > ==如，2016年的accident-year data只包括所有发生在当年度（2016年）的event loss（之前之后年份的不算）==

- ==随着对loss进行支付，paid loss会增加，loss reserve会等额减少，incurred loss保持不变==

  - 但如果随着现有claim有new information或发生new claim，则incurred loss会改变
  - ==accident year的account会一直开放多年，等到当年度所有occurred loss都赔付完成后，才会关闭==

- 在accident year结束后，保险公司会尽量准确的估算loss reserve

  - 若loss reserve估算准确，则incurred loss应等于年末时点的ultimate loss

    - ultimate loss是支付accident year所有loss的final paid amount

  - ==实际中，incurred loss通常小于ultimate loss==

    - accident year结束侯收到的information，往往会导致loss reserve增加，从而增加incurred loss

      > 如loss 发生多年后的court judgment，导致保险公司必须支付大额赔款
      >
      > 在最初建立reserve时，可能没有预料到这笔付款，这将导致accident year的incurred loss增加

    - ==loss development是一段时间内incurred loss的上升或下降==

      > 如actuary可回顾某年度的incurred loss的life cycle
      >
      > - 发现72个月之后（从accident year的第一个月开始算），incurred loss等于ultimate loss amount；
      > - 发现108个月之后（从accident year的第一个月开始算），所有的loss全部fully paid

### （2）Implications of Inadequate Loss Reserve

- loss amount是保险公司financial statement的重要部分，accurate claim reserving对维持保险公司financial strength非常重要

  - ==低估或高估final claim cost均会distort financial condition==
    - ==持续underreserveing claim（understate claim，低估理赔）会导致保险公司insolvency和bankruptcy==
  - ==建立维护adequate loss reserve对保险公司的financial health很重要，因为IBNR reserve会直接影响保险公司维持existing business和future grow的能力==
- state regulator关注continued solvency（对应loss reserve adequacy）和pay claim ability in future（对应understating loss reserve history）
- 持续overstate（高估） loss reserve会导致的问题
  - unwarranted rate增加
  - insurance product overpriced
  - tax penalty和deferred income
- past claim payment属于future rate basis，actuary在指定future rate时会依赖open/ closed claim的paid amount，open claim reserve和IBNR claim
- consistent和accurate的loss reserve会让insurance rate准确反映future loss potential

### （3）建立Adequate Loss Reserve的挑战

- 影响loss reserve的问题

  | internal/ external | 具体问题                                             | 影响方式                                                     | 后果                                                         |
  | ------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | internal           | claim personnel error                                | 按照incomplete或inaccurate information确定initial reserve    | inadequate loss reserve                                      |
  |                    | lack of expertise                                    | -                                                            | inaccuracy                                                   |
  |                    | 不想reevaluate claim或adjust loss reserve amount     | -                                                            | inaccuracy                                                   |
  |                    | claim representative缺少training                     | -                                                            | underreserving/ overreserving（understate/ overstate）       |
  |                    | claim department的frequent turnover                  | -                                                            | underreserving/ overreserving（understate/ overstate）       |
  |                    | management <br/>change                               | -                                                            | loss reserve adequacy                                        |
  |                    | reserving guideline change                           | -                                                            | loss reserve adequacy                                        |
  |                    | restructuring of reinsurance program                 | -                                                            | loss reserve adequacy                                        |
  | external           | legislation/ regulation change (如WC benefit change) | court case judgment会产生new case law，并产生emerging coverage area（如environmental/ construction defect claim） | 此类claim之前没有过（或现有的保单不承保）<br><br>claim personnel需review claim file以确定是否要establish reserve |
  |                    | inflation                                            | 如medical malpractice claim会持续数年后才会settle/ close，在这期间，external factor（如inflation会增加medical cost，new/ expensive medical technology development）会影响claim | -                                                            |
  |                    | new/ expensive technology development                | 同上                                                         | -                                                            |

  

- reserve会反映claim ultimate cost（而非claim present value），所以reserve包含claim future settlement value

  > 如medical malpractice claim会持续数年后才会settle/ close，在这期间，external factor（如inflation会增加medical cost，new/ expensive medical technology development）会影响claim，claim reserve要考虑此类increased cost

## 2. Loss Reserve和Surplus的关系

- 保险公司的net worth（asset和liability之间的差）是policyholder surplus

  - 在owner entitled to fund前，保险公司所有的net worth都可用于支付claim

  - ==balance sheet - liability中最大的一部分为loss reserve==

    - ==loss reserve列在Losses科目下==
    - ==loss adjustment expense reserve列在Loss Adjustment Expense科目下==

  - 保险公司balance sheet上的主要element如下

    | Asset                    | Liability                                      | Surplus and Other Funds          |
    | ------------------------ | ---------------------------------------------- | -------------------------------- |
    | Bonds                    | Losses（loss reserve列在Losses科目下）         | Surplus as Regards Policyholders |
    | Stocks                   | Loss Adjustment Expenses（LAE，含LAE reserve） |                                  |
    | Cash                     | Unearned Premiums                              |                                  |
    | Premium Balances         |                                                |                                  |
    | Reinsurance Recoverables |                                                |                                  |
    

- ==policyholder surplus对保险公司的financial strength非常重要==

  | situation                                                    | 结果                                                         | 纠正                                                         |
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ==case reserve过低（underreserving，understate reserve，低估准备金）== | ==导致policyholder surplus和当年度的underwriting profit高估（overstate）== | 随着claim逐渐settle和reserve调整，future underwriting profit会逐渐减少<br><br>随着inadequate reserve和liability amount逐渐被纠正，policyholder surplus会降低 |
  | ==case reserve过高（overreserving，overstate reserve，高估准备金）== | ==导致policyholder surplus低估（understate）==               | reserve被纠正后，policyholder surplus会上升                  |

- ==reserve和policyholder surplus的变化成反比==

  > reserve = 10, policyholder surplus = 5，reserve/ policyholder surplus = 10 / 5 = 2
  >
  > - reserve上升10% —> policyholder surplus减少20%
  > - reserve下降10% —> policyholder surplus上升20%

# 二、直保公司reserve对再保公司的意义

- 直保公司和再保公司必须建立reserve

  - reserve和loss adjustment expense（LAE）会影响直保公司和再保公司的financial report和NAIC annual statement

- ==loss reserve是直保公司和再保公司balance sheet上最大的uncertainty，再保公司根据直保公司的reserve data建立自己的loss reserve，所以直保公司reserve adequacy会直接影响再保公司的interest（direct interest）==

  - ==如果直保公司reserve inadequate，再保公司的reserve也会inadequate==

- pro rata和XOL两种方式对再保公司的影响

  |             | 影响方式                                                     | 具体影响                                                     |
  | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | pro rata ri | ==pro rata ri会让再保公司承担一部分直保公司的reserve（因为再保公司会从first dollar就开始承担loss liability）<br><br>pro rata reinsurer会follow直保公司的reserve practice== | ==如果直保公司understate reserve（低估准备金），则会以同等程度（same degree）影响直保公司和pro rata的再保公司== |
  | XOL         | ==再保公司只负责承担超过attachment point的损失，所以再保公司只关注有direct effect的部分== | ==直保公司understate reserve（低估准备金）的，会对XOL reinsurer产生巨大影响== |

  - ==pro rata和XOL都会发生loss reporting的inherent time lag（直保公司在loss occurrence和claim file creation中也会发生time lag）==

- report和reserve的速度方面，property insurance loss > casualty insurance loss

  |                         | 是否会发生delay                                              | 案例                                                         |
  | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | property insurance loss | 通常不会有严重delay，因为property loss通常会readily discovered and reported | -                                                            |
  | casualty insurance loss | ==通常会发生discovery delay和claim reporting delay==<br><br>大量的tort claim（如asbestosis-related injury）的reporting通常会有extreme delay | mesothelioma（asbestos引起的cancer），可能等到claimaint初次接触asbestos几十年后才显现出来 |

  

- ==long loss reporting delay会影响直保公司和再保公司XOL的reserve==

  - ==直保公司的reserve会部分影响ri premium（ri rate）（正相关）==

    > ==understate reserve（低估准备金的），再保公司的ri premium也可能inadequate==

- 再保公司希望直保公司能够long-term survival
  - 如果直保公司发生inadequate reserve，其可能会有financial difficulty（insolvency）
  
  - 与insolvent的直保公司做业务会有问题
  
    > 如处理outstanding claim时，发生lengthy and expensive litigation

# 三、建立Case Reserve的方法

- ==为准确报告financial position，保险公司必须尽可能准确的估计reserve==

  - estimate reserve非常困难，因为大多数情况下，保险公司对claim的最终支付金额通常不确定（eventually pay is uncertain）

    > 保险公司estimate reserve时，并不知道underlying claim的all fact

- ==建立loss reserve（LR）和loss adjustment expense reserve（LAER）的两种方式为case reserve 和 bulk reserve==

  - ==case reserve是可直接assigned to individual claim的loss reserve==

  - ==bulk reserve是settle entire claim group的reserve==

  - 有些claim，可同时适用case reserve和bulk reserve

    > 对reported loss payment不确定时，可为每个individual loss case建立loss reserve，也可为whole loss group（bulk）建立loss reserve

- ==直保公司的claim department会建立case reserve==
  
  - ==每个reported loss都会设立claim file，包括需要支付的ultimate loss estimate==
  - ==case reserve = claim representative估算的ultimate loss - paid loss==
- 也可对每个individual claim建立allocated loss adjustment expense reserve（ALAE reserve）
  
- case reserve适用于Reported losses - payment certain，Reported losses-payment uncertain和Allocated loss adjustment expenses (ALAE)

## 1. Reported losses - payment certain

- 对payment amount已确定的loss建立reserve最简单，其他reserve的计算较复杂
  - ==Reported losses - payment certain是保险公司已经和claimant对payment amount达成一致==
  - ==Reported losses - payment certain reserve是所有claim的agreed settlement的加总==
    - ==Reported losses - payment certain reserve等于所有claim的agreed settlement的加总==

## 2. Reported losses - payment uncertain

- ==确定payment不确定的reported loss reserve时，通常需要expertise==
  
  - 保险公司必须根据known claim information/ similar claim historical loss data/ individual judgment来估算ultimate loss
  - 如果claimant报告了additional fact，则保险公司要相应调整reserve
  
- payment amount不确定时，可使用Judgment method/ Average method/ Tabular method等方法确定case loss reserve

  | 确定payment amount不确定的case loss reserve的方法 | 定义                                                         | mark                                                         | 适用性                                                       | 缺点                                                         |
  | ------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | Judgment method（主观判断法）                     | judgment method是主要根据similar claim和professional experience估算每个claim value | 不使用statistical analysis                                   | -                                                            | ==accuracy result（准确程度）非常依赖claim representative experience的quality和extent== |
  | Average method（平均法）                          | Average method (factor method) 是根据specific claim category的average amount来建立case reserve | 基于past claim analysis，inflationary change trend，insured amount change trend和其他可引起future payment变化的factor | ==适用于frequent claim，及时（promptly）完成reported/ paid，没有extreme variation的claim==<br><br>如automobile physical damage claim | ==有些liability insurance的claim amount会有wide variation和long settlement delay（如medical malpractice和product liability insurance），此时使用average method，可能发生inadequate reserve== |
  | Tabular method（表格法）                          | tabular method是如果claimant有similar characteristics（age/ health/ marital status），则为所有的claim建立average amount | 使用actuarial table中的rate和factor计算future loss payment的present value（未来赔付的现值，此present value即为这些payment的case loss reserve） | ==通常用于计算WC - lost income和liability insurance - structured settlement amount的loss reserve== | ==只适用于某时间段内支付fixed amount的benefit（如计算person life时，可优先使用tabular method）== |

  

### （1）Judgment method（主观判断法）

- ==judgment method是主要根据similar claim和professional experience估算每个claim value==

  - ==judgment method不使用statistical analysis==

- judgment method的缺点

  - ==accuracy result（准确程度）非常依赖claim representative experience的quality和extent==

    > 两个人对同一案件的estimate 可能会非常巨大
    >
    > 一个人对类似loss的estimate，也可能随时间变化

### （2）Average method（平均法）

- ==Average method (factor method) 是根据specific claim category的average amount来建立case reserve==

  - average method基于past claim analysis，inflationary change trend，insured amount change trend和其他可引起future payment变化的factor

- ==average method适用于frequent claim，及时（promptly）完成reported/ paid，没有extreme variation的claim==

  > 如automobile physical damage claim，可为每辆车都建立同一reserve，虽然保险公司可为每辆车设定更准确的reserve，但通常不再花费额外的钱这么做（not worth the expense with the extra effort）

- ==average method中，有的claim reserve属于inadequate，有的claim reserve属于excessive，但只要average amount是准确的，则aggregate loss reserve就可准确反映所有outstanding claim的ultimate loss amount==

- Average method的缺点

  - ==有些liability insurance的claim amount会有wide variation和long settlement delay（如medical malpractice和product liability insurance），此时使用average method，可能发生inadequate reserve==

    - 此时会同时使用average method和judgment method，通过使用combined reserving approach，可为每个reported claim分配一个average value
  
      > 如每辆车bodily injury claim的initial reserve的average value均为1000，每隔60天（或获得claim additional information时），会按照judgment method调整reserve

### （3）Tabular method（表格法）

- ==tabular method是如果claimant有similar characteristics（age/ health/ marital status），则可为所有的claim建立average amount==

  - ==tabular method通常用于计算WC - lost income 和 liability insurance - structured settlement amount的loss reserve==

- tabular method使用actuarial table中的rate和factor计算future loss payment的present value（未来赔付的现值，此present value即为这些payment的case loss reserve）

  - ==case reserve（Tabular method）= present value * annual benefit amount==

  - tabular method可使用的actuarial table包括

    | actuarial table  | 用处                                  |
    | ---------------- | ------------------------------------- |
    | Morbidity table  | 显示sickness/ injury的likelihood      |
    | Mortality table  | death likelihood                      |
    | Annuity table    | survival likelihood                   |
    | Remarriage table | widow/ widower remarriage的likelihood |

- ==有tabular method计算出的case loss reserve可视为有相同characteristic的所有claim的average reserve（如具有same age/ health/ marital status的claimant）==

  - tabular method可对大量individual claim产生出appropriate total reserve（但每个特定claim的case reserve和其ultimate paid amount之间可能会存在巨大差异）

- tabular method的缺点

  - tabular只适用于某时间段内支付fixed amount的benefit（如计算person life时，可优先使用tabular method）

    > 假设一名年老体弱、终身残疾的男性工人每周可获得300美元的收入损失津贴，可通过使用mortality table和present value factor计算benefit的case loss reserve的病例损失准备金
    >
    > - mortality table用于推导各年龄人群一年内的生存概率。由于此人是残疾人，因此可能需要调整mortality table中的factor，以反映残疾人的死亡率（已经有special mortality table）
    >
    > - 通过使用mortality table和present value factor，精算师可以计算出这个人终生支付的1美元年金的现值因子。假设现值因子是16.412
    >
    > - case reserve的计算方法是用present value * annual benefit amount，本例中，case reserve为300/ week * 52 week * 16.412 = 256,027美元

## 3. Allocated loss adjustment expenses (ALAEs)

- ==ALAE的case reserve方法为使用judgment method或为每个case loss reserve增加一个fixed percentage==
- ALAE method的缺点
  - accuracy result（准确程度）非常依赖claim representative experience的quality和extent（和judgment method的缺点一样）
- 对于某些insurance type，可在每个loss reserve上增加一个percentage以生成ALAE aggregate reserve

## 4. 纠正Case Reserve

- 在任何时候，reported loss的total case reserve都有可能inadequate（因为loss会随时间不断develop）

- ==可增加每个claim的case reserve以纠正inadequate total case reserve（correct understated case reserve），有两种方法==

  |                             | 解释                                                         | 难易度                              |
  | --------------------------- | ------------------------------------------------------------ | ----------------------------------- |
  | ==additional case reserve== | ==additional case reserve是为每个case增加same percentage==   | ==最简单==                          |
  | review每个open claim file   | ==review每个open claim file，为inadequate case增加reserve==<br><br>该方法假定reviewer对每个case建立比original claim reserve更准确的reserve，或能获取更多claim information | ==较费时间，time-consuming method== |

  

- ==再保公司可根据自身的financial reporting purpose，补充（supplement）直保公司的case reserve==
  
  - 再保公司的claim personnel可审核直保公司的claim file并根据loss development增加case reserve amount
  - 再保公司的total case reserve = 直保公司的case reserve + 再保公司的additional case reserve

# 四、建立Bulk Reserve的方法

- 保险公司无法确定某个claim的case reserve是否属于inadequate或excessive，也无法确定哪个claim case会reopen，所以保险公司通常会提供additional reserve（即bulk reserve）
  - 对某些insurance type，bulk reserve是保险公司total liability的重要组成部分
- ==actuary负责建立bulk reserve==，bulk reserve分为
  - Reported losses - payment uncertain
  - Incurred but not reported (IBNR) reserve
  - Loss adjustment expenses（both allocated and unallocated） 

## 1. Reported losses - payment uncertain

- ==payment amount不确定时，可通过bulk basis对reported loss建立reserve==

  - ==bulk reserve - reported loss reserve = earned premium * x% - paid loss==

    > 如earned premium = 13，paid loss = 3，actuary预计loss是earned premium的70%
    >
    > 则bulk reserve (reported loss reserve) = 13 * 70% - 3 = 6.1

## 2. IBNR reserve

- ==incurred but not reported/ IBNR loss是已发生未报告的loss，IBNR reserve是（目的是）反映已发生未报告的future loss payment==
  
  - ==IBNR reserve是对occurred but have not yet been reported的loss进行estimate和reserve（包括对known loss的future growth）==
  
- IBNR loss包括reported loss但expected to develop的reserve（这些loss的final payment会大于currently reserved，即incurred but not enought reserved (IBNER)） 

- 较难估计liability insurance的IBNR reserve，因为unreported loss和reported loss development的loss size和loss number都非常不确定（tremendous uncertainty）

- 直保公司对IBNR loss负责
  - 预估late reported loss的number和average size较难，所以IBNR reserve通常为bulk reserve
  - ==IBNR reserve属于residual reserve，因为在任何时点上，IBNR reserve等于reported incurred loss和ultimate loss的差额（difference）==
    - ==IBNR reserve = ultimate loss - reported incurred loss==
  
- 估算IBNR reserve的方法包括Loss ratio method，Percentage method，Loss triangle method

  | 方法                                                         |                                                              |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | Loss Ratio Method                                            | ==假设ultimate loss ratio等于计算premium rate时的loss ratio== |
  | Percentage Method                                            | ==使用IBNR reserve和reported loss之间的historical relationship，得出IBNR forecast中的percentage== |
  | Loss Triangle Method（loss development method/ chain link method/ chain ladder method/ link ratio method） | 使用historical loss data计算loss development factor，从而估计IBNR reserve |

  

### （1）Loss Ratio Method

- ==Loss ratio method是假设ultimate loss ratio等于计算premium rate时的loss ratio==

  > ==如果计算premium rate时的loss ratio = 80%，则earned premium的ultimate loss ratio = 80%==

- Loss Ratio Method中，IBNR reserve = ultimate loss amount - reported loss paid/ reserved amount

- ==loss ratio method适用于long-tail liability insurance中建立IBNR reserve的early stage（只用于incurred loss之后的1-2年内），此时loss triangle method还无法completely reliable，24个月之后loss triangle method才会比loss ratio method更加reliable==

  - 如果actual reported loss可为projecting IBNR reserve提供adequate basis，则应采用更加sophisticated and responsive method

- loss ratio method的缺点

  - actual loss ratio很少等于anticipated loss ratio（有时这种差距非常巨大）

    | situation                                  | 结果               |
    | ------------------------------------------ | ------------------ |
    | actual loss ratio < anticipated loss ratio | redundant reserve  |
    | actual loss ratio > anticipated loss ratio | inadequate reserve |

  - 如果premium rate inadequate（underwriting loss），则再保公司会认为直保公司根据anticipated loss ratio计算得出的premium rate inadequate

### （2）Percentage Method

- ==percentage method是使用IBNR reserve和reported loss之间的historical relationship，得出IBNR forecast中的percentage==

  > 如IBNR loss是total incurred loss的30%，则该年度的IBNR loss即为当年度incurred loss的30%

- 实际应用中，percentage method可为每个accident year确定separate percentage，如果IBNR loss的percentage trend（upward或downward）属于measurable，则用于预测IBNR loss的percentage也应反映这一trend

- ==loss发展成为ultimate level所需的月份（number of month）取决于insurance type==

- percentage method适用于估算property loss reserve（因为property loss可在reported后，进行reasonable accurately estimated）。percentage method不适用于估算liability loss exposure（less accurate，因为liability需要更长时间来develop）

- percentage method估算IBNR reserve的方法

  - IBNR reserve（percentage method）= 当年度reported loss * 当年度IBNR factor

    > | historical accident year | reported loss | evaluation point（development month） | IBNR factor | IBNR reserve            |
    > | ------------------------ | ------------- | ------------------------------------- | ----------- | ----------------------- |
    > | 2011                     | 4725679       | 48                                    | 0           | 4725679 * 0 = 0         |
    > | 2012                     | 4887963       | 36                                    | 0.05        | 4887963 * 0.05 = 244398 |
    > | 2013                     | 4878845       | 24                                    | 0.10        | 4878845 * 0.1 = 487885  |
    > | 2014                     | 4954876       | 12                                    | 0.20        | 4954876 * 0.2 = 990975  |
    > | total                    | 19447363      | -                                     | -           | 1723258                 |



### （3）Loss Triangle Method（loss development method/ chain link method/ chain ladder method/ link ratio method）

- ==loss triangle method是使用historical loss data计算loss development factor，从而估计IBNR reserve==
  - Loss triangle method常用于估算liability insurance的IBNR reserve（特别适用于需要多年才能fully develop的liability insurance）
  - loss triangle method在前两年的loss development时会有wide variability，且比其他reserving method更复杂
  - 只有有historical data，且actuarial assumption准确的情况下，loss triangle method才能得出reliable result
- loss triangle按三角形（triangle shape）的方式展示historical loss data
  - historical loss data包括每个historical year的total reported loss（也可包括paid loss, paid claim number, average claim size等数据）
  - loss triangle得出的estimate取决于triangle中使用的data。reported loss triangle中的data用于预测每个historical year的total loss amount，之后再根据projected loss development得出IBNR reserve
  - loss triangle会分析historical loss development pattern以预测future loss development，所以loss triangle method的major assumption是loss development的historical pattern一直延续
- 大部分的loss triangle都不会非常consistent，会包括anomalous data item（异常数据）
  - ==loss triangle缺点==
    - ==business practice和external condition的改变都会影响triangle的usefulness==
    - ==一次的large event（如catastrophe）会disrupt historical development pattern==
  - 导致anomalous data（异常数据）的原因包括
    - loss frequency/ severity变化
    - rule/ law change
    - adjusting claim delay
    - claim personnel有意的（conscious）increase/ decrease case reserve level
    - laim handling process改变
  - ==随时间推移，持续的inadequate case reserve会导致loss reserve的systematic increase，进而导致larger than normal的loss development factor==
    - 如果loss reserve的systematic increase持续一段时间，知晓reserve是否inadequate或其是否correct会很困难
    - 通常会认为reserve属于inadequate，loss triangle本身不会说明loss reserve adequacy，为阻止此类情况，需仔细分析每个claim file（有时需对individual claim获得additional data）
- 用于loss triangle的loss data可包含/不包含allocated loss adjustment expense (ALAE)
  - 如果loss data包括ALAE，则forecast loss amount也包括ALAE
  - 有时，也可使用单独的loss triangle估算ALAE
- ==使用loss triangle计算IBNR reserve包括4个步骤（P15.17）==
  - ==按loss triangle format组织historical data==
  - ==从loss triangle中计算12-month的loss development factor==
  - ==通过12-month development factor，计算ultimate loss development factor==
  - ==使用ultimate loss development factor计算IBNR reserve==

#### 1）按loss triangle format组织historical data

- Y轴为accident year，X轴为development month，列出对应的incurred loss

#### 2）从loss triangle中计算12-month loss development factor

- ==计算successive 12-month period的loss development factor（12-month loss development factor/ age-to-age loss development factor/ link ratio）==

- 计算average，5-year average（最近5年平均），3-year average（最近3年平均）

- ==确定12-month Loss Development Factors （主要凭judgment）==

  - selection process包括比较不同时期（总的average，5-year average，3-year average）的average factor

    - 选择average factor的方法

      | average factor趋势           | selected factor    |
      | ---------------------------- | ------------------ |
      | ==average factor呈上升趋势== | ==选最大的factor== |
      | average factor呈下降趋势     | 选最小的factor     |
      | average factor没有trend      | 选择中间档         |

    - 如果selected factor和loss data或其他adjacent factor不一样（inconsistent），可对selected factor进行调整

      - 每12个月的损失发展因素都要比它之前的因素小，因为随着loss age增加，loss development trend往往会下降

        > 如24 - 36个月的factor(1.010)会低于12 - 24个月的factor(1.020)

#### 3）通过12-month development factor，计算ultimate loss development factor

- ==ultimate loss development factor是将incurred loss的recent estimate用于估计当年度的ultimate incurred loss==
- Y轴为time period，ultimate loss development factor等于对应时间的factor相乘

#### 4）使用ultimate loss development factor计算IBNR reserve

- estimated ultimate loss = incurred and reported loss * ultimate loss development factor

- IBNR reserve = estimated ultimate loss - incurred and reported loss

  ​						= incurred and reported loss * ultimate loss development factor - incurred and reported loss

  ​						= incurred and reported loss * (ultimate loss development factor - 1) 

#### 5）案例

- P15.17
- ![](https://s1.ax1x.com/2020/07/18/Uce7RK.jpg)

## 3. Loss adjustment expense（LAE）

- bulk reserve可用于allocated loss adjustment expense (ALAE)和unallocated loss adjustment expense (ULAE)

### （1）Allocated Loss Adjustment Expense (ALAE)

- ==ALAE的bulk reserve可通过对earned premium/ incurred loss乘以一个percentage factor得到==

  - 可通过分析保险公司的experience获得percentage factor

    > 如experience显示ALAE占incurred loss的25%，则ALAE reserve = incurred loss * 25%

- 使用percentage factor估算ALAE的缺点

  - 会假设percentage不变（即计算时未发生影响factor的事件），如果发生变化，则percentage factor需调整
  - loss settle manner的变化
    - small loss（特别是settled without payment）比large loss处理的更快，所以一定时间内，total loss reserve通常会包含disproportionate（不成比例的）large loss number
    - large loss比small loss涉及更大比例的ALAE，percentage method会underestimate（低估）ALAE reserve，可使用loss triangle method来克服这一问题

### （2）Unallocated Loss Adjustment Expense（ULAE）

- ==ULAE不能归属到特定的claim case，所以ULAE reserve必须使用bulk reserve（bulk basis）==
- ==ULAE reserve通常是 (sum of incurred loss + ALAE) 的一部分（percentage）==
  - ==保险公司可基于experience估算percentage==
- ULAE包括budgeted item，可在年初估计某年度的total amount
  - 某些ULAE和几年前的incurred loss有关（如long-tail liability insurance）
  - 将current expense分配到prior accident year很常见，但这种allocation会distort（扭曲）current accident year expense

# 五、Combined Methods of Loss Reserving

- ==单一的reserving method不会在所有situation下都能得出best loss reserve estimate，因为每种reserving method都是基于certain underlying assumption。所以可使用多种reserving method以leverage strength并improve loss reserve accuracy==

- ==combined method的三种方法==

  | ==combined method==                      | ==定义==                                                     |
  | ---------------------------------------- | ------------------------------------------------------------ |
  | Two-part combination method              | ==混合了 loss ratio method 和 loss triangle method 的优点==（在policy year开始后，对两者的development month使用weighted average） |
  | Bornhuetter-Ferguson method（BF method） | ==BF method是使用expected loss和IBNR factor估算IBNR reserve==<br/><br/>two-part combination method的variation（变种），BF method不依赖judgmental weight<br><br>==BF method常用于reported loss尚未sufficiently mature（没有sufficient data/ enough data），无法使用loss triangle method的情况（BF method可在只有很少mature data的情况下，估算IBNR reserve）== |
  | Three-part combination method            | ==混合了loss ratio method，loss triangle method和case loss reserve，所以需要三套（three set）weight== |

## 1. Two-part combination method

- ==Two-part combination method是混合了loss ratio method和loss triangle method的优点（在policy year开始后，对两者的development month使用weighted average）==
  - ==在accident year结束时（12-month of development），reserve会给完全依赖loss ratio method（因为reported loss data 还无法形成loss triangle method），随着时间增长，loss triangle method的权重会越来越高，到最后可以完全依赖loss triangle method（P15.23）==
- 具体的weighted average根据judgment判断，不同的insurance type可选择不同的weight

## 2. Bornhuetter-Ferguson method（BF method）

- ==Bornhuetter-Ferguson Method（BF Method）是two-part combination method的variation（变种），BF method不依赖judgmental weight==
- ==BF method是使用expected loss和IBNR factor估算IBNR reserve==
  
  - ==BF method常用于reported loss尚未sufficiently mature（没有sufficient data/ enough data），无法使用loss triangle method的情况（BF method可在只有很少mature data的情况下，估算IBNR reserve）==
  - loss occur和reported to insurer中间的time delay会导致immature loss data（这种delay在liability insurance中更明显）
- 再保公司会在loss reporting方面经历longer delay（因为其会在直保公司建立reserve之后才建立reserve）
  - casualty excess of loss treaty发生的loss通常会经历most delay
  - 在excess of loss treaty的前两三年，再保公司的可能没有reported loss（因为尚未到达直保公司的retention），之后loss才会报告给再保公司

- ==BF method的缺点==
  
  - ==inherent subjectivity level涉及到如何选择IBNR factor（可使用多种用于industry data/ historical insurer data的technique），在此过程中，assumption的small change会引起IBNR reserve的巨大变化，继而影响net income（有时会严重到直接让公司从profit变为loss）==
  
- BF method的步骤 (P15.24)

  - 先决条件
    - 通过loss triangle method获得ultimate earned premium
    - 通过loss ratio method获得initial expected loss ratio
    - 通过loss development factor获得expected percentage of unreported loss
  - 计算initial expected loss
    
    - initial expected loss = ultimate earned premium * initial expected loss ratio
  - 计算IBNR reserve
  
    - IBNR reserve = initial expected loss * expected percentage of unreported loss
    
      > | accident year | ultimate earned premium | initial expected loss ratio | initial expected loss | expected  percentage of unreported loss | IBNR reserve |
      > | ------------- | ----------------------- | --------------------------- | --------------------- | --------------------------------------- | ------------ |
      > | 10            | 13940                   | 0.85                        | 11849                 | 22.5%                                   | 2666         |
      > | 11            | 19110                   | 0.95                        | 18155                 | 30.8%                                   | 5592         |
      > | 12            | 15870                   | 1.10                        | 17457                 | 42.3%                                   | 7384         |
      > | 13            | 15870                   | 1.15                        | 18251                 | 56.3%                                   | 10275        |
      > | 14            | 19100                   | 0.85                        | 16244                 | 72.7%                                   | 11809        |
      > | 15            | 31310                   | 0.8                         | 25048                 | 82.5%                                   | 20665        |



## 3. Three-part combination method

- ==three-part combination method混合了loss ratio method，loss triangle method和case loss reserve，所以需要三套（three set）weight==

- ==three-part的调整步骤==

  | loss development                                            | loss ratio method (%)  | loss triangle method (%) | case reserve (%) |
  | ----------------------------------------------------------- | ---------------------- | ------------------------ | ---------------- |
  | ==第一年==                                                  | ==大部分或全部weight== | 0                        | 0                |
  | 之后                                                        | weight逐渐降低         | weight逐渐上升           | 0                |
  | 之后                                                        | 0                      | weight逐渐降低           | weight逐渐上升   |
  | 最后（所有loss都已经report（只有个别claim remain open）时） | 0                      | 0                        | 全部weight       |

  - ==第一年的weight会大部分或全部放在loss ratio method上==
  - 之后，loss ratio method的weight逐渐降低，loss triangle method的weight逐渐上升
  - 之后，loss triangle method逐渐降低，weight会分配到loss reserve上
  - 最后当所有loss都已经report（只有个别claim remain open）时，所有的reserve会全部基于case loss reserve
    - 强调case loss reserve的原因是，在loss development的final stage上，case reserve会比bulk reserve更准确

- 案例

  | development month | loss ratio method (%) | loss triangle method (%) | case reserve (%) |
  | ----------------- | --------------------- | ------------------------ | ---------------- |
  | 12                | 100                   | 0                        | 0                |
  | 24                | 50                    | 50                       | 0                |
  | 36                | 25                    | 75                       | 0                |
  | 48                | 0                     | 100                      | 0                |
  | 60                | 0                     | 90                       | 10               |
  | 72                | 0                     | 75                       | 25               |
  | 84                | 0                     | 50                       | 50               |
  | 96                | 0                     | 25                       | 75               |
  | 108               | 0                     | 0                        | 100              |



# 六、Salvage和 Subrogation对Loss Reserve的影响

- 直保公司和再保公司建立loss reserve时，都要考虑salvage和subrogation的问题

- 保险公司会尝试使用salvage和subrogation来追回部分loss
  - ==NAIC Annual Statement - Schedule P将salvage和subrogation放在一个category中（因为salvage和subrogation都能减少paid loss 和reserved loss ）==
  - ==如果再保公司contribute to loss payment（支付了部分部分赔偿款），则直保公司会和再保公司share salvage和subrogation==
  
- ==salvage和subrogation==

  |             | 定义                                                         | 效果                                                         | mark                                                         | 案例                                                         |
  | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | salvage     | ==salvage是property转移到保险公司，之后卖出，以抵消保险公司的loss payment== | ==anticipated salvage是减少loss reserve，从而减少（offset）保险公司balance sheet上的liability== | ==不管salvage是由哪一年的loss导致的，获得salvage时，其只会抵消部分当年度的paid loss== | 保险公司赔偿了stolen car value，之后车被找回，则保险公司获得car possession，保险公司可卖车以offset loss |
  | Subrogation | ==Subrogation是保险公司有权向负有legally responsible的第三方，追偿loss payment的权利，常用于auto accident相关的claim，但也可用于其他insurance type== | ==anticipated subrogation recovery可以减少（offset） loss reserve== | subrogation可防止insured从保险公司和faulty third party同时获得赔偿 | 保险公司为damage auto支付repair或replacement费用后，则保险公司有权从legally responsible的第三方获得collect damage的权利（金额以保险公司支付给insured的claim的金额为限） |



# 七、XOL reinsurer的Reserving method

- 再保公司和直保公司使用同样的reserving technique
  - pro rata reinsurer面临的问题和直保公司基本一样
  - XOL中，再保公司估算loss reserve的问题要大得多，需special consideration
- 由于monetary inflation和social inflation影响
  - excess of loss reinsurer估算loss reserve时，比直保公司面临的问题更大
  - excess of loss reinsurer也会面临更长的loss development period
  - 一些loss reserve technique难以用于excess of loss reinsurer

## 1. 影响estimating loss reserve的因素

- 有些factor会不成比例（disproportionately）的影响excess of loss reinsurer估算reserve的能力
  
  - 常用的loss development technique难以用于excess of loss
  
- 影响XOL reinsurer估算reserve的问题

  | ==影响XOL reinsurer估算reserve的问题== | ==具体影响==                                                 |
  | -------------------------------------- | ------------------------------------------------------------ |
  | Monetary inflation                     | monetary inflation会让长时间才能settle的claim的ultimate value变多，从而影响XOL reinsurer的loss reserve<br><br>==monetary inflation对XOL reinsurer的影响大于直保公司== |
  | Social inflation                       | social inflation是某些legislative change会让claimant或certain trend获益（benefit）<br><br>social inflation会增加超过attachment point的claim value，也会增加再保公司需要赔付的claim number |
  | Long loss development period           | long loss development period会让XOL reinsurer低估（understate）loss reserve，因为再保公司无法意识（unaware）到loss已经发生 |

### （1）Monetary inflation

- ==monetary inflation会让长时间才能settle的claim的ultimate value变多，从而影响XOL reinsurer的loss reserve==

- ==monetary inflation对XOL reinsurer的影响大于直保公司==

  > 例如，inflation会让低于retention的property value变得超过retention，继而增加XOL reinsurer的contribution（主要是claim number方面）

- ==liability insurance的long loss development period也会造成inflationary pressure==

  - 如果直保公司的retention未增加，则inflation会disproportionately影响excess of loss reinsurer

### （2）Social inflation

- US legal system的trend导致保险公司支出higher cost

  > judgment amount的增长速度超过inflation的增长速度

- ==social inflation是某些legislative change会让claimant或certain trend获益（benefit）==

- ==social inflation会增加超过attachment point的claim value，也会增加再保公司需要赔付的claim number==

### （3）Long loss development period

- ==long loss development period会让XOL reinsurer低估（understate）loss reserve，因为再保公司无法意识（unaware）到loss已经发生==
- long loss development period取决于contract nature
  - XOL中，只有赔款超过retention时，再保公司才开始赔付，所以直保公司会只向再保公司报告超过agreed amount的claim
  - 但是有些claim在收到报案时，并未超过agreed amount，但最终损失会超过agreed amount，这导致直保公司无法在claim case一开始的时候就报告给再保公司，继而导致再保公司对loss没有sufficient data
  - actuary必须仔细审核loss需要多久才会发展到ultimate value，其需要使用mathematical technique来develop additional loss development factor
- ==XOL reinsurer通常使用Bornhuetter-Ferguson method（BF method是使用expected loss和IBNR factor估算IBNR reserve的方法），BF method可在只有很少mature data的情况下，估算IBNR reserve==

## 2. 使用reserving technique时的困难

- ==再保公司使用的reserving technique和直保公司一样，但有些技术很难应用于XOL reinsurer==
  - ==loss triangle method(损失三角形)中，每个historical accident year的loss development factor会有一个wide rage，很难选择合适的factor==
  - ==再保公司的loss来自于很多直保公司，这些损失并非是homogeneous（同质的），各家公司的reserving practice和claim settlement practice也各有不同==
    - ==再保公司解决lack of homogeneity的方法==
      - ==将数据分为homogeneous category，并为每个category构建单独的triangle的方式解决==
      - actuary负责将data按insurance type和category（如按照treaty layer）对数据进行分类
  - 使用historical claim count和average claim amount构建loss triangle时，也会造成估算reserve的问题
  - ==直保公司的loss reserve可能会比之前的预期更高（reserve may develop much more than originally anticipated）==
- ==每个XOL treaty都不相同==
  - ==有的treaty会有special term或condition，如aggregate limit（再保公司的loss不会超过specific aggregate）==
  - 有的treaty只承保特定的insurance type或unusual loss development pattern的insurance
  - ==combining individual treaty result可增加loss data的statistical credibility，但强调individual treaty的special feature会非常有用==