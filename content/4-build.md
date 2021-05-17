---
title: Build
nav: true
---
# Building a text corpus or dataset

--------
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

{% capture alert %}*Note:* Always close facets when you are finished with them, so as not to affect future facets or results.
{% endcapture %}
{% include alert.md text=alert color="warning" %}


{% include button.md text="Watch this video to work through the activities" link="https://vimeo.com/412540178/a0a65e0c0f" color="info" %}

----

#### More on Facets

As well as  `Text facets`  and  `timeline facets` , OpenRefine also supports other types of facets. These include:

- `Numeric facets`  : displays a graph and includes 'drag and drop' controls to set a start and end range to filter the data displayed. Explore these later in the lesson on [Examining Numbers in OpenRefine](https://griffithunilibrary.github.io/intro-data-wrangle/content/7-lesson.html).
- ` Customized facets`  provide a range of different facets including:

  - `Word facet`  - to break down text into words and count the number of records each word appears in
  - `Duplicates facet`  - this results in a binary facet of 'true' or 'false'. Rows appear in the 'true' facet if the value in the selected column is an exact match for a value in the same column in another row.
  - `Text length facet`  - creates a numeric facet based on the length (number of characters) of the text in each row for the selected column. This can be useful for spotting incorrect or unusual data in a field where specific lengths are expected (e.g., if the values are expected to be years, any row with a text length of more than 4 for that column is likely to be incorrect.)
  - `Facet by blank`  - a binary facet of 'true' or 'false'. Rows appear in the 'true' facet if they have no data present in that column. This is useful when looking for missing data.

{% capture text %}
Use a  `Customized facet`  to find out how many records are missing crash type data.
{% include modal.md button="Quiz 1 Solution" color="success" title="Quiz 1 Solutions" text="Select  `Facet > Customized facets > Facet by Blank or Null`. 
Result 7" %}{% endcapture %} {% include card.md header="Quiz 1. What data is missing in  `Crash_Type`  column?" text=text %}

--------


{% include alert.md text=alert color="warning" %}

{% include button.md text="Watch this video to learn these functions" link="https://vimeo.com/412536655/cfbb96bb38" color="info" %}

----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/3-rights.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/5-prepare.html">NEXT --></a>
</p>
