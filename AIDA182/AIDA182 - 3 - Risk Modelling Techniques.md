# 一、概述

- Big Data Analysis Techniques
  
  - big data是data is too large，无法使用traditional method进行gather和analyze
  
  - new data analysis technique（如text data mining，social network analysis）正在改进risk modeling
  
    > 如可使用data analysis technique分析adjuster notes/ customer service conversation
  
- Machine Learning（机器学习）是computer根据previous results 和new data作出better decision
  
  - 机器学习可持续改进（continually improve）risk model
  - 通过在computerized model中不断导入new data，model可从new data中不断学习，进而产生更准确的prediction

# 二、modeling method

- Modeling Method
  - 何时使用model/ 如何使用model取决于model的limitation
- modeling method的分类
  - 基于historical data的method
  - 基于expert input的method
  - 基于historical data 和 expert input的method

## 1. 基于historical data的modeling method

- ==empirical distribution是根据random variable value构建table/ chart/ graph==
  
  - empirical distribution代表variable在一个period之内的frequency
  - empirical distribution是大部分analysis的starting point
  - ==empirical distribution中，大数法则非常重要，因为sample越大，sample result越accurate且reliable==
  - ==随着trial number增加，empirical distribution会接近于theoretical distribution==
- ==theoretical distribution是使用mathematical/ analytical formula构造的==
  
  - theoretical distribution可用于statistical reference或comparison
  - ==没有sufficient historical data point number时，可使用theoretical distribution来改进empirical distribution==
  - theoretical distribution可用于解释risk category的potential variability
    - claim frequency和claim severity通常遵循特定的distribution
      - claim frequency遵循negative binomial distribution或Poisson distribution
      - claim severity遵循lognormal distribution或Pareto distribution (conditional claim or tail)
      - actuary负责构建model
  - security price和stock price遵循normal distribution
  
- Extreme value theory（EVT） (for long tail/skewed distribution)

  - EVT主要用于long tail/ long skewed distribution

  - EVT是评估远离median的extreme deviation的statistical estimation（即EVT主要研究分布中tail的情况）

    - 在skewed data中，可使用median（而非mean）来更好的估算expected value

  - ==分析并预测rare event时，主要的困难在于缺少available data==

    - 此时可使用EVT为rarely occurring或unknown variable等极端值（即model的尾部）建模

      > EVT可用于为100-year earthquake建模，对financial/ banking organization进行EVT stress test等

  - ==EVT可用于预测某些event的probability，所以主要用于评估low frequency + high severity的loss risk==

- regression analysis是假设要预测的变量（dependent variable）会随另一个变量（independent variable）变化
  
  - regression analysis也可用于forecast opportunity

## 2. 基于expert input的method

- Preference among bets是将expert opinion转换为probability（通过使用事件发生的probability formula完成）

  - Preference among bets适用于几乎没有observable data的情况

    > Preference among bets可用于Political Risk 或 Legal risk

- relative likelihood judgments是通过使用expert input的方式来估算event outcome的likelihood

  - relative likelihood judgments的limitation是expert input会受unintentional bias的影响，从而导致对unfamiliar event估算的likelihood较小，对more familiar event估算的likelihood较大
  - relative likelihood judgments有助于从不熟悉probability assessment的expert处获得knowledge 或opinion

- Delphi technique是一种collaborating estimating technique strategy，其通过不断完善自身的response（continuously refining individual response）来获得expert input的consensus

  - Delphi technique流程中，会不断refine question/ survey并显示之前问题的tabulated result，之后再开始下一个问题

    - Delphi technique鼓励expert share opinion和forecast，之后不断汇总（converging and synthesizing the answered），直到达成group conclusion

  - Delphi technique可用于problem-solving process和decision making process

  - Delphi technique比expert workshop更加cost-effective

  - Delphi technique的适用性

    | 有用                                                         | 无用                               |
    | ------------------------------------------------------------ | ---------------------------------- |
    | 探讨varying subjective judgment topic（主观判断的问题）和encompassing discipline range（学科主题）时非常有用 | forecast new/ unknown entity时无用 |
    | -                                                            | 需要novel way来达成decision时无用  |

