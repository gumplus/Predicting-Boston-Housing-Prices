Using DecisionTreeRegressor to build a model,what can predict the price of house in Buston Area 

## 1.首先利用np.mean,np.max,np.min,np.std等对房价数据的范围分布进行探索,观察
## 2.观察参数特点,找出重要的参数,后面分析时候可以给予一定权重
## 3.利用r2_score衡量如何是一个好的算法/模型
## 4.通过sklearn.cross_validation 库来队数据进行batch & shuffle加工,确保样本均衡以及可验证.
## 5.构建决策树模型,观察学习曲线,找到model最合适的学习深度
## 6.最终构建除合适本次数据集的预测model
