---
title: Create
nav: true
---

# Create a new OpenRefine project

-----

OpenRefine works with a variety of file types, including tab separated (`tsv`), comma separated (`csv`), Excel (`xls, xlsx`), `JSON`, `XML`, `RDF as XML`, and `Google Spreadsheets`. See the [OpenRefine Importers page](https://github.com/OpenRefine/OpenRefine/wiki/Importers) for more information.

----

{% capture text %}
**Windows**: double-click on the `openrefine.exe` file. Java services will start automatically on your machine, and OpenRefine will open in your browser. Be sure to use either Chrome or Firefox, as OpenRefine does not play well with Microsoft Edge or Safari.

**Mac**: OpenRefine can be launched from your Applications folder.

**Linux**: navigate to your OpenRefine directory in the command line and enter `./refine`.

Once OpenRefine is launched in your browser, the home screen displays options to `Create Project`, `Open Project`, or `Import Project`. 

Select `Create a project`.

**If launch fails**

If OpenRefine does not automatically open within your browser after launch, point your browser at `http://127.0.0.1:3333/` or `http://localhost:3333` to launch the program.{% endcapture %}
{% include card.md header="Launch OpenRefine" text=text %}
{% capture alert %}Note: Keep the terminal window hosting Java open in the background.{% endcapture %} {% include alert.md text=alert color="warning" %}
{% include figure.html img="ORJava.JPG" alt="Terminal Java" caption="Keep the terminal window open when using OpenRefine" width="75%" %}

-----

### Create a Project

Projects can be created in a variety of ways, e.g., by uploading data from your computer or by importing it from a web address.

{% capture text %}
- Choose `Create Project`
- Select `Get data from this Computer`.
- Select `Choose Files` and browse to select the file `QLDtrafficAccidentsOpenDataVer1.csv` you saved to your `Downloads` folder.
- Either click `Open` or double-click on the filename to import it into OpenRefine.
- Click `Next`.{% endcapture %}
{% include card.md header="Create a project by uploading data from your computer" text=text %}

Or 

{% capture text %}
- Choose `Create Project`
- Click `Web addresses (URLs)`.
- When a text box opens, enter this address `https://raw.githubusercontent.com/stapletonsl/ClassData2020/master/QLDtrafficAccidentsOpenDataVer1.csv`
- Click `Next`.{% endcapture %}
{% include card.md header="Create a project by importing the data from a Web Address" text=text %}

-----

### Data preview

OpenRefine gives you a preview to show you how it has interpreted the file you have uploaded or imported. If your data was tab-delimited rather than comma-delimited, the preview might look strange. 
- Be sure the correct separator is displayed in the box shown. 
- If you have made any changes, click `Update Preview` (bottom left). 
- If the wrong file is displaying, click `<<Start Over` (upper left).

There are options to indicate whether the dataset has column headers included and whether OpenRefine should skip a number of rows before reading the data. 
- Choose `UTF8` as the method of encoding as this should convert any 'smart' formatting into plain text.
- Make sure `Trim leading & trailing whitespace from strings` is checked. This will automatically remove any whitespace from the beginning or end of data strings or cells, making the data computer readible. Words with spaces at the beginning or end are particularly hard for we humans to tell from strings, but the blank characters will make a difference to the computer.
- Ensure the first row is used to create the column headings by checking the box `Parse next 1 line(s) as column headers`
- Make sure the `Parse cell text into numbers, dates,` ... box is not checked, so OpenRefine doesn't try to automatically detect numbers. Parsing in this context refers to the way the software will interpret the format of the data.
- Give the project a meaningful name such as `TrafficAccidentsCleanV1`
- If all looks fine, click `Create Project`.

{% include figure.html img="20201209_OR_Preview_Screen.png" alt="Create Project" caption="Create a project in OpenRefine" width="75%" %}

{% include button.md text="Watch the steps above on this video" link="https://vimeo.com/412189056/0d9031def0" color="info" %}


-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/1-intro.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/3-lesson.html">NEXT --></a>
</p>

