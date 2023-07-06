# Top 2023 Fashion Trends

**Summary** 

Fashion is an ever-evolving industry, constantly generating excitement and anticipation for the next big trends. This project leverages Natural Language Processing (NLP) techniques to identify the most anticipated fashion trends for 2023. The outcomes can provide guidance to production decisions and empower consumers, enabling them to inform their purchasing choices with the projected trends for the year.

Objectives:
* Determine the predominant fashion trend predictions for 2023
* Scrape data from 10 articles sourced from prominent fashion websites
* Employ text cleaning, topic modeling, and term frequency analysis to derive insights

**Methodology**

This project scrapes the text from 10 different fashion articles to conduct Natural Language Processing (NLP) to identify the most frequently used terms and topics from all of the sources, suggesting what will be the most anticipated trends of 2023.

**Data Acquisition**

First, utilizing the libraries "rvest" and "stringr", the project reads in the 10 htmls. Next, we prepare each individually for usage by removing unnecessary text and filtering out names of brands, designers, or celebrities, as well as any of these articles’ own names. After cleaning the articles individually, we combine them.

**Natural Language Processing (NLP)**

Next, we conduct Natural Language Processing (NLP) on the unstructured text, using document term frequencies and topic models.

First, this conducts a document term frequency matrix. To begin, I read in the necessary libraries "dplyr", "quanteda", "stm", "tm", and "textstem". Next, we convert the text to be model readable. The next step is to create the corpus with document variables to finally conduct the document term frequency. The document term frequency identifies what are the most frequently used terms throughout all of the combined articles.
 
The second NLP analysis we conduct is topic models. We first perform a KTest to identify the most appropriate number of topics. As this has fairly unique results, we conduct a topic model utilizing both 20 topics and 5 topics, and compare results.

**Results** 

When combining the results of Natural Language Processing methods, we find that in 2023, consumers can anticipate seeing:

* Variations of skirt and dress lengths
* Sheer/ cutout design elements
* Silk, leather, cotton
* Crochet/ fringe looks
* Resurgence of denim and jean
