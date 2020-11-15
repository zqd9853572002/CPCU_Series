# 一、Reinsurance Transaction和NAIC Annual Statement Balance Sheet

- ==NAIC Annual Statement是所有保险公司（包括直保公司和再保公司）每年向其authorized to do business所在州的state insurance department提交的standard uniform financial report==
  
  - ==NAIC Annual Statement按照Statutory Accounting Principles (SAP)编制，向state insurance regulator提供solvency的信息，也能提供nearly uniform financial reporting==
- Annual Statement较complex且lengthy
  - Annual Statement包含balance sheet（asset/ liabilities/ policyholder surplus），statement of income，cash flow statement和supporting exhibit and schedule
  - Annual Statement Blank大概200页，大保险公司的Annual Statement会更多（schedule会列出各种investment security和investment transaction）
  - Annual Statement是保险公司financial information的primary source
- balance sheet属于Annual Statement Blank部分
  - 适用于保险公司的科目包括reinsurance recoverable，reinsurance payable，unearned premium reserve
  
  - 再保公司可通过分析直保公司的Annual Statement以评估其financial strength并确定直保公司的再保需求（ri need）
  
  - balance sheet包括
  
    | asset                     | liability/ surplus/ other fund                               |
    | ------------------------- | ------------------------------------------------------------ |
    | bond                      | Loss and Loss Adjustment Expense Reserve（loss reserve，LAE reserve）（P&C公司最大的liability） |
    | common stock              | Unearned Premium Reserve（P&C公司第二大liability（但可能是property insurance的最大的liability）） |
    | short-term investment     | Reinsurance-Related Liability                                |
    | reinsurance-related asset | Surplus                                                      |
  
    

## 1. Asset（资产）

- ==SAP要求asset分为admitted asset和nonadmitted asset==

  | SAP对asset的分类                | 定义                                                         | mark                                                         | 案例                                                         |
  | ------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | admitted asset（认可资产）      | ==admitted asset是state insurance department批准的，可列入保险公司annual statement - balance sheet的asset== | ==admitted asset需满足minimum liquidity requirement，并有predictable market value<br><br>balance sheet - asset只显示保险公司的admitted asset== | -                                                            |
  | nonadmitted asset（非认可资产） | ==nonadmitted asset是state insurance department不允许列在annual statement - balance sheet的asset，主要原因是nonadmitted asset通常属于not readily marketable（难以市场流通）== | nonadmitted asset不能列在balance sheet上，但显示在annual statement上，所以==保险公司投资nonadmitted asset的，会减少policyholder surplus== | ==如agent balance over 90 days past due<br><br>default investment security== |

  

- ==balance sheet - asset只显示保险公司的admitted asset（supporting schedule会提供更多detail）==

  - ==对于大部分P&C公司，最大的admitted asset为investment security，所以annual statement的前9项均为investment asset（invested asset，如bond，stock）==
  - balance sheet中的asset只提供保险公司invested asset的summary information，未给出investment risk indication
    - 持有low-risk investment portfolio的保险公司，可在underwriting operation上承担higher risk，反之亦然

    - ==持有high-risk investment portfolio (high investment risk) 的保险公司需要additional ri protection，以防止investment operation和underwriting operation同时发生损失（simultaneous loss）==
- ==investment portfolio/ investment risk面临的风险包括==
        - ==investment market price variation（市场价格变动）==
        - ==investment security issuer default（发行人违约）==
        - ==lack of asset liquidity（缺乏流动性）==
    
- liquidity是asset在没有value loss或只有little loss的情况下，转换成cash的容易程度（ease）
  
  - 有时，保险公司必须liquidate investment（如赔付catastrophe loss）

### （1）Bond

- bond是P&C公司最大的single invested asset category

  - ==很多小保险公司大部分（predominantly）asset投资于bond（因为bond属于safest long-term investment，最安全的长期投资）==
  - ==bond market price随interest rate大幅变化，但保险公司会将bond按照amortized value计入annual statement balance sheet（使得bond的annual statement value不受current market price影响，policyholder surplus也不受bond market price decline影响（但出售bond时会被影响））==
    - amortized value反映一段时间内principal和interest的payment value

