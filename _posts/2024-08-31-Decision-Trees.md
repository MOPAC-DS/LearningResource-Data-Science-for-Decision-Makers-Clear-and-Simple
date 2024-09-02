---
title: "Decision Trees"
date: 2024-09-02
categories: ['Machine Learning']
tags: ['Prediction', 'Decision Trees', 'Statistical Methods', 'Regression Modelling', 'Classification']
author: <dhammocks>
description: This post discusses Decision Trees in simple terms using accessible language for all.
image:
  path: /assets/images/posts/cover-decision-tree.png
  alt: Image Displaying a Simple Decision Tree
---

# Decision Trees

## What is a Decision Tree?

A decision tree is a model used to make decisions or predictions by following a series of questions or rules. Think of it like a flowchart: it starts with a question at the top, branches out based on possible answers, and leads to different outcomes. It's a structured way to break down complex decisions into simpler steps.


## Simple Example

Imagine you're trying to determine if someone is likely to be satisfied with their interaction with the police. You start with a question like, "Was the interaction in person or over the phone?" If the answer is "In person," you then ask, "Was the person a victim of a violent crime?" Depending on their answers, you will determine whether they are likely to be "Satisfied" or "Not Satisfied." Click on the image above to zoom in on the decision tree -- review each node to see which factors have been included to predict someones satisfaction with their interaction with the police.


## How Does a Decision Tree Work?

- **Start with a Question:** The tree begins with a primary question at the top.
- **Branch Out:** Based on the answer, the tree splits into branches representing different possible outcomes.
- **Ask More Questions:** Each branch leads to further questions, refining the decision.
- **Reach a Conclusion:** Ultimately, the tree provides a decision or prediction at the end of the branches.

For instance, a decision tree might start with questions about the method of interaction (phone or in-person) and the type of crime reported, to predict satisfaction with the police interaction.


## When Should You Use a Decision Tree?

Decision trees are useful when:

- You have various factors to consider in making a decision.
- You need a model that is easy to interpret and visualise.
- You want to understand how different conditions influence the final outcome.
- They are particularly helpful when dealing with categorical data.

## What Can Decision Trees Tell Us?

Decision trees can show:

- **Important Factors:** Which features, such as the type of crime or interaction method, are most significant in making a decision.
- **Outcome Scenarios:** How different combinations of factors lead to different outcomes.
- **Decision Process:** A clear visual representation of how decisions are made step-by-step.

## What Decision Trees Can’t Do

Decision trees have some limitations:

- **Overfitting:** They can become overly complex, fitting too closely to the training data and not generalising well to new cases.
- **Bias:** They might perform poorly with imbalanced datasets where some outcomes are much more frequent than others.
- **Complexity:** Large trees can be challenging to interpret and visualise.

## Key Takeaways
Decision trees are a versatile and interpretable tool for making decisions and predictions, especially valuable in scenarios where understanding the decision-making process is crucial. They help break down complex decisions into simpler, more manageable questions.

- Decision trees offer a straightforward method for making decisions based on multiple criteria.
- They provide a clear, visual representation of how different factors contribute to various outcomes.
- They are useful in crime analysis for understanding and predicting factors like satisfaction with police interactions.


## Glossary of Key Terms
- **Node:** A point on the tree where a decision or split occurs.
- **Branch:** A line connecting nodes, showing possible answers to questions.
- **Leaf:** The end point of the tree representing the final decision or outcome.
- **Overfitting:** When a model is too complex and performs well on training data but poorly on new, unseen data.

## Advanced Topics

### Interpreting Decision Tree Results

Interpreting a decision tree involves following the path from the root to the leaves. Each path represents a series of decisions based on the features of the data, helping to understand which factors most influence the outcome.

### Limitations
- **Overfitting:** Decision trees can become overly detailed, fitting the training data too closely and potentially performing poorly on new data.
- **Bias towards Features:** They can be biased towards features with more levels or categories, which may affect the model's performance.

### Assumptions
- **Independence:** Decision trees assume that the features used for making decisions are independent of each other.
- **Non-Linearity:** They can capture non-linear relationships between features and outcomes.

