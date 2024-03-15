# FuturesAnalysis-ARMA-GARCH-MonteCarlo
本项目利用Python进行ARMA-GARCH-MonteCarlo，包括数据预处理、统计检验、模型拟合、残差分析、预测及蒙特卡洛模拟。

## 数据预处理

- 数据读取：使用`pandas`库从Excel文件中读取数据，并将时间列转换为`datetime`对象。
- 数据清洗：处理缺失值和无限值，确保数据质量。

## 统计检验

- 平稳性检验：通过ADF检验和Phillips-Perron检验来确定时间序列的平稳性。

## 模型拟合

- ARIMA模型：拟合ARIMA模型预测未来价格。
- GARCH模型：基于ARIMA模型的残差拟合GARCH模型，分析价格波动性。

## 残差分析

- 残差图表：绘制残差的散点图、直方图、自相关图和偏自相关图。
- ARCH效应检测：使用滞后回归和LM检测来识别残差中的ARCH效应。

## 预测

- 预测图表：展示真实值与预测值的对比。
- 风险度量：通过模拟ARIMA过程来计算价格的风险度量。

## 使用说明

1. 安装所需库：`pandas`, `numpy`, `statsmodels`, `arch`, `matplotlib`, `seaborn`。
2. 运行代码：执行Python脚本进行数据分析。
3. 查看结果：检查生成的图表和Excel文件。

## 贡献者

- 雷聪


