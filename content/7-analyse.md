---
title: Analyse
nav: true
---

# Process & Analyse - methods and tools

-----

## Pathways to analysis

no matter what data you are starting with, it is important that you have an idea of what outcomes you are looking for. For analysis we need:
- data set
- clean data, transcibe, annotated 
- processed by a computational method

### Processing methods

Once the text is cleaned and formatted it can be computationally processed by a number of different methods, depending on your analysis needs.

#### Natural language processing (NLP) techniques

Natural language processing (NLP) is the branch of artificial intelligence (AI) that deals with training a computer to understand, process, and generate language. Search engines, machine translation services, and voice assistants are all powered by the technology. (https://www.cio.com/article/228501/natural-language-processing-nlp-explained.html view 19-01-2021)

NLP tools break down text into analysable parts, these include:

-	Tokenization - Split the text into sentences and sentences into words.  Change to lowercase and remove punctuation.  This is creates a 'bag of words' for analysis


-	Part-of-speech tagging
-	Shallow parsing
-	Named entity extraction
-	Syntactic parsing (Tsuruoka, n.d.) 

<<<<IMAGE HERE>>>>

## Computational Analysis

The use of computational analysis techniques in humanities reserach is the start point of Digital humanities research. Using code for analysis can show us paterns and connections not seen through close reading alone and can help us find greater meaning in the data. R and Python are the most popular code used  to analyse corpus.

### Common types of analysis
Once the data has been processed, we can undertake analysis tasks such as:
- Find and compare instances of particular terms over time from particular source collection
- Word frequency analysis and visualisation via word clouds
- Topic modeling - "identify groups of terms that tend to be representative of a given topic" (Toon, 2016)
- Named entity recognition, to find either person or place, or both.  
- Machine learning https://en.wikipedia.org/wiki/Machine_learning & https://www.zdnet.com/article/what-is-machine-learning-everything-you-need-to-know/
- sentiment analysis - a natural language processing technique used to determine whether data is positive, negative, or neutral.
- mapping - to show locations and even movements of people or ideas, growth of cities and how landscapes have been changed.
- plotting data 

----
## Plug and Play analysis tools

Plug and play tools are interfaces where you can easily add data and analysis is done for you. The tools run on your web browser and are also know as Graphic user interface or GUI tools. The majority of these tools will be based up python or R analysis codes. We can use these tools for simple data analysis and visulations, they are really useful in getting started with analysis and getting an idea of what your data holds. 

- Pro's - easy to use, high level analysis, 
- Cons - often inflexible, not good for deeper analysis, may not be able to use with identifiable data

### Gale Digital Scholar Lab 
Gale Digital scholar lab is subscription service with tools that can build, clean and analyse text based data. The lab is designed to use the Gale Primary Source archives, but you can use the analysis tools with your own data.
Find out more about Gale Digital Scholar Lab <a href ='https://go-gale-com.libraryproxy.griffith.edu.au/ps/start.do?p=DSLAB&u=griffith' target="_blank"> here </a> (login required)  and <a href ='https://sway.office.com/v4sYacFkErbH9HNo' target="_blank"> here. </a>

### Open source tools
- <a href ='https://voyant-tools.org/' target="_blank"> Voyant </a>
- <a href ='https://rawgraphs.io/' target="_blank"> Raw graphs </a>

----

#### Sentiment analysis
Sentiment analysis is commonly used in research to see public sentiment on products, ideas or policy. It is useful when scanning social media or comments sections to see the response to ideas, good or bad. 

This tool will show you the sentiment of one resource, 
 - <a href = 'https://www.danielsoper.com/sentimentanalysis/default.aspx' target="_blank"> Free Sentiment Analyzer from Prof. Soper </a>

zero being neutral, over zero positive sentiment and less than zero negative. 

Sentiment analysis is available in Gale digital scholars lab, but is more commonly utilized through code where you can analyze multiple documents at a sentence level.  


{% capture text %}
in this activity try the plug and play tools listed. look at the results, look for the opportunity for use to the analysis and the limitations of each tool.{% endcapture %} {% include card.md header="Activity" text=text %}


#### Support and training 

*Sentiment analysis*

[Top 5 Unknown Sentiment Analysis Projects On Github To Help You Through Your NLP Projects - 2021](https://medium.com/analytics-vidhya/top-5-unknown-sentiment-analysis-projects-on-github-to-help-you-through-your-nlp-projects-8d8f195e80fc) 

{% capture text %}
For this activity take a look at the example DH project,  think about the process taken to get from the original resources to the final analyzed product.
If possible, see if you can identify the tools and coding packages used to undertake the project.{% endcapture %} {% include card.md header="Activity " text=text %}

-----


{% capture text %}
- Activity.{% endcapture %} {% include card.md header="Activity - ..." text=text %}


{% include button.md text="Watch this video for instructions" link="https://vimeo.com/...." color="info" %}

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/5-build.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/7-vis.html">NEXT --></a>
</p>