- balance sheet中的asset无法反映bond portfolio quality，bond market value，maturity date

  - Schedule D - Part 1会列明保险公司持有的每个bond的information，包括interest rate，maturity date，book value（amortized value），par value，fair value（market value），accrued interest。
  - Schedule D - Part 1A显示了所有bond的quality rating和maturity summary
  - Schedule D的其他部分显示了当年度acquired bond和disposed bond

- long-maturity bond会有higher risk（更高的风险）

  - long-maturity bond的market price会和market interest rate呈反向变化（inversely）

    > interest rate下降，long maturity bond的market price上升
    >
    > interest rate上升，long maturity bond的market price下降

  - interest rate change对long-maturity bond的变化大于对short-maturity bond的变化（因为long-maturity bond的interest rate会在较长时间内被锁定（locked））

    - 如果long-maturity bond发行后不久market interest rate上升，holder就会被长期锁定在lower interest rate，继而导致long-maturity bond market value下降

### （2）Common Stock

- P&C公司投资的第二大invested asset category为common stock，但小保险公司不持有大量common stock
  - ==annual statement上的common stock价格会以当年度最后一个business day market value显示==
  - ==stock必须显示其market value，所以stock price fluctuation会导致policyholder surplus的剧烈波动==
  - Schedule D - Part 2 - Section 2会显示common stock detail
- 很多保险公司会在affiliated company/ subsidiary的公司上投入大量stock
  - 这种stock没有established market，所以会导致大量liquidity risk
  - 如果保险公司对subsidiary或affiliated company有significant ri arrangement，则liquidity risk会增加
  - subsidiary的investment value通常属于subsidiary的policyholder surplus
- Schedule D - Summary by Country显示了保险公司投资于其parent company/ subsidiary/ affiliated 的bond/ preferred stock/ common stock的total amount，具体细节会放在Schedule D - Part 6中

### （3）Short-Term Investment

- P&C公司的第三大invested asset为cash/ cash equivalent/ short-term investment
- Short-Term Investment包括某些bond/ bill/ notes/ commercial paper/ certificate of deposit/ money market fund share
- 所有short-term investment的maturity period均不超过1年，short-term investment应和保险公司一年内的payment liability short-tail type of insurance的loss reserve）相match

### （4）Reinsurance-Related Asset

- ==保险公司的annual statement balance sheet上和ri transaction直接相关（deal directly with ri）的asset item，通常只有3个==

  | 和ri transaction直接相关的asset                              | 定义                                                         | 出现位置                                                     | 常用性   |
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
  | ==amounts recoverable from reinsurers==                      | ==amounts recoverable from reinsurer是直保公司可从再保公司recover的total amount，显示在annual statement balance sheet上的asset中== | recoverable by individual reinsurer会列在Schedule F - Part 3 | 最常用   |
  | ==funds held by or deposited with reinsured company==        | funds held by or deposited with reinsured company是再保公司存在直保公司的fund（fund deposited with a primary insurer），amount属于asset of reinsurer<br><br>出于监管目的，unauthorized reinsurer必须deposit asset（deposit asset amount等于unearned premium和loss payable（含loss reserve）） | 显示在balance sheet的asset部分                               | 最常用   |
  | ==other amounts receivable under reinsurance contract==      | other amounts receivable under reinsurance contract是用于不符合amount recoverable from reinsurer科目，但确实可从ri contract中recover的amount recoverable | 列入annual statement balance sheet的asset部分                | 最常用   |
  | Uncollected premiums and agents’ balances in the course of collection | 包括再保公司无法从直保公司收回的premium（uncollected premium） | -                                                            | 数额较小 |
  | Receivables from parent, subsidiaries and affiliate          | 如果parent company和subsidiary或affiliated company存在reinsurance relationship（特别是parent company为其subsidiary或affiliated company购买了reinsurance），则包含部分ri element | -                                                            | 数额较小 |

## 2. Liabilities, Surplus, and Other Fund（负债，权益和其他fund）

