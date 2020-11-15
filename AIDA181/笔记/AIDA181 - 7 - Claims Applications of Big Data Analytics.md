# 一、使用Network Analysis and Clustering来Detect claim fraud

- data mining的advance对识别fraudulent claim activity的pattern非常有效（effective），保险人员和风管人员可据此了解如何分析social network的link和data point cluster，进而capture claim fraud中的new trend

## 1. Detect claim Fraud

- P&C insurance industry中，(incurred loss + LAE)中的10%都和fraud相关（该部分主要用于claim adjuster对predicted as severe的assignment进行fraud detection）

- 保险公司detect fraud的方法包括
  - identify pattern
  - 在point of sale时，control underwriting
  - 使用special investigation unit (SIU)
  
- ==通过compare social media post和claim statement，claim rep会发现claimant lying（lie）的evidence==
  
  - analyze social media以detect fraud claim practice时，要investigate social media post，也要investigate within network中的connection
  - ==network analysis中的connection会帮助identify fraud ring==
  
- ==detect claim fraud时，data science team主要使用cluster analysis和classification tree==

- 识别fraudulent claim的步骤

  |      | 具体步骤                                                     | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 1    | 保险公司根据traditional fraud indicator建立自己的fraud indicator（own list），也可使用mining social media data | traditional fraud indicator是National Insurance Crime Bureau（NICB）发布的claim fraud indicator list<br /><br />fraud indicator包括insured/ claimant push for quick settlement，或有too much/ too little documentation<br /><br />==traditional fraud indicator是基于historical data建立的== |
  | 2    | ==使用social network analysis，以examine link and suspicious connection and relationship in a network== | ==social network analysis是研究network中的node和edge==       |
  | 3    | 使用cluster analysis，以discover可以indicate fraud的claim characteristic |                                                              |

- ==尽管保险公司会identify fraudulent claim，但仍有很多fraud属于undetected（因为traditional fraud indicator取决于过去已经发生的fraud）==
  
  - intelligent and innovative fraudster会改变其approach和pattern，进而limit indicator usefulness
  - traditional approach通常是highly subjective，并取决于claim rep在field上的experience
  - automated approach会有greater objectivity（客观性），并让new claim rep能在less time中more effective

## 2. Network Analysis的应用

## 3. Cluster Analysis的应用

- cluster analysis可用于根据various attribute来为similar claim创建cluster
  - ==data scientist会使用cluster analysis来improve claim handling process，因为cluster analysis属于explanatory technique，其没有predefined variable（所以cluster analysis中的attribute通常not known in advance）==
- claim instance的cluster会根据claim severity周围的attribute来进行group
- cluster analysis会continue to apply on individual cluster，直到data scientist对significant variable之间的relationship有good understanding
- ==完成cluster analysis后，cluster的characteristic会作为attribute，进而develop classification tree==
  - ==classification tree适用于根据target variable来assign new claim==
- 可使用logistic regression来估算每个outcome的probability，保险公司可据此为每个complex claim确定appropriate resource
- detect fraud claim中，predictive modeling属于long term solution
  - predictive modeling不会increase auto rate，也不会增加investigate fraud claim的resource
- ==对于predictive modeling==
  - ==保险公司可能只有very less historical data来indicate fraud claim==
  - ==由于fraud一直evolving，predictive model会变得quickly outdated，此时需要使用cluster analysis来识别fraudulent claim的new attribute==
    - ==cluster属于unsupervised learning technique==
    - ==在使用predictive modeling前，clustering technique可用于identify new fraud indicator==
  - ==k-means是一种algorithm，其会group claim data into cluster==
    - ==k-means属于unsupervised learning technique==
    - ==k-means适用于没有target variable的情况==
- 从本质来看，fraudulent claim是already outlying cluster的outlier

# 二、在claim assignment中使用Classification Tree Analysis

- ==classification analysis是一种computer recursively，用于分析attribute value的different split==

  - ==computer recursively是用model分析attribute value的different split==

