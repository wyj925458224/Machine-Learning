## 目录

- [1 什么是XGBoost](#1)
   - [1.1 XGBoost目标函数](#1.1)
   - [1.2 ](#1.2)
   - [1.3 ](#1.3)
- [2 ](#2)
- [3 ](#3)
- [4 ](#4)
- [5](#5)
### <span id="1">1 什么是XGBoost</sapn>
XGBoost是陈天奇等人开发的一个开源机器学习项目，XGBoost是经过优化的分布式梯度提升库，旨在高效、灵活且可移植。
它是基于Gradient Boosting框架实现的机器学习算法。

#### <span id="1.1">1.1 XGBoost目标函数</sapn>
XGBoost的核心思想就是：
- 不断的添加树，树节点选择合适的特征进行分裂，每棵树本质上是在学习新的函数 *f(x)*，去拟合上次预测的残差；
- 假设训练完成得到 *K* 棵树，要得到一个样本的预测值时，实际上就是根据这个样本的特征，在每棵树中会对应到一个叶子节点，每个叶子节点就对应一个值；
- 最后将每棵树对应叶子结点的值加起来就是该样本对应的预测值；  
XGBoost目标函数如下图所示：  
![objective](https://github.com/wyj925458224/Machine-Learning/blob/master/XGBoost/objective.jpg)


![round_t](https://github.com/wyj925458224/Machine-Learning/blob/master/XGBoost/round_t.jpg)

![taylor_expansion](https://github.com/wyj925458224/Machine-Learning/blob/master/XGBoost/taylor_expansion.jpg)

![objective_taylor_expansion](https://github.com/wyj925458224/Machine-Learning/blob/master/XGBoost/objective_taylor_expansion.jpg)

#### <span id="1.2">1.2 XGBoost</sapn>

#### <span id="1.3">1.3 </sapn>

### <span id="2">2 </sapn>

### <span id="3">3 </sapn>

### <span id="4">4 </sapn>

### <span id="5">5 </sapn>