- balance sheet的liability side总结了保险公司的liability/ policyholder surplus/ other fund
- 保险公司的principal liability包括loss reserve，loss adjustment expense reserve，unearned premium reserve
  - ==loss reserve和loss adjustment expense（LAE） reserve是P&C公司最大的liability==
  - ==unearned premium reserve是P&C公司第二大liability（但可能是property insurance的最大的liability）==

### （1）Loss and Loss Adjustment Expense Reserve（loss reserve，LAE reserve）

- loss and loss adjustment expense reserve（loss reserve和LAE reserve）包括
  - ==loss reserve是指保险公司要支付已发生但仍未settle（already occurred but have not yet been settled）的liability，loss reserve会显示在balance sheet中liability的部分==
    - reinsurance payable on paid loss and loss adjustment expense是直保公司已经支付给被保险人，但再保公司尚未支付给直保公司的赔款
  - ==loss adjustment expense reserve/ LAE reserve是已发生的，保险公司应当支付的LAE-related loss==

- loss reserve information的位置

  | 位置                                                         | 具体信息                                                |
  | ------------------------------------------------------------ | ------------------------------------------------------- |
  | Underwriting and Investment Exhibit/ UIE - Part 2A - Column 8 | loss reserve的detailed information（by insurance type） |
  | Schedule P                                                   | loss reserve detail                                     |
  | Underwriting and Investment Exhibit/ UIE - Part 2A - Column 9 | total unpaid LAE reserve                                |
  | Schedule P - Part 1                                          | LAE的additional detail（by insurance type）             |

  

### （2）Unearned Premium Reserve

- ==unearned premium reserve是已从policyholder收取，但尚未earned的premium==
- Underwriting and Investment Exhibit/ UIE - Part 1A会列出Unearned Premium Reserve（by insurance type）
- 可使用straightforward procedure计算unearned premium reserve
- unearned premium reserve基于保险公司收取的premium，如果premium不足以支付loss and expense，则unearned premium reserve会inadequate，无法支付future loss and expense

### （3）Reinsurance-Related Liability

| asset item                                                   | 定义                                                         | 对应                                                         | 显示位置                          |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------- |
| ==再保公司balance sheet - liability - Reinsurance payable on paid loss and loss adjustment expenses== | ==直保公司已经支出，且再保公司应当支付给直保公司的loss amount== | ==直保公司balance sheet - asset - Amounts recoverable from reinsurers== | Schedule F - Part 1 - Column 6    |
| ==直保公司balance sheet - asset - Receivables from parent, subsidiaries, and affiliates== | -                                                            | -                                                            | -                                 |
| ==直保公司balance sheet - asset - Other amounts receivable under reinsurance contracts== | -                                                            | -                                                            | -                                 |
| **liability item**                                           | **定义**                                                     | **对应**                                                     | **显示位置**                      |
| ==直保公司balance sheet - liability - Ceded reinsurance premiums payable== | ==直保公司拖欠的，应当支付给再保公司的premium==              | ==再保公司balance sheet - asset - Uncollected premiums and agents balances in course of collection== | -                                 |
| ==直保公司balance sheet - liability - Funds held by company under reinsurance treaties== | ==直保公司从再保公司获得的fund<br><br>- 从unauthorized reinsurer购买再保的，直保公司可通过此类fund获得ri credit== | ==再保公司balance sheet - asset - Funds held by or deposited with reinsured companies== | detail会显示在Schedule F - Part 3 |
| ==provision for reinsurance==                                | ==total provision for overdue reinsurance and collateral deficiency requirement for unauthorized and certified reinsurer== | -                                                            | Schedule F - Part 8               |



### （4）Surplus

- ==surplus分为三类：contributed surplus，unassigned surplus，treasury stock==
  - ==contributed surplus是其他方投资给公司的money==
  - ==unassigned surplus是undistributed/ unappropriated surplus amount==
- policyholder surplus entry和noninsurance business（非保险企业）的surplus entry类似，但保险公司会使用Surplus as regards policyholder entry（此项不用于noninsurance business）

