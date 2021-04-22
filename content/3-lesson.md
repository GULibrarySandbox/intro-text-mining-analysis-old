---
title: Layout
nav: true
---
# The Layout of OpenRefine

-----

### Display 

OpenRefine displays data in a tabular format, similar to how you might view data in a spreadsheet or database. 
- Each row will usually represent a 'record' or 'observation' in the data
- Each column represents a type of information or 'variable'
- Individual bits of data or 'values' live in 'cells' at the intersection of a row and a column

- A limited number of rows of data are displayed to save on memory, however the program is working on ALL rows.
- Adjust the number of rows displayed by selecting 5, 10, 25 or 50 at the top left of the table of data.

### Working with data in OpenRefine

- Navigate through records using *previous/next/first/last* navigation options at the top right of the table of data
- Use the drop-down menus at the top of each column to work with data
- Selecting an option in a particular column (e.g., to make a change to the data), affects all the cells in that column 
- Perform changes one column at a time, even when making changes across several columns 


###  Rows and Records

OpenRefine has two modes of viewing data: 'Rows' and 'Records'. 
- Rows mode: each row represents a single record in the data set
- Records mode, OpenRefine can link together multiple rows as belonging to the same record 

This is useful when working with `xml` files, MARC records, as well as `csv` files. We will see an example of this later.

{% include figure.html img="ORLayout.png" alt="OpenRefine layout" caption="OpenRefine layout" width="75%" %}

### Undo / Redo

OpenRefine provides Undo and Redo operations to make changes to your data work, going back to your very first action. Find out how this works in the [GREL](https://griffithunilibrary.github.io/intro-data-wrangle/content/6-lesson.html) activities. 

### Saving projects

Projects are saved automatically as you work on them,  so there is no need to save copies as you go along. 

### Opening existing projects

To open an existing project in OpenRefine, click  `Open Project`  from the main OpenRefine screen (in the left-hand menu). 
When you click this, you will see a list of the existing projects and can click on a project's name to open it.

{% include button.md text="Watch this video to see OpenRefine's layout" link="https://vimeo.com/412542634/f5b1ced9b9" color="info" %}

-----

<p align="center">
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/2-lesson.html"><-- BACK</a> |
  <a href="https://griffithunilibrary.github.io/intro-data-wrangle/content/4-lesson.html">NEXT --></a>
</p>
