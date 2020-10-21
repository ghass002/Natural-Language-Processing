# Natural-Language-Processing
## Steps for Natural Language Procssing using Python NLTK

### 1. Tokenization: 
  - Break a complex sentence into words
  - Understand the importance of each of the words with respect to the sentence
  - Produce a structural description on an input sentence-
  - Bigrams: Tokens of two consecutive written words
  -Trigrams: Tokens of 3 consecutive written words
  -Ngrams: Tokens of any number of consecutive written words defined by the user

2. Stemming
  - Normalize words into its base form or root form
  
3. Lemmatization
  - Groups together different inflected forms of a word, called Lemma
  - somehow similar to Stemming as it maps several words into one common root
  - Output of Lemmatisation is a proper word
  - For example, a Lemmatiser should map gone, going and went into go
  
4. Get rid of Stopwords

5. POS TAGS: Each word in a sentence has a TAG: wether it is a noun, adjective, adverb...etc

6. Name Entity Recognition
  - Noun Phrase Identification: extracting all the noun phrases 
  - Phrase Classification: Classification into respective categories such us locations, names..
  - Entity Disambiguation
  
7. Chunking: picking up individual pieces of information and grouping them into bigger pieces: Grouping of tokens
