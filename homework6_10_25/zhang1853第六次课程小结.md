# 策略研究报告

## 交易观点

- 整体激进+保守对冲
- 趋势跟随
- 规模投资
- 动量投资



## 具体策略（小市值+金叉死叉+海龟）

### 股票池

- 每隔30天选取市值在20-30亿的公司股票来更新股票池



### 买入

- 今天的收盘价大于过去20个交易日中的最高价时，买入
- 或者
- 出现金叉



### 卖出

- 当收盘价小于过去10个交易日中的最低价时
- 而且
- 出现死叉



## 策略回测结果及说明

### 回测结果


| 夏普比率 | 最大回撤 | 交易次数 | 信息率 | 年化收益 | 胜率  | Alpha | Beta  |
| :------: | :------: | :------: | :----: | :------: | :---: | :---: | :---: |
|  2.055   |  15.40%  |   819    | 0.954  |  38.4%   | 0.553 | 0.319 | 0.237 |



### 结果说明

- 时间跨度长，股票池是自动选取，避免了偷价

- 短期内可以获得大量收益，后续趋于平稳
- 交易次数较少，趋向于长持股票
