---
title: "Multi-core Sentiment Engine"
excerpt: "Sentimental Analysis from text: A text analysis algorithm based on ETL approach with multiprocessing for parallel processing of multiple text files<br/><img src='images/multicore-se.png'>"
collection: portfolio
---

This rule-based text analysis algorithm is able to utilize multiple cores of a processor, and is designed to run on a server as an engine and not a end to end web application. The algorithm takes URLs and id as input and calculates the positive, negative, ... scores from the article text and updates the values to output destination, data from here can be used for other applications. The data extraction and NLP problem is tasked with solving ways to design and implement a sentimental analysis algorithm, which analyzes textual data from web and assess its sentiments, positive, negative, or neutral, along with determining more variables such as subjectivity score, readability. Implementation is available at [github](https://github.com/suwesh/Multi-core_SentimentEngine) and [huggingface](https://huggingface.co/suwesh/Multi-core_SentimentEngine).
