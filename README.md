# Python text mining

In order to be successful in this course, you will need to know how to program in Python. The expectation is that you have completed the first three courses in this Applied Data Science with Python series, specifically Course 1 on Introduction to Data Science in Python and Course 3 on Applied Machine Learning in Python, so that you are familiar with the numpy and pandas Python libraries for data manipulation, and scikit-learn toolkit for machine learning algorithms.

## Primitive constructs in Text

* Sentences / input strings
* Words or Tokens
* Characters
* Document, larger files

In this course in python we are tolking about all this concepts and their properties

## Week 1

Les liens utils:

1. https://docs.python.org/3/library/re.html

2. https://www.analyticsvidhya.com/blog/2014/11/text-data-cleaning-steps-python/

3. https://ieva.rocks/2016/08/07/cleaning-text-for-nlp/

4. https://chrisalbon.com/python/cleaning_text.html

## Week 2
In this module, we will tolk to **Natural Language**

### What is Natural Language ?

* Language used for everyday communication by humans
   * English
   * Chinese
   * spanish

compared to the artificial computer language

* Any computation, manipulation of natural language
* Natural language evolve
  * new words get added
  * old words lose popularity
  * language rules themselves may change.

## NLT Task: A Broad Spectrum

* Computing words, counting frequency of words
* Finding sentence boundaries
* Part of speech tagging
* Parsing the sentence structure
* Identifying semantic roles
* Identifying entities in a sentences
* Finding which pronoun refers to which entity

## An Introduction to NLTK

* NLTK: Natural Language Toolkit
* Open source library in Python
* Has support for most NLP tasks
* Also provides access to numerous text corpora

## Usage of NLTK

* Importation<br/>
    <code>import nltk</code>

* Let's get some text corpora<br/>
    <code>nltk.download()</code>

    <code>from nltk.dowload()</code><br>

    for more information see lab week2

## Tokenization

* Recall splitting a sentence into words / tokens

## Part-of-speech (POS) Tagging

* Recall high school grammar: nouns, verbs, adjectives,...<br/>
  ![image 2](images/2.png)

## Ambiguity in POS Tagging  

  ![image 3](images/3.png)
## Parsing Sentence Structure

  ![image 4](images/4.png)

## Ambiguity in Parsing 

![image 5](images/5.png)

![image 6](images/6.png)

## POS Tagging & Parsing Complexity

![image 8](images/8.png)

## Task Home Concepts

![image 10](images/10.png)

## Examples of Text Classification

![image  11](images/12.png)

## Supervised Learning

![image  12](images/13.png)

## Supervised Classification Step

![image  14](images/14.png)

## Supervised Classification Model

![image  15](images/15.png)

## Divide Dataset in two parts

![image  16](images/17.png)

## Classification paradigms

![image  19](images/19.png)

## Questions to ask in Supervised Learning

![image 20](images/21.png)

## Why is textual data unique ?

![image 22](images/22.png)

## Types of textual features (1)

![image 23](images/23.png)

## Types of textual features (2)

![image 24](images/24.png)

## Types of textual features (3)

![image 25](images/25.png)

## Naive Bayes Classifiers

## Case study: Classifying text search queries

![image 26](images/26.png)

![image 27](images/27.png)

## Probabilistic model

![image 29](images/29.png)

## Bayes' Rule

![image 30](images/30.png)

## Naive Bayes Classification

![image 32](images/32.png)

![image 33](images/33.png)

## Example classification

![image 34](images/34.png)

## Na??ve Bayes: Learning parameters

![image 35](images/35.png)

![image 37](images/37.png)

## Na??ve Bayes: Smoothing

![image 38](images/38.png)

## Take Home Concepts

![image 39](images/39.png)

## Two Na??ve Bayes Variants For Text

![image 40](images/40.png)

## Support Vector Machine

## Decision Boundaries

![image 41](images/41.png)

## Choosing a Decision Boundary

![image 42](images/42.png)

## Finding a Linear Boundary

![image 44](images/44.png)

![image 45](images/45.png)

![image 46](images/46.png)

## SVM: Multi-class classification

![image 47](images/47.png)

![image 48](images/48.png)

![image 49](images/49.png)

![image 50](images/50.png)

![image 51](images/51.png)

![image 52](images/52.png)

## SVM Parameters (1): Parameter C

![image 53](images/53.png)

## SVM Parameters (2): Others Params

![image 54](images/54.png)

## Take Home Messages

![image 55](images/55.png)

## Using Sklearn's NaiveBayesClassifier

![image 57](images/57.png)

## Using Sklearn's SVM Classifier

![image 58](images/58.png)

## Model Selection in Scikit-learn

![image 60](images/60.png)

![image 59](images/59.png)

## Supervised Text Classification in NLTK

![image 61](images/61.png)

## Using NLTK's NaiveBayesClassifier

![image 62](images/62.png)

## Using NLTK's SkearnClassifier

![image 63](images/63.png)

## Take Home Concept

![image 65](images/65.png)


## Application of semantic similarity
![image 68](images/68.png)

## WordNet

![image 69](images/69.png)

## Semantic similarity using WordNet

![image 70](images/70.png)

## Coming back to our deer example

![image 71](images/71.png)

## Similarity with NLP in Python 

![image 66](images/66.png)

## Distributional Similarity: Context

![image 72](images/72.png)

## Strength of association between words

![image 75](images/75.png)
## Take Home Concepts

![image 67](images/67.png)

## What is Topic Modeling ?

![image 76](images/76.png)

![image 77](images/77.png)

![image 78](images/78.png)

## Generative Models for Text

![image 79](images/79.png)

## Generative Model can be complex

![image 80](images/80.png)

## Latent Dirichlet Allocation (LDA)

![image 81](images/81.png)

## Topic Modeling in Practice

![image 82](images/82.png)

## Topic Modeling: Summary

![image 83](images/83.png)

## Working with LDA in Python

![image 86](images/86.png)

![image 88](images/88.png)

## Take Home Concepts

![image 89](images/89.png)

## Information is hidden in free-text

![image 90](images/90.png)

## Information Extraction

![image 92](images/92.png)

## Fields of Interest

![image 93](images/93.png)

## Named Entity Recognition

![image 94](images/94.png)

## Approche to identify named entities

![image 95](images/95.png)

![image 96](images/96.png)

## Relation extraction

![image 97](images/97.png)

## Co-reference resolution

![image 98](images/98.png)

## Question Answering

![image 99](images/99.png)

## Take Home Concepts

![image 100](images/100.png)

## Additional Resources & Readings

* [http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)

* [https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)

* [https://en.wikipedia.org/wiki/Plate_notation](https://en.wikipedia.org/wiki/Plate_notation)

* [https://www.nltk.org/howto/wordnet.html](https://www.nltk.org/howto/wordnet.html)
