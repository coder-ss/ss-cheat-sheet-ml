# 机器学习速查手册

机器学习中的概念、知识点拆分成一个一个点，方便回顾和查阅。由Markdown或Jupyter Notebook来完成，有公式和代码的时候Jupyter Notebook非常方便。

但是，有时候会发现Github解析的Jupyter Notebook的公式和我本地看到的有些不一样，我发现了的地方都会修改好，保证两个地方的显示都是OK的。

## 数学基础

- [距离、相似度](./basic-mathematics/distance.ipynb)

### 概率统计

- [极大似然估计](./basic-mathematics/probability-statistics/maximum-likelihood-estimate.ipynb)


## 性能度量

- [均方误差（MSE）与精度（Accuracy）](./measurement/MSE-accuracy.ipynb)
- [泛化误差（generalization error）、欠拟合（underfitting）与过拟合（overfitting）](./measurement/overfitting-underfitting.ipynb)
- [查准率（Precision）、查全率（Recall）、F1](./measurement/precision-recall-f1.ipynb)
- [ROC曲线、AUC](./measurement/ROC-AUC.ipynb)
- [偏差（bias）、方差（variance）](./measurement/bias-variance.ipynb)


## 特征处理

- [归一化](./feature/normalization.ipynb)
- PCA


## 学习算法

### 决策树

- [决策树概念与基本流程](./decision-tree/summary.ipynb)
- [ID3、C4.5、CART决策树算法](./decision-tree/ID3-C45-CART.ipynb)
- [剪枝](./decision-tree/pruning.ipynb)
- 连续值、缺失值处理
- 处理回归问题


### 线性模型

- [线性回归](./linear-model/linear-regression.ipynb)
- [逻辑回归](./linear-model/logistic-regression.ipynb)


### SVM

- [支持向量机（SVM）](./svm/svm.ipynb)
- SMO


### 神经网络

- [神经网络概念](./neural-network/network-summary.ipynb)
- [误差逆向传播算法（BP神经网络）](./neural-network/bp.ipynb)


### 贝叶斯分类

- [贝叶斯决策论（Beyesian decison theory）](./bayes/beyesian-decison-theory.ipynb)
- [生成式（discriminative）与判别式（generative）](./bayes/discriminative-generative.ipynb)
- [朴素贝叶斯分类器](./bayes/naive-bayes.ipynb)
- 半朴素贝叶斯分类器
- 贝叶斯网


### 聚类

- [k均值（k-means）](./cluster/k-means/k-means.ipynb)
- [层次聚类](./cluster/hierarchical-clustering/hierarchical-clustering.ipynb)
- [高斯混合模型](./cluster/gmm/gmm.ipynb)


### k近邻（kNN）

- [kNN概念](./kNN/kNN.ipynb)
- [基于kNN的验证码识别](./kNN/verify-code.ipynb)

### 增强学习


## 其他事项

- 正则化


## 优化算法

- 梯度下降
- 牛顿法
- [拉格朗日乘数法](./optimization/lagrange-multiplier-method.ipynb)
- [正规方程组](./optimization/normal-equation.ipynb)
- EM算法