# 二、Underwriting and Investment Exhibit/ UIE

- ==保险公司会准备多个schedule和exhibit，以展示NAIC Annual Statement中balance sheet和statement of income的detail==
  - ==schedule和exhibit会提供大量保险公司financial condition和reinsurance operation方面的information==
- ==statement of income是衡量保险公司一年之内的earning（可据此确定保险公司的federal income tax liability）==
  - 各种exhibit中，关于underwriting/ investment/ other income source方面的detail可支持statement of income中的summary value
  - ==Underwriting and Investment Exhibit/ UIE可为statement of income - underwriting income section提供supporting information==
  - Underwriting and Investment Exhibit/ UIE受ri transaction影响

## 1. Statement of Income

- statement of income和其他行业的income statement结构类似
  - statement of income包括premium earned，losses and expenses incurred，resulting net underwriting gain or loss
- ==再保公司使用statement of income来确定直保公司的financial strength（indicator）==
  - statement of income只显示当年度和上一年度的profit/ loss
  - five-year historical data exhibit显示当年度和过去4年的income
  - ==应从直保公司的earned premium中减去incurred loss adjustment expense（LAE），以获得net underwriting gain or loss amount（而非获得Net investment income earned）==

## 2. Underwriting and Investment Exhibit（UIE）

- ==Underwriting and Investment Exhibit/ UIE为statement of income - underwriting income section提供supporting information==
  
  - Part 1和Part 1B列出了保险公司所有的insurance type（包括进入excess of loss reinsurance的保险）
    - ==pro rata ri会根据所属的insurance type列出==
    - ==non-proportional ri会按照property/ liability/ financial的分类显示==
    - Part 1，Part 1B和Part 2（按insurance type显示loss experience）放在一起会展示多更多的useful information
    
  - 各部分列出的内容
  
    |                                                     | 显示内容                                                     | 分类方法                                                     | mark                                                         |
    | --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | Part 1 - Premiums Earned                            | ==premium earned<br><br>premium earned component==           | ==insurance type==                                           |                                                              |
    | Part 1B - Premiums Written                          | ==premium written<br><br>net written premium==               | ==insurance type==                                           |                                                              |
    | Part 2 - Losses Paid and Incurred                   | ==loss==                                                     | ==loss paid和loss incurred按direct business，reinsurance assumed，reinsurance recovered分类显示<br><br>不区分reinsurance with affiliates和reinsurance with other reinsurer== | ==Part 2使用Part 1的premium earned计算每个insurance type的loss ratio== |
    | Part 2A - Unpaid Losses and Loss Adjustment Expense | ==loss 和 loss adjustment expense（LAE）的total estimated loss<br><br>unpaid net loss（包括Column 8 - IBNR，但不包括 Column 4 - IBNR）== | ==insurance type==                                           |                                                              |
    | Part 3 - Expenses                                   | ==为statement of income提供supporting document==             | ==按3个major functional area和numerous expense group分配expense，但不会根据insurance line分析expense== |                                                              |
  
    

### （1）Part 1 - Premiums Earned

- ==Part 1是按insurance type显示premium earned和premium earned component（均属于assumed and ceded ri）==

- ==premium earned = 本年度的net written premium + 上年度（12月31日的）unearned premium - 本年度 unearned premium==

  > background：
  >
  > - net written premiums（ current year） = 500
  >
  > - unearned premiums as of December 31 of the prior year = 50
  > - unearned premiums for the current year = 150
  >
  > solution：
  >
  > - premiums earned = (500 + 50) - 150 = 400

### （2）Part 1B - Premiums Written

- ==Part 1B是按insurance type显示premium written和net written premium（均属于assumed and ceded ri）==

- ==net written premium = direct business + reinsurance assumed - reinsurance ceded==

  ​									=== direct business + (reinsurance assumed from affiliates + reinsurance assumed from non-affiliates) - (reinsurance ceded to affiliates + reinsurance ceded to non-affiliates)==

