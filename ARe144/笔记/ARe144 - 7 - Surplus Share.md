# 一、surplus share treaty（SSR）概述

- ==surplus share reinsurance（SSR）属于pro rata ri，直保公司通常使用SSR承保large/ complex的property loss exposure==
- SSR中，直保公司决定哪些loss exposure进入SSR，并决定每个风险的retain percentage和ceded percentage
  - 直保公司通过分出部分风险，可将其liability limit限定为和similar loss exposure一样的coverage limit
- cession是将风险从直保公司转移给再保公司

## 1. SSR operation

- ==SSR中，直保公司和再保公司按share percentage分摊每张保单的premium和loss==

  - ==和QSR不同，SSR中，每个loss exposure的share percentage均不相同==

  - ==share percentage取决于分出的coverage limit和直保公司retention的比例==

    - 直保公司retention percentage = retention / policy limit
    - 再保公司承担的percentage = ceded loss / policy limit

  - 和QSR相同，SSR对每个损失都会从first dollar开始赔（ground-up basis），而不管loss amount

    > 如直保公司的line为100，loss = 1时，再保公司也要按照SSR的比例赔付 loss的部分损失

- SSR的优点

  |                      | QSR的缺点                                                    | SSR的优点                                                    |
  | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | cession pattern      | ==所有loss exposure都要分出（不管size，即使loss exposure可以safely retain，直保公司也要分出每个业务）== | ==直保公司可只分出超过line的业务（即风险必须属于SSR的loss exposure category，且超过line时，才分出业务）== |
  | retention percentage | ==QSR中，直保公司的retention属于fixed percentage<br><br>retention dollar amount会随coverage limit增加而增加== | ==SSR中，直保公司的line是fixed dollar amount<br><br>retention dollar amount不会随coverage limit增加==<br><br>==SSR可对每个exposure设定不同的retention== |

  

- SSR中的line和XOL中的attachment point的区别

  | SSR line                                        | XOL attachment point                                   |
  | ----------------------------------------------- | ------------------------------------------------------ |
  | ==SSR中的line确定了SSR是否适用于loss exposure== | ==attachment point确定再保公司是否要要对loss进行赔付== |

  

- ==SSR的line guide允许直保公司变动line dollar amount（具体取决于每个loss exposure的loss severity potential）==

  > 如line guide明确，没有automatic sprinkler system的line为100，有automatic sprinkler system的line为300（因为有sprinkler的building通常不会发生severe loss）

### （1）SSR的line guide

- 直保公司underwriter可根据guide，将applicant分为high quality/ average quality/ low quality，并据此确定自留的line
- 对于unacceptable loss exposure，直保公司可以拒保或使用facultative ri（不让风险进入SSR，防止影响SSR的profitability和future pricing）

### （2）SSR program

- SSR通常按layer承保

  - ==直保公司retention之上的first layer reinsurance是first surplus treaty==
    - first surplus treaty也可以是QSR或facultative XOL
  - ==second/ third等further surplus treaty可提供更多coverage limit并为直保公司提供additional large line capacity==
  - 只有在individual loss exposure大于preceding layer时，才会提供higher layer的ri coverage

- retention line属于line的标准，之后的ri按照line 表示

  - ==SSR所在的layer越高，其获得的ceding commission percentage越低==

