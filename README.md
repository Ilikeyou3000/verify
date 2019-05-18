## GBDT在处理稀疏数据上的缺点

#### 缺点
  如果数据太少，那么要注意规避GBDT🦹画梯形决策面的缺点，本实验以y-x=b为例，在线上的属于一类，在线下的属于另一类，展示拟合决策面效果。
  
  上述逻辑在数据挖掘中可以体现为，（个体观测量-平均观测量）= b（显著）
#### 规避
  GBDT大概在数据挖掘里面是个王者地位，尝试将这种线性项相减会获得比较好的决策面。

#### 例子，如下图：
<div align=center><img src="https://raw.githubusercontent.com/707043502/verify/master/pic/demo.png" width="150" height="200" alt="图片描述文字"/></div>