- claim payment是保险公司中biggest financial obligation

  - 一小部分claim的amount会占到保险公司整体费用的一大部分（即某些claim payment非常高，但此类claim的数量很少）

    |                                                              | 案例                                                         |
    | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | ==有些high-cost claim可在first report时识别出来==            | fire引起的building的total loss<br/><br/>major auto accident<br/><br/>plant explosion |
    | ==对于potential complex claim，保险公司很难在first report时确定claim cost== | ==很多claim cost会gradually develop into significant loss<br /><br />WC claim中，大部分（一半以上）cost都是medical cost== |

- lift是model positive prediction percentage除以expected by chance的percentage

- 为了effectively use resource，保险公司和risk manager可使用own data，或使用保险公司或their party data，来识别potentially serious claim

- modeling可用于确定claimant characteristic，进而可确定该人是否有chronic problem或develop opoids/ ovoids problem

## 1. Procedure Overview

- ==在claim handling process中，classification tree适用于根据target variable来assign new claim==

- ==为complex claim创建model的procedure（步骤）==

  | 步骤 | 具体步骤                                                     | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 1    | ==识别complex claim的attribute==                             | -                                                            |
  | 2    | ==根据relative information gain，对attribute进行排序（rank）== | -                                                            |
  | 3    | 确定attribute list（input variable），并根据relative importance进行排序（使用complex claim attribute的information gain） | 在data science team中增加claim professional可帮助select most important attribute |
  | 4    | 使用classification tree说明complex claim的attribute，进而build predictive model | ==various sequence的情况下，computer recursively通过分析attribute value的different split，来build classification tree== |
  | 5    | validate complex claim model                                 | 通过machine learning，model会调整每个attribute的assigned weight，进而better predict accuracy（有new incoming data时，让model仍然effective） |

  - classification tree中的attribute sequence不会严格遵守attribute的information gain rank（因为attribute和information gain raking都是developed independently of other attribute）
  - 但classification tree上每个node代表的attribute都取决于sit above的attribute value
    - combination of node是指classification tree上data attribute的representation

## 2. Complex claim Attribute的Information Gain

- complex claim是包含1+ characteristic的claim，complex claim cost会高于average claim cost

## 3. 使用Classification Tree说明Complex claim的Attribute

- complex claim是包含1+ characteristic，这些characteristic可导致cost大于average claim cost
- 保险公司想把complex claim 在更短时间内分配给有经验的理赔人员，同时给他们足够的资源 (但第一次report的时候很难分辨是否是complex claim)
- information gain是衡量1+ attribute的predictive power
- recursively是Successively applying a model（连续应用模型）
  - computer recursively是为了分析attribute value中的different split
- classification tree中的order并非一定按照information gain的顺序，因为information gain的排序是对每个attribute单独进行分析，但classification tree中每个node都要基于其本身和上层的attribute一起分析。
  - ==root node是classification tree中的第一个node（most informative attribute），属于最重要的information==
  - combination of node是classification tree中的data attribute
- ==lift是在model performance evaluation中，衡量predictive model effectiveness的metrics==
  - ==lift基于model的accuracy和precision==
  - ==lift = (model给出的positive prediction)% / (没有model时（expected by change）的positive prediction)%==
- 开发predict complex claim model的步骤
  - 从training data确定complex claim的attribute
  - 对每个attribute的importance进行排序
  - data science team决定要使用的data analytics技术
  - 根据重要性，确定model中attribute的weight
  - 开发好model后，用holdout data测试。

## 4. Validate Complex Claim Model

## 5. Complex claim Reporting

