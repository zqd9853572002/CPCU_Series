# 一、Traditional Data Analysis Techniques

- 大部分保险人员和风管人员不会directly apply data analysis technique

- 大数据和新technique正在扰乱保险业，保险和风管人员应熟悉大数据的概念及分析方法。

  - 了解big data可帮助保险e公司提升competitive advantage，也可让保险人员能够advance career

- traditional data analysis仍很重要（这些technique对现有的保险和风管仍然有效，这些technique也会用于分析大量数据，以及来自非traditional 来源的数据（如social media的数据））。保险和风险管理专业人员应对traditional technique有了解，原因如下：

  - traditional technique在提供information和solve problem问题方面仍然很重要
  - traditional technique是new technique的基础
    - 对于专业人员来说，了解更新的technique，以便能够在团队中与data analyst一起工作，并更好地理解保险的真实情况。

- data analysis有两种主要方法：supervised learning和unsupervised learning

  |                       | 定义                                                         | 案例                                                         |
  | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | supervised learning   | ==supervised learning是machine learning派生出的一种model creation，其定义了attribute和target variable== | 计算个人车险保费时，使用defined variable（age, driving experience, accident record等）来确定defined target variable（车险保费） |
  | unsupervised learning | ==unsupervised learning是一种machine learning中派生出的一种model creation，其未定义target variable，用于explore data，以find relationship，进而用于further analyze== | 为了开发new insurance product，可对social media进行text mining<br /><br />text mining属于unsupervised learning，attribute未知，也没有target variable，model会寻找relationship，之后再进行分析） |

  - 各种technique会有inter-relationship

    > 如通过unsupervised learning获得信息后，可开发predictive model，用获取的信息来进行supervised learning

- analytics和machine learning的combination增加了保险公司predictive modeling的capability

## 1. Exploratory Data Analysis（EDA）

- EDA是一种用于business problem的valuable approach

  - EDA提供的information可为data提供基本的理解，analyst也可获得missing/ inaccurate data的信息
  - 可在develop and test model前使用exploratory data analysis

- EDA technique包括chart，graph等（用以显示data pattern和correlation）

  - develop model前，graph和plot可用于examine relationship

  - EDA包括的chart和graph

    |                        | 解释                                                         | mark                                                         |
    | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | ==scatter plot==       | ==2-dimensional plot of point value==                        | ==可显示2个attribute之间的relationship<br /><br />属于simple data analysis== |
    | ==bubble plot==        | scatter plot的一种                                           | bubble size代表data的第3个attribute                          |
    | ==correlation matrix== | 可先确定几个attribute，并想知道它们是否和target variable有关<br /><br />可开发predictive model来识别最有可能给target variable有贡献的attribute | correlation越强，matrix中cell color越深<br /><br />shade越darker（深），说明这种attribute的组合和结果越相关 |

## 2. data analysis technique

- 完成EDA并确定develop predictive model后，analyst会为model选择most appropriate technique（该technique要fit business context，data type和data source）

- technique在不断发展（evolve），有些常用technique会根据情况进行调整

  | 适用于model的technique              | 定义                                                         | 适用性                                                       | 案例                                                         |
  | ----------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | segmentation                        | Segmentation是将data分成多个category的analytical technique   | supervised learning<br /><br />unsupervised learning         | -                                                            |
  | ==association rule learning (ARL)== | association rule learning是examine data，来discover attribute间的new/ interesting relationship，用以stated as business rule | ==发现variable之间的relationship，以开发出make recommendation的rule<br /><br />association rule learning属于unsupervised learning（unsupervised learning是computer使用多种algorithm寻找large amount of data间的potentially useful relationship，并开发出适用于new data的rule）== | ==人们在网上购物时，online retailer使用association rule learning推荐其他产品==<br />- 如有人买了一本关于电脑的书，零售商很可能会给他发邮件，向他推荐更多的电脑书籍<br />- 同样，当顾客选择了要购买的商品并在结账时，retailer可能会推荐一个类似的商品。<br/><br/>==customer在网上购买auto/ HO insurance时，保险公司使用association rule learning推荐umbrella policy== |

- 大部分technique都会使用machine learning

  - ==machine learning是随着receive additional data或result，computer会继续refine model==
  
