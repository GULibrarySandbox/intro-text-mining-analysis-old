---
title: Export
nav: true
---

# Save & Export

### Save and close a project

By default, OpenRefine saves your project continuously. To close OpenRefine close the *browser tab* and the *terminal window*.  

To find a saved project, open OpenRefine and select  `Open Project`  tab, a list of projects will be available to select and open.

----

### Export features

In OpenRefine you can export the cleaned data or the entire project. Exporting the project as a whole means you are saving the data and all the information about the cleaning and data transformation steps you have done. 

You can export your cleaned data, with different file formats, for use in other tools for analysis.

{% capture text %}
- Click  `Export`  in the top right and select the file type for the data export. Tab-separated values (`tsv`) or Comma-separated values (`csv`) are good choices, as they are non-proprietary, but can easily be opened in programs like Excel, R, Python or the Unix shell.

Any exported file will be saved to your default  `Download`  directory.{% endcapture %} {% include card.md header="Activity - export cleaned data" text=text %}

You can also export project files as a whole. This is helpful if you wanted to send your raw data and cleaning steps to a collaborator, or share the information as a supplement to a publication.

{% capture text %}
- Click the  `Export`  button in the top right and select  `Export project`.

A  `tar.gz`  file will download to your default  `Download`  directory. Depending on your browser, you may have to confirm that you want to save the file. 

The downloaded  `tar.gz`  file is a folder of files which have been compressed. *Linux* and *Mac* machines will have software installed to automatically expand this type of file when you double-click on it. 

For *Windows-based* machines, you may have to install a utility like *7-zip* to expand the zip file.{% endcapture %} {% include card.md header="Activity - export a project" text=text %}


{% include button.md text="Learn to export with this video" link="https://vimeo.com/412609640/189a2a8c7f" color="info" %}

----

{% capture text %}
After you have expanded the file, look at the files that appear in this folder. 

What files are here? What information do you think these files contain?

{% include modal.md button="Quiz 3 Solution" color="success" title="Quiz 3 Solution" text="- a history folder which contains a collection of zip files. Each of these files itself contains a `change.txt` file. 

- These `change.txt` files are the records of each individual transformation that you performed on your data.

- a data.zip file. When expanded, this zip file includes a file called `data.txt` which is a copy of your raw data. You may also see other files." %}{% endcapture %} {% include card.md header="Quiz 3. What files are in the exported project?" text=text %}

----

### Going Further

Want to continue your learning?  Go to [Advanced Data Wrangling with OpenRefine](https://griffithunilibrary.github.io/Advanced-data-wrangle/) for more.

