---
title: Setup
nav: true
---
# Setup

-----

## Download & install software

{% capture text %}
- Check that you have Chrome, Chromium, Opera or MS Edge browser installed and set as your default browser. OpenRefine runs in your default browser. It will also run in Firefox, however some performance issues have been noted. It will not run correctly in Internet Explorer.
{% endcapture %}
{% include card.md header="Browser Requirements" text=text %}

{% capture text %}
- OpenRefine requires Java to be installed.  Check if your computer has Java and if not, select the *Windows kit with embedded Java* when downloading the software.
- Download the latest software version from [http://openrefine.org](http://openrefine.org). 
- Unzip the downloaded file into a directory by right-clicking and selecting `Extract ...`.   Name that directory something like OpenRefine.
- Go to your newly created OpenRefine directory.
- Move the folder to `c:\program files` (you may need administrator privileges to do this)
- Launch OpenRefine by clicking the `openrefine.exe` file (this will launch a command prompt window, but you can ignore that and wait for the browser to launch)
- If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at [http://127.0.0.1:3333/](http://127.0.0.1:3333/) or `http://localhost:3333` to launch the program.
 {% endcapture %}
{% include card.md header="Windows" text=text %}
  
{% capture text %}
- Download latest software version from [http://openrefine.org](http://openrefine.org)
- Drag icon into `Applications folder`
- Doubleclick to launch OpenRefine
- If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at [http://127.0.0.1:3333/](http://127.0.0.1:3333/) or `http://localhost:3333` to launch the program.
  
 **Mac Troubleshooting**
- If OpenRefine doesn’t open due to security settings go to:
  - `System Preferences> security & privacy >` see message re: OpenRefine
  - Select Open anyway{% endcapture %}
{% include card.md header="Mac" text=text %}

{% capture text %}
- Download the latest software version from [http://openrefine.org](http://openrefine.org). 
- Unzip the downloaded file into a directory. Name that directory something like OpenRefine.
- Go to your newly created OpenRefine directory.
- Launch OpenRefine
-Type `./refine` into the terminal within the OpenRefine directory
- If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at [http://127.0.0.1:3333/](http://127.0.0.1:3333/) or `http://localhost:3333` to launch the program.{% endcapture %}
{% include card.md header="Linux" text=text %}

-----

## About the data

The dataset used in this workshop is adapted from [Crash data from Queensland roads](https://www.data.qld.gov.au/dataset/crash-data-from-queensland-roads), © 2019 The State of Queensland, licensed under a Creative Commons Attribution 4.0 International licence, [CC BY 4.0.](https://creativecommons.org/licenses/by/4.0/).  It was downloaded from the Queensland Government’s [open data portal](https://www.data.qld.gov.au/).

The original dataset presents 17 years of traffic accidents, their location, type of accident, level of injury, and other features, with over 300,000 observations. 

The  data used in these lessons is a smaller, four-year subset and has had changes made for training purposes. 

{% capture text %}
- Download the `QLDtrafficAccidentsOpenDataVer1.csv` dataset from [Griffith University’s Research Storage Space](https://research-storage.griffith.edu.au/owncloud/index.php/s/4Yn7Hdeb2NNqYMF)
- To your `Downloads` folder. We will then import the data into OpenRefine.

Alternately, when you launch OpenRefine in the [*Create*](https://griffithunilibrary.github.io/intro-data-wrangle/content/2-lesson.html) lesson:

- Import the data directly from a *Web address*
- Using this link [https://raw.githubusercontent.com/stapletonsl/ClassData2020/master/QLDtrafficAccidentsOpenDataVer1.csv](https://raw.githubusercontent.com/stapletonsl/ClassData2020/master/QLDtrafficAccidentsOpenDataVer1.csv){% endcapture %}
{% include card.md header="Download workshop data" text=text %}

-----


## Get help

##### Online

You can find out more at the [OpenRefine](http://openrefine.org) website.  Check out the [documentation](http://openrefine.org/documentation.html) and great introductory videos. These videos and others on OpenRefine can also be found on YouTube - use the search term 'OpenRefine'.

There is a [Google Group](https://groups.google.com/forum/#!forum/openrefine) that can answer a lot of beginner questions and problems.

##### At Griffith University

Help is available from eResearch and Library specialists at Griffith University. Get in touch with us [here](https://intranet.secure.griffith.edu.au/library/forms/help) for an online consultation.

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/1-intro.html">NEXT --></a>
</p> 
