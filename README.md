# OTTO--Summary

## Week2 讨论内容(Jan 7)

**将train数据合理分成 batch_train 和 validation，目的：**
- 分析 evaluation 中，click cart & order 分别分数权重；
- 缩短模型计算时间（batch_train & validation 可占 train 数据50%）;

**根据“电商项目”，对数据做组合特征处理，并分析选择合适的特征**

**对时间信息进行尝试**
1. 相对位置编码尝试，位置信息尝试
2. 当天时间分箱，早上，中午，下班，晚上，凌晨；或者是否周末，是否上班
3. 年月去掉，保证test里面的时间数据不冲突；

**每人确认至少一个模型，并结合上述内容进行尝试。**
