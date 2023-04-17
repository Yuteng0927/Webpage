---
title: YouTube Data Extraction and Visualization  
summary: This project observed the YouTube's Videos category, counts, likes and comments based per country and its relation to each other.  
tags:
- coding
date: "2022-10-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: ""
  preview_only: false

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


### Research Summary
This project observed the YouTube's Videos category, counts, likes and comments based per country and its relation to each other. This project answers the question Our analysis focuses on answering below questions: Is there a significant difference in the average like count of the top 50 videos within each designated region within YouTube? Ha:Average like count will be significantly different between the regions H0: There is no difference between the average like count by region 

Is there a significant difference in the average like count of the top 50 videos of each designated category within YouTube? Ha: Average like count will be significantly different between the categories H0: There is no difference between the average like count by category 

Additional Correlations: What is the average percent of videos liked by the number of views they have received? 

Project is built to call the YouTube API's dataset related to Video . Due to large size, dataset is saved in CSV file for further analysis(5000 records). Python matplotlib, bar graph, pie charts are used to analyzed the data and specify the correlation in between videos, categories, likes, views and counts. Various methods such a correlation, aggregation, t-test, comparison , ANOVA tests are used to do further analysis of data.



