---
title: Build
nav: true
---
# Building a text corpus or dataset

Building a corpus is the process of creating your data set. A corpus can be built either through existing data, collation of resources or generating your own data. No matter how the dataset is created there are a few things that are required. The data needs to be machine readable, the data needs to be clean and if you are using tabular or structured data, your dataset needs to be consistent. 

## Find data
Data is everywhere, we can find data in repositories, archives, libraries, museums to name a few. an easy way to get started in finding discipline specific data sets is in the Griffith guide <a href ='https://libraryguides.griffith.edu.au/finddata' target="_blank">Finding data guide </a>

datasets are often available directly from the source, repositories will have links to the dataset that can be downloaded. 
When using text data or gaterhing data from online sources you many need to use an API.  API is the acronym for Application Programming Interface, which is a software tool that allows two applications to talk to each other. In the case of collecting web data, this is a database that stores the webpages data and something that can read, display or store that data (i.e. a webbrowser, a programming language such as python or some other program on your computer, or a cloud based application).
If a website has an API, then use it. Generally, it won't let us collect data that your not allowed to collect, and its by far the easiest way to collect a websites data. 



### Building a data set
Building your data set is the process of finding and collating the materials you wish to analyse. Data sets in humanities reserach are also known as a corpus, please be aware that these terms are used interchangably.

Building a data set can be as simple as collecting PDFs from your literature search, or as complex as transribing handwritten texts to a computational form. 
Regaurdless of how your data set is created there are several elements that need to be enacted for you to be able to analyse the resource.

- the materials must be compuationally readable. For modern PDFs of typed materails this is not an issue, however if you are usign scans of old texts, images of text or hand written documents these need to be transcribed or transformed into a readable format.  best formats for text are .PDF and .txt
- Structured Vs Unstructured text.  Structured text is waht we more commonly call spread sheet data. This can take the form of log books, ledgers and other records, eg: old census data, birth deaths and marraige records, shipping logs and so on. These materails have a structure and need to be transcribed as such. Unstructured text is written text. This is generally found as letters, diary entries, journal articles books and written content. Our main focus on these pages is to use the data found in unstructured text. *we will cover how to get your data in to computationally analyisable formats in the prepare section*


### Cleaning your data 
depending on what type of data you have 

- clean. The resources must be clean, in practice this means free of white space, pages of text must be free of images, the text needs to be clear and unobscured.
- consistent formatting 


tools for data cleaning
- for structured data sets we suggest <a href = 'https://openrefine.org/' target="_blank"> Open Refine </a> a free open source tool to clean and organise tabular datasets. training for open refine is availble <a href ='https://griffithunilibrary.github.io/intro-data-wrangle/' target="_blank">here. </a>
- for unstructured data - we suggest the <a href ='https://intranet.secure.griffith.edu.au/computing/software?_gl=1*16nj6v1*_ga*MjA2NDEzMDYwLjE2MTUxNTU0NjY.*_ga_5GKYJEBSN9*MTYzODQwODcxMy44NS4wLjE2Mzg0MDg3MTMuMA..#access' target="_blank">Adobe creative cloud </a> which is freely available to Griffith staff and students.



## Examples

### GLAM Digital collections - primary source materials

Digitisation, Optical Character Recognition (OCR) processing, indexing, encoding, and online hosting of primary source materials by `archives, libraries, museums and galleries (GLAM sector)`  has enabled greater access, and new ways to find, explore, process and analyse text. 

{% capture text %}
The Prosecution Project is a collaborative research project on the history of the criminal trial in Australia from 1788 to 1960. Sources of text data included Supreme Court crimial trial registers, Police Gazettes nontices, Prison and Convict Registers, along with press releases and other newspaper articles  [https://prosecutionproject.griffith.edu.au/](https://prosecutionproject.griffith.edu.au/).

The images below include example source materials:
- Libraries Tasmania Digital Image ID AB693-1-1 1853-1854: Registers of Criminal Cases Prosecuted by the Crown (AB693), 1853-1984. retrieved May 10, 2021, from [https://stors.tas.gov.au/AB693-1-1$init=AB693-1-1_039](https://stors.tas.gov.au/AB693-1-1$init=AB693-1-1_039) 
- (1907, January 16). The Advertiser (Adelaide, SA : 1889 - 1931), p. 1. Retrieved May 10, 2021, from [http://nla.gov.au/nla.news-page930175](http://nla.gov.au/nla.news-page930175)
- Queensland State Archives Digital Image ID 23435: Queensland Police Gazette – Vol LXI, No 66, pp 653-654, 6 December 1924 
[https://blogs.archives.qld.gov.au/2014/08/17/catching-criminals-in-queensland-state-archives-collection/](https://blogs.archives.qld.gov.au/2014/08/17/catching-criminals-in-queensland-state-archives-collection/)
{% endcapture %} {% include card.md header="Case study - the Prosecution Project - finding sources" text=text %}

{% include figure.html img="2021_ProsProjSources.png" alt="Sources of text for the Prosecution Project" caption="Sources of text for the Prosecution Project" width="100%" %}

----
{% capture alert %}*Note:* bla bla.
{% endcapture %}
{% include alert.md text=alert color="warning" %}


{% include button.md text="Watch this video to work through the activities" link="https://vimeo.com/...." color="info" %}

----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/3-rights.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/5-prepare.html">NEXT --></a>
</p>