## 3. 基于historical data 和 expert input的method

- ==基于historical data 和 expert input的method，适用于有多个uncertainty和interaction的complex modeling问题==
- Monte Carlo Simulation（蒙特卡洛模拟）主要关注project中的specific variable
  
  - ==Monte Carlo Simulation（蒙特卡洛模拟）的过程：根据probability distribution，computer为每个variable随机选择value，之后产生上千个possible scenarios，继而形成可代表possible outcome的probability distribution==
- Fuzzy Logic是为indefinite data field赋值（assign value），以获得更准确的probability
  - fuzzy logic的过程中，input/ output/ fuzzy set/ fuzzy rule非常复杂
  - ==fuzzy logic中，会使用complex/ descriptive language expert input，并将其转换成mathematic equivalent==
  - ==fuzzy logic中，probability基于measure degree，而非specific measure==
  - ==fuzzy logic的优点：可使用familiar term，flexible，adapt to imprecise data==
- Bayesian Inference是根据Bayes Rule，将conditional probability分解（break down）成individual component（每个individual component更好估计）
  - ==Bayesian Inference用于没有sufficient data point或没有足够的expert input的情况==
  
  - ==贝叶斯公式==
  
    $P(B |A) = \cfrac{P(A|B)\cdot P(B)}{P(A)}$
  
  - ==conditional probability是在给定given condition的情况下，某个outcome的probability，其是多个data analysis mode的basis==

# 三、分析event consequence

- modeling之后，下一步为analyze event consequence

## 1. Decision Tree Analysis（DTA）

- Decision Tree Analysis是分析decision outcome的uncertainty，==Decision Tree Analysis可同时提供qualitative analysis（定性分析）和quantitative analysis（定量分析）==

  - Decision Tree的qualitative analysis（定性分析）
    - Decision Tree可根据decision产生相应的scenario，progression和consequence
    - Decision Tree的construction开始于initial decision statement
  - Decision Tree的quantitative analysis（定量分析）
    - decision tree可估计decision导致的各种scenario的probability和frequency
    - 对每个event pathway上的probability相乘，之后可比较不同pathway的乘积，以确定可产生highest expected value的pathway（即best pathway through a problem）

- decision tree的优缺点

  |      | 解释                                                         | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 优点 | 可以examine consequence（如cost，gain等）                    | ==企业可使用decision tree（DTA）来比较alternative decision，之后选择most effective strategy以实现goal== |
  | 缺点 | decision会simplify complex problem，导致降低resulting decision的effectiveness | 有时decision tree会非常复杂，从而无法无法有效地向未参与process的人传达decision rationale |
  |      | decision tree无法显示inter-dependency的关系                  | -                                                            |

- ==企业可使用decision tree analysis（DTA）来比较alternative decision的consequence/ cost/ gain等，从而选择most effective strategy以achieve goal==

## 2. Event Tree Analysis（ETA）

- 在qualitative和quantitative analysis方面，Event Tree Analysis（ETA）的representation和calculation与Decision Tree Analysis（DTA）非常相似，但应用场景不同
- ==Event Tree Analysis（ETA）是分析accidental event的consequence==
- ==event tree analysis的起点为accidental event==
  
  - ==accidental event是first significant deviation from a normal situation，该deviation会导致unwanted consequence==
  
- ==Event tree analysis（ETA）可提供qualitative和quantitative analysis==
  - Event Tree Analysis（ETA）的qualitative analysis可根据accidental event产生相应的scenario，progression和consequence
  - Event Tree Analysis（ETA）的quantitative analysis可估算出各种scenarios and outcome的probability和frequency，从而帮助企业确定是否需要risk control和safeguard，及其effectiveness

