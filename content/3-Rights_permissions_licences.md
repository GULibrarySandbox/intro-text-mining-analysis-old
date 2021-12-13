---
title: Rights
nav: true
topics: Getting ethical clearance; Licenses and access agreements; Copyright
---

# Ethics, permissions, rights and licences

{% include figure.html img="eratosthenes.jpg" alt="Eratosthenes Teaching in Alexandria" caption="'Eratosthenes Teaching in Alexandria' by Bernardo Strozzi by mark6mauno is licensed under CC BY 2.0" width="100%" %}

## Research data ethics

{% capture text %}
Any research involving **human subjects** carries ethical obligations. Even if you are working with publicly available datasets, it might be necessary to obtain consent from the individuals involved and ethical clearance from the university.
{% endcapture %}
{% include alert.md text=text color="warning" %}

### Does my research involve 'human subjects'?

If you are obtaining your data by scraping webpages you may be inadvertently gathering personal information. [GLAM](https://glam-workbench.net/) archival sources might also contain personally identifying information.

According to Griffith's [Ethics Booklet on Information Technology and Online Research](https://www.griffith.edu.au/__data/assets/pdf_file/0026/354752/booklet37.pdf), whether online content analysis is viewed as 'human research' depends on:

1. the degree to which the material is 'on the public record' and;
2. whether it is contentious or likely to be of concern to the subject.

In general, the less the information could be considered 'on the public record' and the more likely the material might be contentious or of concern to the person, the more likely its inclusion would make the work 'human research'. 

{% capture text %}
If you're unsure about your ethical obligations, contact [Griffith research ethics](https://www.griffith.edu.au/research/research-services/research-ethics-integrity).
{% endcapture %}
{% include alert.md text=text color="info" %} 

{% capture consent %}
It may be necessary to gain consent from individuals whose information is contained in the data set you are using. 'Informed consent' requires that the subject know exactly how the information will be published and the potential risks to them or their reputation, as a result of publishing the information.

It's important to note that just because a person has made a post on a public forum (like Twitter or Facebook), it doesn't mean they have given their implied consent to being included in your research.

{% capture ongoing %}
**Consent may also be an ongoing process.**

If you've already gained consent from your subjects and then want to do something new or different with your data, you might need to approach them for further consent.
{% endcapture %}
{% include alert.md text=ongoing color="primary" %}

{% endcapture %}
{% include card.md header="Gaining informed consent" text=consent %}

### What are my ethical obligations?

Chapter 3.1, Element 4 of the National Statement on the [Ethical Conduct in Human Research](https://www.nhmrc.gov.au/about-us/publications/national-statement-ethical-conduct-human-research-2007-updated-2018) describes the ethical standards relating to the collection, use and management of data in human research.

Griffith publishes a [Guide for Managing Your Research Data](https://www.griffith.edu.au/__data/assets/pdf_file/0025/1233907/20210107-Guide-to-managing-research-data.pdf) that outlines the considerations involved in preparing a Data Management Plan. Having this information ready will help you to explain to your participants 

{% capture deidentify %}
It is usually (but not always) necessary to remove personally identifying data from your data set before analysing and publishing it. This applies even where the information is not sensitive, unless the participants have given their informed consent to being identified in your study.

{% capture reidentification %}
**Beware of re-identification**

If de-identification is done carelessly, or there are many data points in a data set that are unique to an individual, the data can be re-identified. In at least one case, this has led to published data sets being retracted.

Note also that when a social media service has a search function, direct quotes from individuals can identify them
{% endcapture %}
{% include alert.md text=reidentification color="danger" %}

{% endcapture %}
{% include card.md header="De-identifying data" text=deidentify %}

{% capture text %}
If you're unsure about your ethical obligations, contact [Griffith research ethics](https://www.griffith.edu.au/research/research-services/research-ethics-integrity).
{% endcapture %}
{% include alert.md text=text color="info" %}

- - -

## Data copyright

{% capture copyrightwarning %}
Accessing and downloading data is one thing — publishing it is another. Obtaining permission to do one does not mean you have permission to do the other.
{% endcapture %}
{% include alert.md text=copyrightwarning color="warning" %}

If you have created the textual data yourself, or it is in the public domain, then you do not need to seek permission to use the data (you will still need permission from individual participants where that's appropriate — see the section on ethical considerations above). Usually, however, you will be obtaining data from a source that may have copyright ownership over it. So how do you get a license to use it?

## Gaining access and permission

{% capture permissionsblock %}

Specific sites have specific terms explaining how researchers may access their data and what they are permitted to do with it. Some are very generous with their access provisions, while some do not allow re-use at all. Many sites allow their data to be used for research but prohibit commercial re-use.

**When using data from a repository**

Info about terms of service

**When scraping web pages or querying an API**

Info about scraping

{% capture commercialuse %}
**What constitutes commercial use?**

You might need to consider whether your publication constitutes commercial use.
{% endcapture %}
{% include alert.md text=commercialuse color="info" %}

Before undertaking research on existing datasets, be sure to read the terms and conditions of the use of the data.

A quick checklist might be: 

 - How will the data be downloaded? Directly from the web, or via an API?
 - To what degree is the data set in the public domain? Who is it owned by, if not?
 - Is there an agreement or terms of use that you agreed to? What does it say about allowed or excluded uses?
 - Do you have any plans to commercialise your research? Is that allowed by your access agreement?
 - Will your published data be 'substantially similar' to the mined dataset?
 - Will you be mixing different data sources? You might need to comply with both sets of terms, if they exist.

When you are working with data you have generated yourself, or with text that is out of copyright and in the public domain (see below), then there will be no conditions attached to your use of the data.

{% capture text %}
**NB:** This does not mean there are no ethical considerations! If your corpus contains information about people then you hold ethical obligations to those people. 
{% endcapture %}
{% include alert.md text=text color="warning" %}

However, if you are using a dataset built, created or maintained by someone else, you will always be accessing it under the terms of some license or other. It might be an open license such as Creative Commons or the Unlicense

The level of permission you need to use and reuse research data depends on several variables, who owns the data, how you got the data and what you intend to use the data for.

{% endcapture %}
{% include card.md header="Terms of service" text=permissionsblock %}

When publishing the data - sensitive data,  de- identified data

--


  
-----
  

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/2-why.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/4-build.html">NEXT --></a>
</p>
