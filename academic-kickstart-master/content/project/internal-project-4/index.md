---
title: Data Anaysis in Python
summary: 15 data analysis projects guided by dataquest. Implemented using Python and SQL (rarely).
tags:
- Data Analysis
- Python
- SQL
date: "2019-09-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: #Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

**1. Profitable App Profiles For *The App Store* And *Google Play Markets*.**

In this project the data of a company that builds Android and iOS mobile apps is under consideration. The company makes the apps available on Google Play and the App Store and only builds apps that are free to download and install; and the main source of revenue consists of in-app ads. This means that comnany's revenue for any given app is mostly influenced by the number of users who use the app — the more users that see and engage with the ads, the better. Therefore the goal of this project is to analyze data to help company's developers understand what type of apps are likely to attract more users.

**2. Exploring *Hacker News Posts*.**

In this project, the work with a data set of submissions to popular technology site Hacker News is under consideration. Hacker News is a site, where user-submitted stories (known as "posts") are voted and commented upon. Hacker News is very popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

The posts whose titles begin with Ask HN or Show HN are specifically interesting in this project. Users submit Ask HN posts to ask the Hacker News community a question; users submit Show HN posts to show the Hacker News community a project, product, something interesting.

The main goal of this project is to answer the following questions:
Do Ask HN or Show HN receive more comments on average?
Do posts created at a certain time receive more comments on average?

**3. Exploring *Ebay Car* Sales Data.**

The goal of this project is to clean the data and analyze the included used car listings.

**4. Visualizing Earnings Based On College Majors.**

The dataset on the job outcomes of students who graduated from college between 2010 and 2012 is under consideration in this project. Using visualizations (scatter plots, histograms, bar plots), the following questions from the dataset was explored:
Do students in more popular majors make more money?
How many majors are predominantly male? Predominantly female?
Which category of majors have the most students?

**5. Visualizing The Gender Gap In College Degrees.**

**6. Analyzing NYC High School Data.**

**7. Star Wars Survey.**

**8. Clean And Analyze Employee Exit Surveys.**

In this project, exit surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland,

Australia is under consideration. The following was explored:
Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

**9. Analyzing CIA Factbook Data Using *SQLite* and Python.**

**10. Answering Business Questions using *SQL*.**

**11. Designing and Creating a *Database*.**

**12. Finding the Best Markets to Advertise In.**

In this project some e-learning company that offers courses on programming is considered. Most of the courses of the company are on web and mobile development, but they also cover many other domains, like data science, game development, etc. The company want to promote our product and  to invest some money in advertisement. The goal of this project is to find out the two best markets to advertise the company product in.

To avoid spending money on organizing a survey, the first what is necessary to try is to make use of existing data to determine whether the company can reach any reliable result. One good candidate for the purpose is freeCodeCamp's 2017 New Coder Survey. freeCodeCamp is a free e-learning platform that offers courses on web development. Because they run a popular Medium publication (over 400,000 followers), their survey attracted new coders with varying interests (not only web development), which is ideal for the purpose of the analysis.

**13. Investigating *Fandango* Movie Ratings.**

In October 2015, a data journalist named Walt Hickey analyzed movie ratings data and found strong evidence to suggest that Fandango's rating system was biased and dishonest (Fandango is an online movie ratings aggregator). He published his analysis in this article — a great piece of data journalism that's totally worth reading.

Fandango displays a 5-star rating system on their website, where the minimum rating is 0 stars and the maximum is 5 stars.
imgSource: Fandango Hickey found that there's a significant discrepancy between the number of stars displayed to users and the actual rating, which he was able to find in the HTML of the page. He was able to find that:

The actual rating was almost always rounded up to the nearest half-star. For instance, a 4.1 movie would be rounded off to 4.5 stars, not to 4 stars, as you may expect. In the case of 8% of the ratings analyzed, the rounding up was done to the nearest whole star. For instance, a 4.5 rating would be rounded off to 5 stars. For one movie rating, the rounding off was completely bizarre: from a rating of 4 in the HTML of the page to a displayed rating of 5 stars. imgSource: FiveThirtyEight The two distributions above are displayed using a simple line plot, which is also a valid way to show the shape of a distribution. The variable being examined is movie rating, and for each unique rating we can see its relative frequency (percentage) on the y-axis of the graph. When an analysis report is intended for large audiences, relative frequencies (especially percentages) are preferred over absolute frequencies.

Both distributions above are strongly left skewed, suggesting that movie ratings on Fandango are generally high or very high. We can see there's no rating under 2 stars in the sample Hickey analyzed. The distribution of displayed ratings is clearly shifted to the right compared to the actual rating distribution, suggesting strongly that Fandango inflates the ratings under the hood.

Fandango's officials replied that the biased rounding off was caused by a bug in their system rather than being intentional, and they promised to fix the bug as soon as possible. Presumably, this has already happened, although we can't tell for sure since the actual rating value doesn't seem to be displayed anymore in the pages' HTML.

In this project, the analysis of more recent movie ratings data is presented to determine whether there has been any change in Fandango's rating system after Hickey's analysis. One of the best ways to figure out whether there has been any change in Fandango's rating system after Hickey's analysis is to compare the system's characteristics previous and after the analysis.

**14. Mobile App for Lottery Addiction.**

Many people start playing the lottery for fun, but for some this activity turns into a habit which eventually escalates into addiction. Like other compulsive gamblers, lottery addicts soon begin spending from their savings and loans, they start to accumulate debts, and eventually engage in desperate behaviors like theft.

A medical institute that aims to prevent and treat gambling addictions wants to build a dedicated mobile app to help lottery addicts better estimate their chances of winning. The institute has a team of engineers that will build the app, but they need to create the logical core of the app and calculate probabilities.

For the first version of the app, they want to focus on the 6/49 lottery and build functions that enable users to answer questions like:
What is the probability of winning the big prize with a single ticket? What is the probability of winning the big prize if we play 40 different tickets (or any other number)? What is the probability of having at least five (or four, or three, or two) winning numbers on a single ticket? The institute also wants also to consider historical data coming from the national 6/49 lottery game in Canada.

These questions is under consideration in this project. The data set has data for 3,665 drawings, dating from 1982 to 2018.

**15. Winning Jeopardy.**

Jeopardy is a popular TV show in the US where participants answer questions to win money. It's been running for a few decades, and is a major force in popular culture. Let's say you want to compete on Jeopardy, and you're looking for any edge you can get to win.

In this project, the work with a dataset of Jeopardy questions is done to figure out some patterns in the questions that could help you win.

<a href="">

</a>

<a href="https://app.dataquest.io/verify_cert/I9RX67UZ5L610XGEEF8L/">
  Certificate
</a>
