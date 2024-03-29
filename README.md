# SlovakSentimentLexicon
*Slovak Sentiment Lexicon built using crowdsourcing + Sentence-Level Sentiment Analysis dataset*

This repository contains 2 resources for sentiment analysis in Slovak language:
-  **Slovak Sentiment Lexicon**:
Lexicon was constructed using manual annotations of 170 sentences. The annotations were collected using crowdsourcing via game with a purpose named *Sentižrút*. The lexicon contains 920 single words. The lexicon is provided in JSON form, structured as follows:
```code
{
    "word1" : sentiment_category,
    "word2" : sentiment_category,
    ...
}
```
Additional lexicons constructed using gathered annotations may be added later.
- **Manually annotated sentence-level sentiment analysis dataset**
The dataset is built of 15 reviews, totalling to 1220 sentences. Each sentence was manually asigned a sentiment category from possibilities: { -2, -1, 0, 1, 2 }, corresponding to { *very negative, negative, neutral, positive, very positive* }. Dataset is split into 15 excel files (one file holds one review). One row contains one sentence in the first column, sentiment category in second column. Categories are highlighted using conditioned formatting for visual intent. Note that words are lemmatized.


Both the lexicon and the dataset are results of effort published as:

*Radoský, L., Blšták, M. (2021). Constructing Sentiment Lexicon with Game for Annotation Collection. In: Espinosa-Anke, L., Martín-Vide, C., Spasić, I. (eds) Statistical Language and Speech Processing. SLSP 2021. Lecture Notes in Computer Science(), vol 13062. Springer, Cham. https://doi.org/10.1007/978-3-030-89579-2_4*

Usage of these resources as well as suggestions are encouraged. If you use them in academic research, we kindly ask you to quote the publication (be sure to check back occassionaly in case that the publication has not been added yet).
