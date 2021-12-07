---
title: Prepare
nav: true
---

# Prepare 

Preparing or cleaning your data makes it consistent and machine readable for analysis. This process differs depending on what types and formats of files you are analysing.  
{% include figure.html img="Textformats1.jpg" alt="Text as data formats, Speech to text, Handwritten text, Printed text, Digital text" caption="Different text as data formats that need processing" width="100%" %}
## Text as data - what does it include?

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| survey audio recordings | personal letters | books, journals, news articles, legislation, government reports | online databases & digital collections of published or primary sources...
| interview audio or video recordings | official correspondence | unpublished papers | unpublished works, your own digital documents
| observation video recordings | ships logs, diaries, ledgers | typed documents, letters, official records, recipes.... | webpage and social media content |
| | original manuscripts & drafts | brochures, menus, other primary source materials | language corpora |
| | scientific notes, annotations, field books | survey results | interview transcripts, survey results |
{:.table .table-bordered}

## Text as data - how to prepare?

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| audio transcription, then cleaning | transcription, then cleaning | digitisation, then cleaning | reformating, then cleaning |
{:.table .table-bordered}

{% capture text %}
Note: All text documents need to be formatted for machine readability.  
`.txt`  is the best format as it is non-proprietary & used in text analysis tools.  
`.pdf`  OCR processed format is accepted by some analysis tools.{% endcapture %}
{% include alert.md text=text color="info" %}


## Tools to prepare

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| Nvivo software [student access](https://www.griffith.edu.au/student-computing/available-software)  [staff access](https://intranet.secure.griffith.edu.au/computing/software) | [Transkribus](https://readcoop.eu/transkribus/) | High quality scanner | [OpenRefine](https://openrefine.org/) |
| [Microsoft Office 365](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57)| [Google Vision AI](https://cloud.google.com/vision) | Digital Camera | [gImageReader](https://github.com/manisandro/gImageReader#readme) |
| [Griffith's Speech to text service](https://www.griffith.edu.au/eresearch-services/speech-to-text) | MS Word | [Adobe Acrobat Pro DC](https://intranet.secure.griffith.edu.au/computing/software) (staff) OCR recognition |
| | | [gImageReader](https://github.com/manisandro/gImageReader#readme) (students) open source OCR processor for pdfs and images | 
{:.table .table-bordered}

### unstructured text

- text data must be - free of white space - computationally readable
- for modern pdfs - no trouble, for older texts this will require some work, you might need to transcribe the data, or clean the data using various tools as scanned text will read as an image

tools for preparing unstructured text data
- for transcribing text- transkribus free tool,good for hand written materials
- digivol - good for structured data
- google docs 
- Adobe or GImageReader, for cleaning up scans, removing images and generating clean resources
 

### structured data

- When we think of structured data we generally think of this a spreadsheet, but this can also be tabular data such as a log book or ledger
- These resources must be machine readable, for spreadsheet data like an excell sheet, no trouble, but make it a CSV file, for other tabular data sets, like log books or ledgers the data will need to be in computationally analyisable state. you may need to transcribe the data for analysis.

Tools for preparing structured data
- open refine <a href ='https://openrefine.org/' target="_blank" > open refine <a/>
- digivol - good for transcribing structured data <a href ='https://volunteer.ala.org.au/' target="_blank" > Digivol <a/> 


### Audio data
How you prepare this depends on what you are analysing for, if you are preparing interviews, you will need to transcribe the audio to text, however, if you are analysing the sounds, say, accents or pronounciations of words you will need to make sure the sound file is clear and unblemished.
- youtube - use the transcription tools to generate text transcriptions
- Alveo - tool to assist with transcription of interviews. <a href='https://www.alveo.edu.au/' target="_blank" > Alveo <a/>
 
 
### Images 
 
### Video 




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

