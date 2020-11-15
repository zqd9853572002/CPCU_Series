# 一、再保险的分类


- primary insurer与reinsurer间的每个ri agreement都是独特的（unique），其term反映了primary insurer need和reinsurer满足need的willingness


- ri transaction分为treaty ri和facultative ri


  - 可根据primary insurer和reinsurer在ri agreement项下的obligation manner继续细分，可分为pro rata ri和excess of loss ri（XOL），这两种分类反映出双方如何share premium/ insurance amount/ loss


- 一个ri agreement中可包含多个ri agreement type，以满足直保公司的需求


- ri agreement都不是标准的（non-standardized）


- ==再保的分类==

  ```mermaid
  graph TD
  id1(ri) --> id2(Treaty)
  id1(Reinsurance) --> id3(Facultative)
  id2(Treaty) -->id4(Pro Rata/ proportional)
  id2(Treaty) -->id5(Excess of Loss)
  id3(Facultative) -->id6(Pro Rata)
  id3(Facultative)-->id7(Excess of Loss)
  id4(Pro Rata) -->id8(Quota Share)
  id4(Pro Rata) -->id9(Surplus Share)
  id5(Excess of Loss) -->id10(Per Risk)
  id5(Excess of Loss) -->id11(Catastrophe)
  id5(Excess of Loss) -->id12(Per Policy)
  id5(Excess of Loss) -->id13(Per Occurrence)
  id5(Excess of Loss) -->id14(Aggregate)
  ```





| 第一层      | 第二层      | 第三层         | 第四层             |
| ----------- | ----------- | -------------- | ------------------ |
| Reinsurance | Treaty      | Pro Rata       | Quota Share        |
| -           | -           | -              | Surplus Share      |
| -           | -           | Excess of Loss | Per Risk XOL       |
| -           | -           | -              | Catastrophe XOL    |
| -           | -           | -              | Per Policy XOL     |
| -           | -           | -              | Per Occurrence XOL |
| -           | -           | -              | Aggregate XOL      |
| -           | Facultative | Pro Rata       | -                  |
| -           | -           | Excess of Loss | -                  |

  

## 1. Pro Rata ri (proportional ri)

- ==Pro Rata ri (proportional ri)是直保公司和再保公司按同样的比例（same proportionately）分摊insurance amount/ policy premium/ loss/ loss adjustment expense (LAE)等==
  
  - loss adjustment expense/ LAE是保险公司用于investigate/ defend/ settle claim的费用
  
- ==Pro Rata ri (proportional ri)中==

  - ==直保公司向再保公司支付ri premium（original insurance premium的一部分）==

  - ==再保公司向直保公司支付ceding commission==

    - ==ceding commission是用于补偿直保公司underlying policy acquisition expense==

      | ==ceding commission的类型==                                  | 解释                                                         | mark                                                         |
      | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
      | ==flat commission==                                          | ==ceding commission按ceded premium的固定比例计算，不根据直保公司的loss experience进行调整== | -                                                            |
      | ==profit-sharing commission<br><br>profit commission<br><br> contingent commission== | ==在treaty year结束后，如果再保公司能earn greater-than-expected profit，则向直保公司支付ceding commission== | profit-sharing commission的比例通常是预先决定好的（predetermined），适用于再保公司的excess profit（扣除了loss, expense, reinsurer minimum profit margin之后的profit） |
      | ==Sliding scale commission==                                 | ==再保公司先付给直保公司initial commission，之后根据ri agreement的actual profit和formula调整commission（有可能低于initial paid commission）== | -                                                            |

  

- ==Pro rata ri适用于newly incorporated（新成立的）或只有limited capital的保险公司（因为Pro rata可提供surplus relief）==
  
  - XOL通常不按pro rata方式支付commission
  
- ==pro rata ri分为Quota Share（QSR）和Surplus Share（SSR）==

  - ==QSR和SSR的区别在于如何确定直保公司的retention==

### （1）Quota Share

- ==quota share/ QSR是双方按照fixed percentage分摊insurance amount/ policy premium/ loss/ loss adjustment expense (LAE)==

  - ==quota share/ QSR适用于property insurance（最常用）和 liability insurance==

- ==QSR命名：按再保公司接收的比例命名==

  > ==直保公司自留45%，再保公司接收55%，此时称为“55% quota share treaty”==

- maximum dollar limit和per occurrence limit

  - ==maximum dollar limit是再保公司最多赔付的金额，超过此金额后的损失，直保公司自行承担==

    - pro rata ri agreement中，maximum dollar amount适用于treaty项下的每张保单

      > 如双方签订55% quota share treaty，同时约定treaty项下每张policy的maximum coverage amount为1 million

  - per occurrence limit限定了再保公司对single occurrence的最大赔付金额

    - per occurrence limit分为aggregate dollar amount或loss ratio cap
      - loss ratio = (loss + loss adjustment expense) / earned premium
      - loss ratio反映了premium被loss consume的比例）
    - per occurrence limit限制了pro rata ri保护直保公司遭受catastrophic event时的usefulness，所以直保公司通常会在其ri program中增加catastrophe excess of loss ri（可保障single catastrophic event导致的accumulation of retained loss）