- ==Event Tree用于判断是否需要risk treatment，以及判断risk treatment 的effectiveness（因为event tree会分析negative consequence（risk of loss））==
  
  - ==event tree会分析accidental event的所有possible outcomes（包括probability，用于prevent/ control的existing measure等）==
  - 企业可使用event tree来检查system/ risk treatment/ risk control的effectiveness
  - 企业可使用event tree来identify/ recommend各种prevent/ risk control method，同时可以justify各项improvement所花费的money/ time/ resource
- ==企业可使用event tree analysis（ETA）来检查accidental event导致的all possible consequence，以及prevent/ control consequence的existing measure的effectiveness==
  
- Event Tree Analysis（ETA）的优缺点

  | ETA      | 解释                                                         |
  | -------- | ------------------------------------------------------------ |
  | 优点     | 和decision tree类似                                          |
  | ==缺点== | ==只提供两个option（success或failure），所以无法呈现progression的complexity== |


## 3. Decision Tree Analysis（DTA）和Event Tree Analysis（ETA）的区别

- ==DTA和ETA都用于describe data（而非decision），但analyst可根据data来make/ justify decision==

- ==DTA和ETA的区别在于purpose（主要区别），used information和information produced==

  |                     | decision tree analysis                                       | event tree analysis                                          |
  | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | function            | ==检查decision的consequence/ cost/ gain<br /><br />比较各alternative decision== | ==检查accidental event的consequence==                        |
  | use                 | 协助选择most effective strategy，以实现goal                  | 检查是否需要risk treatment measure，或评估risk treatment measure的effectiveness<br /><br />帮助identify/ recommend/ justify improvement |
  | feature             | 可以分析negative/ positive consequence (loss/ gain)          | ==只能分析negative consequence (risk of loss)==              |
  | input               | 带有decision point的project plan<br /><br />decision的possible outcome相关的information或可能影响outcome的event | 会导致loss的possible event list<br /><br />risk treatment information和各种barrier failing probability<br /><br />理解failure如何escalate |
  | process（步骤流程） | ==定义problem（第一步）==<br /><br />构建通向outcome的pathway<br /><br />为可影响outcome的event分配probability<br /><br />为每个pathway对应的outcome分配value | ==识别accidental event（第一步）==<br /><br />构建通向outcome的pathway（包括barrier）<br /><br />为pathway上的barrier分配success/ failure probability<br /><br />确定每个pathway的outcome的frequency |
  | output              | 分析每个pathway上的多个option<br /><br />计算每个pathway的expected value | 列出可能发生的potential problem，计算outcome的expected value和frequency<br /><br />根据barrier的effectiveness，作出recommendation |
  | 优点                | 展现problem/ sequence/ outcome的visual portrayal<br /><br />为计算best pathway提供方式<br /><br />==提供qualitative（定性）==和quantitative（定量）信息== | 展现accidental event之后potential sequence的visual portrayal<br /><br />解释accidental event发生后，control system的potential effectiveness<br /><br />==提供qualitative（定性）和quantitative（定量）信息== |
  | 缺点                | 可能会over complex，难以communicate<br /><br />可能会oversimplified，导致less accurate information，从而无法decision making | 可能会无效（ineffective），但如果能识别所有potential initiating event时会有效<br /><br />analysis只限于两个option（即barrier的success/ failure），从而overlook other factor<br /><br />可能无法强调sequence的dependency，导致risk estimate不准确 |


## 4. Classification Tree Analysis（CTA）

- Classification Tree Analysis用于data mining，涉及从data中extract hidden pattern
- classification tree描述data mining context的data（而非decision），但可通过obtained data作出decision

##5. Influence Diagram

- ==Influence Diagram是为decision-making process提供visual graph，属于decision tree（DTA）的另一种方式==
  
  - 对decision process画出graphical overview可帮助decision maker
  - ==influence diagram可为会impact decision的各factor的graphical representation（如描述影响decision的各factor的interdependency）==
  - 有时会使用mathematical expression来构建model，以显示decision和outcome（positive/ negative）相关的known and unknown factor
  - Influence Diagram的目的是获得并理解known and unknown factor和information value的whole picture
  
