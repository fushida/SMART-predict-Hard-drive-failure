海量数据存储系统的硬盘故障预测技术与产业化应用中机器学习研究。基于机器学习算法，对磁盘故障进行预测，在故障发生之前能够主动迁移数据，从而能够显著提升存储系统可靠性、降低运营成本和硬件成本。
研究SMART属性，给出特征选择方案；完成SATA磁盘预测模型，并研究固态硬盘和SAS磁盘故障预测；训练最优故障磁盘数据迁移方法。
主要采用二分法和时间序列的方法。LR,RF,LSTM是主要研究的三个方法。

在项目中主要选择了2017年的数据作为训练与测试集，在这里我只上传了该年中的某天数据作为参考。
数据集由Backblaze公司每季度公布一次，来源地址：https://www.backblaze.com/b2/hard-drive-test-data.html  
SMART相关属性的说明与选择建议    https://www.backblaze.com/blog/hard-drive-smart-stats/
关于数据集的其他说明详见Backblaze官网。