- QSR中常见的问题

  - 由于所有都按fixed percentage分配，所以retention/ cession的dollar amount会随insurance amount变化。保单的insurance amount越高，直保公司的retention也越多
  - ==QSR中，所有保单都会进入分保程序，low insurance amount的业务（直保公司可safely retained的业务）也会自动分保==
  - 由于采用fixed percentage来分配premium/ loss，直保公司可以combine premium and loss amount，并决定amounts owed to the reinsurer in premiums and owed by the reinsurer in losses
  - ==QSR中，再保公司通常不会有adverse selection的问题，对于ceded loss exposure（分出的风险），再保公司的loss ratio和直保公司一样==

- ==variable quota share treaty/ VQSR是retention percentage会根据specified predetermined criteria（如needed insurance amount）而变动==

  - ==variable quota share treaty/ VQSR的优点：可让直保公司自留大量的small loss exposure，但对large loss exposure只自留smaller retention==

### （2）Surplus Share（SSR）

- ==surplus share/ SSR是pro rata的一种，如果underlying policy超过一定金额（line），再保公司承保之后的损失，SSR只适用于property insurance==

- surplus share（SSR）中，再保公司和直保公司按比例分摊premium/ loss

  - 双方先按line（retention）/ total insurance amount和ceded amount/ total insurance amount算出分摊比例，之后根据比例计算premium和loss的分摊金额

    - 直保公司自留的比例 = line (retention) / total insurance amount
    - 再保公司接收的比例 = ceded amount / total insurance amount
    - 之后按上述比例计算各自的premium和loss
    
    > line（直保自留金额） = 25，三个业务如下
    >
    > - A: insurance amount = 25, premium = 0.4, loss = 8
    >
    > - B: insurance amount = 100, premium = 1, loss = 10
    >
    > - C: insurance amount = 150, premium = 1.5, loss = 60
    >
    >   | 标的 |                  | 直保公司retention                        | 再保公司cession                                         | total |
    >   | ---- | ---------------- | ---------------------------------------- | ------------------------------------------------------- | ----- |
    >   | A    | 比例             | line/ insurance amount = 25/ 25 = 100%   | ceded amount/ insurance amount = (25-25) / 25 = 0%      | 100%  |
    >   |      | insurance amount | 25 * 100% = 25                           | 25 * 0% = 0                                             | 25    |
    >   |      | premium          | 0.4 *100% = 0.4                          | 0.4 * 0% = 0                                            | 0.4   |
    >   |      | loss             | 8 *100% = 8                              | 8 * 0% = 0                                              | 8     |
    >   | B    | 比例             | line/ insurance amount = 25/ 100 = 25%   | ceded amount/ insurance amount = (100-25) / 100 = 75%   | 100%  |
    >   |      | insurance amount | 100 * 25% = 25                           | 100 * 75% = 75                                          | 100   |
    >   |      | premium          | 1 * 25% = 0.25                           | 1 * 75% = 0.75                                          | 1     |
    >   |      | loss             | 10 * 25% = 2.5                           | 10 * 75% = 7.5                                          | 10    |
    >   | C    | 比例             | line/ insurance amount = 25/ 150 = 16.7% | ceded amount/ insurance amount = (150-25) / 150 = 83.3% | 100%  |
    >   |      | insurance amount | 150 * 16.7% = 25                         | 150 * 83.3% = 125                                       | 150   |
    >   |      | premium          | 1.5 * 16.7% = 0.25                       | 1.5 * 83.3% = 1.25                                      | 1.5   |
    >   |      | loss             | 60 * 16.7% = 10                          | 60 * 83.3% = 50                                         | 60    |

  

  - ==如果insurance amount < retention，则该风险不参与分保，即所有的风险，保费，loss均由直保公司自留==

- SSR中的ri limit (total limit/ capacity) 按照直保公司line（线）的几倍表示，也可按照再保公司愿意提供的insurance amount表示

  > ==policy limit为1000，retention为200，可表示为“4-line SSR with 200 line”==

  > line = 300，surplus share treaty为9 line（9条线），则underwriting capacity 为300 * (1 + 9) = 3000
  >
  > 或表示为 ri = 2700

- surplus share的特点

  - ==SSR不承保直保公司line以下的保单。所以直保公司会使用surplus share（作为quota share ri的alternative）来承保其可以safely retained的保单==

  - 大量的小额保单，可能引发aggregate loss，从而让直保公司发生not reinsured significant loss

    > 大量同地区的家财险保单，均未超过直保公司的line（也就无法进入surplus share的分保），one single occurrence（如一次hurricane）导致直保公司发生extensive loss

  - ==每个loss exposure的分摊比例不一样，导致其administer cost高于quota share treaty。直保公司必须保留各种记录（包括所有loss exposure history）并定期向再保公司报告bordereau（明细表）==

    - ==bordereau是直保公司定期向再保公司提供的，包含所有treaty项下所有loss exposure history的report==

  - SSR可为直保公司提供surplus relief（再保公司得到ceded policy，其会向直保公司支付ceding commission）
    
    - ==SSR只分保超过line的业务，所以在surplus relief方面，SSR  < QSR==

- ==很多SSR允许直保公司根据potential loss severity，变动line（但有minimum amount/ maximum amount限制），但不改变treaty中line的倍数（即通过变动line，缩小或扩大最终的underwriting capacity）==

  - 直保公司可据此自留不想分出的风险
  - ==再保公司的underwriter通过line guide (line authorization guide)向直保公司提供/ 沟通line flexibility==
    - ==line guide (line authorization guide)写明了直保公司可自留的minimum line和maximum line==

