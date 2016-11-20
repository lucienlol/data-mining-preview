# data-mining-preview
data mining预习资料

***

## 1-intro

### 1.Why data mining
* Science

  data collected and stored at enormous speeds
  tarditional techniques infeeasible for raw data
  data mining helps scientists
* Industry

  lots of data is being collected and put into data warehouses
  computers are cheap and powerful
  competitive pressure is Strong
* Motivation 

  often information "hidden" in the data that is not redily evident
  human analysts take weeks
  much data never analyzed at all
  data mining turns a large collection of data into knowledge
  
### 2.What is data mining
* Defition

  1.non-trivial extraction of implicit, previously unknown and useful information from data
 (从数据中抽取含蓄的，有用的，之前未知的信息)
 
  2.exploration&analysis, by automatic or semi-automatic means, of large quantities of adata in oder to discover    meaningful pattens
 (采用全自动或者半自动的方法，从大量数据中分析探索出有意义的模式)
 
  3.process of semi-automatically analyzing large databases to find patterns that are:
  valid:hold on new data with some certainty
  novel:non-obvious to the system
  useful:should be possible to act on the item
  understandable:human should be able to interpret the patten
 
* Process
  databases -> Data Warehouse -> Data mining -> pattens -> knowledge
  
### 3.What kinds of Data can be Mined
* Database Data
* Data Warehouse
* Transaction Data

### 4.What kinds of Patterns can be Mined
* Class/Concept Description
* Mining Frequent Patterns
* Classification and Regression
* Cluster
* Outlier

### 4.What technologies are used
statistics, artificial, intelligence, databases, visualization

* Statistics

  statistical descriptions, inferential statistics, statistical hypothesis testing

* Machine Learning

  supervised learning, unsupervised learning, semi-supervisied learning, active learning

### 5.What kinds of applications are targeted
### 6.Major issues in data mining
* Mining methodology
* User interaction
* Efficiency and Scalability
* Diversity of Database Types
* Data Mining and Society

***
## 2-data-exploration

### 1.Data Objects and Attribute Types

* Type of attributes

  Nominal(名词性属性), Binary, Ordinal, Numeric

  Numeric attribute contains Interval-scaled attributes(区间属性) and Ratio-scaled attributes(比例属性)
  
  
### 2.Basic Statistical Descriptions of Data
### 3.Data Visualization
### 4.Measuring Data Similarity and Dissimilarity
### 5.Useful thing to know:Document representatio and Similarity measure between documents

***
## 3-data-prepocessing

### 1.data preprocessing:overview
* why process data

* major tasks
  * data cleaning
  * data integration
  * data reduction
  * data transformation
  
### 2.data cleaning
* handle missing values
  1. ignore the tuple
  2. fill in the missing value manaually
  3. use a global constant
  4. use a measure of central tendency
  5. use mean or median for all samples belong to the same class 
  6. use the most probable value

* handle noisy data
  
### 3.data integration
### 4.data reduction
### 5.data transformation and data discretization
