Financial markets are looked at with awe and confusion by market participants, investors, data scientists and anybody that tries to forecast prices or extract valuable information in order to invest in such markets. The constant flow of information, let it be from news or analyst reports, have a direct impact on investors’ positions and market prices.

However, vast amount of new financial information is created every day and manually deriving actionable insights from it is impossible for any single entity. Thus, automatic sentiment analysis of texts becomes critical for firms and investors as it provides faster access to salient information and can give actors an edge. In fact, automatically inferring the polarity of a financial news or headline saves time and provide valuable insights. 

Even though massive amount of new financial data is created everyday, there is a serious lack of labeled financial data. Moreover, it is largely domain specific as opposed to traditional news data and require heavy domain knowledge to decipher. Hence, traditional deep learning models such as Recurrent Neural Networks as well as state-of-the-art data-hungry text classification models are quite ineffective in regards to financial sentiment analysis. 

As such, the principal research interest for this thesis is polarity analysis. More specifically, we investigate two areas of research related to Natural Language Understanding in the field of finance. We heavily base our work upon previous research, namely the FinBERT paper by [Ara19] and described in section 2. 

We first hypothesize that a MultiTask learning approach offers better performance than a single-task approach on financial sentiment analysis as proposed by the FinBERT authors. Furthermore, we hypothesize that the unfreezing strategy of the pre-trained layers as stated in the FinBERT paper should be part of the hyper-parameter tuning step since it is expected to increase the model’s performance. 

Thus, the goal of this thesis is to test the hypothesized advantages of exploring different unfreezing strategies as well as using fine-tuned pre-trained language models for financial domain in a Multi-Task scenario.
