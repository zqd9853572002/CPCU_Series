# 一、probability

- Probability Analysis是研究某事件的probability
- probability是在long run stable environment（长期稳定的环境）里，event会expected to occur的relative frequency，需要有大量的data作basis
  - 如果condition不变，事件发生的frequency会保持一致（remain constant throughout）
  - 若无法确定loss  probability，保险公司则无法成功underwrite insurance
  - ==Probability是从historical data中获得的，如果有new data或environment change，则probability也会改变==

## 1. probability的分类

- ==任何probability都可表示(express)为fraction (1/2) / percentage (50%)/ decimal (0.5)等numerically number==
- ==不可能事件的概率为0，确定事件的概率为1==
  - ==probability的范围为$0 \leq p \leq 1$==
- probability分为theoretical probability和empirical probability (posteriori probability)
- 概率可用theoretical data distribution或用historical data得到

### （1）theoretical probability

- ==theoretical probability是基于theoretical principle（而非基于actual experience）的probability==

  > ==扔色子时，每个面的概率为theoretical probability==

- ==只要physical condition不变，theoretical probability就保持不变==

  - 所以保险人员倾向于使用theoretical probability，但这种情况不适用于所有的situation

- ==保险公司和风管人员分析的loss exposure通常不属于theoretical distribution==

  > workers compensation claim，medical claim均不属于theoretical distribution

### （2）empirical probability

- ==empirical probability (a posteriori probability) 是基于actual experience（historical data/ fact observation）的probability==

  - ==empirical probability无法从理论获得，只能从研究sample loss experience获得==

  - ==如果有new data 或 environment有变，empirical probabilit也会改变==

  - ==empirical probability属于estimate，所以empirical probability的accuracy取决于sample size和sample representative nature（sample代表的nature）==

- empirical probability distribution的条件

  | probability distribution的要求（condition）                  | mark                                                 |
  | ------------------------------------------------------------ | ---------------------------------------------------- |
  | ==probability distribution中的值都是mutually exclusive且collectively exhaustive（穷尽所有的outcome）== | ==必须设定好loss category（bin），以包含所有的loss== |
  | ==每个possible outcome对应了相应的probability==              | -                                                    |
  
- ==保险和风管人员必须使用empirical probability==

  - 尽管theoretical probability因其不变的性质而更可取，但对于保险和风管人员分析的风险，theoretical probability不适用或不可用

## 2. probability distribution

- ==probability distribution是在particular set of circumstance下，对各个possible outome的presentation==
  - ==probability distribution表示特定情况下，某个possible outcome的probability==
  - ==probability distribution通常用table/ chart/ graph表示==
- ==probability distribution基于empirical probability==
  - ==probability distribution是mutually exhaustive（相互独立，即所有condition情况下的probability相加等于1） 且 collectively exhaustive（即穷尽所有的outcome，不会再有其他情况）的==
    - ==mutually exhaustive是指每次实验都只有一个结果，且每次实验的结果都不相互影响，所有condition情况下的probability相加等于1==
- ==probability distribution的要求（condition）==
  - ==probability distribution中的值都是mutually exclusive且collectively exhaustive==
    - ==mutually exclusive是指结果相互独立==
    - ==collectively exhaustive是指穷尽了所有的outcome==
  - ==每个possible outcome对应了相应的probability==
  - 必须设定好loss category（bin），以包含所有的loss

## 3. probability analysis

- probability analysis是假设probability distribution不变，进而对事物（如accidental loss/ business loss）进行forecast的技术
- ==probability analysis可有效预测企业的loss或gain的likelihood和consequence==
  - ==probability analysis需要有大量past loss/ gain的数据（substantial volume of data on past loss），也要有fairly stable operation（即loss/ gain pattern可持续下去）==
    - ==企业过去经历的loss越多，其可用于分析的sample就越大，继而对future的预测更可靠（随时间的推移而一致），因为预测是基于产生损失的环境的更大样本。这是大数法则的应用，也适用于gain和其他情况==
  - ==对于unchanging environment，企业过去的loss/ gain可看作是企业未来所有loss/ gain的sample==
- ==大数法则是随着sample size（similar but independent exposure unit）增加，empirical frequency和theoretical probability之间的差距会下降==
- ==大数法则的缺点（limitation）：只有同时满足以下三个条件时，才能用大数法则准确预测future==
  - ==event是在substantially identical condition的情况下，在过去发生的，且是由unchanging和basic causal force引起的==
  - ==如果condition保持不变，event会在未来同样的情况下（unchanging condition）继续发生==
  - ==event之间都是相互独立（independent）的，且sufficiently numerous（数量众多）==