- 为满足additional coverage limit的需求，直保公司可购买facultative ri

  - ==如果loss exposure的volume过大，且需要的coverage limit过高，直保公司通常不愿意使用facultative ri（太贵，价格过高）==

  > background: 
  >
  > - line = 50，ri提供的coverage为9 line（其中first layer = 3 line，second layer = 3 line，third line = 3 line），gross premium = 6
  > - 每个layer的ceding commission = 40%
  > - loss exposure coverage limit = 450，loss = 10
  >
  > solution
  >
  > - 直保公司的line/ retention = 50，再保公司提供 9 line coverage（即再保公司提供450的coverage），total capacity = line + 9 line coverage = 50 + 450 = 500
  > - loss share
  >
  > |                | loss exposure share percentage | loss | loss share |
  > | -------------- | ------------------------------ | ---- | ---------- |
  > | 直保公司       | 50 / 450 = 11%                 | 10   | 1.1        |
  > | first surplus  | 150 / 450 = 33%                | 10   | 3.3        |
  > | second surplus | 150 / 450 = 33%                | 10   | 3.3        |
  > | third surplus  | 100 / 450 = 22%                | 10   | 2.2        |
  > | total          | -                              | -    | 10         |
  >
  > - premium allocation
  >
  >   |                | gross premium | loss exposure share percentage | gross premium share | ceding commission          | net premium |
  >   | -------------- | ------------- | ------------------------------ | ------------------- | -------------------------- | ----------- |
  >   | 直保公司       | 6             | 11%                            | 0.66                | 2.133                      | 2.8         |
  >   | first surplus  | 6             | 33%                            | 2                   | 2 * 40% - 2 = 0.8          | 1.2         |
  >   | second surplus | 6             | 33%                            | 2                   | 2 * 40% - 2 = 0.8          | 1.2         |
  >   | third surplus  | 6             | 22%                            | 1.33                | 1.33 * 40% - 1.33 = -0.533 | 0.8         |
  >   | total          | -             | -                              | 6                   | 0                          | 6           |
  >
  >   

## 2. SSR的function

- ==SSR的function包括==
  - ==增加large line capacity==
  - ==稳定loss experience==
  - ==提供surplus relief==

### （1）增加large line capacity

- ==SSR的设计初衷是为直保公司承保large loss exposure时，提供flexibility（前提是loss exposure需要符合predetermined parameter（预先确定的条件））==

- ==SSR会和直保公司的line guide放在一起，所以其可根据loss exposure的attribute，调整直保公司的underwriting capacity（即为直保公司提供automatic capacity）==
  
  - ==当直保公司需要additional large line capacity时，SSR可为直保公司提供automatic capacity==
  - 直保公司也可通过facultative ri获得additional large line capacity，但facultative ri的价格较贵
  
- 直保公司underwriter会参考line guide，并依据judgment设定loss exposure的line，再保公司会面临直保公司的adverse selection（如直保公司把高风险业务分给再保公司）

- 为减少adverse selection（但同时能给直保公司line flexibility），再保公司可在SSR中设定minimum line和maximum cession

  - minimum line是如果直保公司的retention < minimum line，则SSR不会承接此业务

  - maximum cession是一个dollar limit（即最大的分出风险。实际中，SSR的ceded amount会基于直保公司line的多少倍）

    > 如SSR约定maximum cession是直保公司retention（line）的5倍，loss exposure limit = 1200
    >
    > - line = 200时，maximum cession = 1000。此时满足loss exposure limit
    > - line = 100时（直保公司认为风险过大，只愿意自留少量风险），maximum cession = 500。此时距离1200还有600的coverage amount差距，直保公司必须自留additional liability或购买facultative ri

- 再保公司会在SSR中设定sliding scale commission provision，以激励直保公司underwrite effectively和给SSR分出quality loss exposure

### （2）稳定loss experience

- ==SSR通过限定直保公司对每个loss exposure的participation来稳定loss experience==

  - ==SSR可在一段时期内有效稳定loss experience，但无法为catastrophic event导致的loss accumulation提供sufficient protection==
  - ==直保公司通常会使用additional catastrophe XOL ri来保护其catastrophe loss exposure==

- SSR可帮助直保公司为每个loss exposure category开发size homogeneity

  - 直保公司愿意对loss exposure进行size homogeneity，以让loss forecasting更准确

    > 相较于承保same coverage limit，承保vary coverage limit导致的loss ratio fluctuate会更大

- 直保公司的line guide使用loss exposure attribute（主要基于potential loss severity）对loss exposure进行分类，从而影响直保公司对每类loss exposure的line

### （3）提供surplus relief

- ==SSR提供surplus relief的方式和SSR一样==

  | 提供surplus relief的方式          | 效果                          |
  | --------------------------------- | ----------------------------- |
  | ==直保公司分出大量premium==       | ==减少gross written premium== |
  | ==直保公司获得ceding commission== | ==增加policyholder surplus==  |
  

  
- ==从surplus relief的效果来看，SSR < QSR（因为SSR分出的保费更少，获得的ceding commission也更少）==

