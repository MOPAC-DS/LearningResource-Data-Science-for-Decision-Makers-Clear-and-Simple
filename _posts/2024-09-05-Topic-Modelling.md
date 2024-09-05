---
title: "Topic Modelling"
date: 2024-09-05
categories: ['Natural Language Processing (NLP)', 'Text Classification']
tags: ['Classification', 'Topic Modelling', 'NLP', 'Unsupervised Learning', 'Document Classification', 'Text Analytics', 'Content Summarisation']
author: <dhammocks>
description: This post discusses Topic Models in simple terms using accessible language for all.
image:
  path: /assets/images/posts/cover-topic-model.png
  alt: Image Displaying Topic Model Results
---

# A Simple Guide to Topic modelling

## What is Topic modelling?

Topic modelling is a technique used to automatically find the main topics in a large collection of text. It helps us understand what the text is mostly about without having to read everything. It’s like sorting through a pile of documents and grouping them by themes or subjects.

## Simple Example

Imagine you have 100 police reports. Some reports are about theft, some are about assault, and others are about traffic violations. Reading each report would take a long time. Instead, topic modelling can automatically sort these reports into different groups based on the themes that appear most frequently, like "theft," "assault," and "traffic."

## How Does Topic modelling Work?

Topic modelling works by scanning large amounts of text and looking for patterns in the words used. It doesn't know the actual topics beforehand but finds clusters of words that tend to appear together. These clusters of words are then labeled as "topics."

Here’s a simple breakdown:

- **Step 1:** The model looks at the text and tries to find words that often appear together.
- **Step 2:** It groups these words into “topics.”
- **Step 3:** It assigns each piece of text (like a report) to one or more topics based on the words it contains.

For example, words like "stolen," "property," and "suspect" might get grouped into a "theft" topic, while words like "accident," "vehicle," and "driver" might belong to a "traffic" topic.

## When Should You Use Topic modelling?

Topic modelling is helpful when:

- You have a large amount of text data and want to quickly understand what it’s about.
- You want to find hidden themes or patterns without reading everything yourself.
- You need to categorise or group text data for analysis.

## What Can Topic modelling Tell Us?

Topic modelling can tell us:

- **What the main topics are** in a collection of text (e.g., crime reports, survey responses).
- **How often each topic appears** across different documents.
- **Which topics are related** or often appear together.

For example, in crime analysis, you could use topic modelling to find out the key themes discussed in a survey of people affected by crime.

![img-description](/assets/images/posts/tm-topics.png)
_Screenshot of Interactive Visualisation Demonstrating Words That Form A Topic_

![img-description](/assets/images/posts/tm-words.png)
_Screenshot of Interactive Visualisation Demonstrating Words And Their Usage Across Topics_

![img-description](/assets/images/posts/tm-documents.png)
_Screenshot of Interactive Visualisation Demonstrating Documents Their Composition of Topics and Topic Prevalence Over Time_


## Practical Use of Topic modelling

In real-life scenarios, topic modelling is used for:

- **Summarising large text collections:** Like summarising thousands of police reports to identify the main types of crime.
- **Monitoring trends:** For example, it can help see if certain crimes are becoming more common over time.
- **Classifying documents:** Automatically grouping complaints, reports, or feedback into different categories based on the topics.

## What Topic Models Can’t Do

While topic modelling is a powerful tool, it has limitations:

- **No labels:** The topics that are discovered are not labeled automatically. You need to interpret what each topic is about.
- **Not always precise:** The model might group unrelated words into a topic or miss subtle differences between topics.
- **Hard to handle small data:** Topic models work best when there’s a lot of text to analyse. With smaller datasets, the results might not be as accurate.

## Key Takeaways

- Topic modelling helps discover the main themes in large amounts of text.
- It can be used to organise, summarise, and understand text data.
- While powerful, topic modelling has its limits and may require interpretation.

## Glossary of Terms

- **Topic:** A group of words that often appear together in the text and represent a theme.
- **Document:** A single piece of text, such as a report or article, that the model analyses.
- **Model:** The algorithm used to identify and group words into topics.
- **Word Frequency:** How often a word appears in the text, which helps the model find important words.
