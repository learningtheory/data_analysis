#  Machine Learning from Disaster

https://www.kaggle.com/lishulong

https://www.kaggle.com/ntnu-testimon/paysim1

# 什么是数据分析？

> analysis of data is a process of inspecting ,cleansing ,transforming ,and modeling data with the goal of discovering usefull information ,suggesting conclusions and supporting decision-making


> 数据分析是一个过程的检查、清洗、转换，并发现有用信息的目标数据建模，提出结论和决策支持

- 数理知识
- 数据获取，加工能力
- 行业知识

# 数据科学家

### - fundamentals
- 矩阵 二叉树 cap理论 pandas numpy sharding etl nosql re env setup

### - statistics
- 数据分析，概率论 贝叶斯，

### - programming
- python sas R 
- google tenserflower

### machine learning

机器学习的模型

### text mining / NLP
机器学习的分支

### visualization
数据可视化

### big data

### data ingestion (数据提取)
data fusion（数据融合）

### data munging

### tollbox
- java python
- excel
- weka
- hadoop


## 数据分析

1. 明确思路
2. 数据收集，外部数据库，公开信息，私有数据库，第三方，调查问卷，客户数据
3. 数据处理 数据分析建模理论基础 数据分析工具 pandas，数据清晰：可读性，完整性 唯一性 权威性 以及合法性
4. 数据分析：pandas 探索性数据分析EDA以及可视化，金融数据分析，图像数据处理分析，文本数据分析
5. 数据展现 机器学习 scikit learn 深度学习 tenserflow
6. 项目实战：交叉验证和参数调整，特征降纬，特征选择


### 数据分析建模基础

1. 分类 把用户分为几个类别 
2. 回归 预测房价
3. 聚类 不知道数据的标签
4. 时序分析 股价走势？

#### 分类和回归
应用：信用卡申请人 风险评估，预测公司业务增长量，预测房价
原理：
    分类：将数据映射到预先定义的群组或者类，算法要求基于数据属性来定义类别，把具有某些特征数据项映射到给定的某个类别上
    回归：用属性的历史数据预测未来走势，算法首先假设一些 已知类型的函数可以拟合目标数据，然后利用某种误差分析确定一个与目标数据拟合程度最好的函数
    区别：分类模型采用的是 离散预测值，回归模型采用连续的预测值

#### 聚类

应用：根据症状归纳为特定疾病，发现信用卡高级用户，根据网上行为对用户分群而进行精确营销

原理：
    在没有给定划分类的情况下，根据信息相似度进行信息聚类
    聚类的输入是一组，未被标记的数据，根据样本特征的距离或相似度进行划分，划分的原则是保持最大的组内相似性和最小的组件相似性
    
### 建模基础

测试数据 和训练数据

1. 定义一系列函数
2. 定义函数的优劣
3. 选择最优的函数