- Influence Diagram的element

  |                   | 表示的内容    |
  | ----------------- | ------------- |
  | rectangle（矩形） | decision node |
  | ovals（椭圆）     | variable      |
  | diamond（菱形）   | Benefit/ Cost |
  | arrow（箭头）     | independency  |

- Influence Diagram和Decision Tree的区别在于construction和data representation

  - Influence diagram给出了cost return benefit analysis的holistic view
    - ==influence diagram通过arrow，decision node，和影响decision/ benefit/ cost的variable，展现出inter-dependency==
  - decision tree有每个alternative（go/ no-go decision）的branch
    - branch代表outcome
    - branch从circle中发出，circle都代表每个branch的probability
    - decision tree

- Influence Diagram和decision tree的比较

  |                                              | influence tree（Influence Diagram）                          | decision tree                                |
  | -------------------------------------------- | ------------------------------------------------------------ | -------------------------------------------- |
  | 是否可展现holistic view或alternative outcome | ==代表holistic view，代表decision-making process的overview，可以合并所有的identified variable和对应的probability== | 无法combine alternative及其outcome           |
  |                                              | 可构建为Bayesian network（包括table和graph）                 | -                                            |
  |                                              | ==通过arrow，decision node，和影响decision/ benefit/ cost的variable，展现出inter-dependency== | -                                            |
  | 适用性                                       | ==用于企业内的ongoing decision making==                      | ==用于一次性(one-time)的go/ no-go decision== |

- dashboard
  - Risk Dashboard是一种computer interface，用以报告企业key risk indicator（KRI）的quantitative data
    - Key Risk Indicator/ KRI是企业衡量实现objective时uncertainty的工具
- gather input data并计算不同target variable probability时，需假设target variable应当是mutually exclusive（相互独立）且collectively exhaustive（穷尽）的

## 6. case analysis的步骤

- case analysis的步骤（typical scenario）
  - 对于每个option，评估data，绘制influence diagram
  - 确定每个option的probability
  - Cost benefit analysis：考虑每个option的economic and financial issue
  - 比较各个option
  - 作出recommendation

# 四、financial risk和financial outcome的VaR和EaR

## 1. Value at Risk（VaR）

- ==Value at Risk/ VAR是一种threshold value，其用于衡量在给定的time horizon之内，loss超过threshold level水平的probability==

  - ==VaR假定market不变，且portfolio没有trading==

  > ==one-day, 5% VaR of 300,000，代表有5%的可能在第二天损失300,000或更多==
  >
  > ==分布图上的代表为损失左侧的区域==

- 使用VaR作为risk measure的优缺点

  | VaR的优点                                                   | VaR的缺点                                 |
  | ----------------------------------------------------------- | ----------------------------------------- |
  | 可以量化（quantify）investment decision相关的potential loss | 无法准确衡量损失超过VaR threshold的extent |
  | 可以量化complex position（如涉及multiple decision的情况）   | -                                         |
  | 用易于理解的monetary term来表达loss                         | -                                         |

（1）Conditional Value at Risk（CVaR）

- ==CVaR是确定loss大于等于VaR的likelihood==
- ==CVaR假设market不变，且portfolio没有trading==
- CVaR（Conditional Value at Risk）的优点和VaR一样
  - ==CVaR会考虑distribution tail中可能发生extreme large loss（损失概率通常很低）的情况==
- ==CVaR在fat-tailed distribution中非常重要，因为在fat-tailed distribution中，extreme large loss的发生率高于常规的distribution==

## 2. Earnings at Risk (EaR)

- ==Earnings at Risk (EaR)是在一年内的特定time period内，在一定的confidence degree情况下，最大的expected loss of earning==

  - 通常使用Monte Carlo Simulation（蒙特卡洛模拟）对EaR进行建模（model），EaR model的展现形式为probability distribution curve或individual probability的histogram

  - ==EaR threshold 表示一定confidence情况下（如95%以下）的lower end of projected earning==

    - 企业收益大于EaR threshold的概率由EaR threshold右侧distribution curve下的面积表示

    - EaR threshold左侧曲线下的区域表示收益低于EaR threshold的概率

      > ==EaR 是 200,000 with 90% confidence：表示有10%的概率，earning小于200,000==

