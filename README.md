# Automatically categorize questions

Stack Overflow is a website offering questions and answers on a wide range of computer programming topics. A member wishing to ask a question must use the dedicated form in which he must fill in a title, a question and 1 to 5 tags in order to categorize it. For experienced users this is not a problem, but for new users it would be a good idea to suggest some tags related to the question asked.

The proposed solution consists of setting up a tag suggestion tool. It will be based on the title and content of the question. After a first pre-processing, a machine learning model will propose a series of tags depending on the content of the question asked. 

# Table of contents

1. [Problem description](#problem-description)
2. [Data cleaning](#data-cleaning)
3. [Data analysis overview](#data-analysis-overview)
4. [LDA](#lda)
5. [Modelization](#modelization)
6. [Results](#results)

# Problem description

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_desc.png" width="1200">

[Back to table of contents](#table-of-contents)

# Data cleaning

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_data_cleaning.png" width="600">

[Back to table of contents](#table-of-contents)

# Data analysis overview

## Tags number per post

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_tags.png" width="600">

1. The number of tags per post has an empirical distribution ranging from 1 to 5
2. In the sample, mostly there are 2 tags on post

## Wordcloud

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_wordcloud.png" width="600">

Visual representation of the 100 most common words

[Back to table of contents](#table-of-contents)

# LDA

## Process description

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_lda.png" width="1200">

## Coherence score

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_lda_score.png" width="600">

## Topics overview

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_lda_result.png" width="600">

[Back to table of contents](#table-of-contents)

# Modelization

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_model.png" width="1200">

[Back to table of contents](#table-of-contents)

# Results

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p5_results.png" width="600">

The model using Universal sentence encoder is the best performing model

[Back to table of contents](#table-of-contents)
