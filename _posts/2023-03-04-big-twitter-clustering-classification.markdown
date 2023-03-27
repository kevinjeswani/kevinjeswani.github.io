---
layout: post
title:  Big Twitter Clustering & Classification
description: Topic modelling and sentiment analysis on big twitter data (4-55mil. tweets)
date:   2023-03-04 15:00:00 +0800
image:  '/images/1013.jpg'
tags:   [NLP,classification,clustering,spark,big-data]
featured: false
---

- Streamed tweets into AWS S3 with Kinesis Firehose and combined it with a larger 55 mil.-tweet dataset (Not covered in this repo)
- Utilized PySpark in DataBricks to build custom PySpark transformers, label sentiment with SparkNLP/VADER, explore SparkML RandomForest and Logistic Regression classifiers, and to perform Latent Drichlet Allocation topic modelling
- Visualized results in AWS QuickSight through an Athena pipeline

[Github](https://github.com/kevinjeswani/BigTwitter_Clustering-Classification)