## 4. discrete distribution和continuous distribution

- probability distribution分为discrete distribution（离散分布）和continuous distribution（连续分布）


### （1）Discrete distribution

- Discrete distribution是指有限个可能的结果，即可在一个table中列出所有的possible outcome和每个outcome对应的probability

  - Discrete distribution可用于分析多长时间会发生一次（如frequency distribution）

    > 如分析WC的loss frequency

  - Discrete distribution常用于loss frequency

### （2）continuous distribution

- ==continuous distribution是有无限多个可能的结果，通常使用line graph表示==
  - ==可将distribution分成countable number of bin（有限个bin），之后计算结果落在一定范围内的probability==
  - frequency和severity中都有无限多个value，所以可使用chart format或table来研究continuous distribution，用frequency distribution和severity distribution以forecast future loss
- continuous distribution中，outcome显示在水平轴（horizontal axes），结果可能性（probability）显示在垂直轴（vertical axes，具体表示为在结果之上的直线或曲线的高度）
- continuous distribution的结果称为probability density function（概率密度函数）。
- ==continuous distribution常用于研究loss severity（即用于描述loss value，而不是描述outcome number）==

# 二、Central Tendency Theorem（CTT）

- 确定empirical probability并建立probability distribution后，风管人员应使用central tendency和dispersion来比较概率分布的characteristic（特点）
  - ==Central Tendency是probability distribution中最能代表所有可能结果的单个结果（即对结果best guess），即给出最能代表（most representative）所有empirical probability distribution的single outcome==
    - 许多probability distribution都围绕一个特定值，这个值可能在distribution的exact center（也可能不在）
    - ==可通过expected value和mean来衡量central tendency==
      - expected value/ mean可为compare distribution characteristics提供useful information
  - ==dispersion是衡量distribution在expected value周围（而非聚集在expected value周围）分散的程度（spread out dispersion），即not concentrated around the expected value的extent==
    - ==可使用standard deviation和coefficient of variation来衡量dispersion==

## 1. Central Tendency中常用的measure

- 最常使用的measure（度量）为mean/ median/ mode

### （1）mean

- ==mean是data set中的所有值相加（sum of value），除以值的个数(number of value)==

  $mean = \cfrac{sum\ of\ value}{number\ of\ value}$

  | 分布类型                 | 计算方式                          | 计算方法                                                     |
  | ------------------------ | --------------------------------- | ------------------------------------------------------------ |
  | theoretical distribution | 使用probability计算expected value | -                                                            |
  | empirical distribution   | 使用mean计算expected value        | 通过每个结果的weighting和frequency，之后再除以number of outcome value来计算mean |

- 当underlying condition不变时，mean才能良好估计expected outcome

  - mean来源于经验，若产生experience的环境（condition）改变，则mean无法准确估计central tendency

  - ==forecast future event时，风管和保险人员仍会将mean作为single best guess来预测未来事件==

    > 企业下年度worker compensation的claim number通常是前几年事件frequency distribution的mean

### （2）Expected Value

- ==Expected Value是probability distribution中，所有possible outcome的weighted average（加权平均值）==
  - ==可通过weighting和average outcome，衡量central tendency的程度==
  - ==weight是某个结果的概率==
  - ==可能的结果用$x_n$表示，概率用$p_n$表示==
  - ==$distribution\ expected\ value = \sum_1^n(p_n \cdot x_n)$==
- ==expected value的计算方法适用于所有theoretical discrete distribution（不管discrete distribution的形状或dispersion如何）==
- ==continuous distribution的expected value也是所有possible outcome的weighted average，但计算方法更复杂==

### （3）median

- median是data set先按大小顺序排号，最中间位置的值（如果data set有偶数个value，则取最中间两个值的平均值）
- 对于loss probability distribution
  - 计算小于loss number或loss dollar amount的probability有助于选择retention level
  - 计算大于loss number或loss dollar amount的probability有助于选择insurance coverage的upper limit
  - 所以应当关注cumulative probability和individual probability的column

### （4）mode

- mode是distribution中最常出现的值（most frequently occurring value in a distribution）
- 保险公司可通过mode来关注most common outcome

## 2. distribution dispersion（分布的分散情况）