- 再保公司可使用Part 1B评估直保公司的business mix，也可和Schedule T - Exhibit of Premiums Written（按state/ territory展示written premium）一起评估
  - 再保公司可使用Schedule T确定直保公司policy portfolio的geographic distribution
  - 再保公司可使用使用Underwriting and Investment Exhibit/ UIE和Schedule T一起，评估直保公司的operation comprehensive overview

### （3）Part 2 - Losses Paid and Incurred

- ==Part 2是按insurance type显示loss==
  - ==loss paid和loss incurred按direct business，reinsurance assumed，reinsurance recovered分类显示，但不区分reinsurance with affiliates和reinsurance with other reinsurer==
- ==Part 2使用Part 1的premium earned计算每个insurance type的 loss ratio==

### （4）Part 2A - Unpaid Losses and Loss Adjustment Expense

- ==Part 2A是按insurance type显示loss 和 loss adjustment expense（LAE）的total estimated loss==
  - Schedule P会列明supporting detail
- ==Part 2A显示unpaid net loss（包括Column 8 - IBNR，但不包括 Column 4 - IBNR）==
  - 通过结合Part 2, Part 2A, Part 1B的loss data，可大致看出直保公司在ri operation上的profitability
  - incurred loss方面，affiliate和nonaffiliates的ri transaction未能分开
- Part 2A - Column 8按insurance type显示了total net unpaid loss，Column 8的total figure会转到balance sheet - liability section
- Part 2A - Column 9按insurance type显示了total unpaid LAE reserve，其会转到balance sheet - liability section

### （5）Part 3 - Expenses

- ==Part 3是为statement of income提供supporting document==

- ==Part 3按3个major functional area和numerous expense group分配expense，但不会根据insurance line分析expense==

  | ==major functional area== | ==expense group==        |
  | ------------------------- | ------------------------ |
  | loss adjustment           | claim adjustment service |
  | other underwriting        | commission and brokerage |
  | investment                | advertising              |
  | -                         | salary                   |
  | -                         | others                   |

  

- claim adjustment service LAE 和net other underwriting expense from commission and brokerage = direct business + reinsurance assumed - expense from reinsurance ceded (P14.17)

# 三、Schedule F

- ==Schedule F是包括和保险公司reinsurance activity的information==

  - ==Schedule F是显示ceded reinsurance和assumed reinsurance的详细信息，portfolio transfer，restated balance sheet（显示ri transaction之前的直保公司的asset 和liability on a gross basis）==

    | Schedule F | 内容                                                         |
    | ---------- | ------------------------------------------------------------ |
    | Part 1 - 3 | 为保险公司的assumed ri and ceded ri accounting entry提供supporting data |
    | Part 4 - 7 | 为Part 8的reinsurance provision提供data                      |
    | Part 9     | restate statutory balance sheet from net to gross basis      |

  

- Schedule F各部分显示的信息

  | Schedule F - Part                                            | 显示的信息和作用                                             |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | Part 1 - Assumed Reinsurance                                 | 再保公司的reinsurance assumed<br><br>- paid and reserved loss<br/>- loss adjustment expense (LAE) amount<br/>- fund deposited with primary insurer（包括代表直保公司的letter of credit） |
  | Part 2 - Premium Portfolio Reinsurance                       | 保险公司本年度（current year）所有的ceded and assumed portfolio reinsurance transaction |
  | Part 3 - Ceded Reinsurance                                   | ceded reinsurance的detail<br><br>会列明authorized reinsurer/ unauthorized reinsurer/ certified reinsurer |
  | Part 4 - Aging of Ceded Reinsurance                          | 说明了paid loss和paid LAE的aging of ceded reinsurance recoverable<br/><br/>recoverable amount分为current amount (Column 5)和amount overdue by a certain number of days (Column 6 - 10) |
  | Part 5 - Provision for Unauthorized Reinsurance              | 计算unauthorized insurance provision（属于直保公司balance sheet - liability中overall reinsurance provision的一部分） |
  | Part 6 - provision for overdue certified reinsurance         | NAIC reform之后添加的，用以减少reinsurance collateral requirement<br><br>Part 6 为各州certify和rate再保公司提供了process |
  | Part 6 - provision for overdue certified reinsurance - Section 1 | 为certified reinsurer计算因collateral deficiency而导致的reinsurance provision |
  | Part 6 - provision for overdue certified reinsurance - Section 2 | 为overdue reinsurance ceded to certified reinsurer建立了provision，也用于决定certified reinsurer是否属于slow-paying (by reference to particular percentage) |
  | Part 7 - Provision for Overdue Authorized Reinsurance        | 确立了每个authorized reinsurer的overdue amount，通过reference to a particular percentage确定再保公司是否属于slow-paying |
  | Part 8 - Provision for Overdue Reinsurance (authorized over 20%) | 计算属于slow-paying的provision for overdue authorized reinsurance |
  | Part 9 - Restatement of Balance Sheet to Identify Net Credit for Ceded Reinsurance | 属于restatement of balance sheet，以识别ceded reinsurance<br><br>会restate asset和liability，以显示balance sheet的gross of ceded reinsurance<br><br>==Part 9的figure表明直保公司ri program的effectiveness== |
  
  
  
