FDDC2018金融算法挑战赛01 - A股上市公司季度营收预测
================
刘立功, 武睿琦, 李家翔
2020-06-16

<!-- README.md is generated from README.Rmd. Please edit that file -->

## top-line-predictor

1.  参赛队伍名称为 *超级数据挖掘机*。
2.  最后成绩为 150/2724, 前5.5%，见[证书](refs/certificate.pdf)
3.  项目名称解释
    1.  top line，得名于收入表，位于开头，主要记录上市公司财务报表中的营业收入(Boyte-White 2018)。
    2.  predictor，预测因子的意思。

对所有上市公司二季度营收数据进行预测，清洗历史财务数据、宏观数据、市场数据、行业数据，构建XGBoost。
在当年8月5日22：00前发布财报的公司营收数据为评判标准，计算累计相对误差。

## To-dos

1.  [x] 增加模型的信息
    1.  [x] ~~百度云相关预测文档~~，无新文件
    2.  [x] 整合本地 - 天池的文档
2.  [x] 增加 coc
3.  [x] 增加 contributor 解释
4.  [x] 增加证书
5.  [x] 发博客
6.  [ ] 这里有多加股票，并且都是时间序列，所以算 longitudinal data，这里可以采用 LSTM 进行训练，参考 [6
    神经网络应用](https://jiaxiangbu.github.io/learn_longitudinal_analysis/analysis/introduction-panel-data.html)

## Contributions

参考 [CONTRIBUTING.md](.github/CONTRIBUTING.md)，建立 Pull Request 增加名字。

<h4 align="center">

**Code of Conduct**

</h4>

<h6 align="center">

Please note that the `top-line-predictor` project is released with a
[Contributor Code of
Conduct](https://github.com/JiaxiangBU/top-line-predictor/blob/master/CODE_OF_CONDUCT.md).<br>By
contributing to this project, you agree to abide by its terms.

</h6>

<h4 align="center">

**License**

</h4>

<h6 align="center">

MIT © [Ligong Liu;Ruiqi Wu;Jiaxiang
Li](https://github.com/JiaxiangBU/top-line-predictor/blob/master/LICENSE.md)

</h6>

## 参考文献

<div id="refs" class="references">

<div id="ref-White2018">

Boyte-White, Claire. 2018. “How Do Operating Income and Revenue Differ?”
Investopedia. 2018.
<https://www.investopedia.com/ask/answers/122714/what-difference-between-operating-income-and-revenue.asp>.

</div>

</div>