- traditional data analysis technique（DAT）对insurance和RM仍很重要，原因如下

  |                                                              | mark/ 案例                                                   |
  | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | traditional 的technique对provide information和solve business problem仍很重要 | 确定insurance product rate<br /><br />设定unpaid claim/ future claim的reserve |
  | traditional technique是newer technique的foundation           | 保险人员应了解newer technique，以便能和data analyst一起工作，也能better understand insurance future |
  | traditional technique可以adapt，也可组合使用（used in various combination） | 可以分析large volume of data或分析来自nontraditional source的data（如social media的data） |

- 保险公司和风管人员会依赖traditional data analysis technique（DAT）来解决business problem（如确定保险产品保费和unpaid claim reserve）

  - traditional data analysis technique适用于internal structured data（如claimant的loss cost和injury type），有时也会使用external structured data（如monthly GDP）

- ==traditional data analysis technique可确定以下outcome type==

  | traditional data analysis technique可确定的outcome type | mark                                                         | 案例                                                         |
  | ------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ==data属于哪个non-numerical category==                  | 属于bucket还是bins                                           | 保险公司想知道车祸是否涉及人身伤害或只是财产损失<br /><br />风管人员想知道雇员是否发生过事故。 |
  | 基于data的numerical answer（model会给出一个value）      | linear regression                                            | 保险公司想分析在线申请时输入的数据，从而决定保费。           |
  | 基于historical data的probability score                  | commercial insurance的catastrophe loss<br /><br />classification tree<br /><br />logistic regression | 风管人员想确定safety solution降低事故frequency的概率<br /><br />保险公司想确定被保险人发生catastrophic loss的概率。 |
  | 基于current data/ past data，预测future result          | decision tree<br /><br />event tree                          | 保险公司想知道一条line的ultimate cost<br /><br />风管人员想预测员工back injury的cost |

- traditional data analysis technique包括classification tree，statistical regression model和cluster analysis

  - 这些technique开始使用machine learning，用以improve result accuracy

### （1）Classification Tree

- ==classification tree是使用similar to tree的structure，根据known attribute来segment data，来确定categorical target variable的value==
  - ==classification tree的training data应当包含target variable的known data==
  - ==classification tree属于supervised learning technique==

- classification tree的内容

  |                | 解释                                                         | mark                                                         |
  | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | node           | node是代表data attribute                                     | -                                                            |
  | arrow          | arrow是classification tree中的pathway                        | -                                                            |
  | ==leaf nodes== | ==leaf node是classification tree上的terminal node（end node）<br /><br />leaf node可根据attribute 来classify instance，进而表明target variable（target model）的classification== | ==可确定target/ output variable/ probability/ classification的value<br /><br />target variable会以leaf node结束== |

- 每个sample的attribute将跟随arrow穿过leaf node，这些leaf node根据attribute将数据分割到一个ultimate leaf node

  > 如标记为return to work或not return to work

- ==classification tree中的classification/ category不一定是actual outcome==

- ==可使用machine learning，对classification tree model进行continually improve==

### （2）Regression Model

- ==当需要知道target variable的numerical value时，需要用到regression==
  - regression是使用math function创建algorithm
  - ==algorithm是用于解决数学问题并创建computer program的operational sequence==

### （3）Cluster Analysis

- ==cluster analysis是确定previously unknown grouping of data的model==
- ==cluster analysis属于unsupervised learning==
- ==cluster analysis适用于已经知道want to solve的general problem，但不知道需要which variable it must analyze to do so的情况==
  - 可开发模型来分析dataset，结果可能是围绕explanatory variable的某个特定值
- cluster analysis获得的information可用于开发predictive model，model也可使用其他supervised learning

## 3. association rule learning

- association rule learning是examining data，以发现attribute间的new relationship，进而state as business rule，包括develop make recommendation的rule

  > 人们在网上购物时，retailer常使用association rule learning推荐其他产品。如有人买了一本关于电脑的书，零售商很可能会给他发邮件，向他推荐更多的电脑书籍。同样，当顾客选择了要购买的商品并在结账时，retailer可能会推荐一个类似的商品
  >
  > 客户在网上购买汽车保险和房屋保险时，保险公司可使用association rule learning推荐umbrella policy