- 如果SSR的underwriting capacity无法满足需求，直保公司可和另一家再保公司合作，安排additional SSR

  - 涉及多个SSR时，在直保公司line之上的第一个SSR称为first surplus，其他treaty按顺序提供additional large line capacity（second surplus treaty, third surplus treaty…）

## 2. Excess of Loss (non-proportional)

- ==excess of loss ri (XOL，non-proportional ri)是只有直保公司的损失超过retention（attachment point）后，再保公司才进行补偿==

  - ==attachment point是再保公司开始赔付的起赔线（start to respond的dollar amount）==

    - ==直保公司自留attachment point之下的赔款==
    - ==如果有co-participation provision，直保公司也会赔偿attachment point之上的一部分赔款==

  - 再保公司excess of loss的obligation取决于loss amount和再保公司提供的coverage layer

  - excess of loss ri（XOL）可在直保公司的retention上，按层（layer）叠加

    - ==layer表示方法为250 in excess of 250 (250 xs 250)==
    - ==如果损失超过所有layer coverage，则多余的损失由primary insurer自行承担==

    | insurance amount | ri layer  | total insurance coverage | 表示          |
    | ---------------- | --------- | ------------------------ | ------------- |
    | 20000            | layer 4   | 25000                    | 20000 xs 5000 |
    | 4000             | layer 3   | 5000                     | 4000 xs 1000  |
    | 500              | layer 2   | 1000                     | 500 xs 500    |
    | 250              | layer 1   | 500                      | 250 xs 250    |
    | 250              | retention | 250                      | retention     |



- ==XOL ri premium取决于loss超过attachment point的likelihood，premium由双方协商确定==

  - ==XOL premium是underlying policy保费（subject premium/ underlying premium）的一定比例（percentage/ rate）==
    - ==subject premium/ underlying premium是直保公司对underlying policy收取的保费，再保公司据此和rate，确定ri premium==
  - ==再保公司一般不对XOL之下的部分支付ceding commission，但为奖励直保公司的favorable loss experience，再保公司提供profit commission，或在计算ri premium时减少rate==

- 直保公司的attachment point通常设定在retained claim的位置

  - ==如果直保公司可能发生的损失数量（loss volume）特别巨大，XOL ri agreement可能会设定low attachment point（称为working cover）==
  - ==working cover可让直保公司在多年内spread loss（profitable year会抵消unprofitable year）==
  - ==working cover适用于inexperienced（无经验）的直保公司（直到其完全了解某个保险产品的loss frequency/ loss severity）==
  - ==再保公司通常要求在working cover中包括occurrence limit（通常为ri limit的2-3倍），以避免catastrophic event造成的损失==

- ==co-participation provision是要求直保公司在attachment point上，自留一定比例的损失==

  - ==co-participation provision的目的是激励直保公司有效管理超过attachment point的损失==

  - co-participation provision表示为layer的一定比例

    > 如co-participation = 5%，表示为 “95% of 20000 xs 5000”（即再保公司承保超过5000之上的20000里的95%）

- ==再保公司要赔偿layer loss，还要赔偿 loss adjustment expense（LAE）==

  - ==处理loss adjustment expense（LAE）的方法包括==

    - ==pro rata in addition: 根据和loss share同样的比例，分摊LAE==
    - 如果使用pro rata in addition，在损失未超attachment point时，直保公司支付LAE
    - ==loss adjustment expense included in the limit: 使用attachment point时，将LAE放入loss中一起考虑==
    - 如果使用loss adjustment expense included in the limit，即使loss amount未超过attachment point，再保公司也要赔偿LAE
      - 谈判ri agreement时，双方通常会在loss中包括LAE

  - loss adjustment expense（LAE）适用于liability insurance，liability insurance通常将LAE放在loss中，从而让他们共用一个attachment point

    > medical malpractice insurance通常包括大量的loss adjustment expense（LAE，如legal fee等）
    >
    > - 不管最后要不要赔付，都有可能支出legal fee

### （1）Per risk XOL

- ==per risk XOL ri（property per risk excess of loss，PPR）适用于每个risk的每个loss，主要用于property insurance==

- ==Per risk XOL中，直保公司负责决定如何确定one risk (one loss exposure)==

  - ==Per risk XOL中，attachment point和ri limit适用于每个risk（即每个risk都要扣除attachment point，并以ri limit为限）==

    | risk number | loss amount | 直保公司retention | 再保公司赔付 |
    | ----------- | ----------- | ----------------- | ------------ |
    | 1           | 500         | 50                | 450          |
    | 2           | 350         | 50                | 300          |
    | 3           | 700         | 50                | 650          |
    | total       | 1550        | 150               | 1400         |

- per risk XOL中通常包括per occurrence limit

  - 如果single occurrence影响多个risk，per occurrence limit限定了再保公司的赔偿额，但也将直保公司暴露于额外风险之中

  - 所以直保公司在per risk excess of loss之外，通常还会购买catastrophe excess of loss

    > 上述表格中，再保公司的赔偿额为1400，如果再保公司的per occurrence limit为1000，则再保公司只赔1000，剩下的400由直保公司承担

### （2）Catastrophe excess of loss（CATXOL）