- Schedule F的特点是计算直保公司balance sheet中liability部分的reinsurance provision

  - 如果保险公司只在balance sheet中post liability，而不增加其asset，则policyholder surplus会减少，所以保险公司会倾向于minimize provision for reinsurance

## 1. Part 1 - Assumed Reinsurance

- ==Schedule F - Part 1 - assumed reinsurance显示了再保公司的reinsurance assumed，包括==
  - ==paid and reserved loss==
  - ==loss adjustment expense (LAE) amount==
  - ==fund deposited with primary insurer（包括代表直保公司的letter of credit）==
- Schedule F - Part 1 - Column 12是Funds Held By or Deposited With Reinsured Companies，期限是reinsurer deposited with the primary insurer，会在再保公司balance sheet的asset中显示total amount

## 2. Part 2 - Premium Portfolio Reinsurance

- ==Schedule F - Part 2 - premium portfolio reinsurance显示保险公司本年度（current year）所有的ceded and assumed portfolio reinsurance transaction==
  - ==portfolio reinsurance transaction包括保险公司已经written的business block==
  - ==portfolio reinsurance transaction可只包括known loss（loss portfolio transfer），或同时包括known loss + unknown loss==
    - loss portfolio transfer通常属于extraordinary event，Schedule F会强调这些transaction的additional scrutiny
    - Schedule F - Part 2写明了portfolio reinsurer name，ri contract （ri agreement） date，original premium/ underlying premium amount，reinsurance premium amount

## 3. Part 3 - Ceded Reinsurance

- ==Schedule F - Part 3 - ceded reinsurance提供ceded reinsurance的detail==
  - ==会列明authorized reinsurer/ unauthorized reinsurer/ certified reinsurer==
  - 应显示paid loss和 paid LAE，known case loss和LAE reserve，IBNR reserve和LAE reserve，unearned premium，contingent commission（profit commission）
  - Schedule F - Part 2 - Column 19 （funds held by company under reinsurance treaties）amount that reinsurer deposited with the primary insurer
  - total amount汇集在直保公司balance sheet的liability部分
  - ==应从total recoverable中subtract（减去）ceded balances payable to reinsurer，以让直保公司确定net amount recoverable from reinsurer==

## 4. Part 4 - Aging of Ceded Reinsurance

- ==Schedule F - Part 4 - aging of ceded reinsurance说明了paid loss和paid LAE的aging of ceded reinsurance recoverable==
  - ==recoverable amount分为current amount (Column 5) 和 amount overdue by a certain number of days (Column 6 - 10)==
  - reinsurance recoverable基于uncollected的时间越长，保险公司越不可能collect（即时间越长，坏账可能性越大）

## 5. Part 5 - Provision for Unauthorized Reinsurance

- ==Schedule F - Part 5 - Provision for Unauthorized Reinsurance计算unauthorized insurance provision（属于直保公司balance sheet - liability中overall reinsurance provision的一部分）==
- ==reinsurance provision的效果是减少policyholder surplus==
  - ==将unauthorized reinsurance amount纳入进来，会减少直保公司和unauthorized reinsurer做业务的incentive（即产生disincentive effect）==