## 3. ri program中的SSR

- ==SSR适用于承保large/ complex property loss exposure，且直保公司需要large line capacity和surplus relief的情况==

  - 新的直保公司（或出售new insurance product或进入new territory的直保公司）会使用QSR（直到sold policy增加到可稳定loss experience时）
  - 当直保公司具有sufficient and credible loss experience时，直保公司会用SSR替换QSR（以便retain more premium）

- ==SSR可单独使用，也可和QSR或XOL一起使用（conjunction）==

  - SSR通过提供layer，为直保公司提供large line capacity

- 和QSR一样，SSR无法为直保公司提供catastrophe loss protection

  - 虽然直保公司对每个loss的liability有限，SSR无法承保loss accumulation导致的损失
  - 直保公司最好使用catastrophe XOL treaty以获得catastrophe loss protection

- ==直保公司有时使用per risk XOL (PPR) 来增加其line，并使用SSR获得更高的large line capacity（underlying excess）==

  - ==underlying excess是XOL ri的一种，直保公司维持现有retention，之后增加XOL ri。之后直保公司以 (retention + XOL)作为line，再使用SSR，据此让直保公司在low retention的情况下，承保large limit的风险==

    > background
    >
    > - 直保公司retention（line）= 50
    > - SSR为9 line SSR
    > - loss exposure coverage limit = 1000
    >
    > 不使用underlying excess时
    >
    > - line = 50，9 line SSR = 450，总的limit = 50 + 450 = 500
    >
    > 使用underlying excess时
    >
    > - retention = 50，直保公司购买一个50 xs 50 per risk XOL ri，此时line变为100
    > - 之后再使用9 line SSR = 900，总的limit = (50 + 50) + 900 = 1000，满足要求

  - SSR通常会约定其是否允许直保公司按underlying excess的方式进行再保

# 二、SSR中的common clause

- 有些common clause可经过修订，以为SSR提供additional detail和clarification

## 1. Reinsuring clause

- reinsuring clause可以是一个all-encompassing clause，也可分为多个separate clause（如cover clause，business reinsured clause）
- 不管是all-encompassing clause还是separate clause，SSR的reinsuring clause均包括Cession Nature/ statement of attachment/ description of policy covered

### （1）cession nature

- ==和QSR一样，SSR对直保公司和再保公司都有约束力（obligatory for both party）==
  - ==cession nature说明根据约定，保公司赔偿直保公司的损失（indemnification以Retention and limit clause中约定limit为限）==
  - 写明cession nature的原因是cession会基于直保公司的net retention

### （2）statement of attachment（attachment of basis/ basis attachment）

- ==对于new SSR，直保公司通常使用risk attaching basis（即SSR只适用于effective date之后issued/ renewed policy），而非使用loss occurring basis==
- ==从underwriting perspective角度看，risk attaching basis更易于administer==
  - 如果使用loss occurring basis of attachment，直保公司必须审核每个in-force policy的correct retention并记录ceded percentage。必须review的原因是in-force portfolio可能不适合new SSR的minimum retention/ maximum cession/ line number方面的要求
  - new SSR用于in-force portfolio时，通常会发生administrative problem，所以很多SSR会使用risk attaching basis（即SSR只适用于effective date之后issued/ renewed policy）
- 如果直保公司是和同一再保公司签订SSR，则更适合采用loss occurring basis（因为expiring treaty仍会承保in-force policy）

### （3）description of policy covered

- ==reinsuring clause/ business reinsured clause会写明SSR适用于哪些policy==
- ==SSR常用于property insurance policy==
  - SSR的表述通常为fire and allied line/ homeowners business/ all policies for property business
  - 有时SSR的表述会更具体，如property business written in the Company's Farm Department/ all property business written in Illinois, Ohio, and Indiana

## 2. Liability of the reinsurer clause

- ==Liability of the reinsurer clause说明了再保公司何时按什么basis承担责任（cession basis，说明再保公司的liability intent）==

- Liability of the reinsurer clause可以是separate clause，也可放在reinsuring clause中

