# nlp-clickbait-transfers

Thesis Project develop a style trasnfer for new title by transforming it to clickbait title. Develop using dataset from CLICK-ID: A novel dataset for Indonesian clickbait headlines (Yunita, William 2020). 

In this research, we present an implementation for transferring non-clickbait sentences to clickbait sentences for Indonesian news headlines. The research uses a prototype editing method, which demonstrates the application of the Delete, Retrieve, Generate approach based on encoder decoder models for the Indonesian language. Using an Indonesian headline news datasets with 15,000 annotated headlines labeled as clickbait and non-clickbait, the research applies BLEU and loss metrics to assess the end results of text style transfers

The results of this research show the potential of the Delete, Retrieve, Generate approach in clickbait headline style transfer based on the DeleteOnly model with the best result achieved in validation both BLEU metrics 0.1628 and 4.5428 loss. However, it also shows limited ability when using the DeleteRetrieve approach in terms of retrieving clickbait attributes with result only achieve BLEU metrics 0.0022 and 7.976 loss both validation. Both models show contrasting performance results in training and validation, highlighting the challenges posed by the limited amount of data available.

Keywords: Clickbait, Text Style Transfer, Encoder Decoder Model, News datasets
