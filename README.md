# Email_spam_classifier
# Text data preparation, email spam classification , sklearn.feature_extraction.text.CountVectorizer



class sklearn.feature_extraction.text.CountVectorizer(*, input='content', encoding='utf-8', decode_error='strict', strip_accents=None, lowercase=True, preprocessor=None, tokenizer=None, stop_words=None, token_pattern='(?u)\b\w\w+\b', ngram_range=(1, 1), analyzer='word', max_df=1.0, min_df=1, max_features=None, vocabulary=None, binary=False, dtype=<class 'numpy.int64'>)[source]


Convert a collection of text documents to a matrix of token counts.

ngram_rangetuple (min_n, max_n), default=(1, 1)
The lower and upper boundary of the range of n-values for different word n-grams or char n-grams to be extracted. All values of n such such that min_n <= n <= max_n will be used. For example an ngram_range of (1, 1) means only unigrams, (1, 2) means unigrams and bigrams, and (2, 2) means only bigrams. Only applies if analyzer is not callable.


 - unigrams: Sequence of one words element    
 - bigrams: Sequence of two words element
 
 
 
-------------------------------------------------------
References:    
1- https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html.   
2- https://scikit-learn.org/stable/modules/feature_extraction.html.  