- EaR可用于比较不同的RM strategy对earning的effect

  - ==EaR可衡量product price/ production cost change对企业earning的影响==

- EaR的缺点
  - EaR计算很复杂（calculation complexity）
  - 需要了解不同variable之间的relationship
  
- financial 和 non-financial organization可通过使用EaR，对various factor对企业的earning的影响进行建模

- ==EaR需对product price change和production cost change对企业earning的影响进行建模==

# 五、Catastrophe Modeling

- Catastrophe model是评估catastrophe的probability（即loss frequency，估算此类rare event较困难）和相应的potential loss severity

  > 巨灾包括wildfire，winter storm，flood，terrorism

## 1. catastrophe model的operation

- catastrophe model使用insurer-supplied exposure data来产生potential loss range和相应的associated probability of exceedance

  - exceedance是loss等于或超过specified size的probability（概率）

  | Inputs                              | catastrophe modeling component | outputs                      |
  | ----------------------------------- | ------------------------------ | ---------------------------- |
  | insurer-supplied loss exposure data | hazard                         | average annual loss          |
  | -                                   | engineering                    | exceedance probability curve |
  | -                                   | financial                      | -                            |

- catastrophe model通常是proprietary（专有的）

  - ==每个catastrophe model的assumption和result均不相同，所以直保公司会使用多个catastrophe model的结果==
  
- catastrophe model通常使用computer code

  - modeling firm通常会提供上千页的detailed documentation以让model user理解model/ model sensitivity/ uncertainty/ implication for risk management，并让user理解using model result的best practice

## 2. catastrophe model的3个component

- ==catastrophe model包含三个component/ module： hazard component，engineering component，financial component==

### （1）hazard component

- Hazard component是actual physical cause and intensity（以actual geophysical information and weather information为basis）

- ==hazard component模拟catastrophic event，以确定hazard intensity==

  - hazard component由scientist team (meteorologists, seismologists, hydrologists, climate scientists, geophysicist(气象学家，地震学家，水文学家，气候学家，地球物理学家))组成

- ==hazard component要回答的问题是==

  |               | 具体问题                                           |
  | ------------- | -------------------------------------------------- |
  | ==where==     | 哪里（where）最有可能发生catastrophe               |
  | ==how==       | catastrophe有多大（large），多严重（severe）       |
  | ==how often== | 多久发生一次catastrophe（即catastrophe frequency） |
  
- 先生成large catalog（基于上万computer-simulated catastrophe），large catalog代表了broad spectrum of plausible event

  - 对于每个simulated event，model会计算affected area内每个location的intensity

    > 对于earthquake，intensity可表示为ground shaking degree或由event引发的fire的number或intensity
    >
    > 对于hurricane，intensity可表示为wind speed和storm surge height

  - model包含了大量detailed geophysical information database

    > windstorm model使用high-resolution digital land use and land cover data来计算wind speed对surface friction的effect
    >
    > earthquake model使用detailed soil data，来确定seismic wave amplification degree和event对特定地点的liquefaction

- ==不同的catastrophe model会产生不同的结果（因为其基于不同的theoretical assumption和variable）==

  > 如hurricane有100年的数据，但早期数据不如recent data（not detailed/ sophisticated/ accurate）。不同的modeling form会使用不同的dataset，从而对future hurricane的frequency和severity发展出不同的theory

### （2）engineering component

- ==engineering component是使用hazard component中的hazard intensity information，估算发生simulated catastrophe event时的property structural damage extent==

  - ==engineering component进行估算时，需要如下information==

    | ==engineering component需要的information== | ==additional information==           |
    | ------------------------------------------ | ------------------------------------ |
    | building construction                      | roof shape                           |
    | occupancy                                  | roof-to-wall connection              |
    | height                                     | hurricane shutter的presence或absence |
    | age                                        | -                                    |
    | building code enforcement                  | -                                    |