- ==catastrophe excess of loss（CATXOL）保护保险公司免受single catastrophic loss event导致的accumulated retained loss的影响==

  - 直保公司根据ri recovery之后的net basis购买catastrophe excess of loss（即假设所有的ri可以正常赔付，按照剩余的net basis risk购买）
  - catastrophic event会造成billions dollars loss，包括tornado/ hurricane（较严重）/ earthquake等

- ==CATXOL的attachment point和ri limit都使用loss dollar amount表示，且attachment point和ri limit适用于保单期间的每个catastrophe==

  - attachment point 通常会设定的很高（用于只承保会损害直保公司 policyholder surplus的情况）
  - CATXOL会为超过attachment point的损失，设定co-participation provision

- ==loss occurrence clause（hours clause）定义了catastrophe occurrence scope==

  - ==loss occurrence clause定义了同一catastrophe occurrence的time period (in hours)（即该时间段内的损失适用一个attachment point和ri limit）==

  - ==catastrophe occurrence对灾难的时间定义==

    | ==catastrophe occurrence== | ==time period==      |
    | -------------------------- | -------------------- |
    | hurricane                  | 连续的72小时（3天）  |
    | earthquake                 | 连续的168小时（7天） |

  - 进行CATXOL的claim时，直保公司可自行选择occurrence的开始时间（commence date），以最大化recovery amount

    > 案例：hurricane导致4天的损失，但loss occurrence clause中对hurricane的定义只有3天，此时直保公司可选择哪三天属于hurricane

    - | day   | loss | 从第1天开始算 | 从第2天开始算 |
      | ----- | ---- | ------------- | ------------- |
      | 1     | 1000 | 1000          | -             |
      | 2     | 1000 | 1000          | 1000          |
      | 3     | 2000 | 2000          | 2000          |
      | 4     | 4000 | -             | 4000          |
      | total | 8000 | 4000          | 7000          |

  

- CATXOL通常包括reinstate provision（复效条款，需要加保费）

  - 再保公司对直保公司赔付catastrophe loss，会降低future ri coverage limit，可使用reinstate provision将保额恢复至原保额

- ==CATXOL适用于unlikely but possible的，可导致直保公司unstable operating result或导致policyholder surplus无法absorb的风险==

  - 直保公司对catastrophe excess of loss的需求和需要购买amount取决于其catastrophe loss exposure

- 确定CATXOL的步骤（P2.16案例）

  | step | 解释                                  | 公式                                                   |
  | ---- | ------------------------------------- | ------------------------------------------------------ |
  | 1    | 确定超过attachment point的loss amount | loss amount - retention                                |
  | 2    | 确定co-participation amount           | 超过attachment point的amount * co-participation        |
  | 3    | 确定再保公司负担的loss amount         | 超过attachment point的amount - co-participation amount |
  | 4    | 确定直保公司负担的loss amount         | retention + co-participation amount                    |

  

### （3）Per policy XOL

- ==per policy XOL是将attachment point和ri limit分别适用于直保公司的每张保单，不管每张保单发生过多少次损失（loss number），常用于liability insurance==

### （4）Per occurrence XOL

- ==per occurrence XOL是将attachment point和ri limit用于single event导致的所有policy的损失，常用于liability insurance==
- per occurrence XOL的attachment point < 直保公司的highest liability policy limit

- clash cover可提供多种liability insurance（auto/ general/ professional/ WC）的combination

  - clash cover attachment point > underlying policy的limit

    > 直保公司可承保WC保单和CGL保单，each occurrence limit为1000，为获得higher coverage limit，直保公司可购买多层的clash cover
    >
    > 如果一个accident同时导致WC和CGL责任，则clash cover适用，因为所有的claim都源自single occurrence
    >
    > clash cover会follow已有的retention（即不会重复扣除retention）

  - P2.18 案例

    | loss amount | 直保自留（250） | per occurrence （3000） | 直保自留 | clash cover（3000） | 直保自留 |
    | ----------- | --------------- | ----------------------- | -------- | ------------------- | -------- |
    | 1000        | 250             | 750                     | 0        | 0                   | 0        |
    | 1000        | 0               | 1000                    | 0        | 0                   | 0        |
    | 1000        | 0               | 1000                    | 0        | 0                   | 0        |
    | 1000        | 0               | 250                     | 750      | 0                   | 0        |
    | 1000        | 0               | 0                       | 0        | 1000                | 0        |
    | 1000        | 0               | 0                       | 0        | 1000                | 0        |
    | 1000        | 0               | 0                       | 0        | 1000                | 0        |
    | 1000        | 0               | 0                       | 0        | 0                   | 1000     |



- CATXOL（for property insurance）和clash cover (for liability insurance)通常为pure risk cover，因为其目标是只承保rare event，而非common claim

- ==clash cover适用于loss adjustment expense（LAE）非常高，且underlying per occurrence ri limit包括LAE的liability==

  > 如professional liability insurance（medical malpractice, D&O, accountant professional liability）和有environmental claim expense的保险（asbestos and pollution liability）

- 如果直保公司想获得Extra-contractual damage或excess of policy limit loss protection，则可使用clash cover
  - ==Extra-contractual damage是保险公司未能properly handle claim导致的被保险人的损失==
    - improper behavior属于bad faith，表示保险公司未能fairly deal with insured
    - 因为claim handling bad faith而判给insured 的damage award，不属于underlying policy的coverage，所以再保公司也不会承保此损失（但有的再保协议会特别说明承保此损失）
  
