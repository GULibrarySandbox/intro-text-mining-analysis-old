---
title: How
nav: true
---
# How?

-----

### Activities and workflows


A text mining and analysis workflow is a messy, iterative and complex process. It’s often like the diagram below. "Depending on the project, a researcher may repeat certain steps in small cycles, or return to previous steps, or do some exploratory steps to determine next steps." (Green, et al. 2018)

{% include figure.html img="2021_UniIllinois_TextMineWorkflow.png" alt="Text mining workflow" caption="Text mining workflow" width="100%" %}

Source: Green, H., Henley, A., Morse, G., Courtney, A., Heidenwolf, T., Koehl, E. D., ... & Morris, S. (2018). " Digging deeper, reaching further: libraries empowering users to mine the HathiTrust Digital Library resources" curriculum. [http://hdl.handle.net/2142/102049](http://hdl.handle.net/2142/102049)

### Text as data considerations

Consider the questions below when embarking on a text mining project.

**what is your desired outcome?**
- think about what you need the outcome of your research to be and decide if using this method is the best way to reach that outcome.  The learning curve for many of the tools and processes is quite steep and there may be easier options. 


**Do you already have a dataset, corpus or text source?**
- GLAM catalogues, subscription databases, websites, social media are all great sources [here, link to new libguide]

**Is the text you want to use already digitised?**
- if the text is in the form of a modern PDF it should not need any further amendments. However, with texts made up of handwritten content, OCR recognition tools or even Speech to Text services might be needed, where you read the text into a transcription tool. With older PDFs or handwritten digital texts you will need to transcribe the materials to a machine readible format. txt is the universal format, PDF can also be used. 



**What are the copyright or licencing requirements?**
- Some collections, particularly before a certain date provide licences for use such as [TROVE](https://trove.nla.gov.au/) from The National Library of Australia, or
- You can request permission from copyright owners for subscription databases via the [Library](https://www.griffith.edu.au/library/contact). 
- Griffith's [Information Policy Officer](https://www.griffith.edu.au/copyright-matters/research-staff) can provide advice on specific use cases.

**How much technical experience do you need?**
- Some tools and methods are plug and play, which we will explore and others require coding. 
- [eResearch Services](https://www.griffith.edu.au/eresearch-services) run regular coding workshops and provide great support via Hacky Hour.

**Do you have funding?**
- Sometimes you need to pay for access to OCR text from vendor sources.


### Prepare text for processing

- prior to processing you will need to ensure your text is clean. By clean we mean consistently formatted, white space removed and the text is computationally analysable .txt is the preffered format, PDF can also be used. 


### Computationally process text to extract data

Natural language processing (NLP) techniques

Natural language processing (NLP) is the branch of artificial intelligence (AI) that deals with training a computer to understand, process, and generate language. Search engines, machine translation services, and voice assistants are all powered by the technology. (https://www.cio.com/article/228501/natural-language-processing-nlp-explained.html view 19-01-2021)

in practice, NLP tools break down text into analysable parts, these parts include
-	Sentence splitting
-	Tokenization
-	Part-of-speech tagging
-	Shallow parsing
-	Named entity recognition
-	Syntactic parsing
-	(Semantic Role Labeling)?? source: Dr. Yoshimasa Tsuruoka's tutorial at the National Centre for Text Mining here: http://www.nactem.ac.uk/teaching/ 

With these parts we can create new data on the resource, look for themes and relationships in the text and identify person and place names.  (example)

## Machine learning 

The processes then enable tasks such as:

- "find and compare the number of instances of particular terms over time in a defined corpus"
- "finding the relative frequency of the words in a text and then visualising these in a way that makes the different frequencies apparent, for example, by size and position in word clouds"
- topic modeling - "identify groups of terms that tend to be representative of a given topic" Toon, E., Timmermann, C., & Worboys, M. (2016). Text-mining and the history of medicine: Big data, big questions? Medical History, 60(2), 294-296. https://doi.org/10.1017/mdh.2016.18 
- named entity recognition 

https://en.wikipedia.org/wiki/Machine_learning

https://www.zdnet.com/article/what-is-machine-learning-everything-you-need-to-know/


### Analyse
Computational text analysis methods include:
- thematic analysis
- sentiment analysis
- content analysis
- network analysis 
- .....

### Visualise


<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/1-what.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/3-build.html">NEXT --></a>
</p>
