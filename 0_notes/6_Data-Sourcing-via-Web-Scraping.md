# Data Sourcing via Web Scraping 

# BeautifulSoup Object 

## Web Scraping Use Cases

* Ecommerce Store Automation
* Hydrological Analysis
* Emergency Resource Allocation Plannning 
* Oil and Gas Production Intel

## Four BeautifulSoup Object Types

1. BeautifulSoup Object
2. Tag object
3. NavigatableString object
4. Comment Object

### The BeautifulSoup Object

* The BeautifulSoup object is a representation of the document you're scrapin, as a whole
* It is easilty navigatable and searchable 

### The Tag Object 

* Tag objexts correspond to XML and HTML elements in an original document
* You can navigate and reference data using tag attributes

### The NavigatableString Object

* A NatvigatableString object is to add a bit of text within a tag
* BeautifulSoup uses the NavigableString class as a container for bits of text

### The Comment Object

* The Comment Object is a type of NaviagbleString object that you can use for commenting your code. 

# NavigableString object

# Data parsing

## Working with Parsed Data in BeautifulSoup

1. Parsing data: just pass an HTML or XML document to the BeautifulSoup() constructor; the constructor converts the document to unicode and then parses it with a built in HTML parser (by default)
2. Getting data from a parse tree
3. Searching and retrieving data from a parse tree

## Searching and Retrieving Data

**The find_all() method:**

* Searches a tag and its descendants to retrieve tags or strings that match your filters. 

**Methods for searching and filtering a parse tree:**

* Name argument
* Keyword argument
* String argument
* Lists
* Boolean values
* Strings
* Regular expressions

You can pass any of these arguments into the find_all() method to use as filters and return either strings or tags

# Web scraping in practice 

## Demonstrating Web Scraping

1. Scraping a webpage
2. Saving web scraping results

# Introduction to NLP (natural language processing)

## Sentence Tokenization 

Sentence tokenization is the process of breaking down paragraphs or a complete set of text into sentences.   

### An Example of Sentence Tokenization 

* Plain sentence: "Geoffrey Hinton, Yann LeCun, and Yoshua Bengio won Turing award this year. They have been awarded for their significant contribution in the field of artificial intelligence."
* The output is an array with two elements

## Word Tokenization

Word tokenization is the process of breaking down a paragraph, a sentence, or a complete text corpus into an array of words.

### An Example of Word Tokenization

* Plain sentence:"They have been awarded for their significant contribution in the field of artificial intelligence"
* Tokenized output:['They', 'have', 'been', 'awarded', 'for', 'their', 'significant', 'contribution', 'in', 'the', 'field', 'of', 'artificial', 'intelligence']

## Stop Words

Stop words are extremely common (thus, general) words that add little to little meaning to a body of text at large. 

Stop words can be thought of as a noise in the corpus of a body of text. 

### Examples of Stop Words

* Examples of stop words include "a", "these", "they'd", "do", "have", "you"

### Removing Stop Words

Since stop words carry little meaning from within a large body of text, they are removed from the corpus

Advantages of removing stop words include:

* Removes noise
* Reduces the size of textual data to be analyzed

We will be using the Natural Language Toolkit (NLTK) library in Python to do our NLP demo

A nice thing about NLTK is that it has a set of stop words already defined within it, so you don't ahve to waste your time putting that together

## Stemming 

Stemming is a process of reducing the size of the corpus by converting words to their root word. 

Stemming is basically a process for linguistic normalization. 

## Stems 

Stems (or word stems) are simply parts of words. 

### Example of Stemming 

* Raw text: "run", "ran", "running"
* Root word: "run"

### Root Words vs. Base Words

* Root word: a stem word that may, or may not have meaning when taken alone
* A root word from which other words are derived 
* The primary form of a word, upon which derivates are made

* Base word: a stem word that has meaning, even when taken alone
* It is a base word that used outright within a language with only prefixes or suffixes being attached
* It is the simplest form of a word

## Lemmatizing

Lemmatizing is the process of reducing a word to its base word.

### Example 

Stemming
* Raw text: "better"
* Root word: "better"

Lemmatizing
* Raw text: "better"
* Base word: "good"

## Part of Speech Tagging

The process of identifying a part of speech within a given body of text

![image](https://user-images.githubusercontent.com/76530973/194639594-27d9d5ac-9331-4183-bb25-94d66b76602e.png)

![image](https://user-images.githubusercontent.com/76530973/194639637-c53e31ab-8542-4bda-bd73-31a1f1d8a64d.png)

![image](https://user-images.githubusercontent.com/76530973/194639791-fa7f9a39-0a1e-47c5-89f5-d912bfde7cf7.png)

## Frequency Distribution Plotting

Frequency distribution plotting is the initial step towards quantifying a textual corpus.

It counts and plots the frequence of words in a given text. 

* Why it matters: this can be used for sentiment analysis and to understand the distribution of words

# Cleaning and stemming textual data

# Lemmatizing and analyzing textual data