- 如果保险公司有机会在policy limit之内进行settle claim，但保险公司未这么做，被保险人起诉保险公司的，会发生excess of policy limit loss
  - 和Extra-contractual damage不同，excess of policy limit loss属于Extra-contractual obligation，也属于covered loss（因为其属于直保公司错误而超过policy limit的情况）
  - ==excess of policy limit loss（XPL）和其他Extra-contractual obligation type（ECO）的区别在于excess of policy limit loss（XPL loss）可设定在insured policy limit之内==
  - ri agreement会约定是否赔偿excess of policy limit loss

### （5）AXOL（AXOL）

- ==AXOL承保一定时间（通常为一年）内，超过attachment point的aggregated loss，可用于property和liability insurance==

- ==AXOL的attachment point可表示Q为dollar amount或loss ratio==

  - ==使用loss ratio作为attachment point时，称为stop loss ri==

    > 如直保公司自留loss ratio <= 90%的部分，再保公司赔偿90%-120%的部分，120%以上的部分直保公司自留
    >
    > 此情况可表示为30% xs 90% loss ratio

- AXOL不常用，且比其他类型的excess of loss的保单都贵

- AXOL treaty通常会约定attachment point和ri limit，如果原保单unprofitable，直保公司也不会earning profit。

- 大部分的AXOL会包含一个5%-10%的co-participation provision，以激励直保公司有效的处理超过attachment point的claim

- 使用AXOL时，再保公司认为只会在primary insurer has been reimbursed under its other ri agreement之后，才进行赔付

-  AXOL ri可承保catastrophe和 unforeseen non-catastrophic loss accumulation，所以可为直保公司提供broader protection（体现在loss severity和loss frequency两方面）

## 3. treaty ri的function

| RI type        | Ri Type        | 稳定loss experience | 提高 large line capacity | 提供catastrophe protection | 提供surplus relief | 主要目的                                            |
| -------------- | -------------- | ------------------- | ------------------------ | -------------------------- | ------------------ | --------------------------------------------------- |
| Pro Rata       | Quota Share    | N                   | Y                        | N                          | Y                  | 提供surplus relief                                  |
|                | Surplus Share  | N                   | Y                        | N                          | Y                  | 提供large-line capacity + 一些surplus relief        |
| Excess of Loss | Per Risk       | Y                   | Y                        | Y (some extent)            | N                  | 提供large-line capacity + stabilize loss experience |
|                | Catastrophe    | Y (some extent)     | N                        | Y                          | N                  | 防止one event导致的 catastrophic loss               |
|                | Per policy     | Y                   | Y                        | Y (some extent)            | N                  | 提供large-line capacity + stabilize loss experience |
|                | Per occurrence | Y (some extent)     | N                        | Y                          | N                  | 防止one event导致的 catastrophic loss               |
|                | Aggregate      | Y                   | Y (some extent)          | Y                          | N                  | stabilize loss experience                           |



# 二、传统再保险的alternative

- catastrophe risk无法通过传统ri进行suitably addressed
- ri的alternative包括
  - Finite Risk Reinsurance（FRR）
  - 使用capital market进行risk financing
    - 使用insurance-linked security
    - 各种exchange-traded product

## 1. Finite Risk Reinsurance（FRR）

- ==finite risk insurance（FRR）是再保公司只承担limited (finite) liability，再保公司的anticipated investment income表示为underwriting component==
- ==finite risk insurance（financial reinsurance）的目的是转移limited risk给再保公司，以提升直保公司的financial result==
    - ==FRR和传统ri的区别在于FRR只转移limited risk给再保公司==
- FRR可帮助直保公司保护其traditional insurable/ uninsurable loss exposure，处理extremely large/ unusual loss exposure（如oil rig explosion/ earthquake导致的catastrophic loss）

  - traditional insurable loss exposure包括explosion引起的building loss
  - traditional uninsurable loss exposure包括economic variable (product demand或market competition)导致的loss
- ==finite risk ri agreement通常有multi-year term（3-5年），即可在多年内spread over risk/ loss，但总额不得超过agreement entire term的aggregate limit==
- 多年期FRR的优点
    - 直保公司获得long-term protection和predictable ri cost
    - 再保公司获得continual premium flow（持续的保费）
    - 基于上述优点，直保公司和再保公司都愿意在price和term上flexible
- finite risk ri premium通常是ri limit的一定比例

  - premium和ri limit的关系，降低了underwriting loss（小于traditional ri）
- ==FRR适用于high severity loss==

  - ==如果loss experience较好，或prepaid premium investment产生income，再保公司会和直保公司share profit==

  - profit-sharing income可补偿直保公司付出的，higher-than-usual premium的FRR premium

  - ==如果loss > premium，再保公司也不会收取additional premium==

## 2. Traditional and Nontraditional ri的Capital Market Alternative 

