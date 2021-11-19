---
title: Prepare
nav: true
---

# Prepare 

preparing your data for analysis means

is the data computataionally readable?
is the data clean?

### text data
- text data must be - free of white space - computationally readable
- for modern pdfs - no trouble, for older texts this will require some work, you might need to transcribe the data, or clean the data using various tools as scanned text will read as an image

tools for preparing text data
- there are a variety of tools available to assist transcribe text based resroucres
- for transcribing text- transkribus free tool,good for hand written materials
- digivol - good for structured data
- google docs 
- adobe, for cleaning up scans, removing images and generating clean resources

The best document types for analysis are PDF and .txt
 

### structured data
- when we think of structured data we generally think of this a spreadsheet, but this can also be tabular data such as a log book or ledger
- again these resources must be machine readable, for spreadsheet data like an excell sheet, no trouble, but make it a CSV file, for other tabular data sets, like log books or ledgers the data will need to be in computationally analyisable state. you may need to transcribe the data for analysis.

tools for preparing structured data
- open refine <a href ='https://openrefine.org/' target="_blank" > open refine <a/>
- digivol - good for transcribing structured data <a href ='https://volunteer.ala.org.au/' target="_blank" > Digivol <a/> 


### audio data
how you prepare this depends on what you are analysing for, if you are preparing interviews, you will need to transcribe the audio to text, however, if you are analysing the sounds, say, accents or pronounciations of words you will need to make sure the sound file is clear and unblemished.
- youtube - use the transcription tools to generate text transcriptions
- Alveo - tool to assist with transcription of interviews. <a href='https://www.alveo.edu.au/' target="_blank" > Alveo <a/>




------

{% capture text %}
Prosecution Project researchers worked with a team of eResearch specialists and database and web designers to develop a structured database managed through a secure web portal. With the support of volunteers, they undertook massive digitisation, transcription and indexing work resulting in a longitudinal database of criminal prosecutions never before available in Australia. They also recognized the potential of enriching the data via links to the sources used such as newspaper articles in National Library of Australia TROVE database.  
Read more about the project at: 
Finnane, M., & Piper, A. (2016). The Prosecution Project: Understanding the Changing Criminal Trial Through Digital Tools. Law and History Review, 34(4), 873-891. [doi:10.1017/S0738248016000316](doi:10.1017/S0738248016000316)
{% endcapture %} {% include card.md header="Case study -the Prosecution Project - digitising, transcribing, building" text=text %}

{% include figure.html img="ProsectionProject_image_1.png" alt="Prosecution Project database" caption="Prosecution Project database" width="100%" %}

----
### 


{% capture text %}
- .{% endcapture %} {% include card.md header="Activity - bla bla" text=text %}



{% include button.md text="Watch this video on ...." link="https://vimeo.com/..." color="info" %}

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/4-build.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/6-analyse.html">NEXT --></a>
</p>

