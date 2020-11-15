# 一、用Vehicle Telematics制定Automobile Ratemaking

- automobile rate通常基于class basis，即将similar exposure划入一个group，之后对一个group中的member收取同样的rate
  - underwriter和actuary负责识别每个group的attribute and additional attribute，以反映potential loss frequency and loss severity
- telematics可帮助gather information，之后underwriter可以better understand personal and commercial policyholder，进而开发出more accurate automobile insurance rate，或将其用作simple risk management tool
  - ==telematics收集的additional attribute包括car acceleration和hard brake==
- telematics的使用方式包括temporary/ permanent installation of tracking device，embed telematics equipment或smartphone application
  - ==telematics device的purpose（目标）是track driving habit，并将information通过wireless的方式transmit给computer==
  - ==telematics device可以track的information包括driving habit，hard braking，acceleration，speed，cornering，lane shifting，left turn vs right turn，每天vehicle driven的time（time of day）==

## 1. 传统的Automobile Rating Attribute

- traditional automobile rating attributes包括

  | 分类 | traditional automobile rating attributes | 解释                                                         |
  | ---- | ---------------------------------------- | ------------------------------------------------------------ |
  | 车   | Territory                                | territorial factor包括<br />- road condition<br />- state safety law<br />- traffic regulation的extent<br />==- auto normally used/ garaged place== |
  |      | use of the auto                          |                                                              |
  |      | Vehicle Weight                           |                                                              |
  |      | Vehicle Use and Type                     | heavy vehicle更有可能cause severe damage                     |
  |      | Radius of Operation（运营半径）          | long distance会增加accident chance                           |
  |      | Special Industry Classification          | food delivery<br /><br />waste disposal<br /><br />farmers   |
  | 人   | age                                      |                                                              |
  |      | gender                                   |                                                              |
  |      | Marital Status                           |                                                              |
  |      | Driving Record                           |                                                              |
  |      | Driver Education                         |                                                              |
  |      | Years of Driving Experience              |                                                              |
  |      | Credit Score                             |                                                              |

- ==Usage Based Insurance/ UBI是一种premium基于policyholder driving behavior的auto insurance type==

  - UBI的优点和缺点

    |           | 具体项目                                                     | 案例                                                         |
    | --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | UBI的优点 | 在rating classification（preferred/ standard/ non-standard）中，保险公司可以better segment driver | -                                                            |
    | UBI的缺点 | 参与UBI的人可能已经是safe driver                             | -                                                            |
    |           | challenge在于，需要在context中评估data（以便于data不会paint the wrong picture） | 相较于rural area的driver，congested area的driver更有可能brake harder |

- loss ratio是反映premium中被loss consumed的比例（percentage）

  - $loss\ ratio = \cfrac{loss+loss\ adjustment\ expense\ (LAE)}{earned\ premium}$
  - telematics可降低loss ratio，但会增加retention ratio

- 企业可在RM level上使用telematics

## 2. Vehicle Telematics

- ==vehicle telematics可作为participate driver的ongoing education==

## 3. Telematics对ratemaking的影响

- telematics需要sophisticated modeling technique，以让information relevant，并确定有多少information会影响rate
- 保险公司会使用telematics产生的loss exposure data，来supplement traditional data，进而用于ratemaking
- 保险公司会使用sophisticated algorithm（如generalized linear model/ GLM）来分析data，来确定all considered rating attribute之间的correlation和interaction
  - considered rating attribute包括traditional rating attribute（如vehicle use and type）和telematics产生的attribute（如braking，acceleration，time of day）
- ==越来越多的保险公司开始使用machine learning来discover interaction (但这些interaction在predicted linear model中可能not evident)==
- telematics information会被distorted（distortion）
  - older auto有weaker brake，很多young driver都只有older auto，这导致young driver比older driver更容易发生accident
  - machine learning algorithm会分析此类情况，并在rating attribute中pick these interaction

## 4. vehicle telematics的privacy and regulatory consideration

- ==vehicle telematics data不属于state对protected consumer information的definition==

- 不使用（opt out）UBI的customer会有privacy concern，其关注点在于，如何在transmit information过程中protect personal information，以及who own the driver behavior data
- 保险公司须确保使用vehicle telematics来change rate时，必须transparent且not discriminatory

# 二、用machine learning来segment homeowner Policy

- 历史上，保险公司一直通过homeowner policy来获得profit，通过使用more data，保险公司可以发现customer和loss exposure之间的granular data
- ==在machine learning和predictive analytics之前，homeowner policy underwriter在incorporate needed attribute to accurately predict loss方面的ability非常limited (有限)==
- 为开发sophisticated model（用以refine homeowner classification），保险公司必须choose criteria（用以segment homeowner policy）

## 1. Need for Rate Adjustment

