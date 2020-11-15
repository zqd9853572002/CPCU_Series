# 一、Modeling中的basic concept

- 保险公司（underwriter和actuary）依赖mining technique来做出more informed underwriting/ claim/ marketing decision
- 将raw data transform into more useful something中，data modeling是关键
- 理解basic modeling term和model type，可帮助保险人员和风管人员能够effectively communicate with data scientist，以便于create model that will benefit the insurance industry
- 在data mining process中，modeling是data的representation，之后可使用该representation来define and analyze data
  - modeling data是一个complex process，其会使用machine learning and statistics concept
  - actuary和data scientist会基于available data和particular goal来选择appropriate method

## 1. Supervised learning 和 Unsupervised Learning

- data mining technique中，有两种来自于machine learning method，可用于find large dataset的pattern

  |                       | 定义                                         | challenge<br />缺点               | 用途                                                         | 来源                                              |
  | --------------------- | -------------------------------------------- | --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------- |
  | supervised learning   | supervised learning是定义了target variable   | challenge在于target周围应当有data | -                                                            | 来源于machine learning field的model creation type |
  | unsupervised learning | unsupervised learning是未定义target variable | 有时会提供meaningless correlation | ==在supervised learning前，可使用unsupervised learning进行pre-process data into group，进而为define supervised learning的appropriate target提供information== | 来源于machine learning field的model creation type |

## 2. Descriptive Modeling和Predictive modeling

- 两种modeling technique： descriptive model和predictive model

  |                       | 定义                                                         | 用途                                         | 案例                                               |
  | --------------------- | ------------------------------------------------------------ | -------------------------------------------- | -------------------------------------------------- |
  | ==descriptive model== | ==descriptive model是用于study/ find data relationship的model== | 用于gain insight                             |                                                    |
  | ==predictive model==  | ==predictive model是通过确定的（defined）target variable，来predict unknown outcome== | ==用于predict future/ present/ past的value== | ==calendar year结束后，预测claim的ultimate value== |

- modeling technique中的term

  | modeling technique中的term  | 定义                                                         |
  | --------------------------- | ------------------------------------------------------------ |
  | Attribute                   | attribute是在model中describe instance characteristic的variable |
  | instance<br /><br />example | instance是在model dataset中，由a set of attribute描述的data point的representation |
  | Target Variable             | ==target variable是data analytical/ predictive model中，being predicted（被预测）的predefined attribute== |
  | Class Label                 | class label是model中target variable的value，如variable binary |

## 3. Algorithm（算法）

- ==保险公司选择好business model的business objective和analyzed data后，要选择algorithm==
- ==algorithm是用于solve problem或complete process的一系列step==
- ==algorithm和model有区别（严格来说，两个词不能interchangeably use）==
- machine learning algorithm有多种form（如mathematical equation，classification tree，clustering technique等）
  - experienced actuary和experienced data scientist应具备为particular problem选定appropriate algorithm的experience

## 4. Entropy（熵）

- information gain是衡量1+ attribute predictive power的measure

  - information gain是衡量how much if affect the entropy of a given dataset
  - information gain是how it provide about target variable的indication
- entropy是dataset disorder的measure（衡量值），entropy适用于衡量how unpredictable is
  
  - 根据informative attribute对dataset进行segment时，information gain和entropy的关系
  
    | information gain          | entropy  |
    | ------------------------- | -------- |
    | ==high information gain== | ==减少== |
    | ==low information gain==  | ==增加== |

## 5. Lift和leverage

- Lift 和Leverage可帮助保险人员和风管人员evaluate predictive model，并知道predictive model的reliability（how reliable）

### （1）lift

- ==lift是在model performance/ model value evaluation时，用有model的positive prediction percentage除以没有model（by chance时）的positive prediction percentage==

  $lift = \cfrac{Positive\ Percentage\ with\ model}{Positive\ Percentage\ without\ model}$

  > Percentage with model = 50%
  >
  > Percentage without model = 20%
  >
  > $lift = \cfrac{50\%}{20\%} = 2.5$