- 分析probability distribution时，可通过衡量dispersion来评估central tendency measure的credibility（可用于分析loss exposure）

  |                | 解释                                                         | mark                                     |
  | -------------- | ------------------------------------------------------------ | ---------------------------------------- |
  | dispersion较小 | 更能确定expected outcome（即variation更低，less uncertainty） | 保险人员愿意围绕expected outcome承保风险 |
  | dispersion较大 | 更不能确定expected outcome<br /><br />此时distribution shape更平坦（flatter） |                                          |

  - ==保险人员愿意承保estimated loss周围的风险（variation更低），因为围绕central tendency的variantion越低，risk越小==
  
- ==衡量dispersion的statistical measure包括standard deviation和Coefficient of Variation==

### （1）standard deviation

- ==standard deviation是衡量distribution value和expected value（mean）的dispersion==

  - ==standard deviation的公式==

    ==$standard\ deviation = \sqrt{variance}$==

- 计算sample outcome的standard deviation时，不需知道每个outcome的probability，只需知道每个outcome如何occurred即可

- ==standard deviation越大，则value越desperse（分散）==

  - underwriter应选择standard deviation较小的客户
  - ==对于保险人员和风管人员，可通过计算standard deviation来确定expected value有多靠近actual value（即衡量对expected value的确定程度）==

### （2）Coefficient of Variation（CoV）

- ==Coefficient of Variation是用standard deviation除以mean来衡量distribution的dispersion==

  $Coefficient\ of\ Variation = \cfrac{standard\ deviation}{mean\ (expected\ value)}$

- ==coefficient of variation越大，表明loss更难以predict==
  
  - underwriter应选择coefficient of variation较小的客户
  - higher coeffiecient of variation说明higher variablility，意味更难以预测loss（即less predictable），进而意味着很难forecast individual outcome accurately
  
- ==Coefficient of Variation可用于衡量loss control measure是否让loss变得more predictable或less predictable（即分布是否更variable或less）==

- standard deviation和Coefficient of Variation的使用

  |                                          | 使用的measure                | 解释                                                        |
  | ---------------------------------------- | ---------------------------- | ----------------------------------------------------------- |
  | ==两个分布的mean（expected value）相同== | ==standard deviation==       | ==standard deviation越大，其variability越大==               |
  | ==两个分布的mean（expected value）不同== | ==coefficient of variation== | coefficient of variation越大，则dispersion或variability越大 |


## 3. skewed distribution

- 各种情况下，mean/ median/ mode的情况

![](https://s1.ax1x.com/2020/09/10/wGEWlj.jpg)

- 导致loss distribution发生skewed的原因

  - small loss的probability很大
  - large loss的probability很小

- ==severity distribution通常属于asymmetrical distribution==

- ==如果distribution是skewed，则median（而非mean）是对最多发生事件的better estimate==

  - 可使用cumulative frequency和culmulative frequency的median value来寻找median或mid point

  > 如WC claim distribution是skewed，则本年度的claim median可对下一年的claim提供better estimate。通过使用median，被保险人可更好的选择deductible

## 4. normal distribution

- ==保险人员和风管人员使用normal distribution（正态分布）来预测future loss，进而可以提供loss control resource（用以prevent或mitigate的loss）或为无法避免的loss提供finance==

- 正态分布是bell-shaped curve的probability distribution
  - ==正态分布属于theoretical distribution==
  - 正态分布可准确预测expected value/ mean/ average value的variability，从而可以准确预测physical phenomena的variability
  
- ==normal distribution的curve永远不会触达水平线（x轴）==

  - ==normal distribution中每个结果的概率都大于0，不管这个结果距离mean有多远）==
  - ==normal distribution中，mean左右的概率各为50%==

- 68-95-99 rule

  ![](https://s1.ax1x.com/2020/09/10/wGQzB4.jpg)



| 左边4标准差 | 左边3标准差 | 左边2标准差 | 左边1标准差 | 正态分布中50%的位置                 | 右边1标准差 | 右边2标准差 | 右边3标准差 | 右边4标准差 |
| ----------- | ----------- | ----------- | ----------- | ----------------------------------- | ----------- | ----------- | ----------- | ----------- |
| 0.13        | 2.15        | 13.59       | 34.13       | mean (expected value)/ median/ mode | 34.13       | 13.59       | 2.15        | 0.13        |

- 正态分布中，mean左边1个standard deviation之内，有34.13%的outcome，mean右边1个standard deviation之内，有34.13%的outcome
- $mean \pm 2 个SD$之内，覆盖了95.44%的outcome
  - ==所以只有5%的outcome在$mean \pm$ 2个SD之外==
- $mean \pm 3 个SD$之内，覆盖了99.74%的outcome
- mean的一侧，49.87%(=34.13% + 13.59% + 2.15%)的outcome落在3个SD之内