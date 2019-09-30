# Time Series Forecasting 

## Position-based Content Attention for Time Series Forecasting with Sequence-to-sequence RNNs 

> 17arXiv
>
> Yagmur Cinar∗, Hamid Mirisaee∗, Parantapa Goswami+, Eric Gaussier∗, Ali A¨ıt-Bachiry, and Vadim Strijovz 
>
> Univ. Grenoble Alpes, CNRS, Grenoble INP, LIG
>
> Viseo R&D, y Coservit, z CCRAS
> ∗firstname.lastname@imag.fr, z Strijov@ccas.ru
> +parantapa.goswami@viseo.com, ya.ait-bachir@coservit.com 

**Abstract**. We propose here an extended attention model for sequence-to-sequence
recurrent neural networks (RNNs) designed to capture (pseudo-)periods in time
series. This extended attention model can be deployed on top of any RNN and is
shown to yield state-of-the-art performance for time series forecasting on several
univariate and multivariate time series. 

**中文简介**

使用了注意力机制的RNN模型

**2 Related Work**

Various stochastic models have been developed for time series modeling and forecasting. Notable among these are **autoregressive (AR)** [9] and **moving averages (MA)** [10] models, that were combined in a more general and effective framework, known as autoregressive moving average (**ARMA**), or autoregressive integrated moving average (**ARIMA**) when the differencing is included in the model [11]. Vector ARIMA, or
**VARIMA** [12], is the multivariate extension of the univariate ARIMA model. More recently, based on the development of statistical machine learning, time series prediction has been formulated as a regression problem typically solved with Support Vector Machines (**SVM**) [13] and, even more recently, with Random Forests (**RF**) [14,15]. RF have been in particular used for prediction in the field of finance [14] and bioinformatics [15], and have been shown to outperform ARIMA in different cases [16]. 



**参考文献：**

9. Walker, G.: On periodicity in series of related terms. Proceedings of the Royal Society of
London. Series A, Containing Papers of a Mathematical and Physical Character 131(818),
518–532 (1931)
10. Slutzky, E.: The summation of random causes as the source of cyclic processes. Econometrica: Journal of the Econometric Society pp. 105–146 (1937)
11. Box, G.E., Jenkins, G.M.: Some recent advances in forecasting and control. Journal of the
Royal Statistical Society. Series C (Applied Statistics) 17(2), 91–109 (1968)
12. Tiao, G.C., Box, G.E.: Modeling multiple time series with applications. journal of the American Statistical Association 76(376), 802–816 (1981) 

13. Sapankevych, N.I., Sankar, R.: Time series prediction using support vector machines: A
survey (2009)
14. Creamer, G.G., Freund, Y.: Predicting performance and quantifying corporate governance
risk for latin american adrs and banks (2004)
15. Kusiak, A., Verma, A., Wei, X.: A data-mining approach to predict influent quality. Environmental monitoring and assessment 185(3), 2197–2210 (2013)
16. Kane, M.J., Price, N., Scotch, M., Rabinowitz, P.: Comparison of arima and random forest
time series models for prediction of avian influenza H5N1 outbreaks. BMC bioinformatics
15(1), 276 (2014) 

