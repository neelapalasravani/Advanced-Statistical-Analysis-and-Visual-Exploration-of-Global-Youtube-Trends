# Advanced-Statistical-Analysis-and-Visual-Exploration-of-Global-Youtube-Trends

**Name**: Sravani Neelapala
**Date**: September 5, 2023

---

## 🌍 Why I Chose This Project

While exploring datasets for a meaningful data analysis project, I came across the Global YouTube Statistics 2023 dataset on Kaggle. It immediately caught my attention because it's about a platform I, and so many others, use daily. YouTube is full of creators from different parts of the world, and I was curious to see what the data could tell us about success on the platform—who's rising, in which countries, and what categories perform best.

---

## 📄 Project Summary

This project explores the top 1000 YouTube creators globally based on subscriber count, views, uploads, earnings, and other factors. I used R (RMarkdown + tidyverse) to analyze the data, perform hypothesis testing, and run a linear regression to explore patterns and relationships.

---

## 📅 What I Set Out To Do

* Clean and prepare the dataset (995 observations, 28 variables)
* Convert key variables into factor types for better analysis
* Visualize trends: Who’s uploading the most? Which categories get the most subscribers?
* Test a few hypotheses based on research and assumptions
* Build a simple linear regression model to understand how different metrics relate to channel ranking

---

## 🔧 Tools I Used

* **Language**: R
* **Packages**: tidyverse, dplyr, ggplot2, lubridate
* **Platform**: RStudio, RMarkdown

---

## 📊 What the Data Showed Me

Some interesting takeaways:

* The **Entertainment** and **Music** categories dominate the top YouTubers list
* **Shows** and **Trailers** tend to have higher subscriber averages
* **Uploads** vary widely—some creators have fewer than 10, while others have over 100,000
* There’s a strong **negative correlation** between **rank** and **subscribers** (lower rank = more subscribers)

I created histograms, boxplots, bar charts, and density plots to better understand these patterns.

---

## 🧬 Hypothesis Testing

I tested whether the average number of subscribers matched the benchmark reported in a media article. I also compared upload activity between Entertainment and Music channels.

* The t-test suggested no significant difference from the benchmark.
* The F-test showed that Entertainment and Music channels do differ significantly in upload behavior.

---

## 🔢 Linear Regression

I built a model to see if **subscribers**, **uploads**, and **video views** can help predict a channel’s **rank**.

* **Subscribers** were clearly a strong predictor.
* **Uploads** didn’t show a significant relationship.
* **Video views** had a weak but noticeable correlation.

I also checked the residuals and diagnostics. The model was far from perfect but helped me understand the structure of the data.

---

## 🚀 Final Thoughts

This project gave me a chance to work through a full data workflow: from cleaning and summarizing to modeling and interpreting results. More importantly, it gave me insight into how creators succeed on YouTube—and how data can tell those stories.

I learned how to:

* Handle messy real-world data
* Use statistical tests to validate assumptions
* Build a basic predictive model
* Communicate findings with visuals

---

## 🌟 What’s Next

* Build an interactive dashboard using Shiny
* Dig deeper into time-based trends if timestamped data becomes available
* Try PCA or clustering on numerical variables

---

## 🔗 Data Source & Credit

* [Kaggle Dataset - Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023)

Thanks for checking out my project! If you're a recruiter or collaborator interested in data, media, or just good storytelling through code, feel free to connect.