- 再保公司为直保公司提供reinsurance recoverable collateral，可减少unauthorized reinsurance provision amount
  - collateral amount列在Schedule F - Part 5，包含fund that a reinsurer deposit with the primary insurer和再保公司为直保公司出具的letter of credit
  - 但即使all recoverable属于fully secured，对于超过90天past due或in dispute的amount仍要支付unauthorized reinsurance provision。实践中，直保公司可能会redeem部分或全部collateral，以便于no loss are overdue by more than 90 days

## 6. Part 6 - provision for overdue certified reinsurance

- ==Schedule F - Part 6 - provision for overdue certified reinsurance是NAIC reform之后添加的，用以减少reinsurance collateral requirement==
  - ==Part 6 为各州certify和rate再保公司提供了process==
  - certified reinsurer需根据其rating，在0-100%范围内post collateral，直保公司可从和certified reinsurer的业务中获得ri credit
- Part 6分为Provision for Reinsurance Ceded to Certified Reinsurers (Section 1) 和 Provisions for Overdue Reinsurance Ceded to Certified Reinsurers (Section 2)

### （1）Part 6 - Section 1 - Provision for Reinsurance Ceded to Certified Reinsurers

- ==Part 6 - Section 1为certified reinsurer计算因collateral deficiency而导致的reinsurance provision（会成为overall provision for reinsurance的一部分）==

### （2）Part 6 - Section 2 - Provisions for Overdue Reinsurance Ceded to Certified Reinsurers

- ==Part 6 - Section 2为overdue reinsurance ceded to certified reinsurer建立了provision，也用于决定certified reinsurer是否属于slow-paying (by reference to particular percentage)==

- percentage = 90天之外的ri recoverable on paid loss and paid LAE / 90之内的ri recoverable on paid loss and paid LAE

  | percentage范围    | 结果                               |
  | ----------------- | ---------------------------------- |
  | percentage < 20%  | 要计算overdue reinsurance penalty  |
  | percentage >= 20% | certified reinsurer属于slow-paying |

## 7. Part 7 - Provision for Overdue Authorized Reinsurance

- ==Schedule F - Part 7 - Provision for Overdue Authorized Reinsurance确立了每个authorized reinsurer的overdue amount，通过reference to a particular percentage确定再保公司是否属于slow-paying==

- percentage = 大于90天的reinsruance recoverable on paid loss and paid LAE / 小于90天的sum reinsurance recoverable on paid loss and paid LAE

  | percentage范围    | 结果                                |
  | ----------------- | ----------------------------------- |
  | percentage < 20%  | 进行penalty                         |
  | percentage >= 20% | authorized reinsurer属于slow-paying |

## 8. Part 8 - Provision for Overdue Reinsurance (authorized over 20%)

- ==Schedule F - Part 8 - Provision for Overdue Reinsurance (authorized over 20 percent) 计算属于slow-paying的provision for overdue authorized reinsurance==
- ==可实现两个目标==
  - ==top part计算超出Part 7 20% benchmark的overdue provision==
  - ==penalty会和Part 5 - 7的penalty合在一起，确定total reinsurance provision，并成为balance sheet - liability的ultimate report==

## 9. Part 9 - Restatement of Balance Sheet to Identify Net Credit for Ceded Reinsurance

- ==Schedule F- Part 9 - Restatement of Balance Sheet to Identify Net Credit for Ceded Reinsurance属于restatement of balance sheet，以识别ceded reinsurance==
  - ==会restate asset和liability，以显示balance sheet的gross of ceded reinsurance==
- ==Part 9的figure表明直保公司ri program的effectiveness==

## 10. ==provision of reinsurance分类表==