- lift可帮助确定model给business带来的value

### （2）leverage

- leverage是examine两个outcome的difference

  - leverage属于model accuracy的alternate measure

- 在model performance evaluation中，leverage是model positive prediction percentage减去without model positive prediction percentage

  - ==$leverage = Positive\ Percentage\ with\ model - Positive\ Percentage\ without\ model$==

    > Percentage with model = 50%
    >
    > Percentage without model = 20%
    >
    > $leverage = 50\% - 20\% = 30\%$

# 二、Similarity and Distance

- Unsupervised data mining会search similarity（其会成为predictive model的basis） 
  - 可通过instance（example）之间的distance（通过identify through data point），来找到most popular instance
- find similar data对business非常valuable（根据nearest neighbor and link prediction的concept，可以predict behavior and information flow）
- data modeling的目标（objective）是找到data point（instance）之间的similarity
  - 确定significant similarity时，非常subjective

## 1. Similarity and Distance的衡量

- ==在data mining context中，similarity是衡量两个instance data point之间的distance==

  | distance | similarity degree |
  | -------- | ----------------- |
  | small    | high              |
  | large    | low               |

### （1）Nearest Neighbors

- ==在data mining concept中，nearest neighbor是data model中的most similar instance==

- ==k nearest neighbor (K-NN, KNN) 是一种algorithm==

  - ==k是代表graph上，nearest neighbor plot的number（used neighbor的number）==

- combination function是指2个function进行combine，形成一个new function

  |                                                              | 定义                                                         | 解释                                                         | mark                                                         |
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | majority class function<br /><br />majority combining function | major nearest neighbor value会predict target variable的class label | ==为all nearest neighbor赋予equal weight<br /><br />不考虑distance（不管instance到average data point是否有equal distance）== | -                                                            |
  | weighted average                                             | ==weighted average会根据distance，为nearest neighbors’ contribution赋予不同的weight== | 为计算contribution，会对每个distance amount进行squared，之后计算倒数（reciprocal），得到similar weight。之后对similarity weight进行weighted，以便于each other的和为1，从而得出contribution amount<br />- 如为计算每个claim 的probability estimate，1是yes，0是no | ==相较于simple majority combining function，weighted average可提供more accurate estimate（因为在weight nearest neighbor contribution时，会考虑nearest neighbor的distance）== |

### （2）在network中衡量Similarity

- similarity不一定总按graph上的distance来衡量

  - 可通过examine network connection来衡量similarity

    > 保险公司可以examine social network，并基于similarity来获得customer information（gain information）

- ==在link prediction中，model通过衡量两个instance间的similarity的方式，来predict a pair of instance==

- centrality measure可用于measure connection，centrality measure包括如下

  |                          | 定义                                                         | mark                                                         |
  | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ==degree count/ degree== | ==在social networking scenario中，degree count/ degree是计算有多个人connected to a person== | -                                                            |
  | closeness measure        | closeness是衡量这些人到central person的distance（即相互之间的similarity） | ==说明information能以多快的速度（how quickly，speed）在人群中travel== |
  | betweenness              | betweenness是衡量person connect other的extent                | 在social network中，friend之间通常有high degree of betweenness |

## 2. Similarity and Distance的应用

- similarity and distance可帮助企业understand customer和predict behavior（prediction对planning resource非常有用）

- ==使用nearest neighbor algorithm的步骤==

  | 步骤 | 具体步骤                                                     |
  | ---- | ------------------------------------------------------------ |
  | 1    | ==确定哪些attribute是desirable risk==                        |
  | 2    | compile一份indicate desirable risk的general attribute list（common attribute list） |
  | 3    | 使用majority combining function（nearest neighbor's majority values会predict target variable的class label） |
  | 4    | 计算weighted average                                         |

# 三、Predictive Model的Training和 Evaluating

