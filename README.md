# Master Thesis
## Predictive Value of Sentiment Analysis from Headlines for Crude Oil Prices
### Understanding and Exploiting Deep Learning-based Sentiment Analysis from News Headlines for Predicting Price Movements of WTI Crude Oil

The focus of this thesis deals with the task of research and development of state-of-the-art sentiment analysis methods, which can potentially provide helpful quantification of news that can be used to assess the future price movements of crude oil. 

CrudeBERT is a pre-trained NLP model to analyze sentiment of news headlines relevant to crude oil. 
It was developed by fine tuning [FinBERT: Financial Sentiment Analysis with Pre-trained Language Models](https://arxiv.org/pdf/1908.10063.pdf)

Performing sentiment analysis on the news regarding a specific asset requires domain adaptation. 
Domain adaptation requires training data made up of examples with text and its associated polarity of sentiment. 
The experiments show that pre-trained deep learning-based sentiment analysis can be further fine-tuned, and the conclusions of these experiments are as following: 

Deep learning-based sentiment analysis models from the general financial world such as FinBERT are of little or hardly any significance concerning the price development of crude oil. 
The reason behind this is a lack of domain adaptation of the sentiment. 
Moreover, the polarity of sentiment cannot be generalized and is highly dependent on the properties of its target. 

The properties of crude oil prices are, according to the literature, determined by changes in supply and demand. 
News can convey information about these direction changes and can broadly be identified through query searches and serve as a foundation for creating a training dataset to perform domain adaptation. 
For this purpose, news headlines tend to be rich enough in content to provide insights into supply and demand changes. 
Even when significantly reducing the number of headlines to more reputable sources. 

Domain adaptation can be achieved to some extend by analyzing the properties of the target through literature review and creating a corresponding training dataset to fine-tune the model. 
For example, considering supply and demand changes regarding crude oil seems to be a suitable component for a domain adaptation.  

In order to advance sentiment analysis applications in the domain of crude oil, this paper presents CrudeBERT. 
In general, sentiment analysis of headlines from crude oil through CrudeBERT could be a viable source of insight for the price behaviour of WTI crude oil. 
However, further research is required to see if CrudeBERT can serve as beneficial for predicting oil prices. 
For this matter, it is made publicly available on the Hugging Face platform [https://huggingface.co/Captain-1337/CrudeBERT] for future research. 
