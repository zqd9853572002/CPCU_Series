# 一、Text Mining

- text mining是通过language recognition来获取信息
  - text analysis model比其他model更复杂，因为text属于unstructured data，且text可能包含unorganized field或non-numerical value
  - text source包括claims files, social media posts, news stories, consumer reviews等（unstructured data可以来自internal data或external data）

- 分析text mining result时，可使用traditional modeling或newer modeling technique

- text是unstructured data，必须clean up并将text转换成structure data后，才能用于model

  - 应当了解text mining的process，进而来了解text mining的challenge and benefit

- 为将modeling algorithm用于text，text必须使用algorithm可以recognize的方式进行处理（如giving numerical value）

  - 各种文字材料对computer或algorithm来说无意义，所以必须对其进行预处理（preprocess）以解决各种语法标点问题，及同义词含义（synonyms）

    > 如将text转换成每个单词的出现次数（该过程称为结构化，即将unstructured data（text）转化为structured data（number）），之后再用高级统计技术进行分析

  - algorithm是一系列用于解决数学问题或create computer program的operational sequence

- natural language processing/ NLP是使用语言学（linguistics）来理解speech或阅读文档

  - NLP属于text mining一部分

  - NLP可用于获取每个字的意思，继而帮助计算机学习context

  - NLP对某些应用非常关键，如sentiment analysis和robot

    |                    | 定义                                                         | mark                                                         |
    | ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | sentiment analysis | ==sentiment analysis是通过衡量something/ product或behind text的opinion的方式，来确定text要表达的positive/ negative/ neutral的opinion/ emotion== | opinion是unstructured social data<br /><br />sentiment analysis会为每个term赋予positive/ negative/ neutral value，并将这些value相加，得出sentiment score |
    | robot              | robot可以自动执行claim process/ 阅读不同语言的文件/ 挖掘public information（后者在obtain public information以评估supply chain risk方面非常有用） | -                                                            |

- semantic network是显示concept之间的logical relationship

  - semantic network的优点是，在某些text mining situation（特别是large amount of data和limited amount of time的situation）中，可以skip pre-processing step，进而让computer自己在unstructured data中寻找meaningful word，具体方法包括
    - 创建一套linguistic rule，可以automatically process text，其结果就是semantic network
    - 使用neural network
      - neural network是会replicate human brain的process
      - neural network在linguistic setting方面有缺陷

- text mining可用于其他风管领域

  > 从potential fraudulent claim中挖掘worker compensation data
  >
  > 从social media中确定sentiment level以评估声誉风险等

- ==可使用confusion matrix来展现text mining model result，进而可以calculate performance metrics==

  - ==confusion matrix是显示model的predicted result和actual result==

- ==text mining的步骤（process）==

  |      | text mining的步骤（process）                              |
  | ---- | --------------------------------------------------------- |
  | 1    | ==retrieve and prepare text（使用preprocess technique）== |
  | 2    | 从unstructured data create structured data                |
  | 3    | 使用data mining technique create model                    |
  | 4    | evaluate text mining model                                |

## 1. Retrieve data and Prepare Text

- retrieve data 和 prepare text的步骤

  | 步骤 | 具体步骤                            | mark                                                         |
  | ---- | ----------------------------------- | ------------------------------------------------------------ |
  | 1    | collect corpus                      | ==corpus是collection of writing/ document==<br />- 每个document都由various word组成（term token）<br /><br />token是指meaningful term或group term |
  | 2    | preprocess corpus                   | text cleaning<br /><br />remove punctuation/ spaces/ numbers（这一步取决于context)<br /><br />==stopword是指只有little meaning的common word，所以要在text mining context中filtered out/ ignored== |
  | 3    | remove abbreviation（去除各种缩写） | -                                                            |
  | 4    | stemming                            | 去除各种suffix                                               |

## 2. 从Unstructured Data create Structured Data

- 可以extract key term，并将其放入table/ spreadsheet，转化为structured data

- ==term frequency是衡量how often a term appear in a document==

  - 可对term frequency设定upper bound和lower bound，进而只分析fall in inner bound之内的term

- inverse document frequency/ IDF是根据document出现在corpus的次数，来衡量term在corpus document中的term significance（term rarity）

  - $IDF = 1 + \log(\cfrac{total\ document\ number}{包含term的document\ number})$

    | IDF值 | term多少   | term significance | document significance |
    | ----- | ---------- | ----------------- | --------------------- |
    | IDF高 | 少（rare） | 高                | 高                    |
    | IDF低 | 多         | 低                | 低                    |

