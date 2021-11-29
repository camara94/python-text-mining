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

## Naïve Bayes: Learning parameters

![image 35](images/35.png)

![image 37](images/37.png)

## Naïve Bayes: Smoothing

![image 38](images/38.png)

## Take Home Concepts

![image 39](images/39.png)

## Two Naïve Bayes Variants For Text

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

## Take Home Message