- 直保公司可使用traded security instrument来进行insurance risk financing

  - capital market是交易long-term security的financial market

  - 有些capital market instrument允许直保公司exchange asset for cash，有的工具基于insurance derivative或contingent capital arrangement

    | capital market instrument          | 定义                                                         | 案例                                              |
    | ---------------------------------- | ------------------------------------------------------------ | ------------------------------------------------- |
    | ==securitization of risk==         | ==使用security/ financial instrument帮助保险公司进行catastrophic loss financing== | ==stocks/ bonds/ commodities/ financial futures== |
    | ==Special purpose vehicle (SPV)==  | ==为特定目的建立的一种facility，目的包括<br>- 购买income-producing asset<br>- holding title<br>- 使用asset进行collateralize security，之后卖给investor== | -                                                 |
    | ==Insurance derivative==           | ==一种financial contract，其value取决于特定时间内insurable loss level== | -                                                 |
    | ==Contingent capital arrangement== | ==损失发生前达成的agreement，如果企业的loss超过certain threshold后，可按照prearranged term，selling stock/ issuing debt，从而raise cash== | -                                                 |


- 常用的Capital Market product/ method包括catastrophe bond，catastrophe risk exchange，contingent surplus note，Industry Loss Warranty（ILW），Catastrophe option，Line of Credit，sidecar

### （1）catastrophe bond

- ==catastrophe bond是专门设计的insurance-linked security，将insurable catastrophe risk转移给investor==
  
  - ==insurance-linked security是一种financial instrument，其value主要由insurance和或ri loss event确定==
  
- ==catastrophe bond的issue bond condition是，如果issuer遭受的cat loss大于特定金额，则其pay interest obligation/ repay principle的obligation会defer或forgive==

  | ==situation==          | ==结果==                                                     |
  | ---------------------- | ------------------------------------------------------------ |
  | cat loss不超过特定金额 | investor获得high interest rate并能收回principal              |
  | cat loss超过特定金额   | bondholder会forgone（放弃）interest和或principal，以支付损失 |

- catastrophe bond通常由保险公司，大型再保公司或大型公司的SPV发行，以应对任何类型的 catastrophic insurable risk（如hurricane，earthquake，adverse weather，environmental risk等）

### （2）catastrophe risk exchange

- ==catastrophe risk exchange是直保公司和其他保险公司exchange部分insurance risk==
  - risk exchange可基于internet-based forum (adverted/ negotiated/ completed)等
- 可根据geographic area/ property type/ cause of loss进行exchange
  - ==如果风险属于geographic concentration，直保公司可使用catastrophe risk exchange来减少single loss occurrence导致的损失（即直保公司可diversify insured property，减少single cause of loss导致的susceptible to heavy loss）==

### （3）contingent surplus note

- ==surplus note可通过issue note at pre-agreed interest rate，帮助直保公司immediately obtain fund==
- ==surplus note属于unsecured debt instrument，只有保险公司可以issue==
- ==surplus note的特点==
  - ==conventional equity和debt security==
  - ==surplus note属于policyholder surplus，而不是保险公司的liability==
- ==surplus note可在不增加liability的情况下，增加直保公司的的asset==

### （4）Industry Loss Warranty（ILW）

- ==ILW属于insurance-linked security，如果catastrophe event导致industry-wide loss（全行业损失）超过predetermined threshold，ILW赔偿直保公司的损失==
- ==ILW的trigger为industry whole loss（全行业的所有损失），而非某一个直保公司的损失==

### （5）Catastrophe option

- ==如果catastrophe loss index到达一定level（strike price），直保公司可从investor获得cash payment right==
  - ==strike price是call option (warranty)/ put option涉及的stock/ commodity可在特定时间内purchased（called）/ sold（put）的价格==
- The catastrophe loss index（如ISO提供的Property Claim Service（ISO PCS））会根据geographic region/ cause of loss/ occurrence time等追踪catastrophe loss

### （6）Line of Credit

- ==直保公司发生loss时，bank或其他financial institution同意给直保公司提供loan==
- credit（interest rate/ principal repayment commitment）是在loss之前已经决定的
- 为获得credit commitment，直保公司要支付commitment fee
- ==line of credit不是risk transfer，只是让直保公司access to capital==

### （7）sidecar

- ==sidecar属于limited-existence SPV，通常是independent company==
- ==直保公司承保property catastrophe business或通过QSR承保short-tail line的业务时，sidecar可为直保公司提供additional capacity==
- SPV investor会认为risk proportion会赚取对等的profit
- ==sidecar中，如果book of business profitable，直保公司会收取ceding commission和profit commission==

# 三、ri program的设计

- ri program是直保公司购买的，用于满足其再保需求的ri agreement combination

- well-planned/ well-executed ri program可帮助满足直保公司的特定需求
  - 可帮助stabilize loss experience
  - 提供large-line-capacity
  - 提供catastrophe protection，有效的ri program会影响直保公司的survival
  - 提供surplus relief
  
- 设计ri program时，要分析直保公司的need/ retention/ ri limit
  
  - reinsurer/ intermediary/ consultant可提供帮助
  
- ==影响ri need/ ri retention/ ri limit的因素==

  | 影响ri need的因素                  | 影响ri retention的因素           | 影响ri limit的因素             |
  | ---------------------------------- | -------------------------------- | ------------------------------ |
  | ==Growth plans==                   | 直保公司可以自留的maximum amount | 直保公司的maximum policy limit |
  | 直保公司出售的insurance type       | 直保公司愿意自留的Maximum amount | Extra-contractual obligation   |
  | Geographic spread of loss exposure | 再保公司要求的 minimum retention | loss adjustment expense（LAE） |
  | Insurer size                       | Co-participation provision       | Clash cover                    |
  | Insurer structure                  | -                                | catastrophe exposure           |
  | Insurer financial strength         | -                                | -                              |
  | Senior management's risk tolerance | -                                | -                              |

  