- QSR和SSR承担liability的区别

  |      | 流程                                                         | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | QSR  | 直保公司接受coverage时，再保公司自动接受一定比例的liability  | -                                                            |
  | SSR  | ==直保公司underwriter会参考line guide，set the line，之后分出liability== | 如果loss发生在直保公司设定line之前，则直保公司必须使用normal standard and practice 来设定line |

## 3. Definitions clause

- definition clause可包含在整个ri treaty中，也可包含在specific clause中

- ==SSR中最重要的definition为surplus liability/ risk/ net retention==

  | SSR中最重要的definition | 定义                                                         | mark                                                         |
  | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ==surplus liability==   | ==surplus liability是分给再保公司的liability amount<br><br>SSR通常会定义surplus liability== | -                                                            |
  | ==risk==                | ==risk是包括<br>all insured value under one roof<br>all insured value within four walls<br>all insured value at one location== | 直保公司负责确定one risk和four walls的定义<br><br>再保公司可同意使用直保公司自己的inspection report或其他information来定义four walls |
  | ==net retention==       | ==net retention是确定了直保公司可对retention使用哪些underlying reinsurance== | -                                                            |

## 4. Exclusions clause

- ==SSR没有standard exclusion，可以有各种各样的exclusion（extensive variety）==
  - exclusion的范围取决于双方的negotiation，范围可能很广，也可能非常brief（如只写明不承保nuclear incident/ pollution/ war risk/ terrorism/ insolvency fund）
  - 由于SSR通常用于property insurance，exclusion 可能很多（以宠物爱specific cause of loss, insurance type, property type）
  - exclusion可适用于all time（或不适用于某些listed operation/ cause of loss）

## 5. Reports and remittances clause

- SSR的Reports and remittances clause和QSR类似，区别在于SSR的record-keeping requirement
  - ==SSR的record-keeping requirement要求，直保公司要记录每个loss exposure的net retention和cession amount，并通过bordereau向再保公司提供information，所以相较于QSR，SSR的administration更复杂==

# 三、SSR的专门条款

- 有些条款是专门用于SSR的

## 1. Surplus liability clause

- ==surplus liability clause是有多个layer时，定义了直保公司向再保公司分出liability的threshold==

  | ==surplus liability clause确立的内容== | 适用范围                 |
  | -------------------------------------- | ------------------------ |
  | ==cession priority==                   | ==如果SSR有多个layer时== |
  | ==minimum net retention==              | -                        |
  | ==underlying ri agreement==            | -                        |

- 并非所有SSR都有surplus liability clause，没有surplus liability clause时，retention and limit clause会确定cession limit

### （1）first or second surplus的定义

- 按layer组织SSR时，直保公司会使用会用尽first SSR，之后再使用second SSR
  - first SSR中，surplus liability clause会说明surplus liability是超过直保公司net retention之上的部分
  - second SSR中，surplus liability是超过直保公司net retention和first surplus treaty之上的部分

### （2）underlying ri agreement disclosure

- ==直保公司可在net retention中使用其他ri agreement（如QSR，其他SSR，XOL，combination of treaty）==
- ==直保公司对net retention使用ri的原因==
  - ==增加net retention level，使其高于直保公司的own financial resource==
  - ==增加SSR的large line capacity==
- ==如果直保公司对其net retention使用ri，直保公司必须告知再保公司所有的underlying reinsurance agreement==

## 2. Net retention clause

- ==net retention clause是说明直保公司是否可对其net retention使用underlying reinsurance（underlying ri）==
  - net retention clause定义了直保公司的net retention
  - separate net retention clause或definition clause/ reinsuring clause/ retention and limit clause，均可定义net retention

## 3. Retention and limits clause

- 如果SSR不包括surplus liability clause，则retention and limit clause可用于同样的目的

- ==retention and limit clause是==

  - ==限定了直保公司可向再保公司transfer的liability amount==

  - ==确立了直保公司的minimum net retention==

    > 如说明net retention为100，再保公司承保5 line，one loss exposure的maximum cession为1000

- ==SSR通常将maximum cession表示为line的倍数并以一个dollar amount为限（cap），也可根据probable maximum loss basis（MPL，insured可能发生的最大损失）说明dollar limit==

