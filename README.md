# Text-pre-processing-for-NLP-using-nltk
<h1> Stemming </h1>
Stemming is a technique used to extract the base form of the words by removing affixes from them. It is just like cutting down the branches of a tree to its stems. For example, the stem of the words eating, eats, eaten is eat.</br>

Search engines use stemming for indexing the words. That’s why rather than storing all forms of a word, a search engine can store only the stems. In this way, stemming reduces the size of the index and increases retrieval accuracy.</br>

<h1> Lemmatization </h1>
Lemmatization technique is like stemming. The output we will get after lemmatization is called ‘lemma’, which is a root word rather than root stem, the output of stemming. After lemmatization, we will be getting a valid word that means the same thing.</br>

![image](https://user-images.githubusercontent.com/67821036/140009647-38217c7d-1853-4e25-bdf2-4d61ec325193.png)

<h1> Tokenization </h1>
Tokenization is a way of separating a piece of text into smaller units called tokens. Here, tokens can be either words, characters, or subwords. Hence, tokenization can be broadly classified into 3 types – word, character, and subword (n-gram characters) tokenization.</br>
![image](https://user-images.githubusercontent.com/67821036/140010298-559bed7c-73a7-47ec-b3c0-053ea7d8fcae.png)

<h1> Bag of Words </h1>
A bag-of-words model, or BoW for short, is a way of extracting features from text for use in modeling, such as with machine learning algorithms.</br>
A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things:</br>

1.A vocabulary of known words.</br>
2.A measure of the presence of known words.</br>
![image](https://user-images.githubusercontent.com/67821036/140009896-5e0052bd-a90e-42d1-a2e6-8b245bbeada4.png)


<h1> TF-IDF </h1>
TF-IDF stands for Term Frequency Inverse Document Frequency of records. It can be defined as the calculation of how relevant a word in a series or corpus is to a text. The meaning increases proportionally to the number of times in the text a word appears but is compensated by the word frequency in the corpus (data-set).</br>
![image](https://user-images.githubusercontent.com/67821036/140009999-d17eb3fc-8b5a-4cff-8b32-aa26a22bbd90.png)

<h1> Word2Vec </h1>
Each word is basically represented as a vector of 32 or more dimensions insted of a single number. These vectores help in representing semantic meaning aw well as finding similarities between words in a document.
![image](https://user-images.githubusercontent.com/67821036/140010160-3509dfa4-c941-4d2b-ac08-b1e540524a88.png)
