---
date: "2020-06-01T00:00:00Z"
authors: 
- Yinglei Han
- Lawrence Ning Lu
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
slides:
summary:
tags:
- Machine Learning
title: Classification Models of Software-related Medical Device Recalls by Machine Learning
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

This project focuses on software-related medical device recalls. As the application of software in the medical devices field becomes more popular and complex, this issue deserves more attention. Most existing work involves distribution, fault modes and trend analysis, and related recalls are collected by manual work, which is time-consuming. The paper attempts to build an automatic classification model by machine learning. Firstly, the data is from the FDA website from 2018 to 2019. Secondly, text mining is conducted to deal with human written descriptions. Thirdly, the paper uses k-NN algorithm and Naïve Bayes algorithm to build models, and then tests them by cross validation. The models perform well and their accuracy are both around 90%, which means such classification models by machine learning are feasible. But there are also some problems, such as the selection of parameter k value in k-NN model, and they do not perform well in some other measurements such as sensitivity. In future work, more optional algorithms including hybrid ones should be considered, then the study in this area will provide a more efficient way to medical agencies and manufacturers.