---
title: Analyse
nav: true
---

# Process & Analyse - methods and tools

-----

### Processing methods

Once the text is cleaned and formatted it can be computationally processed by a number of different methods, depending on your analysis needs. Explore some of popular the methods below. It is important to note that you will still need to make meaning of and from the results.

#### Natural language processing (NLP) techniques

Natural language processing (NLP) is the branch of artificial intelligence (AI) technology to train a computer to understand, process, and generate language. Search engines, machine translation services, and voice assistants are all powered by the technology. Source: [Bell & Olavsrud, 2021](https://www.cio.com/article/228501/natural-language-processing-nlp-explained.html view 19-01-2021)

NLP tools break down text into analysable parts, these include:

-	Tokenization - Split the text into sentences and sentences into words.  Change to lowercase and remove punctuation.  This is creates a 'bag of words' for analysis
-	Part-of-speech tagging
-	Shallow parsing
-	Named entity extraction
-	Syntactic parsing (Tsuruoka, n.d.)
-	Stylometry: method of studying a linguistic style. 

{% include figure.html img="BagOfWords.PNG" alt="Bag of words" caption="Natural Language Processing - tokenization" width="100%" %}

#### Machine learning
Machine learning is a branch of AI and process of teaching a computer system to recognise patterns in text without explicit human programming. Machine learning can be either unsupervised (with minimal human intervention) or supervised (with more human intervention). Explore machine learning from [Heath, 2020](https://www.zdnet.com/article/what-is-machine-learning-everything-you-need-to-know/). Analysis using Machine learning includes topic modelling, and Naive Bayes Classification, which are detailed below.


## Common types of Computational analysis tasks

{% include figure.html img="TextAnalysisTasks.PNG" alt="Text analysis tasks" caption="Text analysis tasks" width="100%" %}
Image Source: Jänicke, S., Franzini, G., Cheema, M. F., & Scheuermann, G. (2017, September). Visual text analysis in digital humanities. In Computer Graphics Forum (Vol. 36, No. 6, pp. 226-250) [https://doi-org.libraryproxy.griffith.edu.au/10.1111/cgf.12873](https://doi-org.libraryproxy.griffith.edu.au/10.1111/cgf.12873)

Analysing similar text patterns:
- `Linguistic patterns` such a word frequency analysis which is useful for historical exploration of language as well as topic identification
- `Collocation` : words commonly appearing near each other
- `Concordance` : the contexts of a given word or set of words
- `N-grams` : common two-, three-, etc. word phrases
- `Dictionary tagging` : locating a specific set of words in texts

Analysing one or a number of texts of interest:
- `Topic modeling` : unsupervised machine learning to identify groups of terms that may be representative of a given topic, uncovering hidden themes.  [Example](https://doi.org/10.1111/faf.12399)
- `Document classification` such as `Naive Bayes Classfication` : machine learning to classify documents based on information in the text, used in Sentiment and other analysis.
- `Sentiment analysis` : used to determine whether data is positive, negative, or neutral. Used in research to see public sentiment on products, ideas or policy, can undertaken via NLP or machine learning. Try the [Tweet Sentiment Visualization tool](https://www.csc2.ncsu.edu/faculty/healey/tweet_viz/tweet_app/) from NC State University.
- `Network analysis` : analysis of social or other structures comprising variables or actors (represented by nodes), and the relationships (edges) between the nodes.
- `Named entity recognition` generates a list of people, places, dates, times, percentages, monetary terms [Illinois Library](https://hdl.handle.net/2142/102049).  

Learn more about these methods and types of analysis from the [Australian Text Analytics Platform Methods Guide](https://www.atap.edu.au/methods).

----
##  Analysis tools

### Griffith University subscription software

Login and installation required.
- [NVivo](https://www.griffith.edu.au/student-computing/available-software) - cluster analysis, phrase nets, tag clouds, and sentiment analysis available.
- [Leximancer](https://www.griffith.edu.au/student-computing/available-software) – network analysis, topic modeling, sentiment analysis, named entity recognition available.

### Platforms with prepared text and tools

The virtual research environments below have been developed to support digital text scholarship.
- [JSTOR text mining support](https://about-jstor-org.libraryproxy.griffith.edu.au/whats-in-jstor/text-mining-support/) for metadata, n-grams, and word counts for most articles and book chapters, and for all research reports and pamphlets available via Griffith University's subscription to JSTOR. Login required.
- [Gale Digital Scholar Lab](http://libraryproxy.griffith.edu.au/login?url=https://infotrac.gale.com/itweb/griffith?db=DSLAB) for document clustering, named entity recognition, Ngrams, Parts of Speech, Sentiment Analysis, Topic Modelling all available via Griffith University's subscription. The lab is designed to use the Gale Primary Source archives, but you can use the analysis tools with your own data. Learn about it and Gale Primary Sources [here](https://sway.office.com/v4sYacFkErbH9HNo). Includes [online tutorials](https://go-gale-com.libraryproxy.griffith.edu.au/ps/helpCenter?userGroupName=griffith&inPS=true&nspage=true&prodId=DSLAB&docId=VJWVZS717322017). Login required. 
- [Hathi Trust Research Center Analytics](https://analytics.hathitrust.org/) supports large-scale computational analysis of the digital library works to facilitate non-profit and educational research. Individual researchers can sign up for free with their Griffith email and use out of copyright materials and analysis tools.  


### Plug & Play open source (free) tools

Plug and play tools let you add data and the software performs the computational analysis. The majority of the tools are based on Python or R analysis codes. We can use these tools for simple data analysis and visulations, and they are really useful for exploratory analysis and getting an idea of what your data holds. Some are downloadable to your computer, others are web interfaces, each with their own benefits and limitations.
`Pro's` : easier to learn than coding, good for high level analysis
`Cons` : can be inflexible, may not be good for deeper analysis, web based tools may not approprate for using with identifiable data.

- [Voyant Tools](https://voyant-tools.org/) web based online tool for frequency, distribution and collocation of terms, keywords in context, term clusters and more.
- [Sentiment Analyzer](https://www.danielsoper.com/sentimentanalysis/default.aspx) web based tool for analysing one source at a time.
- [Topic Modelling tool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html).
- [Cytoscape](https://cytoscape.org/) software platform for visualizing complex networks. 
- [Stanford Named Entity Recognizer (NER)](https://nlp.stanford.edu/software/CRF-NER.html) is particularly good for person, organisation and location recognition.

---- 
{% capture text %}
Try this [activity](https://griffithunilibrary.github.io/data-vis-basics/content/5-voyant.html) using [Voyant tools](https://voyant-tools.org/). Look at the results, think how you might use it for analysis and the limitations of the tool.{% endcapture %} {% include card.md header="Voyant tools activity" text=text %}

### Coding for text analysis
- [R](https://www.rstudio.com/products/rstudio/) & R Studio - network analysis, topic modeling, classification/clustering, named entity recognition, sentiment analysis 
- [Python](https://www.python.org/) – network analysis, topic modeling, classification/clustering, named entity recognition, sentiment analysis

#### Support and training 


##### Methods training

- Prof. Miriam Possner's [Topic Modelling online tutorials](http://miriamposner.com/classes/dh201w21/tutorials-guides/text-analysis/messing-around-with-the-topic-modeling-tool/) using the Topic Modelling Tool.
- [Demystifying Networks](http://www.scottbot.net/HIAL/index.html@p=6279.html) by Scott Weingart, written as an introduction for HASS scholars 

##### Learn coding for text mining and analysis
- [Beginner R & Python workshops](https://www.griffith.edu.au/eresearch-services/hacky-hour) are available from Griffith's eResearch services throughout the year. 
- [Constellate tutorials](https://constellate-org.libraryproxy.griffith.edu.au/) a series of lessons to help you learn about programming in Python, text analysis, and the Constellate platform for JSTOR.
- [Programming Historian](https://programminghistorian.org/en/lessons/)  novice-friendly, peer-reviewed tutorials that help humanists learn a wide range of digital tools, techniques, and workflows to facilitate research and teaching. These include lesons in R and Python. 
- [GLAM Workbench tutorials](https://glam-workbench.net/getting-started/) learn how to use the GLAM Workbench to extract and analyse data from Australia's galleries libraries, archives and museums.
- [Top 5 Unknown Sentiment Analysis Projects On Github To Help You Through Your NLP Projects](https://medium.com/analytics-vidhya/top-5-unknown-sentiment-analysis-projects-on-github-to-help-you-through-your-nlp-projects-8d8f195e80fc) 
- [Language Technology and Data Analysis Laboratory (LADAL) Tutorials](https://ladal.edu.au/tutorials.html) provides online text analysis tutorials in R.

{% capture text %}
Note: All software should be referred to in your methods notes and software developers attributed by citation e.g. 
- Sinclair, Stéfan and Geoffrey Rockwell, 2016. *Voyant Tools*. Web. http://voyant-tools.org/.{% endcapture %}{% include alert.md text=text color="info" %} 

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/5-build.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/7-vis.html">NEXT --></a>
</p>