- SSR可包含per occurrence limit，以限制catastrophic loss amount（通过限定catastrophe-related loss accumulation，保护SSR的profitability）

  - per occurrence limit会写在retention and limit clause中
  - per occurrence limit的定义会写在definition clause中

## 4. Method of cession clause

- ==SSR适用于为complex property loss exposure提供large line capacity==

- ==method of cession clause的目的==

  - ==解决涉及multiple location/ coverage part/ cause of loss的，涉及sublimit和按blanket basis承保loss exposure时的ceding method==
    - SSR解决了property loss exposure的typical complexity，以便于所有当事方都同意ceded
  - ==减少将风险分给再保公司时，直保公司的adverse selection==

- ==method of cession clause说明直保公司可为coverage sublimit调整ceded percentage（但不得detriment再保公司）==

  > ==如commercial property policy（CPP） limit = 1000，其中earthquake sublimit = 100==
  >
  > - ==如果直保公司对CPP自留200，则直保公司对earthquake sublimit自留20==
  > - ==根据method of cession clause，直保公司不得减少对earthquake sublimit的retention（即直保公司不能只减少某个benefit的自留额，此时会发生adverse selection）==

- 涉及multiple-location的loss exposure，不管insured是在一张保单还是在多张保单投保，再保公司会对所有地点的风险按比例承担风险（assume liability proportionately for all locations）

  - 如果procedure导致某个location的net retention小于SSR要求的minimum net retention，则针对此地点，双方会ignore SSR中要求的minimum net retention requirement，但直保公司必须遵守一个location的minimum net retention requirement

# 四、SSR pricing

- ==SSR - pricing取决于再保公司愿意支付的ceding commission（和QSR一样）==

  | 影响ceding commission的factor                                | QSR - retention | SSR - retention |
  | ------------------------------------------------------------ | --------------- | --------------- |
  | 直保公司的retention                                          | Y               | N               |
  | ri treaty limit                                              | Y               | Y               |
  | 直保公司的policy acquisition expense                         | Y               | N               |
  | 直保公司的 expected loss ratio/ underwriting ability/ rate adequacy | Y               | N               |
  | ri marketplace competition                                   | Y               | Y               |
  | treaty的 perceived profitability                             | N               | Y               |
  | 直保公司的line                                               | N               | Y               |

- ==SSR - ceding commission取决于==
  
  - ==treaty的 perceived profitability==
  - ==ri treaty's limit==
  - ==直保公司的line==
  - ==ri marketplace competition==
  
- ==SSR中，直保公司对每个loss exposure的retention均不一样==
  
  - retention取决于每个loss exposure的line 和coverage limit
  - 确定SSR价格时，需对treaty适用的policy进行thoroughly analysis，可通过limit profile分析thoroughly analysis
  
- 直保公司可使用limit profile评估alternative line的financial consequence，使用line guide确定特定policy category的maximum insurance amount

## 1. Limits profile

- ==limit profile是按coverage limit对policy进行分类的table==
- 可通过limit profile减少capacity ratio，使其进入合理范围（capacity ratio < 3）
- ==limit profile可帮助确定，various level retention（各retention level）的SSR对直保公司的financial effect==

ceded percentage = (midpoint - retention) / midpoint

ceded dollar amount = ceded percentage * premium account

capacity ratio = premium amount / policyholder surplus

​						= (premium amount - ceded dollar amount) / policyholder surplus

## 2. Line Guide

- ==直保公司使用line guide（underwriting tool），来确定各policy category的maximum insurance amount==
  - ==line guide可用于property insurance（主要，因为property比liability更易quantify）和liability insurance==
- ==property line guide中的property loss exposure attribute（Risk-specific features）包括==
  - ==construction type==
  - ==occupancy classification==
  - ==public protection classification==
- ==line guide会说明每种loss exposure class的suggest net retention==，直保公司的ri program也会基于line guide information

### （1）Commercial Property Line Guide

- 有些直保公司会在line guide中加入其它element（如structure中的floor number，fire wall use）
- line guide会写明building的construction/ occupancy/ public protection classification等

#### 1）construction