## 1. 影响ri need的因素

### （1）Growth plans

- ==对ri 的需求方面，rapid premium growth的公司 > remain premium stable/ decrease的公司==

- ==需要additional ri的原因==

  | 需要additional ri的原因  | 解释                                                         |
  | ------------------------ | ------------------------------------------------------------ |
  | ==rapid growth==         | ==rapid growth会导致直保公司policyholder surplus drain（枯竭）==<br/><br>==pro rata ri可补充直保公司的policyholder surplus（因为再保公司可支付ceding commission）== |
  | ==loss ratio==           | ==新业务的loss ratio会很不稳定==，如果直保公司出售新产品或没有operation experience的产品，loss ratio instability会非常严重<br><br>==对于rapid growing company，新产品会占total premium很大的比例，所以new policy variability的loss ratio会大幅影响直保公司的overall loss ratio==<br><br>再保公司有时不承保此类业务 |
  | ==higher/ new coverage== | ==为在new market竞争，直保公司必须提供higher limit或new coverage== |

- ri type的选择

  | ri type           | 可满足直保公司的需求                        |
  | ----------------- | ------------------------------------------- |
  | pro rata ri       | surplus relief                              |
  | excess of loss ri | loss ratio stability<br>large line capacity |

- ri agreement会让直保公司损失long-term profit（因为会将potential profitable loss exposure转出），但牺牲long-term的目的是获得short-term growth，从而获得greater future profit

### （2）直保公司出售的insurance type

- 直保公司出售的insurance type是ri need的决定因素

  - 直保公司的产品会导致loss stability剧烈波动，从而影响直保公司project loss experience’s ability
  - ri program必须根据直保公司的 loss characteristic进行tailored

- ==对再保的需求方面，personal line < commercial line（personal insurance < commercial insurance）==

  |                     | ==personal line==                                   | ==commercial line==   |
  | ------------------- | --------------------------------------------------- | --------------------- |
  | ==coverage limit==  | ==low==                                             | ==high==              |
  | ==risk nature==     | ==主要是homogeneous risk<br><br>severe hazard更少== | ==severe hazard更多== |
  | ==loss experience== | ==stable<br><br>predictable==                       | ==unstable==          |

- 有些保险产品需要更多的policyholder surplus（capital）

  - state insurance regulator使用risk-based capital system衡量保险公司的minimum capital requirement

  - risk-based capital system会给underwriting risk赋予greater weight

    - ==underwriting risk衡量insurance type的loss volatility==

      > medical malpractice insurance会发生severe loss，难以通过past loss experience预测损失。所以直保公司需要更多的policyholder surplus以absorb unexpected loss fluctuation

  - ri可提供surplus relief，从而帮助直保公司减少对policyholder surplus的需求

- ==insurance type的数量会影响insurance need==

  - ==出售多种保险产品属于diversified，其loss ratio更加stable==

### （3）Geographic spread of loss exposure

- ==wide geographic spread可稳定保险公司的loss ratio，并减少ri need（特别是property insruance方面），原因如下==
  - ==各地的catastrophe loss exposure nature不同，catastrophe不会同时袭击所有geographic area==
  - ==其他地区的good loss experience会抵消一个地区的bad loss experience==
- 可在worldwide和US之内进行geographic diversification
- 只在某一地区出售property insurance的直保公司更易受到catastrophe loss fluctuation的影响，所以需要ri
- geographic diversification可帮助stabilize loss ratio
  - geographic diversification也可在insurance regulation/ law/ tort liability/ law enforcement practice方面分散风险

### （4）Insurer size

- ==小直保比大直保需要更多的再保，以稳定loss ratio==
  - ==根据law of large number，随着loss exposure 数量增加，actual loss会趋于稳定，所以大公司的loss ratio更stable==

### （5）Insurer legal structure

- 直保公司的legal structure会影响ri need

  > stock insurer更容易接入capital market，mutual insurer和reciprocal insurer更难接入
  >
  > 所以stock insurer可接受less stability in loss ratio，其能从capital market获得policyholder surplus。但这样做也有风险，因为capital provider（investor）不喜欢有heavy loss的保险公司


### （6）Insurer financial strength

- ==financial strong —> 需要的ri小，原因如下==

  - ==financial strong的直保公司不需要用surplus relief增强premium capacity==
  - ==financial strong的直保公司不需要ri 来稳定loss ratio/ loss experience==

- strong surplus position让直保公司absorb more adverse loss ratio variation，进而只需支付lower ri cost

- 衡量保险公司的financial strength涉及评估invested asset的stability和liquidity

  - 若直保公司依赖policyholder surplus来absorb abnormal loss，则surplus必须投资到readily marketable且market price不会wide fluctuation的asset，否则会导致没有sufficient financial resource to pay loss