| ==再保公司类型==       | ==provision of reinsurance（ri provision/ reinsurance provision）== |
| ---------------------- | ------------------------------------------------------------ |
| unauthorized reinsurer | ① 100% of recoverables owed less collateral provided<br> + <br>② 20% of recoverables more than 90 days past due not in dispute<br>+<br>③ 20% of amounts in dispute<br><br>整体的上限为100% of all recoverables |
| certified reinsurer    | ① 0%~100% of recoverables owed less collateral provided<br>+<br> ② 20% of recoverables more than 90 days past due not in dispute<br>+<br>③ 20% of amounts in dispute |
| authorized reinsurer   | ① 20% of recoverables more than 90 days overdue regardless of collateral provided<br>+<br>② 20% of amounts in dispute |
| slow-paying reinsurer  | ① 20% of total recoverables owed less collateral provided<br>+<br>② GREATER OF（以下两项中取高）<br><br>a. 20% of unsecured recoverables including amounts in dispute <br><br>b. 20% of recoverables more than 90 days past due |



# 四、Schedule P

- ==评估loss reserve对确定保险公司的financial condition非常重要==

- ==对loss和loss adjustment expense（LAE）的total estimated liability出现在balance sheet的liability部分，也出现在Underwriting and Investment Exhibit - Part 2A部分==
  
  - ==NAIC Annual Statement - Schedule P包括相关的supporting data==
  
- ==Schedule P显示paid and reserved loss 和 LAE方面的detailed historical information==

- Schedule P的size和complexity显示了loss reserve的重要性
  - Schedule P - Analysis of Loss and Loss Expense由7部分 + interrogatory组成
  - 前4部分均包括每个insurance type的subpart
  - Part 1总结了Part 1 - 4，即part 1包括所有的insurance class
  
- Schedule P的各部分

  |                     | 内容                                                         | 分类方法               |
  | ------------------- | ------------------------------------------------------------ | ---------------------- |
  | Schedule P - Part 1 | 提供historical loss/ loss expense的detailed information和earned premium和loss/ loss expense的分析 | insurance type subpart |
  | Schedule P - Part 2 | 提供incurred net loss and defense and cost containment expense的history和development | insurance type subpart |
  | Schedule P - Part 3 | 提供cumulative net paid loss/ defense and cost containment expense方面的history<br><br>==包括closed claim number with loss payment and without loss payment== | insurance type subpart |
  | Schedule P - Part 4 | ==包含IBNR的bulk history（data会形成loss development triangle（损失进展三角形））== | insurance type         |

  

## 1. Schedule P - Part 1

- ==Schedule P - Part 1提供historical loss/ loss expense的detailed information和earned premium和loss/ loss expense的分析==
  - Schedule P - Part 1按照insurance type subpart进行区分
- ==Schedule P - Part 1 - Summary包括premiums earned，loss and loss expense payment，losses unpaid，defense and cost containment unpaid，adjusting and other unpaid，total losses and loss expenses incurred==
- Schedule P - Part 1会显示最近10年的relevant data，过去10年的aggregate data
  - 不包括numerical data的部分会标记为XXX

## 2. Schedule P - Part 2

- ==Schedule P - Part 2提供incurred net loss and defense and cost containment expense的history和development==

- ==Schedule P - Part 2按照insurance type subpart进行区分==

  | ==column==    | ==内容==                                  |
  | ------------- | ----------------------------------------- |
  | ==column 11== | ==显示过去几年的loss amount development== |
  | ==column 12== | ==显示过去两年的loss development==        |

  - ==每个column中的positive number表示incurred loss增加，negative number表示incurred loss 减少==

## 3. Schedule P - Part 3

- ==Schedule P - Part 3提供cumulative net paid loss/ defense and cost containment expense方面的history==
- ==Schedule P - Part 3还提供closed claim number with/ without loss payment==
- Schedule P - Part 3按照insurance type subpart进行区分

## 4. Schedule P - Part 4

- ==Schedule P - Part 4包含IBNR的bulk history，按insurance type分类==
  - ==data会形成loss development triangle（损失进展三角形）==
- ==loss and expense的bulk and IBNR reserve包括==
  - ==IBNR claim reserve==
  - ==reopened claim reserve==
  - ==newly reported claim without specific case reserve的aggregate reserve==
- 随时间推移，bulk和IBNR reserve会被case reserves reported和claim payment made替代