# ADS Project 1:  R Notebook on Lyrics Analysis

This Project aims to utilize text mining and NLP tools to analyze semantic pattern under 120,000 + lyrics

In Preprocessing part, I add more contraction words, such as 'youre','ill','havent' to stopwords. 

With wordcloud2, I investigate the most popular words in whole lyrics, and in different genres. For example, for all lyrics, the most popular words are 'love','time','girl','night'; For Country, the most frequent words are similar. However, for Hip-hop style song, some dirty words such as 'die','shit','ass', although love is still very popular.

Therefore, next step I use a basic model Naive Bayes to fit the data. I split the data into training (75%) and test sets. And I found that the accuracy is rather low. Among them, the 'Metal', 'Hip-Hop' and 'Jazz' style have relatively higher accuracy, although still at the low level. So I have the conclusion that the lyrics for different songs have semantic patterns without huge difference.