- complex claim reporting的步骤

  |      | 具体步骤                                                     | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 1    | 通过online或telephone来report claim                          | -                                                            |
  | 2    | 根据geographical location，将claim转给appropriate claim intake | -                                                            |
  | 3    | 如果是catastrophic claim，将其分给senior claim adjuster      | -                                                            |
  | 4    | 使用machine learning algorithm，预测claim type（complex或not complex） | 应根据要使用的modeling technique type，来确定claim type（complex或not complex） |
  | 5    | 使用machine learning，model会调整每个attribute的weight，用以better predict complexity | -                                                            |

# 三、使用Business Process Analytics (BPA)来improve Claim Process

## 1. Procedure Overview

- 保险公司可使用data analytics来improve claim process

- claim handling process分为6个major activity

  |      | 具体步骤                                  |
  | ---- | ----------------------------------------- |
  | 1    | acknowledge and assign the claim          |
  | 2    | identify policy                           |
  | 3    | 联系insured/ insured’s rep                |
  | 4    | investigate and document the claim        |
  | 5    | 确定cause of loss，liability，loss amount |
  | 6    | conclude claim                            |

  ![](https://s1.ax1x.com/2020/11/03/BrjP81.jpg)

- claim handling process会确定how the loss occurred，witness，potential fraud or subrogation opportunity，loss amount

## 2. Business Process Analytics和claim

- 将business process analytics/ BPA用于claim handling process，有助于improve customer service/ efficiency/ cost-effectiveness
- business process management/ BPM是一套systemic/ iterative plan，其通过life-cycle phase来analyze and improve business process，进而achieve long-term goal and client satisfaction
  - ==BPM的目标（goal）是optimize business process (如claim handling process)==
    - ==具体到claim handling中，BPM的目标（goal）是improve claim efficiency/ customer service/ cost-effectiveness==
  - BPM开始于对current process的explanatory analysis，之后为improvement来develop model
- data analysis可用于gather intelligence和develop model

## 3. 将Process Mining应用于claim

- process mining是使用exploratory data analysis，为business process提供insight，并识别potential improvement

  - ==process mining类似于data mining，但在application上有区别==

    | process mining和typical data mining的区别 | 主要适用范围                                  |
    | ----------------------------------------- | --------------------------------------------- |
    | ==process mining==                        | ==关注entire process result==                 |
    | ==data mining==                           | ==只关注specific area（如只关心claim cost）== |

- ==process mining的步骤==

  |      | 具体步骤                                                     | mark                                                         |
  | ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | 1    | ==对claim activity log进行data analysis==                    | -                                                            |
  | 2    | 使用analysis technique来explore existing process相关的data，以理解entire process | ==process mining和typical data mining的区别<br />- process mining适用于entire process<br />- data mining只关注specific area（如只关心claim cost）== |
  | 3    | ==mining claim activity log，以识别claim handling activity及其timing== | ==auto claim中process mining的first phase涉及对claim activity的process discovery（会显示每个activity的起止时间，如reviewed policy indicator）== |
  | 4    | 将得到的information用于design claim activity的classification tree model | classification tree model可用于为claim assignment，fraud investigation，subrogation potential等claim activity来design model |

- process discovery是使用data analysis来识别current process中的activity
  - process discovery适用于为current claim activity来develop process map（如process instance，或each process instance的average duration）
  - ==process instance是business process的discrete activity==

- ==process map是基于process discovery result的process diagram/ process workflow==
  
  - ==通过process map，保险公司可了解到在current claim process中，每个process instance的average time length，并根据claim log设置benchmark==
  - ==通过process map，保险公司可根据internal metrics，为current claim handling process的each activity设定initial benchmark==
- ==完成process map后，保险公司需将process mining和data analysis technique混合（combine）在一起，才能better understand different claim type涉及的investigation和resolution==

## 4. 使用data analytics来improve claim process

- data analysis technique包括classification technique和clustering
  - ==cluster analysis属于exploratory technique，其没有predefined variable，可用于attribute not known的情况，所以cluster analysis可用于improve claim handling process==
- ==在predictive mode时（包括使用data analysis来detect claim fraud时），保险公司应准备好reevaluate attribute==