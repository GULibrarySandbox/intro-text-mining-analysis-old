---
title: What
nav: true
---
# What is text mining and analysis?

-----
### Insights from text 

Text is the main form for "communicating, discovering and processing information" (Sinclair and Rockwell, 2016).  Even popular non written forms of communication such as streamed videos are largely inaccessible without text-based searches of metadata such as title, description or creator.  

We are all, regardless of discipline, methodology, or objective, trying to gain insights from text.

- communication scholars analyse [news texts](https://doi-org.libraryproxy.griffith.edu.au/10.1080/17524032.2015.1056542) and [social media feeds](https://doi-org.libraryproxy.griffith.edu.au/10.1080/13669877.2019.1673798)
- qualitative sociologists process and analyse hundreds of hours of [interview transcripts](https://research-repository.griffith.edu.au/handle/10072/386927) 
- political scientists analyse [collections of speeches](https://research-repository.griffith.edu.au/handle/10072/401011) and [parliamentary transcripts](https://doi.org/10.1017/S0738248016000304)
- engineering researchers examine [accident reports](https://ieeexplore-ieee-org.libraryproxy.griffith.edu.au/document/7277059)
- historians access primary source materials from remote repositories enabling broader perspectives and [new research](https://research-repository.griffith.edu.au/handle/10072/380293)
- literary scholars work with digitized [single texts](https://academic-oup-com.libraryproxy.griffith.edu.au/dsh/article/32/suppl_1/i17/2755123), [multiple versions](http://librarycatalogue.griffith.edu.au/record=b2773844) of text, [whole corpus or person-of-interest collections](https://publications.hse.ru/en/chapters/158772968)
- environmental scientists undertake [network analysis of research literature](https://research-repository.griffith.edu.au/handle/10072/403109)
- medical researchers analyse electronic [patient records](https://link-springer-com.libraryproxy.griffith.edu.au/book/10.1007/978-3-319-78503-5)
- legal scholars examine [case law and legislation](https://www-annualreviews-org.libraryproxy.griffith.edu.au/doi/10.1146/annurev-lawsocsci-052720-121843#_i9)

### Computational methods

Text mining is the use of computational methods to extract data from collections of unstructured or semi-structured text. In the humanities this is often described as distant reading of a corpus (text collection).  The goal of text mining is to discover & extract information or patterns hidden in text.  

There is a long research tradition in text analysis in the humanities and with the explosion in digital text, computational analysis methods have developed in fields including statistics, computer science, (computational) linguistics, and library science.


### Processing

### Computational processing of text to extract data

Natural language processing (NLP) techniques

-	Sentence splitting
-	Tokenization
-	Part-of-speech tagging
-	Shallow parsing
-	Named entity recognition
-	Syntactic parsing
-	(Semantic Role Labeling)?? source: Dr. Yoshimasa Tsuruoka's tutorial at the National Centre for Text Mining here: http://www.nactem.ac.uk/teaching/ 

Machine learning 

The processes then enable tasks such as:

- "find and compare the number of instances of particular terms over time in a defined corpus"
- "finding the relative frequency of the words in a text and then visualising these in a way that makes the different frequencies apparent, for example, by size and position in word clouds"
- topic modeling - "identify groups of terms that tend to be representative of a given topic" Toon, E., Timmermann, C., & Worboys, M. (2016). Text-mining and the history of medicine: Big data, big questions? Medical History, 60(2), 294-296. https://doi.org/10.1017/mdh.2016.18 
- named entity recognition 

Computational text analysis methods include:
- thematic analysis
- sentiment analysis
- content analysis
- network analysis 
- 


### Uses in research 

You can use computational methods with text to:
- increase [validity](https://doi-org.libraryproxy.griffith.edu.au/10.1177%2F1466138117725340)
- [repeat processes and analysis](https://glam-workbench.net/hansard/) on other other text or corpus
- enable broader questions of [larger corpora](https://muso.arts.gla.ac.uk/index.html)
- help understand texts and [underlying social and cultural phenomena at scale](https://ebookcentral-proquest-com.libraryproxy.griffith.edu.au/lib/griffith/detail.action?docID=5772971)
- expand textual studies with [temporal or geographical context](https://glam-workbench.net/web-archives/#exploring-change-over-time)
- create [visual exploration](http://www.sixdegreesoffrancisbacon.com/) of text
- use [statistical analysis methods](https://journals-sagepub-com.libraryproxy.griffith.edu.au/doi/pdf/10.1177/1532673X02030002003)



{% capture text %}
- Map the meaning of the dataset to its structure, see ['Tidy data'](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html) by [Hadley Wickham](http://hadley.nz/){% endcapture %} {% include card.md header="Clean & standardise data" text=text %}


{% include figure.html img="MessyData.JPG" alt="Messy Data" caption="Messy Data" width="100%" %}



<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/2-why.html">NEXT --></a>
</p>