- homeowner policy中，traditional rating attribute包括

  | traditional rating attribute                                 | mark/ 案例                                                   |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | year built（建造年代）                                       |                                                              |
  | construction type                                            |                                                              |
  | location                                                     |                                                              |
  | age of home electrical system                                | 属于risk grouping的additional attribute                      |
  | geo-location<br />（可从governmental wildfire agency处获得） | underbrush（灌木丛）<br /><br />==relative wind speed（可帮助更好的理解wildfire related claim）==<br /><br />home和fuel之间的distance（可帮助更好的理解increasing wild-fire related claim） |

- ==loss ratio越低，profitability越高==
  
  - 通过使用analytics（如machine learning），保险公司可以实现其目标（goal），增加insurance rate，降低overall loss ratio，进而在marketplace上more competitive
  - lower loss ratio的customer会寻找competitive rate
    - 保险公司的challenge在于为low loss ratio customer提供lower premium的同时，要对high loss ratio且不会leave的customer收取sufficient premium (high premium)
    - ==为了降低premium，insured会motivated to implement personal RM technique，并upgrade home，从而lower premium==
  
- ==对entire homeowner book使用traditional flat rate时，会导致的结果==

  - ==lower loss ratio的customer去别的地方找less expensive coverage==
  - ==higher loss ratio的customer会stay，导致导致homeowner book的profitability降低，overall loss ratio也不会improve==

- ==personal line insurer会根据homeowner使用smart home device的情况，对homeowner insurance policy进行discount==

- personal line insurer开发了usage-based homeowner insurance
  
  - usage-based homeowner insurance的rate会部分基于家里device传出的wireless data（和auto insurance中的UBI类似）

## 2. 通过Machine Learning识别Loss Ratio Segment

- ==使用advance machine learning和predictive analytics前，homeowner underwriter accurately predict loss的ability仅限于incorporate many needed attribute==
- 使用machine learning来segment policy时，保险公司会看到additional attribute（more attribute）及其interaction（traditional rating model中未考虑这些attribute和interaction），进而支持underwriting decision
  - 根据traditional variable和new variable之间的interaction，保险公司发现segment的loss ratio属于inconsistent
  - fully trained segmentation model可在data中寻找meaningful pattern，并能automatically segment policy
- ==保险公司缺少data时（如small size的保险公司），可使用producer file和claim rep file（包含significant amount of data）进行machine learning==
  - 如果没有machine learning，find variable会非常费时间（time-consuming）
  - ==machine learning会解释traditional ratemaking analysis中未找到的relationship和trend==

## 3. 评估 Machine Learning对homeowner policy的影响

# 三、用Data Mining来承保Products Liability Risk

- ==cluster analysis可用于寻找recent large claim中是否有pattern（如寻找涉及gluten-free product的claim activity的pattern）==
  
  - ==cluster analysis包括unsupervised learning technique，k-means，nearest neighbor clustering等==
  - supervised learning和predictive modeling主要处理known attribute和known target variable的情况
  
- ==由于是product liability risk，保险公司可使用social media data/ text mining来search social media，进而为customer manufactured product提供reference==
  
  - 此过程等于给出positive/ negative sentiment，进而给customer manufactured product提供sentiment score
  
- 基于insurance professional knowledge，data science team会为predictive model设定attribute和target variable

- ==predict liability risk非常重要，原因在于==

  |                                                              | mark                                                         |      |
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
  | ==hold business liable for their product的law越来越多（increasingly expanded）== | -                                                            |      |
  | ==如果product导致customer injury，则retailer/ retailer/ manufacturer/ distributor都会承担liability== | ==如果manufacturer知道product会adversely affect large number of people，则其有在product label上提供adequate warning的duty== |      |
  | ==social philosophy会favor consumer==                        | -                                                            |      |

- data mining可帮助保险公司properly evaluate客户的product liability loss exposure（特别是product有uncertain risk characteristic时）
  
  - 评估product liability loss exposure时，underwriter不能只依赖traditional underwriting guideline，也会benefit from data mining，进而寻找出underwriting中未发现的new trend

## 1. Discover Emerging Risk

- 对social media cluster analysis，text mining

### （1）Cluster Analysis

### （2）Text Mining

## 2. emerging risk的predictive modeling

- ==对于newly introduced insurance product and emerging technology的风险时，不能只依赖traditional underwriting guideline，还要依赖advance data analytics（所以advance data analytics很重要）==
- 保险公司会使用predictive model来underwrite new account
- 通过more accurately predict claim likelihood，保险公司能够确定应当在pricing level上accept哪些客户，继而maintain line of business的profitability
- 对social media进行text mining的功能包括
  - monitor product和liability的reaction
  - mine historic liability claim，进而more accurately price similar exposure
  - 保险公司可识别用于build predictive model的attribute和target variable
- 在realistic and complex scenario中，保险公司会和data scientist一起分析data mining，并利用insurance professional knowledge和liability claim的past experience，来确定product liability中的important product attribute
- 从RM perspective来看，保险公司可使用data mining中的valuable information来help customer
- 对social media进行cluster analysis，text mining，以及使用predictive modeling，可帮助保险公司predict claim，进而predict account loss exposure