## Deep Learning based Recommender System: A Survey and New Perspectives
> Fire 2017.12.07

### 为什么关注深度学习的推荐系统
工业界：Recently, many companies resort to deep learning for further enhancing their recommendation quality [12, 17, 81]. Covington et al. [17] presented a deep neural network based recommendation algorithm for video recommendation on YouTube. Cheng et al. [12] proposed an App recommender system for Google Play with a wide & deep model. Shumpei et al. [81] presented a RNN based news recommender system for Yahoo News. All of these models have stood the online testing and shown signi cant improvement over traditional models.  us, we can see that deep learning has driven a remarkable revolution in industrial recommender applications.

学术界：Another noticeable change lies in the research area.  e number of research publications on deep learning based recommendation methods has increased exponentially in these years.  e leading international conference on recommender system, RecSys1, started to organize regular workshop on deep learning for recommender system2 since the year 2016.  is workshop aims to promote research and encourage applications of deep learning based recommender system.

### 分类
* 神经网络模型：
	1. 使用单个深度学习技术：MLP, AE, CNN, RNN, DSSM, RBM, NADE and GAN based recommender system. 
	2. 使用复合深度学习技术。

* 融合模型
	1. 结合深度学习和传统推荐模型
	2. 结合不同的深度学习模型

### 质量分析
提到了最近几年的论文数量爆发性增长。分析了不同深度学习方法的数量，提到了常用的数据集和评价指标，以及最有名的一些出版源，还列举了一些应用领域。

### 基于深度学习的推荐系统
目标是阐述最显著的发展，而不是详尽的清单。

* 多层感知机MLP。单独的 / 结合其他的
* 自动编码机AE。单独的 / 结合传统方法（紧密连接的 / 松散连接的）
* CNN
* RNN
* 受限玻尔兹曼机RBM
* 涌现的新方法：NADE（神经自回归分布评估） / GAN

### 深度组合模型
* CNN+AE
* CNN+RNN
* CNN+MLP
* RNN+MLP
* CNN+DSSM
* RNN+DSSM

### 未来研究方向&开放问题
* 深度理解用户和物品
* 深度组合模型
* 时间动态
* 跨领域推荐
* 多任务学习
* 注意力机制
* 规模化
* 新的评测指标
