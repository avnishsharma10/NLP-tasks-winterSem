NLP -TASKS
NATURAL LANGUAGE PROCESSING
TASK 1

assign a sentence to a variable
assign a multiline paragraph to a variable -use triple quotes
assign a text in any language(except english) to a variable
Additional Tasks -Finding Frequencies of each word in the paragraph -Finding unique words and counting the number of words -Converting the paragraph in to a vector of words
Task 2

Finding errors in Google translate
Finding and analysing the reason for popularity of a politician in COCA(concordance search)
using Readable.com to just learn and know the parameters for readabolity of any paragraph
Character Encoding identification algorithm:

Library used chardet
Refrences
mozilla auto char encoding detection
Chardet Documentation
Charset detection Mozilla project

what it is? Based on the bytes of data it guess the charset.
What it is not? It doesn't just look at the meta data and find the encoding,it guess the encoding on unreliable data.
Refrence
Char detection: we could easily detect UTF-8 encoding as the top bits have a pattern and as the pattern reccurs we can confirm the encoding as UTF-8.This similar pattern recognition is used for UTF-1.

Other Refrences:

ICU Project
Charset detector
Typographic:

It basically is the visual component of a word.The font the stress in which it is written conveys meaning and emotion.
Orthographic:

Related to the conventional spelling of a word.Derived from greek words Ortho(Correct) and Graph(Writing). Eg: School is written as skool or awesome is written as ossum. This makes it difficult for processing.
Suprasegmental:

When we speak , we also include sounds that are above the level of segments,this is called Suprasegmental or Prosody.The primary pieces of suprasegmental information are pitch,stress,loudness.
JIEBA(A python moudle for chinese text segmentation)

segmenting the wiki of Zhu Shenghao Output
Detecting sentences in a text without punctuations: code demo

Tokenization:

It is the process in which a sequence of characters are chopped up into pieces(tokens).
Methods:
1.using python split() function
2.using regex
3.using Spacy
4.using keras
5.using nltk
Refrences: IBM Spacy StanfordNLP
Task 3:

working with brown and inaugural corpus
Removing stopwords from Lincoln's speech
finding the most used words in his speech
finding freqDist for the categories in brown corpus
finding the avg number of words in the president's speech.
Task 4:

working woth stop words and tokenizers
Magnum Opus Task 1:

Creating a corpus.This is a simple corpus in hindi which is made up of Narendra Modi's speeches .It consists of around 65000 words The data has been scraped from Narendra Modi's offical website.The data has been scraped using BeautifulSoup and made available publically at Modi-corpus.The website was created using node js
Task 5:

Stemming
lemmatizers
count vectorizier
Task 6

POS Tagging
Task 7

Chunking
Noun phrase chunking
Verb phrase chunking
prosodic chunking
Finding the most commonly used adjectives in articles for the top CEOs
