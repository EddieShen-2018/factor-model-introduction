


对过去所做工作的汇总，多为提纲挈领的材料，仅用于展示，代码及具体工作此处隐去。

整体工作主要分为大部分：。量化方面的工作主要以多因子选股为核心，辅以择时指标及机器学习思路。其他工作包含对私募管理人的尽调、绩效分析和期权希腊字母归因等工作。


1、多因子模型：多因子模型主要分为alpha模型和风险模型。
alpha模型主要分为因子研究和因子回测（因子策略）两块。因子研究主要基于alphalens包，编辑因子公式后，可批量快速的对因子进行分析，包含收益分析、IC分析、换手率分析、行业分析；因子回测则是基于ricequant的RQalpha平台，进一步对前者优选出的因子进行回测分析，优点是回测结果更接近实际交易（相对前者）。
风险模型主要为复现了Barra结构化风险模型，计算若干风险因子收益（含Beta、BTOP、EarnYld、Growth、Leverage、Liquidty、Momentum、ResVol、Size、SizeNL十大类因子），可对组合进行归因分析（早期版本含组合优化器）。

2、对择时指标的研究：入门初期主要以研究择时指标为主，后转为多因子模型，曾自写过回测框架，后主要借用ricequant平台进行研究。例如HSAR、GP、MACD、MCMC、adx、emd、rsrs、ma体系等，其中，ma体系为一大类，含经过改进后的自适应移动平均线。

3、掌握主流机器学习算法，如回归模型、聚类、主成分分析、随机森林、遗传算法等，对深度学习有所了解。编写回测隐马尔可夫择时模型的策略。个人理解机器学习适用于因子组合、参数寻优、因子挖掘等方面，直接用来预测股票收益方面效果不一定有优势。

4、私募管理人尽调及绩效分析。

5、期权：希腊字母归因 和 波动率指数构建。



*多因子模型框架及部分结果（Barra因子收益）已上传。

----记于2019年6月1日，更新于2019年7月6日
