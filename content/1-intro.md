---
title: Intro
nav: true
---
# Background

-----

{% include figure.html img="OpenRefine.JPG" alt="OpenRefine software" caption="OpenRefine" width="100%" %}

[OpenRefine](http://openrefine.org) is a [Java](https://www.java.com/en/)-based program that runs on your computer (not online).

It runs inside your Web browser, but no internet connection is needed to use it, unless you want to bring in Web-based data for cleaning. Once web-based data has been read into OpenRefine, no further internet connection is needed.

#### Features of OpenRefine
  
- Open source collaboratively developed software (OpenRefine source code is housed on GitHub)
- A growing community of users worldwide, from novice to expert, ready to help
- Works with large datasets, i.e. those greater than 100,000 rows
- Can adjust memory allocation to accommodate larger datasets 

#### Tasks you can use OpenRefine for

{% capture text %}
- Identify where data is missing
- Fix inconsistencies such as date formats, name case format and order
- Find and correct errors inlcuding misspellings, typos, whitespace
- Find and remove duplicate observations
- Identify and fix illegal values (data that does not fall within the accepted range for the variable)
- Map the meaning of the dataset to its structure, see ['Tidy data'](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html) by [Hadley Wickham](http://hadley.nz/){% endcapture %} {% include card.md header="Clean & standardise data" text=text %}

{% capture text %}
- Split columns or rows of data up into more granular parts
- Combine multiple datasets into one
- Combine values from two or more variables (concatenation)
- Add new variables (columns) or observations (rows) to a dataset
- Reshape data from rows and columns to visualise data in a different arrangement
- Organise data{% endcapture %} {% include card.md header="Extend & transform data" text=text %}

{% capture text %}
- Sort by variables and values
- Agregrate: reorganise to get a summary of the data
- Filter: extract a subset by value
- Facet: summarise values to provide a big picture of your data or to identify outliers{% endcapture %} {% include card.md header="Explore data prior to analysis" text=text %}

{% capture text %}
- Document all steps taken to process the data
- Create scripts to automate and repeat the processes on other datasets{% endcapture %} {% include card.md header="Document & repeat steps" text=text %}

Explore the two figures below to see examples of messy and clean tabular data.

**Messy data example**
{% include figure.html img="MessyData.JPG" alt="Messy Data" caption="Messy Data" width="100%" %}

**Clean data example**
{% include figure.html img="TidyData.JPG" alt="Clean Data" caption="Clean Data" width="100%" %}


<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/0-setup.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/2-lesson.html">NEXT --></a>
</p>

