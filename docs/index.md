--- 
title: "Data Skills" # edit
#subtitle: "optional" 
author: "Emily Nordmann" # edit
date: "2025-03-17"
site: bookdown::bookdown_site
documentclass: book
classoption: oneside # for PDFs
geometry: margin=1in # for PDFs
bibliography: [book.bib, packages.bib]
description: "This is the Level 1 data skills book for Psychology at UofG"
csl: include/apa.csl
link-citations: yes
url: https://psyteachr.github.io/data-skills-v3 # edit
github-repo: psyteachr/data-skills-v2 # edit
cover-image: images/logos/logo.png # replace with your logo
apple-touch-icon: images/logos/apple-touch-icon.png # replace with your logo
apple-touch-icon-size: 180
favicon: images/logos/favicon.ico # replace with your logo
always_allow_html: true
---



# Overview {-}

<div class="small_right"><img src="images/logos/logo.png" 
     alt="Data skills Logo" /></div>

By the end of this book, you will be able to analyse data from classic psychological experiments and questionnaires by:

* Importing and simulating data
* Manipulating and wrangling data into an appropriate format for analysis
* Calculating summaries of descriptive statistics
* Producing informative data visualisations
* Performing basic probability calculations using simulation

This book accompanies our first-year undergraduate psychology curriculum. The course materials for our [second](https://psyteachr.github.io/analysis-v2/) and [third](https://psyteachr.github.io/stat-models-v1/) year courses are also available open-access, in addition to [PGT and ad-hoc courses.](https://psyteachr.github.io/)

## How to use this book and the walkthrough videos

For most chapters of this book there is an associated walkthrough video. These videos are there to support you as you get comfortable using R, however, it's important that you use them wisely. You should always try to work through each chapter of this book (or if you prefer each activity) on your own and only then watch the video if you get stuck, or for extra information. 

For many of the initial chapters, we will provide the code you need to use. You can copy and paste from the book, however, we strongly encourage you to type out the code by yourself. This will seem much slower and you will make errors, but you will learn much more quickly this way.

Additionally, we also provide the solutions to many of the activities. No-one is going to check whether you tried to figure it out yourself rather than going straight to the solution but remember this: if you copy and paste without thinking, you will learn nothing. 

Finally, on occasion we will make updates to the book such as fixing typos and including additional detail or activities and as such this book should be considered a living document. When substantial changes are made, new walkthrough videos will be recorded, however, it would be impossible to record a new video every time we made a minor change, therefore, sometimes there may be slight differences between the walkthrough videos and the content of this book. Where there are differences between the book and the video, the book should always be considered the definitive version. 

## Changes from version 2

The main change from version 2 aside from typos and edits for clarity is that we have reverted back to instructing students to locally install R and RStudio on their machines rather than using a browser-based version due to issues with the stability of the service around assessment deadlines. 

## Statement on use of AI

A premium subscription to ChatGPT using GPT4.0 was used to assist in the writing of these materials in the following ways:

* To suggest multiple-choice questions and other types of quizzes and/or to provide the text for "Explain this answer" for such quizzes
* To proof-read and check for typos and inconsistencies in variable names
* To suggest improvements to the text

Any information provided by ChatGPT was verified, for example, where code was used, the syntax and output was checked to ensure it was correct and where theoretical or conceptual information was provided, only that which the author could verify from their pre-existing expertise was included. 


