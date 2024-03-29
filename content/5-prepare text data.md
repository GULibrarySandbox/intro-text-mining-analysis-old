---
title: Prepare text
topics: Prepare and format; Useful tools; Cleaning text
nav: true
---

# Prepare and format

Preparing and formating your data makes it consistent and machine readable for analysis. This process differs depending on the types and formats of files you are analysing.  
{% include figure.html img="Textformats1.jpg" alt="Text as data formats, Speech to text, Handwritten text, Printed text, Digital text" caption="Different text as data formats that need processing" width="100%" %}
## Preparation steps

There can be a number of steps to prepare, clean, then format text data depending on its type.  Interview data may be in audio or video format and require transcription. Correspondence may be handwritten on paper or in a digital format as a scanned image. Let's explore the different formats and preparation steps below.

### Types of text data

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| survey audio recordings | personal letters | books, journals, news articles, legislation, government reports | online databases & digital collections of published or primary sources...
| interview audio or video recordings | official correspondence | unpublished papers | unpublished works, your own digital documents
| observation video recordings | ships logs, diaries, ledgers | typed documents, letters, official records, recipes.... | webpage and social media content |
| | original manuscripts & drafts | brochures, menus, other primary source materials | language corpora |
| | scientific notes, annotations, field books | survey results | interview transcripts, survey results |
{:.table .table-bordered}

### How to prepare text data

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| audio transcription | transcription | digitisation, transcription | reformat to .txt |
{:.table .table-bordered}

### Tools to prepare text data

| *Speech to text* | *Handwritten text* | *Printed text* | *Digital text* |
| Nvivo software [student access](https://www.griffith.edu.au/student-computing/available-software)  [staff access](https://intranet.secure.griffith.edu.au/computing/software) | [Transkribus](https://readcoop.eu/transkribus/) | High quality scanner (then OCR processing) | [OpenRefine](https://openrefine.org/) to create structure to text |
| [Microsoft Office 365](https://support.microsoft.com/en-us/office/transcribe-your-recordings-7fc2efec-245e-45f0-b053-2a97531ecf57)| [Google Vision AI](https://cloud.google.com/vision) | Digital Camera (then OCR processing) | [gImageReader](https://github.com/manisandro/gImageReader#readme) (students) open source OCR processor for pdfs and images |
| [Griffith's Speech to text service](https://www.griffith.edu.au/eresearch-services/speech-to-text) | MS Word, google docs or equivalent | | [Adobe Acrobat Pro DC](https://intranet.secure.griffith.edu.au/computing/software) (staff) OCR recognition |
|[Alveo](https://www.alveo.edu.au/)| | | [DigiVol](https://volunteer.ala.org.au/) for structured text 
{:.table .table-bordered}

### How to clean text

No preparation tool will create perfect text.  Errors will be generated in the transcription or conversion processes. You may need to manually review and clean the text, correcting errors generated from OCR (Optical character recognition) of scanned images of pages, misinterpretations of spoken words, and other transcription errors. Some programs are available to automate some cleaning processes such as Python, read about how to do this from [machinelearningmastery.com](https://machinelearningmastery.com/clean-text-machine-learning-python/). Some processing and analysis tools enable you to clean the text prior to analysis, such as Voyant tools. More on this in the next lesson. 

### How to format text

All text documents need to be formatted for machine readability by software programs or code.
- `.txt` : is the best format as it is non-proprietary & used in text analysis tools.
- `.csv` : is the best format for structured text data in spreadsheets and can be read by tools such as Nvivo  
- `.pdf` : that has been OCR processed (not just an image, the text can be read by the software) is accepted by some analysis tools.

### Unstructured vs structured text and machine readibility

Humans understand that language, and the text that represents it, is highly complex and full of structure. However text is often described as unstructured, when it does not fit easily into a database management system, or is not easily processed by a computer. 
- Unstructured text may include text from narratives (books, articles etc.), interviews, survey responses with free text and more.  
- Structured text can include metadata from GLAM catalogues or finding aides, text in structured databases, possibly spreadsheets, even old ledgers and logbooks. 

There are different processes that need to be undertaken to prepare structured vs unstructured text.

#### Unstructured text formats 
- Text data must be free of white space to make it computationally readable.  
   For modern pdfs this no trouble, for older texts you might need to transcribe the data, or clean the data, as scanned text may read as an image.
- All tools in the table above can be used for preparing unstructured text data and OpenRefine can help provide structure to unstructured text.
- Unstructured text in file formats such as `.doc` , `.docx`, `.rtf` (rich text format) can be exported as `.txt` via Microsoft Word.

#### Structured text formats
- spreadsheet data like an excel sheet, reformat as a `.csv` file 
- file formats including `.xml`, `JSON`, `html`, import and convert using Microsoft Excel into `.csv` or `.txt` delimited text file, in which a `tab` separates each field of text.

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

