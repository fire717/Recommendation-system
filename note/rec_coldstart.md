## 冷启动
> By Fire

推荐系统冷启动主要分为：系统冷启动，物品冷启动，用户冷启动。

目前常见方法：

* 系统冷启动
  1. 利用专家知识，给物品分类/打标签；
  2. 从互联网上爬取数据。
  
* 物品冷启动
  1. 利用内容信息，将它们推荐给喜欢过和它们相似物品的用户；
  2. 利用物品特征，推荐给喜欢该类别的用户，做粗粒度的个性化。
  
* 用户冷启动
  1. 利用用户社交网站的信息，获取好友，推荐好友喜欢的物品；
  2. 利用用户社交网站信息，获取发过的状态，通过nlp等技术分析获取喜欢的物品，进行相关的物品推荐；
  3. 利用隐式用户信息，比如社交网站的账号资料信息，手机设备信息，地理位置信息等等，获取用户特征，进行粗粒度推荐（通过热门物品的不同类别，或者专家人工设置好对应类别的推荐，或者通过爬取的数据进行机器学习分类聚类等）；
  4. 利用显式用户信息，比如用户注册时填写的资料，进行粗粒度推荐；
  5. 直接要求用户注册时回答一些问题，进行粗粒度推荐；
  6. 直接先推荐一定数量的物品（热门物品、区分度高的物品等），让用户评价反馈，再进行个性化推荐。


### 网站
* [推荐系统冷启动](http://blog.csdn.net/huruzun/article/details/50912736)
* [推荐系统中的冷启动和探索利用问题探讨](http://www.datagrand.com/blog/coldstartee.html)
* [推荐系统中冷启动问题](http://blog.csdn.net/u013963380/article/details/73519212)
* [推荐系统浅谈系列（三） - 冷启动问题](https://www.jianshu.com/p/97e46f933010)
* [有哪些解决推荐系统中冷启动的思路和方法？](https://www.zhihu.com/question/19843390)

### 论文
* [Ling, Guang, et al. "Online learning for collaborative filtering." Neural Networks (IJCNN), The 2012 International Joint Conference on. IEEE, 2012.](https://pdfs.semanticscholar.org/3848/5c7b4e991a67cda20c38062626a7637955b9.pdf)
