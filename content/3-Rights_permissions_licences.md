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

Further, just because a person has made a post on a public forum like Twitter or Facebook, it doesn't mean they have consented to its being included in your research.

According to Griffith's [Ethics Booklet on Information Technology and Online Research](https://www.griffith.edu.au/__data/assets/pdf_file/0026/354752/booklet37.pdf), whether online content analysis is viewed as 'human research' depends on:

1. the degree to which the material is 'on the public record' and;
2. whether it is contentious or likely to be of concern to the subject.

In general, the less the information could be considered 'on the public record' and the more likely the material might be contentious or of concern to the person, the more likely its inclusion would make the work 'human research'.

{% capture text %}
If you're unsure about your ethical obligations, contact [Griffith research ethics](https://www.griffith.edu.au/research/research-services/research-ethics-integrity).
{% endcapture %}
{% include alert.md text=text color="info" %} 

{% capture consent %}
'Informed consent' requires that the subject know exactly how the information will be published and the potential risks to them or their reputation, as a result of publishing the information.

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
Unless the participants have given their informed consent to being identified, you might need to remove personally identifying data from your data set before publishing it. This applies to all personal information, not just data which is sensitive or confidential.

Where a social media service has a search function, using direct quotes can identify individuals.

{% capture reidentification %}
**Beware of re-identification**

If de-identification is done carelessly, or there are many data points in a data set that are unique to an individual, the data can be re-identified. In at least one case, this has led to published data sets being retracted.

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

Both copyright law and any relevant licensing terms will affect what you can do with scraped data.

{% capture copyrightwarning %}
Accessing and downloading data is one thing — publishing it is another. Obtaining permission to do one does not mean you have permission to do the other.
{% endcapture %}
{% include alert.md text=copyrightwarning color="warning" %}

Copyright law prevents you from publishing data sets owned by someone else without permission. If your published data is only slightly altered from the original, its copyright would still remain with the original owner. However, the results published from text or data mining are often very different from the data they mine, meaning it may not be considered substantially the same work.

{% capture checkwithcopyrightofficer %}
If you are intending to publish anything based on copyrighted data, always check with the [Information Policy Officer](http://www.griffith.edu.au/copyright-matters/) first.
{% endcapture %}
{% include alert.md text=checkwithcopyrightofficer color="info" %}

## Gaining access and permission

Social media sites, online archives and repositories all have Terms of Service that determine what you are allowed to do with their data (including whether scraping or bulk-access is allowed). Where a site provides an API, separate Terms of Service will usually apply to that.

Many sites allow research or non-commercial scraping or API use.

{% capture publicdomain %}
Some data is in the public domain (meaning nobody owns the copyright), or is licensed under free or public licenses like [Creative Commons](https://creativecommons.org.au) or (Copyleft)[https://opensource.com/resources/what-is-copyleft]. Creative Commons is not the same as being copyright-free. It is still a kind of license that you need to comply with. The main difference is that you don't have to ask permission to use the material. Permission is granted by the owner in advance, provided that you conform to the licence terms. 

{% capture stillethics %}
**NB:** This does not mean there are no ethical considerations! If your corpus contains information about people then you may still hold ethical obligations to them.
{% endcapture %}
{% include alert.md text=stillethics color="warning" %}

It's possible for some Creative Commons licenses include a 'No Derivatives' term, which would prevent you from publishing new works based on the original. It's unlikely however that that a CC dataset would be published with a 'No Derivatives' term.

{% endcapture %}
{% include card.md header="Public domain and Creative Commons" text=publicdomain %}

{% capture permissionsblock %}

**When using data from a repository**

Info about terms of service

**When scraping web pages or querying an API**

Info about scraping

{% capture commercialuse %}
**What constitutes commercial use?**

You might need to consider whether your use of the data constitutes commercial use.

{% endcapture %}
{% include alert.md text=commercialuse color="info" %}

When you are working with data you have generated yourself, or with text that is out of copyright and in the public domain (see below), then there will be no conditions attached to your use of the data.

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