- predictive model implementation是通过帮助define target market/ increase policy price point number/ reduce claim fraud的方式，帮助improve保险公司的marketing/ underwriting/ claim service的consistency and efficiency

- 很多公司使用predictive model（通过defined target variable来predict unknown outcome）来guide future business decision

  | predictive model对保险公司consistency和efficiency的作用 | 具体作用                     |
  | ------------------------------------------------------- | ---------------------------- |
  | marketing                                               | 准确定位market               |
  | underwriting                                            | 增加policy price point的数量 |
  | claim                                                   | 减少claim fraud              |

- 企业对依赖predictive model持谨慎（cautious）态度（这属于understandable）

  - 在develop predictive model时，企业会评估model的effectiveness/ specificity和reliability/ sensitivity

- 企业可使用model来确定risk的likelihood

- training model和evaluate model的流程（process，步骤）

  | 步骤 | 所属阶段                                   | 具体内容                                                     |
  | ---- | ------------------------------------------ | ------------------------------------------------------------ |
  | 1    | training model                             | obtain data<br /><br />将data分为training data和holdout data |
  | 2    | training model                             | 使用training data来build model                               |
  | 3    | training model<br /><br />evaluating model | 将model适用于holdout data（必要时使用cross-validation）      |
  | 4    | evaluating model                           | 使用performance metrics来评估model<br /><br />为第2步提供feedback |
  | 5    | evaluating model                           | 将model放入production（必要时reevaluate model）              |

## 1. Training Model

### （1）Training Data

- ==training data是用于train predictive model的data，所以必须知道target variable的value（known value）和class label==
  - ==target variable是在model中being predicted predefined attribute==
  - ==class label是model中target variable的value==
- ==model success取决于predictive model中的attribute selection（attribute selection会进行多次fine-tuned (微调)）==
  - attribute是描述model中instance（也称为sample，data set中一组描述数据点
  - 如果使用了过多attribute，model可能会overfit to the training data
  - ==overfit是将model fit too closely to the training data（model overly tailored to training data），以至于model对其他data无效（no effectiveness）==
- 为了accuracy，model必须complex enough（过少attribute无法准确描述，过多使用attribute会导致模型overfit），但如果model过于复杂(即overfit)，则其准确性将无法用于training data之外

### （2）Holdout Data

- ==holdout data是training data中保留的数据（与training data一样，holdout data也有model target variable的known class label），用于test predictive model==

  - ==对predictive model使用holdout data的目标是，确保predictive model在未用于model development的data上表现依然良好，从而帮助确保model没有overfitted to training data==
  - holdout data可用于检验两个变量间的correlation是否显著（significant）或异常（anomaly）

- 若holdout data 可展示出predictive model中两个变量的相关性，则说明model可以generalization（模型可在training data外使用）

  - generalization是指model用于training data之外的data的ability（即泛化，model应当具有complexity）

- model complexity和error rate的关系

  ![](https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1888539/gET7psl7y_AqB41oC0mpL1iogCc/medium_File_003__35_.jpeg)

### （3）Cross-Validation

- 有时，使用holdout data也无法确保model能很好地用于生产环境可使用cross-validation解决这个问题

- ==cross-validation是将available data split into multiple fold，然后使用不同的data fold来train model并完成holdout test==

  - 所有的data都以两种方式使用，predictive model也可使用多种方式开发，从而允许开发人员选择perform best的version
  - 之后再用全部dataset对selected model进行training

