# Dynamic-Financial-News-Collection-and-Analysis
Final project

## 爬虫数据来源
Reuters 

Booloomberg


股票涨幅做label  新闻正文-->提到的股票公司-->股票统计涨跌-->涨1,跌0


正文出现的公司代码，公司名称 去对应股票


后期考虑加入:


知识图谱 Wiki Data ，法人，竞争公司，公司标签等属性


各种属性分配不同的权重


attention mechanism

gu piao


股票涨跌与新闻情感极性的相关性
         scores    labels
scores  1.000000  0.068339
labels  0.068339  1.000000


 scores  labels
0        0.0       0
1        0.0       1
2        0.0       1
3        0.0       1
4        0.0       1
5        0.0       1
6        0.0       1
7        0.0       1
8        0.0       1
9        0.0       1
10       0.0       1
11       0.0       1
12       0.0       1
13       0.0       1
14       0.0       1
15       0.0       1
16       1.0       1
17       0.0       1
18       0.0       1
19       0.0       1
20       0.0       1
21       0.0       1
22       1.0       1
23       0.0       1
24       1.0       0
25       1.0       1
26       0.0       0
27       0.0       0
28       1.0       0
29       1.0       0
...      ...     ...
1431     0.0       1
1432     0.0       0
1433     0.0       0
1434     1.0       1
1435     0.0       0
1436     0.0       0
1437     0.0       0
1438     1.0       1
1439     0.0       0
1440     0.0       0
1441     1.0       1
1442     0.0       1
1443     0.0       1
1444     0.0       0
1445     0.0       0
1446     1.0       1
1447     0.0       1
1448     1.0       1
1449     0.0       1
1450     1.0       1
1451     0.0       1
1452     1.0       1
1453     0.0       1
1454     0.0       1
1455     1.0       1
1456     0.0       1
1457     1.0       1
1458     0.0       1
1459     1.0       1
1460     0.0       1

