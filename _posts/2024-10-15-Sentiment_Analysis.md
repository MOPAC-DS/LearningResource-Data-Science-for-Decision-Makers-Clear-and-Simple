---
title: "Sentiment Analysis"
date: 2024-10-15
categories: ['Natural Language Processing (NLP)']
tags: ['Classification', 'NLP', 'Text Analytics']
author: <dhammocks>
description: This post discusses Sentiment Analysis in simple terms using accessible language for all.
image:
  path: /assets/images/posts/cover-sentiment-analysis.png
  alt: Image Showing Scale of Positive and Negative Emotional Response
---

# A Simple Guide to Sentiment Analysis


## What is Sentiment?

In everyday life, people express their feelings and opinions all the time—whether in conversations, online posts, reviews, or surveys. These feelings can generally be categorised into three types:

 - Positive (e.g., happiness, satisfaction)
 - Negative (e.g., frustration, anger)
 - Neutral (e.g., indifference or balanced views)

Sentiment refers to these emotional tones or attitudes that people express when they talk or write.


## What is Sentiment Analysis?

Sentiment analysis is a data science technique that automatically detects and classifies these emotions (sentiments) from text. It helps us understand how people feel about a particular topic, brand, policy, or event based on what they say or write.


## Why is Sentiment Analysis Important?

Sentiment analysis is useful for decision-makers because it provides insights into public opinion. By analysing large amounts of text (e.g., feedback, social media posts, or survey responses), organisations can quickly gauge how people feel about their services, policies, or events.

For example:

 - Businesses use it to understand customer satisfaction.
 - Governments use it to evaluate public reaction to policies.
 - Marketing teams use it to measure the success of campaigns.


## Sentiment Calculation

Sentiment Calculation involves analysing text to assign a sentiment score, typically ranging from positive to negative. This is done using two main approaches:

1. Rule-based Approach:
- This method uses pre-defined lists of positive and negative words (e.g., "happy" is positive, "angry" is negative).
- It calculates sentiment based on the presence of these words. For instance, if a review says "The service was excellent!", the word "excellent" would trigger a positive sentiment score.
- This approach is simple but may miss context (e.g., sarcasm or irony).
2. Machine Learning-based Approach:
- This approach trains algorithms to recognise sentiment from examples. The algorithm learns from labeled data (text where the sentiment is already known) and then predicts sentiment for new, unseen text.
- These models are more sophisticated, as they can capture complex patterns like sarcasm or sentence structure.


## What is Polarity?

In sentiment analysis, polarity refers to the strength and direction of sentiment. It tells us whether the sentiment is:

- Positive (e.g., +1)
- Negative (e.g., -1)
- Neutral (e.g., 0)

Polarity helps us quantify sentiment in a standardised way. For example, a social media post with the phrase "I love this product!" might get a score of +0.9 (strong positive sentiment), while a post like "This product is okay" might score +0.1 (weak positive sentiment).


## What is Subjectivity?

In addition to measuring sentiment, sentiment analysis can also determine how subjective or objective a statement is:

- **Subjectivity** refers to how personal, opinion-based, or emotional a statement is. For example, “I love this product!” is highly subjective because it expresses a personal opinion.
- **Objectivity** refers to more factual, neutral statements that don’t involve personal feelings or opinions. For instance, “The product weighs 500 grams” is an objective statement because it’s based on fact.

Subjectivity helps decision-makers understand the nature of the feedback. Subjective statements reflect personal emotions and opinions, while objective statements provide facts that are less influenced by personal feelings.


## Other Considerations: Sentiment Beyond Words

### Context Matters:

Sentiment can change based on context. For example, "This phone is a monster" could be positive (meaning the phone is powerful) or negative (meaning the phone is too bulky), depending on the situation. Advanced sentiment analysis models try to understand context by looking at the structure of sentences and even considering emoji or slang used in modern communication.

### Emotion Detection:

In addition to simple positive or negative classifications, some tools go further and detect specific emotions like joy, anger, or sadness. This can provide even deeper insights into how people are feeling.


## Key Takeaways

 - Sentiment refers to the emotions or attitudes expressed in text, which can be positive, negative, or neutral.
 - Sentiment analysis is the process of automatically detecting and classifying emotions in text data, helping organisations understand public opinion.
 - There exist two main approaches to sentiment analysis:
     - Rule-based approach uses pre-defined lists of positive/negative words.
     - Machine learning-based approach uses algorithms trained on labeled data to predict sentiment.
 - Polarity is the strength and direction of sentiment, ranging from positive to negative.
 - Subjectivity helps classify statements as personal opinions (subjective) or factual information (objective), adding important context to the sentiment.
 - Sentiment analysis is useful for understanding customer feedback, public opinions on policies, and reactions to marketing campaigns.
- Sentiment can change depending on how words are used or structured in sentences.
- Sentiment analysis can handle multiple languages and detect more nuanced emotions like joy, anger, or sadness.


## Glossary of Terms

- **Sentiment**: The emotional tone (positive, negative, or neutral) expressed in a piece of text.
- **Polarity**: A measure of the strength and direction of the sentiment. Positive polarity means the sentiment is positive, negative polarity means it's negative, and neutral polarity means no strong emotion.
- **Subjectivity**: How much a statement expresses personal opinions, emotions, or beliefs, as opposed to being factual. Higher subjectivity means more opinion-based content.
- **Objectivity**: The extent to which a statement is factual and unbiased, without expressing personal feelings or opinions.
- **Rule-based Approach**: A method that classifies sentiment by using a predefined set of positive and negative words.
- **Machine Learning-based Approach**: A method that uses algorithms trained on labeled data to predict sentiment in new text.
- **Emotion Detection**: A more advanced form of sentiment analysis that identifies specific emotions (e.g., joy, anger, sadness) in text.