- cross-validation的结果是所有的data都用于model training和holdout testing，且通过多种方式来develop predictive model（使得developer可选择perform best的predictive model version，之后可使用entire dataset来train model）

  ![](https://s1.ax1x.com/2020/10/31/BUkQts.jpg)

- ==使用cross-validation的原因==

  - ==model在holdout data上的performance不足以sufficiently reassure其能perform well in production==
  - ==available training data is very limited，使得developer认为只用部分data做training（另一部分data做holdout data）属于unwise（model developer认为不需使用某些数据）==

## 2. evaluating model

- 使用predictive model前，企业应评估model对untrained data的effectiveness
- training and testing process结束后，企业将model放入production后，应持续进行evaluation，以评估model对new data的true effectiveness

### （1）Performance Metrics

- 可使用多种metrics来评估model performance

- ==performance metrics可理解为confusion matrix（其代表predictive model在dataset上的result）==

- 对categorical class label 的 Performance Metrics（以下evaluation method对于predict categorical class label的model非常有用）

  |           | 用途                                                         | 公式                                                         | 具体公式                                                     |
  | --------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | accuracy  | accuracy是衡量how often the model predict the correct outcome（衡量model多久有一次correct predict）<br /><br />简化的方法 | $\cfrac{correct\ prediction}{ total\ prediction}$            | $\cfrac{TP + TN}{TP+TN+FP+FN}$                               |
  | precision | precision是衡量model的success（而非accuracy）<br /><br />不看model的total result<br /><br />==只衡量positive result==<br /><br />比accuracy更能衡量模型的成功率 | $\cfrac{correct\ positive\ prediction}{total\ positive\ prediction}$ | $\cfrac{TP}{TP+FP}$                                          |
  | Recall    | Recall是衡量model在catch positive result方面有多好           | $\cfrac{correct\ positive\ prediction}{correct\ positive\ prediction + negative\ prediction}$ | $\cfrac{TP}{TP+FN}$                                          |
  | F-Score   | ==F-Score是将precision和recall相结合（precision和recall的harmonic mean）<br /><br />最常用（较流性）<br /><br />要先计算precision和recall== | 先计算Precision和Recall，再计算F-score                       | $\cfrac{2 \times Precision \times Recall}{Precision + Recall}$ |

- ==TP，TN，FP，FN==

  |                     | 解释                                |
  | ------------------- | ----------------------------------- |
  | TP（True Positive） | TP是model correctly predict “yes”   |
  | TN (True Negative)  | TN是model correctly predict “no”    |
  | FP (False Positive) | FP是model incorrectly predict “yes” |
  | FN (False Negative) | FN是model incorrectly predict “no”  |

- ==TP，TN，FP，FN的案例==

  > |            | Predicted Yes | Predicted No | total |
  > | ---------- | ------------- | ------------ | ----- |
  > | Actual Yes | 40 (TP)       | 10 (FN)      | 50    |
  > | Actual No  | 5 (FP)        | 945 (TN)     | 950   |
  >
  > - accuracy = $\cfrac{TP + TN}{TP+TN+FP+FN}$ = 0.985
  > - precision = $\cfrac{TP}{TP+FP}$ = 0.889
  > - recall = $\cfrac{TP}{TP+FN}$ = 0.8
  > - F-Score = $\cfrac{2 \times Precision \times Recall}{Precision + Recall}$ = 0.842

- ==evaluate predictive model中，F-score最常用（common），因为其同时考虑了precision和recall==

- 案例

  ![](https://phaven-prod.s3.amazonaws.com/files/image_part/asset/1888542/KICO1IX-a0dA2DgR5KJ1E6VagPw/medium_File_005__29_.jpeg)

## 3. 将model放入production（生产环境）

- model移入production（日常运营）后，training process仍会继续（no end，只是证明了model value）
  - 如果model prediction无法guide good business decision，则应reevaluate model
- 由于situation change，所有predictive model都不能indefinitely make accurate decision
  - 当发生重大的economic/ technology / culture change时，应与data scientist或actuary合作，update prediction model并对其进行re-train，从而提供better result
- understand modeling concept and term可帮助use data modeling across the industry（而非只用在marketing context）

- ==examine model result时，保险人员和风管人员应当defer to（遵循）their professional experience==

  - ==如果model result not make sense，则说明model可能overfit或not complex enough==
  - 保险人员和风管人员应意识到model的limitation（model可能会too complex或not complex enough），其必须frequently reevaluate model

- data scientist使用similarity/ distance/ nearest neighbor/ link prediction来forecast behavior and trend