- structural engineer会开发damage function equation，用于计算building和content的damage level，以及repair/ rebuild所需时间

  - 估算repair/ rebuild所需时间的function（函数）可用于估算residential policy的business interruption（BI）loss或alternative living expense（ALE）
  - catastrophe model damage function会反映published research/ laboratory testing result/ on-site damage survey finding/ 直保公司提供的detailed claim data

- ==catastrophe model可产生多种结果的原因在于使用不同的engineering research来确定damageability==

  > 如针对hurricane wind和不同类型structure的flying debris问题，research和professional的opinion会不一样

### （3）financial component

- ==financial component是将building和content physical damage转换成monetary loss，以进行预估。通过使用insurance policy condition，再将这种estimate转换为total damage estimate==

  - ==本质上看，financial component评估simulated catastrophe对保险公司in-force policy和operating result的effect==

  - 直保公司会sustain loss range（取决于simulated catastrophe的magnitude）

  - financial component反映出in-force policy的coverage characteristic

    > 如使用ACV basis还是使用RC basis来设定loss reserve

- catastrophe model还要考虑的因素包括

  |                                        | 解释                                                         | 案例                                                         |
  | -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | socioeconomic factor                   | -                                                            | 如catastrophe后发生fraud/ theft的likelihood                  |
  | 计算total insured loss时的demand surge | ==demand surge是catastrophe后repair cost大幅增加（因为material/ labor supply shortage）== | 如hurricane后，affected area的glass/ roof shingle/ plywood的价格都会大幅增加 |

## 3. catastrophe model的output

### （1）Average Annual Loss（AAL）

- ==average annual loss（AAL，catastrophe loss cost，pure premium）是任一一年内，in-force policy的expected long-term average loss==
  - ==AAL通常表示为catastrophe loss cost/ pure premium/ expected loss per unit of premium/ exposure unit（每个exposure unit的expected loss）==
- AAL value反映了catastrophe model的所有component（hazard/ engineering/ financial）
  - 相较于simple review in-force policy的geographic distribution，AAL value可更有效的identify in-force policy的catastrophe-prone concentration

- AAL analysis的用途
  - ==catastrophe model可产生policy-level AAL information，从而可制定reinsurance rate==
  - 有时会在reinsurance rate中增加risk load，已承担extreme event产生的超过AAL的loss
  - 直保公司和再保公司会使用AAL来比较不同reinsurance program proposal的pricing
    - ==直保公司使用catastrophe model result来了解in-force policy portfolio的catastrophe loss potential==
    - ==再保公司使用catastrophe model产生的policy-level AAL information以develop catastrophe reinsurance rates==

### （2）Exceedance Probability Curve（EPC）

- ==Exceedance Probability Curve（EPC）是表示potential loss的full spectrum及其相关的occurrence probability（exceedance probability是反映了loss等于或超过specified size的probability）==
  - ==EPC是catastrophe model中最常用output==
- EPC中的return period通常使用year，year的倒数（inverse）即为exceedance probability
- catastrophe model会给出exceedance probability
- 为谨慎考虑，应关注exceedance probability（而非关注return period），以防“100-year loss 不会发生在my lifetime中”以及“已经发生100-year loss，则不会再发生另一个100-year loss”
  - 每年发生100-year loss的probability为1%

- 基于exceedance probability analysis，直保公司可确定应购买的reinsurance limit size

## 4. catastrophe modeling的问题

- catastrophe modeling的问题
  - ==由于data variation和building model使用不同的assumption，不同vendor的不同model会产生不同的结果==
  - catastrophe model output的reliability会和直保公司input exposure的data quality息息相关

## 5. Big data在catastrophe model中的应用

- Big Data可用于创建更准确的catastrophe model
  - 通过分析快速分析multiple source的enormous amounts of data，catastrophe model可对climate/ engineering/ technology/ geopolitical/ socioeconomic的condition change作出respond（响应）

