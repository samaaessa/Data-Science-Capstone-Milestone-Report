# Data-Science-Capstone-Milestone-Report

## Overview

It is the Milestone Report for the Coursera Data Science Capstone project. In this capstone, we will be applying data science in the area of natural language processing. The project is sponsored by SwiftKey.

The final objective of the project is to create text-prediction application with R Shiny package that predicts words using a natural language processing model i.e. creating an application based on a predictive model for text. Given a word or phrase as input, the application will try to predict the next word. The predictive model will be trained using a corpus, a collection of written texts, called the HC Corpora which has been filtered by language.

But, this milestone report describes the exploratory data analysis of the Capstone Dataset.

## Task Gaol

The goal of this project is just to display that you’ve gotten used to working with the data and that you are on track to create your prediction algorithm. Please submit a report on R Pubs (http://rpubs.com/) that explains your exploratory analysis and your goals for the eventual app and algorithm. This document should be concise and explain only the major features of the data you have identified and briefly summarize your plans for creating the prediction algorithm and Shiny app in a way that would be understandable to a non-data scientist manager. You should make use of tables and plots to illustrate important summaries of the data set. The motivation for this project is to:

In short this markup document shows:

1. Demonstration in loading and cleaning the data.
2. Summary statistics about the data sets.
3. First interesting findings.
4. Feedback for creating a prediction algorithm and Shiny app.

## About Data

The corpora are collected from publicly available sources by a web crawler. The crawler checks for language, so as to mainly get texts consisting of the desired language*.

Each entry is tagged with it's date of publication. Where user comments are included they will be tagged with the date of the main entry.

Each entry is tagged with the type of entry, based on the type of website it is collected from (e.g. newspaper or personal blog) If possible, each entry is tagged with one or more subjects based on the title or keywords of the entry (e.g. if the entry comes from the sports section of a newspaper it will be tagged with "sports" subject).In many cases it's not feasible to tag the entries (for example, it's not really practical to tag each individual Twitter entry, though I've got some ideas which might be implemented in the future) or no subject is found by the automated process, in which case the entry is tagged with a '0'.

To save space, the subject and type is given as a numerical code.

Once the raw corpus has been collected, it is parsed further, to remove duplicate entries and split into individual lines. Approximately 50% of each entry is then deleted. Since you cannot fully recreate any entries, the entries are anonymised and this is a non-profit venture I believe that it would fall under [Fair Use](https://web-beta.archive.org/web/20160930083655/http://en.wikipedia.org/wiki/Fair_use).

* You may still find lines of entirely different languages in the corpus. There are 2 main reasons for that:1. Similar languages. Some languages are very similar, and the automatic language checker could therefore erroneously accept the foreign language text.2. "Embedded" foreign languages. While a text may be mainly in the desired language there may be parts of it in another language. Since the text is then split up into individual lines, it is possible to see entire lines written in a foreign language.Whereas number 1 is just an out-and-out error, I think number 2 is actually desirable, as it will give a picture of when foreign language is used within the main language.

Content archived from heliohost.org on September 30, 2016 and retrieved via Wayback Machine on April 24, 2017. https://web-beta.archive.org/web/20160930083655/http://www.corpora.heliohost.org/aboutcorpus.html 

Note : At this Task I use only English Text

## Instructions
The goal of this project is just to display that you've gotten used to working with the data and that you are on track to create your prediction algorithm. Please submit a report on R Pubs (http://rpubs.com/) that explains your exploratory analysis and your goals for the eventual app and algorithm. This document should be concise and explain only the major features of the data you have identified and briefly summarize your plans for creating the prediction algorithm and Shiny app in a way that would be understandable to a non-data scientist manager. You should make use of tables and plots to illustrate important summaries of the data set. The motivation for this project is to: 1. Demonstrate that you've downloaded the data and have successfully loaded it in.2. Create a basic report of summary statistics about the data sets.3. Report any interesting findings that you amassed so far.4. Get feedback on your plans for creating a prediction algorithm and Shiny app.

## Review Criteria
1. Does the link lead to an HTML page describing the exploratory analysis of the training data set?
2. Has the data scientist done basic summaries of the three files? Word counts, line counts and basic data tables?
3. Has the data scientist made basic plots, such as histograms to illustrate features of the data?
4. Was the report written in a brief, concise style, in a way that a non-data scientist manager could appreciate?
