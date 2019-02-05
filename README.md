# Arabic text preprocessing
In this notebook you will find all the functions that we use to process a text

## What this notebook contains ?

<ul>
  <li>
    <b>Transliteration : </b> We've created a library named <a href='https://github.com/saobou/DSAraby'>DSAraby</a> that aims to transliterate text which write a word using the closest corresponding letters of a different alphabet or language. The algorithm gives the possible words in Arabic based on a given word in Latin by mapping Latin letters to Arabic ones, then takes the most frequent word existing in a corpus.
  </li>  
  <li>
    <b>Text Normalization : </b> is the process to transform a text to a unified form, remove Al-tashkil and elongation.
    <img src='assets/tashkil.png' />
  </li>
  <li>
    <b>Stop words : </b> is the process to remove useless words from a text, in Arabic there is a lot of stop words than any other language, for example : أيّان,هَيْهَاتَ, مابرح
  </li>
  <li>
    <b>Dealing with hashtags</b>
  </li>
  <li>
    <b>Dealing with Emojis</b>
  </li> 
  <li>
    <b>Removing Links.</b>
  </li> 
  <li>
    <b>RT, CC, Mentions.</b>
  </li> 
  <li>
    <b>Filtered all non-Arabic text</b>
  </li> 
   <li>
    <b>Remove digits, dash, punctuation marks and any other mark.</b>
  </li>
  
</ul>
