# 信用卡诈骗分析
[由于数据超过25M，只能网盘自取:](https://pan.baidu.com/s/14F8WuX0ZJntdB_r1EC08HA#list/path=%2F)  提取码：58gp  
# 知识点：
* 逻辑回归使用sigmoid函数：
$$ g(z) = \frac{1}{1+e^{-z}}$$
* sigmoid函数图：  
![sigmoid](https://github.com/Arieswk/credit_fraud_analysis/blob/master/sigmoid.jpg)  
* 混淆矩阵中的4个概念：
  * TP，True Positive：预测为正，判断正确  
  * FP，False Positive：预测为正，判断错误   
  * TN，True Negative：预测为负，判断正确   
  * FN，False Negative：预测为负，判断错误  
* 基于以上四种概念的七种指标(accuracy、error rate、precision、recall、F1-score、TPR、FPR)  
  * accuracy(准确率) = (TP + TN) / (TP + FP + TN + FN)  
  * error rate(错误率) = (FN + FP) / (TP + FP + TN + FN)  
  * precision(精确率，查准率) = TP / (TP + FP)  
  * recall(召回率，查全率) = TPR(True Positive Rate) = TP / (TP + FN)  
  * F1-score(F1-measure，F1-值) = 2*P*R/(P+R)，其中P和R分别为 precision 和 recall 
  * FPR(False Positive Rate) = FP / (TN + FP)  
* F1-score有什么用？  
  * 在通常情况下，precision高的话，recall就会低；precision低的时候，recall往往比较高。为了权衡这种关系(tradeoff)，所以有了F值：  
  * $$ F_{\beta}} = \frac{(\beta^{2})*P*R}{(P+R)}$$  
 