## 3. 使用Data Mining Technique create model

- 为将modeling algorithm应用于text，text必须按照algorithm可以recognize的form来显示（如为text给出numerical value）
  - 为create and apply rule for new document 时，可使用nearest neighbor或classification learning technique
  - 缺点包括
    - overfit with too many word list used in model
    - same word的different variation
- 使用classification technique来define probability后，应根据appear in document的probability，使用linear score method为每个term赋予weight。final document就是final score（即indicate fraud的probability）

## 4. 评估Text Mining Model

- confusion matrix是会显示model的predicted result和actual result

- 评估text mining model时，可使用confusion matrix来计算metrics

  ![](https://s1.ax1x.com/2020/11/02/BBCwb8.jpg)

# 二、Social Network Analysis

- 每个人都是social network的一部分
  - scientist已经研究network effect方面的psychology and disease很多年
  - 随着social media prevalence，现在有更多地network connection

## 1. Social Network Analysis简介

- social network analysis是研究network中的node（vertices）和edge（line），类似研究individual和其他人的link和influence（in business word）

- network graph中的元素

  |                  | 代表的涵义                           | mark                                                         |
  | ---------------- | ------------------------------------ | ------------------------------------------------------------ |
  | graphic          | graphic是指social network            | -                                                            |
  | node（vertices） | node是代表network中的vertex或point   | -                                                            |
  | ==edge（link）== | ==edge是一条line，代表relationship== | arrow可用于区分connection是否是only one direction<br /><br />weighted edge（thicker/ thinner line）显示connection的strength或frequency<br /><br />directed tie是network graph中的edge（有direction），可用arrow代表（可以是reciprocated或not reciprocated） |

- ==social network analysis会研究node和point的attribute information，以及data point如何relate to each other in the network（即研究network中的node和edge）==

  > claim adjuster使用social network analysis来trace links among the various individual

- ==social network分为sociogram和matrix==

  |               | 定义                                              | mark                                                         |
  | ------------- | ------------------------------------------------- | ------------------------------------------------------------ |
  | ==sociogram== | ==sociogram是在分析small social network时很有用== | 在office的co-worker中的email communication<br /><br />==sociogram可帮助理解sentiment spread，进而确定target response== |
  | ==Matrix==    | ==matrix是在分析large social network时很有用==    | large network的sociogram可能会很快变得difficult to follow，所以最好通过matrix来分析larger social network<br /><br />matrix是通过social network analysis中的row and column来表示data |

- 分析network时，可使用data mining technique（如supervised learning，unsupervised learning（如clustering）等）

- observe social network connection的method包括Link Analysis，Social Network Metrics和Network Classification

## 2. Link Analysis

- link analysis是network analysis中的key concept
- link prediction是trying to predict a pair of link的process
  - ==similarity是link prediction的basis==
  - measure similarity可让保险人员和风管人员分析group和或potential customer的group，并能observe trend
- 保险公司使用social media时，必须小心privacy concern

## 3. Social Network Metrics

- path是描述something在network中的flow something通常只pass一次node and edge
- ==social network connection中，flow之间的efficiency取决于centrality measure==
  
  - centrality measure是在same network中，一个node和其他node的relationship的quantification
  
    |                          | 定义                                                         | mark                                                         |
    | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | ==degree count/ degree== | ==在social networking scenario中，degree count/ degree是each node的connection（计算有多个人connected to a person）== | -                                                            |
    | ==closeness==            | closeness是衡量central person到其他人的distance（即相互之间的similarity）<br /><br />closeness是衡量network中，particular node和其他node的average distance或path length | ==说明information能以多快的速度（how quickly）在人群中travel== |
    | ==betweenness==          | betweenness是衡量person connect other的extent<br /><br />betweenness是衡量how many times a particular node is part of the shortest path between two other nodes in a network | 在social network中，friend之间通常有high degree of betweenness |
  
    - node会作为network中separated node的connection

## 4. Network Classification

- network classification是一种nearest neighbor和data mining algorithms（如logistic regression），network classification可用于分析social network

- egonet是由ego及其directly connected node组成的network

  > ego包括individual的personality或trait
  >
  > node包括similar people

- bigraph是有两种node type的network，可为network提供complete picture

- homophily是指people通常会connect with similar people

- 在modeling中，每个node都是一个instance（可用local variable和network variable描述node）

  - 通过这种format，可使用data mining algorithm（如classification，clustering，logistic regression等）来分析gathered data
  
    |                      | 定义                                                         |
    | -------------------- | ------------------------------------------------------------ |
    | local variable       | local variable是指和specific node的characteristic相关的attribute |
    | ==network variable== | network variable是指network中，和node connection相关的attribute<br /><br />==network variable是会考虑network中node interaction的attribute== |

# 三、Neural Network

- neural network是一种data analysis技术，由input layer，hidden layer（nonlinear function）和output layer组成

- neural network适用于solve complex problem和simulate human brain的功能
  - 尽管Neural Network无法完全像human brain一样工作，但其在对input data进行分类时，可以使用类似方式进行
  - neural network可以完成human brain无法完成的工作，如快速解答large quantity of data的数学计算
  
- data scientist可一起使用cluster和neural network，以产生more accurate result

- ==neural network和其他data analysis technique的区别是，neural network可以make observation==

  > ==可通过observe loss data中的characteristic，找出not previously been considered as rating factor的information，进而将其用于rating==

## 1. Neural Network的mechanic

- neural network的most important ability是分析large quantity of data

  - ==neural network只适用于numerical data==

- ==为让neural network能predict project success，必须先知道导致previous project success/ failure的factor==

  - predictive analytics是一种statistical and analytical technique，其用于开发model，以predict future event/ behavior

- neural network 可用于深度学习数据之间的关系。

- neural network的另一特点为可使用incomplete data
  
- ==neural network的analysis result基于observation, detected correlations and new concept==
  
    > 可通过分析公开数据知晓供应商的供应商（2nd-tier or 3rd-tier supplier），从而在风险分析时，企业可完成一个更为全面的risk profile
  
- ==neural network属于machine learning==
  
  - machine learning是从一个model开始，data scientist开发并测试model，以完成predictive analysis
  - 当computer使用模型时，其会从result和new data中学习

- neural network的优点

  | ==neural network的优点==                                     | mark                             |
  | ------------------------------------------------------------ | -------------------------------- |
  | ==neural network会perform各种mathematical function，进而develop rule以make prediction== | 最主要的优点                     |
  | ==neural network可使用incomplete data==                      | -                                |
  | ==neural network更少依赖rules，computer会进行independent observation，之后会提供intuitive result（直观结果）== | 和其他machine learning方法的区别 |

- neural network的缺点

    | ==neural network的缺点==                                     | mark                                                         |
    | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | ==hidden layer非常不透明（too opaque），对hidden layer的optimization必须precisely determined== | neural network optimization的标准是，output layer能够evaluated to actual value<br /><br />data scientist的work是precisely determine optimization function |
    | network必须从error中学习（可能导致overfit）                  | -                                                            |
    | 很难identify and correct overfit                             | -                                                            |
    | ==neural network无法用于non-numerical data==                 | -                                                            |

- ==neural network由input layer，hidden layer和output layer组成==

### （1）input layer

- input layer是提供network 分析的data

### （2）hidden layer

- hidden layer是介于input layer和output layer之间
- hidden layer是由neurons构成的，neurons是neural network中receive input的mathematical function
  - neuron会learn，并recode input data的information
- ==hidden layer会perform mathematical function进行calculation，用以match input and output==
  - hidden layer的mathematical function涉及cluster analysis，classification analysis，linear function等
    - classification analysis是根据known attribute的value，来segment data，以确定categorical target variable的value（classification analysis属于supervised technique）
- ==hidden layer的calculation process属于不透明（opaque）且难以理解==
- 通常来看，neural network由thousands of neurons and links to perform calculation（with large amount of data）

### （3）output layer

- output layer是提供分析结果

## 2. Neural Network的应用

- 当neural network可接触到各种smart product提供的数据后，即可用于RM和risk control领域

  > 如可对machine failure, catastrophes, financial impropriety, defective product等进行复杂分析以预测风险

- neural network的应用领域

  > premium increase后，预测customer retention
  >
  > premium change后，预测renewal
  >
  > ==为individual customer提供more accurate rate (tailored rate)==
  >
  > 可以pick up small nuance（small pattern in data）
  >
  > 使用machine learning and cluster analysis来确定project的success probability/ failure probability
  >
  > perform mathematical function时，能够develop rule，以make prediction

# 四、pattern matching

- pattern matching是指finding matching pattern in data。 可通过比对来完成风管工作

  - pattern matching中，可分析transaction data来找出fraudulent pattern，通过对比之前分析过的案件，对可疑的交易进行flag

    > 如寻找fraud in financial transaction和network security issues

- computer vision已经发展到可对细微差别（nuance）进行区分（通过不断feed massive number of images和deep learning of neural network）

  > 如通过图像对比，可分析土壤湿度（soil moisture level）