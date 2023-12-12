# SPED7500-2023F

The project aims to analyze the dataset containing information on the civic engagement of parents of individuals with intellectual and developmental disabilities (IDD) based on their open-ended responses. The analysis involves the following steps:

1. The responses are accessed and processed using Colab, a cloud-based platform for running Python code, and Pandas, a library for data manipulation and analysis.
2. The CEWs list, which contains words related to civic engagement, and the Bing Sentiment Lexicon, which contains words with positive or negative polarity, are imported into Colab for further analysis.
3. The responses are analyzed using spaCy, a library for natural language processing (NLP), to measure the sentiment and the use of language. Specifically, spaCy is used to calculate the normalized frequency of parts of speech (POS) tags, such as adjectives, adverbs, and verbs, that match the words in the sentiment lexicon. This indicates the parents' expression of their emotions and attitudes towards civic engagement.
4. SpaCy is also used to calculate the semantic similarity, which is a measure of how closely related two words are in meaning, within the content words of each response, as well as between the content words of the responses and the CEWs list. This indicates the parents' consistency and relevance in their responses to the topic of civic engagement.
5. The results of the spaCy analysis are appended to the Pandas dataframe, which contains the original responses and other variables, and exported for further analysis or visualization.
