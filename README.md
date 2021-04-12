# SlovakSentimentLexicon
*Slovak Sentiment Lexicon built using crowdsourcing + Sentence-Level Sentiment Analysis dataset*

This repository contains 2 resources for sentiment analysis in Slovak language:
-  **Slovak Sentiment Lexicon**:
Lexicon was constructed using manual annotations of 170 sentences. The annotations were collected using crowdsourcing via game with a purpose named *Sentižrút*. The lexicon contains 546 single words. With additional n-grams (for *n*=2 up to 5), the lexicon contains total of 6364 entries. The lexicon is provided in JSON form, structured as follows:
```code
{
    1: {
        "word" : sentiment_category,
	...
    },
    2: {
        "word1,word2" : sentiment_category,
	...
    },
    ...
}
```
Lexicon quality was tested using very simple lexicon-based sentiment analysis methods on the dataset mentioned below. The achieved results spanned circa in interval *<0.4; 0.5>* for all tested metrics: Precision, Accuracy, Recall, and F1 Score.
Additional lexicons constructed using gathered annotations may be added later.
- ** Manually annotated sentence-level sentiment analysis dataset**
The dataset is built of 15 reviews, totalling to 1220 sentences. Each sentence was manually asigned a sentiment category from possibilities: { -2, -1, 0, 1, 2 }, corresponding to { *very negative, negative, neutral, positive, very positive* }.


Both the lexicon and the dataset are results of effort published as:
*To be added*
Usage of these resources as well as suggestions are encouraged. If you use them in academic research, we kindly ask you to quote the publication (be sure to check back occassionaly in case that the publication has not been added yet).
