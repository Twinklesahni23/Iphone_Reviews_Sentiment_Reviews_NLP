# Iphone13_Reviews_Sentiment_Reviews_NLP
![bigstock-Customer-Experience-Concept-H-320869609-2880x1800](https://user-images.githubusercontent.com/99166745/177498021-51e2f323-6920-4f67-8b2c-030e91327f99.jpg)

**This repository contains the sentiment analysis of reviews of Iphone13 on Amazon using VADER model.**

Sentiment analysis is an approach to natural language processing (NLP) that identifies the emotional tone behind a body of text. This is a popular way for organizations to determine and categorize opinions about a product, service, or idea and improve their buisness model thereof.

## Table of Contents
1. Reading and Exploring the data
2. Data Pre-Processing
3. Explanatory Data Analysis
   - Data Visualization
4. Sentiment Analysis
   - Cleaning the text
   - Tokenization
   - StopWords
   - Stemming
   - Lemmantizing
   - VADER Model
     - Overall sentiment
     - Categorical sentiment score
     
## Data
The data for this project has been extracted using web scrapping framework performed on [Amazon.in](https://www.amazon.in/?tag=msndeskabkin-21&hvadid=72911441658757&hvqmt=e&hvbmt=be&hvdev=c&ref=pd_sl_5nz8knj2kb_e) for Iphone 13 with 128gb storage variant. The dataset contains reviews from 801 customers along with the following features:
- Customer Name
- Rating
- Headline
- Date
- Variant
- Product Link
- Reviews
- Upvote

## Insights 
### *Most customers have given a 5-star rating. This confirms the user-friendly and satisfactory performance of Iphone13.*

![image](https://user-images.githubusercontent.com/99166745/177548812-6da38908-b687-4ace-be00-3fd8204e7edc.png)

### *We observed that most reviews were given in the month of May. Moreover, there are relatively lesser reviews during the third and fourth quater of the year. A possible explanation for this fact can be the price-sensitive behaviour of the customers. Mostly, in the month of September, Apple releases the new variant of Iphone and the price remains undiscounted for few following months.*

![image](https://user-images.githubusercontent.com/99166745/177549040-976a3d11-e2db-4948-8149-0e02671224ed.png)

### *Overall sentimeent and categorized sentiment scores:*

**The overall sentiment of reviews stands at Neutral**
**The categorized sentiment scores are:**
- **Positive:  311.37**
- **Negative:  33.74**
- **Neutral:  380.91**




     
      