- association rule learning属于unsupervised learning
  
  - unsupervised learning是computer使用各种algorithm，以发现large amount data间可能有用的关系，并开发可用于new data的rule

## 6. new data analysis technique

- data analytics会处理large volume/ rapidly increasing velocity的data

- new technology产生的data通常属于unstructured data，所以需要new technique来analysis

  > 人工智能/ AI是计算机的processing或output模拟human reasoning或knowledge，其可对visual image data和auditory source data进行更好的分析

- new data analysis technique包括text mining，social network analysis，neural network

### （1）text mining

- text mining是从language recognition中获取information

- text mining随着互联网和social media的增长而变得更加普遍

- text mining model比分析其他数据的model更复杂（complicated，因为没有organized field，也没有numerical value）

  > 如对claim adjuster note进行分析

- text mining approach包括

  |                            | 案例                                                         |
  | -------------------------- | ------------------------------------------------------------ |
  | 搜索既不rare也不common的词 | -                                                            |
  | 查找adjacent word          | 如果serious和injury两个字放在一起，则很有可能说明claim severity |

### （2）social network analysis

- ==social network analysis是研究network中people之间的connection和relationship（即研究network中的node和edge）==

- social network analysis可用于

  |                                               |                                                              |      |
  | --------------------------------------------- | ------------------------------------------------------------ | ---- |
  | 找出social network中的preference或association | 网页中蹦出的广告基于人的兴趣算出（根据社交网络的preference或association） |      |
  | business network setting                      | 如email traffic between people，links between webpage        |      |
  | 识别claim fraud ring                          | -                                                            |      |
  | 预测fraud probability                         | -                                                            |      |

### （3）neural network

- neural network是按人脑的方式从data pattern推断rule，然后构造用于分析的logic，用于解决complex problem

- neural network属于data mining中的新technique

- neural network会产生一个包含layer of node的模型，node之间有weighted link

  - neural network由3个layer组成

    | neural network的3个layer | mark                  |
    | ------------------------ | --------------------- |
    | input layer              | -                     |
    | hidden layer             | 有non-linear function |
    | output layer             | -                     |

  - neural network可在input和output variable中建立复杂的关系

- neural network technique适用于supervised learning和unsupervised learning

- ==neural network的缺点==
  
  - ==neural algorithm建立的rule和logic是不透明的（opaque）==
  - ==很难解释从weighted link中获取的信息==
  
- neural network的无限可能性导致学术界和business努力改进开发和处理相关的计算机软件

# 二、Classification Tree

## 1. Classification Tree Model

- classification tree是通过induction process建立的

  - 在training data中，computer会根据attribute value的different split的various sequence，来recursively analyze
    - recursively是Successively applying a model（连续应用模型）
    - ==computer recursive适用于分析attribute value中的different split==
  - 之后会将classification tree适用于holdout data，以查看其是否能generalize（即使用holdout data来make accurate prediction）
  - classification tree可能会overfit the training data（无法产生useful result），此时需要pruned

- ==develop classification tree model时，需independently analyze各种attribute，进而获得classifying中的information gain==

  - classification tree中的order并非一定按照information gain的顺序，因为information gain的排序是对每个attribute单独进行分析，但classification tree中每个node都要基于其本身和上层的attribute一起分析

- 相关概念

  |                     |                                                              | mark                                                         |
  | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | information gain    | information gain是衡量一个或多个attribute的predictive power  | -                                                            |
  | ==root node==       | ==root node是classification tree中的第一个node（最重要的information，most informative）== | ==确定target variable value时，root node可提供greatest information gain== |
  | combination of node | combination of node是classification tree中的data attribute   | -                                                            |
  | lift                | lift是在model performance evaluation中，用于衡量predictive model effectiveness的关键指标<br /><br />lift基于model的accuracy和precision | $\cfrac{(model给出的positive\ prediction) \%}{(没有model时(expected\ by\ change)\ 的positive\ prediction)\%}$ |

