---
title: Build
nav: true
---
# Building a text corpus or dataset

Building a corpus is the process of finding, accessing and extracting or creating your data set. Building a data set can be as simple as collecting PDFs from your literature search, or as complex as transribing handwritten texts and converting into a computational format.  Data sets in humanities reserach are also known as a corpus and these terms can be used interchangably.

A corpus can be built either through existing data, collation of resources or generating your own data. No matter how the dataset is created there are a few things that are required. The data needs to be machine readable, the data needs to be clean and if you are using tabular or structured data, your dataset needs to be consistent. The first step is to find the dataset or corpus of interest.

## Finding data

{% include figure.html img="GLAMCollections.PNG" alt="Find data in GLAM collections" caption="Find data in GLAM collections" width="100%" %}

Digitisation, Optical Character Recognition (OCR) processing, indexing, encoding, and online hosting of primary source materials by `archives, libraries, museums and galleries (GLAM sector)`  has enabled greater access, and new ways to find, explore, process and analyse text as data.  An easy way to get started in finding discipline specific data sets is in the Griffith guides
- <a href ='https://libraryguides.griffith.edu.au/finddata' target="_blank">Finding data guide </a>   
- [Text mining and analysis guide](https://libraryguides.griffith.edu.au/text-mining)

If you cannot get the data you need from the available guides make an enquiry with the platform of interest. Companies often make their data available to researchers by agreement such as Twitter's Academic Research access service. Archives and other repositories will have links to the datasets that can be downloaded, as will Government webpages.  

### Extracting data

### Using an API to extract data

When using text data or gathering data from online sources you may need to use an Application Programming Interface (API), a software tool that allows two applications to talk to each other. In the case of collecting web data, it is a database that stores the webpages data and something that can read, display or store that data (i.e. a webbrowser, a programming language such as python or some other program on your computer, or a cloud based application).

Using a supplied API is the easiest way to collect a large dataset of text from a database or website. Examples of API's useful to text analysis researchers include:
- [TROVE API guide](https://trove.nla.gov.au/about/create-something/using-api)
- [Assoc Prof Tim Sherrat's Australian GLAM data & API list](https://glam-workbench.net/glam-data-list/)
- [State Library of Queensland's open datasets](https://www.slq.qld.gov.au/get-involved/open-data/open-datasets-released-state-library)
- [QLD Open Data Portal API guides](https://www.data.qld.gov.au/article/standards-and-guidance/publishing-guides-standards/api-user-guide)
- [Twitter's Academic Research Access API](https://developer.twitter.com/en/products/twitter-api/academic-research)
- [JSTOR text mining support](https://about-jstor-org.libraryproxy.griffith.edu.au/whats-in-jstor/text-mining-support/)

{% capture text %}
The Prosecution Project is a collaborative research project on the history of the criminal trial in Australia from 1788 to 1960. Sources of text data included Supreme Court crimial trial registers, Police Gazettes nontices, Prison and Convict Registers, along with press releases and other newspaper articles  [https://prosecutionproject.griffith.edu.au/](https://prosecutionproject.griffith.edu.au/).

The images below include example source materials like those used by the Prosecution Project:
- Libraries Tasmania Digital Image ID AB693-1-1 1853-1854: Registers of Criminal Cases Prosecuted by the Crown (AB693), 1853-1984. retrieved May 10, 2021, from [https://stors.tas.gov.au/AB693-1-1$init=AB693-1-1_039](https://stors.tas.gov.au/AB693-1-1$init=AB693-1-1_039) 
- (1907, January 16). The Advertiser (Adelaide, SA : 1889 - 1931), p. 1. Retrieved May 10, 2021, from [http://nla.gov.au/nla.news-page930175](http://nla.gov.au/nla.news-page930175)
- Queensland State Archives Digital Image ID 23435: Queensland Police Gazette – Vol LXI, No 66, pp 653-654, 6 December 1924 
[https://blogs.archives.qld.gov.au/2014/08/17/catching-criminals-in-queensland-state-archives-collection/](https://blogs.archives.qld.gov.au/2014/08/17/catching-criminals-in-queensland-state-archives-collection/)

{% include figure.html img="2021_ProsProjSources.png" alt="Sources of text for the Prosecution Project" caption="Sources of text for the Prosecution Project" width="100%" %}{% endcapture %} {% include card.md header="Case study - the Prosecution Project - finding sources" text=text %}



----
{% capture alert %}*Note:* Be sure to cite any resource / dataset / corpus you use in your research.
{% endcapture %}
{% include alert.md text=alert color="warning" %}


----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/3-rights_permissions_licences.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/5-prepare.html">NEXT --></a>
</p>
