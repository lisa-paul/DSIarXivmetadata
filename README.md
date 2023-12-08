<h1 align = 'center'>arXiv Unveiled: Analyzing Metadata on Scientific Papers"</h1>

<h4 align = 'center'>GA DSI-911 Captone</h4>
<center> Lisa Paul</center>

 <br><hr><br>


## Problem Statement

## Executive Summary
	paragraph one

	paragrahp 2

## What is arXiv?


 <br><hr><br>
## File Directory / Table of Contents

This is an alphabetical list of the repository's directory and file structure. 

```
├── README.md
├── code
│   ├── 00-json-to-csv.ipynb
│   └── 01-preprocess-EDA.ipynb
├── data
│   ├── arxiv_meta_aa-single-cat.csv
│   ├── arxiv_meta_bb-single-cat.csv
│   ├── featured.csv
│   ├── features.csv
│   └── target.csv
├── images
│   └── top_categories_plot.png
├── presentation
│   └── Lisa Paul GA DSI Capstone_ arXiv metadata.pdf
```



## Software Requirements
- Jupyter Notebook
- Matplotlib.pyplot
- NLTK
- NumPy
- Pandas
- Scikit-Learn (sklearn)
- Seaborn



## Data Dictionary
<br><hr><br>
## Data Dictionary
> This dataset is a mirror of the original ArXiv data. Because the full dataset is rather large (1.1TB and growing), this dataset provides only a metadata file in the json format. This file contains an entry for each paper, containing:

| Feature        | Description                                     |
| -------------- | ----------------------------------------------- |
| id             | ArXiv ID (can be used to access the paper)      |
| submitter      | Who submitted the paper                         |
| authors        | Authors of the paper                             |
| title          | Title of the paper                               |
| comments       | Additional info, such as number of pages and figures |
| journal-ref    | Information about the journal the paper was published in |
| doi            | [Digital Object Identifier](https://www.doi.org) |
| abstract       | The abstract of the paper                        |
| categories     | Categories / tags in the ArXiv system            |
| versions       | A version history                                |


<br><hr><br>
## Conclusions and Recommendations

## Sources
- [arXiv Dataset](https://www.kaggle.com/dsv/7053634)
- [Split JSON into multiple files](https://stackoverflow.com/a/44216101)
- 