- ==持有的金融产品对ri的需求==

  | ==直保公司持有的资产==          | ==ri need== | ==原因==                                                     |
  | ------------------------------- | ----------- | ------------------------------------------------------------ |
  | short-term bond                 | 小          | -                                                            |
  | ==stock/ investment portfolio== | ==大==      | ==common stock可以marketable，但common stock受wide market price fluctuation的影响很大（有可能pay loss的时候，stock的价格不好）== |
  | wholly-owned subsidiary         | 大          | subsidiary stock不是marketable                               |

  - long-term bond受interest rate risk影响，可能发生market loss

### （7）Senior management's risk tolerance

- insurance type和购买多少insurance取决于statistical data和financial model，但也取决于高管层的risk tolerance（反应其assume risk的willingness），高管层必须comfortable with insurance risk（retention/ ri program change）
- 高管层必须确信stakeholder对直保公司的ri plan足够comfortable
  - ==ri program应反映直保公司的BoD/ stockholder/ policyholder的risk tolerance==
  - 高管层必须sensitive to stakeholder’s view
- 需要考虑proposed ri program change对supervisor和underwriter的影响（practical effect）

## 2. 影响retention的因素

- retention主要根据financial need，sold insurance type，双方的negotiation，cost确定
  - ==retention额度越低，treaty ri cost越高（相当于扩大了再保责任）==

### （1）直保公司可以自留的maximum amount

- ==直保公司可以自留的Maximum Amount取决于regulatory requirement和直保公司的financial strength==

  - state insurance regulation的regulatory requirement

    - ==state insurance regulation规定premium capacity只能是policyholder surplus的3倍（300%）==
    - ==对于single loss exposure net amount，要求只能要求自留policyholder surplus的10%==
  - 很多直保公司的自留额小于监管要求
  
- financial strength
  
  - 直保公司不能自留过多的loss exposure，以防在worst-case时发生insolvency
  
  - 直保公司需判断可威胁solvency的loss size
  
  - 直保公司需要考虑retention之内的loss，也要考虑其他相关ri agreement的retention
  
      > 在确定per risk excess of loss treaty的retention时，不知要考虑本保单的retention，还要考虑catastrophe excess of loss treaty的retention

### （2）直保公司愿意自留的Maximum amount

- 直保公司通常不会接收maximum retention，原因在于无法确定会发生多少loss，也可能是因为manager conservatism
- 对于publicly held stock insurance company, market pressure会导致retention小于legally/ financially bear，因为investor更喜欢growing and stable earning
  - 如果选择large retention，会导致earning每年都有变化，从而alienate investor

### （3）再保公司要求的 minimum retention

- ==有时，再保公司会要求 minimum retention（通常发生在CATXOL中）==
- ==minimum retention用于鼓励直保公司执行好的risk control/ underwriting/ loss adjustment==
- 对于profitable pro rata treaty，为获取更多的profitable business，再保公司会寻求lower retention

### （4）Co-participation provision

- ==co-participation是要求直保公司在retention之上继续分摊部分损失，用以鼓励直保公司做好risk control/ underwriting/ loss adjustment==

## 3. 影响ri limit的因素

### （1）直保公司的maximum policy limit

- 可将ri limit设定为原保单的maximum policy limit，但这样做不够economical

  - 可行的方法是根据大多数保单的limit设定ri limit，对于超过此limit之上的原保单，使用facultative ri

    > 直保公司大部分保单的limit为500，少部分保单的limit为1000。此时可使用500作为ri limit，同时对limit为1000的保单购买facultative ri

- stop loss treaty的limit通常设定为loss ratio，应设定为直保公司有可能达到的highest loss ratio

  - 但cost原因会导致直保公司设定一个low limit

### （2）Extra-contractual obligation

- ==如果ri treaty可承保Extra-contractual damage和excess of policy limit loss，则ri treaty limit > 原保险的highest policy limit==
- ==Extra-contractual obligation damage应是highest coverage limit的几倍==

### （3）loss adjustment expense（LAE）

- LAE在per risk XOL和per occurrence XOL中非常重要

- ==LAE通常会加到loss amount中（从而不会pro rate），所以在选择retention和ri limit时，应当考虑LAE==

  > medical malpractice insurance的LAE可能会耗尽insurance coverage，从而无法赔偿loss本身，所以直保公司要仔细评估ri limit，并对LAE提供additional layer

### （4）Clash cover

- ==clash cover适用于liability风险的per occurrence XOL==
  - ==one occurrence导致多个insured/ different kind of insurance受影响时（如one occurrence导致多张保单发生loss时），clash cover可保护直保公司==
- ==设定clash cover limit（clash coverage limit/ clash limit）时，需考虑==
  - ==直保公司的highest limit==
  - ==excess of policy limit（XPL）loss的potential==
  - ==single occurrence导致多个policy发生loss的可能性（likelihood）==

### （5）catastrophe exposure

- 选择catastrophe treaty limit比选per risk excess of loss treaty limit都复杂，因为catastrophe loss涉及single occurrence的loss accumulation

  - loss accumulation取决于同一geographic area中，one single catastrophic occurrence可导致的所有policy loss amount

    > hurricane中，affected area可覆盖hundred of square miles

- 如果保险公司有之前的loss data，其可预测catastrophe（hurricane/ earthquake/ flood）影响区域中的future loss

  - flood/ hurricane/ tornado/ earthquake/ other natural catastrophe的extensive data可从government agency（如NOAA）获得

- catastrophe model（cat model）是估计future potential catastrophic event loss的computer program，可用于帮助确定treaty limit

# 四、案例