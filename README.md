Download Link: https://assignmentchef.com/product/solved-cs6370-assignment1-part1
<br>
The goal of the assignment is to build a search engine from scratch, which is an example of an information retrieval system. In the class, we have seen the various modules that serve as the building blocks of a search engine. We will be progressively building the same as the course progresses. The first part of this assignment is to build a basic text processing module that implements sentence segmentation, tokenization, stemming/lemmatization and stopword removal. The Cranfield dataset will be used for this purpose, which has been uploaded separately on Moodle.

<ol>

 <li>What is the simplest and obvious top-down approach to sentence segmentation for English texts?</li>

 <li>Does the top-down approach (your answer to the above question) always do correct sentence segmentation? If Yes, justify. If No, substantiate it with a counter example.</li>

 <li>Python NLTK is one of the most commonly used packages for Natural Language Processing. What does the Punkt Sentence Tokenizer in NLTK do differently from the simple top-down approach? You can read about the tokenizer <a href="https://www.nltk.org/_modules/nltk/tokenize/punkt.html">here</a><a href="https://www.nltk.org/_modules/nltk/tokenize/punkt.html">.</a></li>

 <li>Perform sentence segmentation on the documents in the Cranfield dataset using:

  <ul>

   <li>The top-down method stated above</li>

   <li>The pre-trained Punkt Tokenizer for English</li>

  </ul></li>

</ol>

State a possible scenario along with an example where:

<ul>

 <li>the first method performs better than the second one (if any)</li>

 <li>the second method performs better than the first one (if any)</li>

</ul>

<ol start="5">

 <li>What is the simplest top-down approach to word tokenization for English texts?</li>

 <li>Study about NLTK’s Penn Treebank tokenizer <a href="https://www.nltk.org/_modules/nltk/tokenize/treebank.html">here</a><a href="https://www.nltk.org/_modules/nltk/tokenize/treebank.html">.</a> What type of knowledge does it use – Top-down or Bottom-up?</li>

 <li>Perform word tokenization of the sentence-segmented documents using

  <ul>

   <li>The simple method stated above</li>

   <li>Penn Treebank Tokenizer</li>

  </ul></li>

</ol>

State a possible scenario along with an example where:

(a) the first method performs better than the second one (if any)

Assignment Part 1            Page 1 (b) the second method performs better than the first one (if any)

<ol start="8">

 <li>What is the difference between stemming and lemmatization?</li>

 <li>For the search engine application, which is better? Give a proper justification to your answer. <a href="https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html">This</a> is a good reference on stemming and lemmatization.</li>

 <li>Perform stemming/lemmatization (as per your answer to the previous question) on the word-tokenized text.</li>

 <li>Remove stopwords from the tokenized documents using a curated list of stopwords (for example, the NLTK stopwords list).</li>

 <li>In the above question, the list of stopwords denotes top-down knowledge. Can you think of a bottom-up approach for stopword removal?</li>

</ol>