- classification tree在claim中的案例

  ![](https://s1.ax1x.com/2020/10/31/BdSFqH.jpg)

  ![](https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1890907/zUfL6sF3H_sDifoYfhJ2YVLmJTc/medium_IMG_9361.JPG)

## 2. Classification Rules

- 每个classification rule都由classification tree上的leaf (attribute) node来表示

## 3. Probability Estimation Tree

- 为了获得more information，predictive model的user会想知道new instance的predicted class，以及correctly classified的likelihood/ probability
  - 此类information可帮助user做cost-benefit analysis
  - ==classification tree可用于estimate class probability==
- ==tree-based class probability estimation是使用construct classification tree的data，通过使用logistic regression，来estimate probability==

- ==tree-based probability的公式==

  $tree-based\ probability = \cfrac{model\ correctly\ predict\ target\ variabl\ value的次数}{each\ leaf\ node的total\ prediction}$

# 三、Linear Function

- linear function是一种mathematical model，其中一个variable的change和另一variable的change呈direct proportion（直接相关）

- regression analysis是一种statistical technique，其用于estimate variable之间的relationship

- instance space是描述instance distribution的area（包括2+ dimension）

  |              | instance space的表现形式                                     |
  | ------------ | ------------------------------------------------------------ |
  | 2 dimension  | x-y graph                                                    |
  | 2+ dimension | 3-dimensional cube<br /><br />discriminant会是一个plane，而非一条line |

## 1. Linear Discriminant

- ==linear discriminant是一种data analysis technique，其使用一条line，将data分为两个class（用于separate and classify data）==
  - ==linear discriminant的target variable结果是分组（class）==
  - linear discriminant line可以是任何angle（用以separate class）
  - 可通过model的accuracy和precision来衡量miss-classification
- linear discriminant会包含line两侧classifying data的margin
- ==Support Vector Machine/ SVM是用于increase linear discriminant的accuracy==
  - SVM会对linear discriminant line的两侧增加margin
    - 在选择linear discriminant的optimal angle时，SVM使用mathematical equation来maximize margin
    - SVM可增加linear discriminant在separate class方面的accuracy，之后保险公司可使用optimized linear discriminant来create rule to predict

## 2. Linear Regression

- ==linear regression是一种statistical method（algorithm），其基于explanatory variable的value，来预测target variable的numerical value（或两个attribute间的ratio）==

  - 可使用averaging method来预测target variable的average output value
  - ==target variable是在data analytical model中，being predicted的predefined attribute==

- linear regression使用minimize the error method（即计算target variable的actual value和forecast value之间的difference）

- ==linear regression是一种linear function，其会预测target variable的numerical value==

- ==linear regression假设predicted value和attribute value成线性关系（linear relationship/ proportionately relationship）==

- linear regression是计算一条可以best fit observation的line，以预估attribute variable和target variable之间的mean relationship

  - error是dot和line之间的vertical distance（即error是target variable observed value（dot）和line estimated mean value之间的difference）
  - calculate regression line的objective（目标）是minimize total error
    - least square regression是一种common algorithm，其根据actual observed value和estimated value（mean）的difference，来minimize sum of the squared error（SSE）
    - 相较于close to line 的value，square error会增加远离line的value的penalty

- 在2-dimensional graph上，linear regression的图形也是一条直线（和linear discriminant一样），但linear regression和linear discriminant有区别

  |                         | ==linear regression和linear discriminant的区别==             |
  | ----------------------- | ------------------------------------------------------------ |
  | ==linear discriminant== | ==linear discriminant是一种data analysis technique，其使用一条line，将data分为两个class（用于separate and classify data）== |
  | ==linear regression==   | ==linear regression是根据1+ attribute variable（explanatory variable），来预测target variable的numerical value== |

### （1）Multiple Regression

- ==multiple regression是linear regression的variation，其涉及2+ attributes (explanatory variable)==
  - ==预估target variable value时，每个attribute会根据其对target variable value的influence，获得相应的weight==

### （2）Linear Model的缺点

- Linear Model的缺点

  |                              | 解释                                                         | 现实                                                         |
  | ---------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | normal distribution          | linear model假设variability（由model error衡量）和variance围绕在target variable的estimated mean周围，且呈normal distribution（即遵循standard symmetrical patter） | P&C insurance data中，mean周围的variability不是normally distributed |
  | Homoskedasticity（同方差性） | linear model假设有Homoskedasticity<br /><br />Homoskedasticity是不管size大小，围绕在target variable mean周围variability都是一样的 | P&C insurance data中，mean周围的variability通常会随size变化  |

## 3. Generalized Linear Model (GLM)

- ==generalized linear model/ GLM是将linear regression与non-linear function连接起来，进而增加linear model的flexibility==

  - ==GLM属于supervised learning==

- GLM适用于more complex data classification（如P&C公司的insurance business） 

- GLM和general linear model有区别

  - general linear model是一组不同类型的linear model

- GLM包括三个部分（random component，systematic component，link function）

  |                      | 解释                                                         | mark                                                         |
  | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | random component     | random component是response variable的probability distribution<br /><br />random component通常是exponential distribution（而非normally distributed）<br /><br />variability/ variance服从exponential distribution | random component的exponential distribution可以克服（overcome）linear model中，random component属于normal distribution的问题<br /><br />可以克服（overcome）homoskedasticity problem |
  | systematic component | systematic component是描述explanatory variable (attribute)间的linear combination | -                                                            |
  | link function        | link function是一种mathematical function，用于描述target variable的random value取决于explanatory variable linear combination产生的mean value<br /><br />link function定义了linear model的estimated mean value和围绕在mean周围的target variable之间的variability关系（random component） | 将random component和systematic component联系起来             |
  
- 估计auto frequency时，通常使用各种explanatory variable（如miles driven, driver experience）作为systematic component来建立linear model

  - linear model通过link function和poission distribution（作为random component）连接

- poission distribution是在fixed time period中，建立independent event的probability，通常用于建立claim frequency的probability distribution

## 4. Logistic Regression（logit regression）

- Logistic Regression是一种generalized linear model (GLM)，其predicted value是probability
  - ==logistic regression可用于accomplish class probability estimation==
  - ==当target variable是binary时，需使用logistic regression==
- logistic regression会根据event occurring的odds logarithm（log odds/ logit）来建立link function
- event occurring odds是event occurring probability除以event not occurring probability

# 四、Cluster Analysis

## 1. Cluster Analysis

- ==cluster analysis是用于explore data，并discover previously unknown information or relationships==
- ==cluster analysis属于unsupervised learning==
- ==cluster analysis的several iteration（迭代）适用于subdivide cluster，进而可以provide more granular information==

## 2. Hierarchical Clustering (分层)

- ==Hierarchical Clustering是根据similarity，对multiple cluster进行group的modeling technique==
  - similar attribute由circle within circle（大圈套小圈）表示
    - big circle说明最大的similarity
    - small circle说明additional similarity
- dendogram是说明hierarchical clustering group的diagram
  - cluster之间的distance说明了两个cluster之间的similarity（how similar）
- ==cluster会先在一个hierarchy level上进行group，remain cluster会在higher level上进行group==

## 3. K Nearest Neighbors（KNN） clustering Algorithm

- ==KNN是一种voting method，其根据similar group的historic data point，来预测future target variable==
  - 如果nearest neighbor是most similar，则其会有greatest weight
  - ==可根据voting method来make decision==
    - ==voting method/ KNN不会预测outcome probability==
- ==k越大，prediction会more accurate==
- 除voting method外，还可使用average method（会计算likelihood的average或probability）

## 3. K-Means Clustering Algorithm

- ==k-means是一种algorithm，其会group data into cluster==

  |       | 解释                        | mark                                                         |
  | ----- | --------------------------- | ------------------------------------------------------------ |
  | k     | ==k是cluster number==       | -                                                            |
  | means | ==means是cluster centroid== | ==centroid是cluster center，其是每个cluster中instance的average value== |

- characteristic point周围的clustering，提供了不同cluster的attribute，用以distinguish instance

## 4. Describe Clusters

- ==可用两种方法来描述cluster： differential description和characteristic description==

  |                                | 解释                                                   | 案例    |
  | ------------------------------ | ------------------------------------------------------ | ------- |
  | ==differential description==   | 描述cluster中某个instance和其他cluster之间的difference | k-means |
  | ==characteristic description== | 描述cluster的typical attribute                         | -       |

- k-means和hierarchical clustering的区别

  |                         | 区别                                                         | mark                                      |
  | ----------------------- | ------------------------------------------------------------ | ----------------------------------------- |
  | k-means                 | characteristic point周围的clustering，提供了不同cluster的attribute，用以distinguish instance | k-means代表differential description<br /> |
  | Hierarchical clustering | Hierarchical clustering是根据similar attribute来进行group    | -                                         |