- construction对building能抵抗fire damage的extent以及抵抗其它loss cause的damage有直接影响

  | ==construction classification基于==                          |      | building construction classification包括  |
  | ------------------------------------------------------------ | ---- | ----------------------------------------- |
  | ==exterior wall（外墙）load-bearing portion的material==      |      | frame（最易受fire damage影响）            |
  | ==building roof/ floor的material（特别是support roof/ floor的材料）== |      | masonry                                   |
  | ==building construction中使用的material的fire-resistive rating== |      | noncombustible                            |
  |                                                              |      | fire-resistive（最不易受fire damage影响） |

#### 2）occupancy

- occupancy是insured operation/ use的nature/ character

- occupancy modifier表示每种operation type的hazard inherent

- 可从ISO occupancy rating system中获得occupancy modifier（说明了特定occupancy类别的hazard degree）

  - occupancy rating system中，使用occupancy code来表示basic occupancy（如office/ habitational property/ sawmill等）
  - basic occupancy charge是反映occupancy hazard 的rating system factor，以base rate的percentage表示（从10%到1000%)

- 可根据content factor的combustibility，susceptibility，其他additional occupancy hazard，imposed surcharge修改basic occupancy charge

  - combustibility是ignite和burn的ability，是确定overall fire hazard的主要决定因素（major determinant）

    - ISO将combustibility（可燃性）分为五类（从noncombustible到rapid/ flash burning）

  - susceptibility是fire和effect会在多大程度上损坏material

    - content的susceptibility也很重要（即使content不会burn，其也会受到fire heat/ smoke/ 灭火用的水的影响），ISO将content susceptibility分为五类（从minimal damage到extreme loss）

      > 如一场小火会产生很多smoke，如果content是expensive clothing/ furniture/ electronic equipment，则会因smoke contaminated而loss value

#### 3）public protection classification (PPC)

- ISO使用Fire Suppression Rating Schedule (FSRS)来收集并评估community的public protection classification

  - FSRS衡量community fire suppression system的major element并对每个community设定对应的Public protection classification(PPC, numerical grading)

  - ISO PPC system 将public fire service quality按1-10分类（1代表最ideal状态）

    - scale用于评估public fire service的equipment adequacy，response time to property in a particular area

      | Class | 适用于                | mark                                                    |
      | ----- | --------------------- | ------------------------------------------------------- |
      | 1-8   | protected community   | -                                                       |
      | 9     | unprotected community | property远离water supply，缺少adequate fire suppression |
      | 10    | unprotected community | 无public fire protection                                |

#### 4）line guide的用法

- 根据construction type和protection class选择basic line
- 确定occupancy class和相应的modifier，获取modified line
  - modified line = basic line * occupancy modifier
- 获取modified sprinkler line
  - fully sprinklered risk of fire-resistive construction = modified line * 2
  - fully sprinklered risk of noncombustible construction = modified line * 1.5
- 确定final line
  - 根据external exposure（如25 feet外的petrochemical plant）和housekeeping/ maintenance的情况，降低modified line或modified sprinklered line

### （2）Homeowner Line Guide

- homeowner line guide中，public fire protection属于dominant factor
  - home是owner-occupied（自住），所以occupancy criterion不重要
  - 通常也不会考虑construction characteristics，因为大部分的home属于frame结构（或substantially frame结构），极易被火破坏（destruction by fire, 即100%的PML）

- public protection class（PPC）会和maximum line相对应

  > 如果PPC等级过低，则ceded SSR的maximum line不足，此时可使用additional ri以提供necessary coverage amount

- 案例

  > background
  >
  > - public protection class（PPC）如下
  >
  >   ![](https://s1.ax1x.com/2020/07/18/UcJWLt.jpg)
  >
  > - 直保公司承保的home的protection class为5
  >
  > - HO保单承保的benefit如下
  >
  >   ![](https://s1.ax1x.com/2020/07/18/UcJdqx.jpg)
  >
  > solution
  >
  > - 第一步，计算HO保单的总的coverage
  >
  > - 第二步，确定PPC的maximum line
  >
  > - 第三步，计算可分给SSR的amount
  >
  >   ![](https://s1.ax1x.com/2020/07/18/UcY9W4.jpg)