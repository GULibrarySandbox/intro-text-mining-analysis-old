---
title: Prepare text data
nav: true
---

![image](https://user-images.githubusercontent.com/42364968/170155378-7e7a9952-f36b-43cf-8ab5-6ba0826de422.png)


# Prepare & Process

Preparing and processing your data makes it consistent and machine readable for analysis. This process differs depending on what types and formats of files you are analysing.  

## Preparation steps - cleaning and formatting your data 
How you clean your data depends on what type of data you have. There are two main types of dataset used; sturctured, which takes the form of tabular data like in spreadsheet or a ledger and unstructured, which is free form text, such as diary entries, newpaper articles, letters and so on. 

For Structured data, broadly speaking, for resources to be clean, this means consistent data in each column, eg; consistent spelling and abreviations and as far as possible no blank spaces in the data sheets.
For unstrucutred data this means the text is compuationally analysable, the tools will be able to read text but not images of text, pages are free of white space, pages of text must be free of images and the text needs to be clear and unobscured. 

{% include figure.html img="Textformats1.jpg" alt="Text as data formats, Speech to text, Handwritten text, Printed text, Digital text" caption="Different text as data formats that need processing" width="100%" %}


## Text as data - what does it include?

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| survey audio recordings | personal letters | books, journals, news articles, legislation, government reports | online databases & digital collections of published or primary sources...
| interview audio or video recordings | official correspondence | unpublished papers | unpublished works, your own digital documents
| observation video recordings | ships logs, diaries, ledgers | typed documents, letters, official records, recipes.... | webpage and social media content |
| | original manuscripts & drafts | brochures, menus, other primary source materials | language corpora |
| | scientific notes, annotations, field books | survey results | interview transcripts, survey results |
{:.table .table-bordered}

## Text as data - how to format?

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| audio transcription, then cleaning | transcription, then cleaning | digitisation, transcription then cleaning | reformating, then cleaning |
{:.table .table-bordered}

{% capture text %}
Note: All text documents need to be formatted for machine readability. Machine readability means consistency of fonts, clear text, the removal of punctuation and white space and all other formatting or macros.

`.txt`  is the best format as it is non-proprietary & used in text analysis tools.  
`.pdf`  OCR processed format is accepted by some analysis tools.{% endcapture %}
{% include alert.md text=text color="info" %}


## Tools to prepare

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| Nvivo software [student access](https://www.griffith.edu.au/student-computing/available-software)  [staff access](https://intranet.secure.griffith.edu.au/computing/software) | [Transkribus](https://readcoop.eu/transkribus/) | High quality scanner (then OCR recognition) | [OpenRefine](https://openrefine.org/) to create structure to text |
| [Microsoft Office 365](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57)| [Google Vision AI](https://cloud.google.com/vision) | Digital Camera (then OCR recognition) | [gImageReader](https://github.com/manisandro/gImageReader#readme) (students) open source OCR processor for pdfs and images |
| [Griffith's Speech to text service](https://www.griffith.edu.au/eresearch-services/speech-to-text) | MS Word, google docs or equivalent | | [Adobe Acrobat Pro DC](https://intranet.secure.griffith.edu.au/computing/software) (staff) OCR recognition |
|[Alveo](https://www.alveo.edu.au/)| | | [DigiVol](https://volunteer.ala.org.au/) for structured text 
{:.table .table-bordered}



### Unstructured vs structured text and machine readibility

Humans understand that language, and the text that represents it, is highly complex and full of structure. However text is often described as unstructured, when it does not fit easily into a database management system, or is not easily processed by a computer. 

Unstructured text in this context may include text from narratives (books, articles etc.), interviews, survey responses with free text and more.  

Structured text can include metadata from GLAM catalogues or finding aides, text in structured databases, possibly spreadsheets, even old ledgers and logbooks. 

There are different processes that need to be undertaken with structured vs unstructured text.

### What to do with unstructured text
- Text data must be free of white space to make it computationally readable.  
   For modern pdfs this no trouble, for older texts you might need to transcribe the data, or clean the data, as scanned text may read as an image.
- All tools in the table above can be used for preparing unstructured text data and OpenRefine can help provide structure to unstructured text.
- Unstructured text in file formats such as `.doc` , `.docx`, `.rtf` (rich text format) can be exported as `.txt` via Microsoft Word.

### How to convert structured text formats
- spreadsheet data like an excel sheet, reformat as a `.csv` file 
- file formats including `.xml`, `JSON`, `html`, import and convert using Microsoft Excel into `.csv` or `.txt` dlimited text file, in which a `tab` separates each field of text.

### Processing methods

Once the text is cleaned, formatted it can be computationally processed by a number of different methods, depending on your analysis needs.

**Natural language processing (NLP) techniques**

Natural language processing (NLP) is the branch of artificial intelligence (AI) that deals with training a computer to understand, process, and generate language. Search engines, machine translation services, and voice assistants are all powered by the technology. (https://www.cio.com/article/228501/natural-language-processing-nlp-explained.html view 19-01-2021)

in practice, NLP tools break down text into analysable parts, these parts include:
-	Sentence splitting
-	Tokenization
-	Part-of-speech tagging
-	Shallow parsing
-	Named entity recognition
-	Syntactic parsing (Tsuruoka, n.d.) 

Once the data has been processed, we can then take on tasks such as:
- find and compare instances of particular terms over time via defined 
- Word frequency analysis and visualisation via word clouds
- topic modeling - "identify groups of terms that tend to be representative of a given topic" Toon, E., Timmermann, C., & Worboys, M. (2016). Text-mining and the history of medicine: Big data, big questions? Medical History, 60(2), 294-296. https://doi.org/10.1017/mdh.2016.18 
- named entity recognition, to find either person or place, or both.  
- machine learning https://en.wikipedia.org/wiki/Machine_learning & https://www.zdnet.com/article/what-is-machine-learning-everything-you-need-to-know/

![image](https://user-images.githubusercontent.com/51395844/180670565-86edcaa7-86b4-4f38-9f30-f8357bff75a4.png)




------

{% capture text %}
Prosecution Project researchers worked with a team of eResearch specialists and database and web designers to develop a structured database managed through a secure web portal. With the support of volunteers, they undertook massive digitisation, transcription and indexing work resulting in a longitudinal database of criminal prosecutions never before available in Australia. They also recognized the potential of enriching the data via links to the sources used such as newspaper articles in National Library of Australia TROVE database.  
Read more about the project at: 
Finnane, M., & Piper, A. (2016). The Prosecution Project: Understanding the Changing Criminal Trial Through Digital Tools. Law and History Review, 34(4), 873-891. [doi:10.1017/S0738248016000316](doi:10.1017/S0738248016000316)
{% endcapture %} {% include card.md header="Case study - the Prosecution Project - digitising, transcribing, building" text=text %}

{% include figure.html img="ProsectionProject_image_1.png" alt="Prosecution Project database" caption="Prosecution Project database" width="100%" %}

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/4-build.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-text-mining-analysis/content/6-analyse.html">NEXT --></a>
</p>

