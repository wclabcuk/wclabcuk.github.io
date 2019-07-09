---
layout: post
title: Energy Theft Detection Using Gradient Boosting Theft Detector With Feature Engineering-Based Preprocessing
hide_title: true
img: "assets/img/portfolio/etf.png"
date: March, 02 2019
tags: [Projects, Machine learning]
---



# Energy Theft Detection Using Gradient Boosting Theft Detector With Feature Engineering-Based Preprocessing

![Image of a glass on a book]({{ "/assets/img/portfolio/etd.jpg" | relative_url }})

For the smart grid energy theft identification, this letter introduces a gradient boosting theft detector (GBTD) based 
on the three latest gradient boosting classifiers (GBCs): 1) extreme gradient boosting; 2) categorical boosting; and 3) 
light gradient boosting method. While most of existing machine learning (ML) algorithms just focus on fine tuning the 
hyperparameters of the classifiers, our ML algorithm, GBTD, focuses on the feature engineering-based preprocessing to 
improve detection performance as well as time-complexity. GBTD improves both detection rate and false positive rate (FPR) 
of those GBCs by generating stochastic features like standard deviation, mean, minimum, and maximum value of daily electricity 
usage. GBTD also reduces the classifier complexity with weighted featureimportance-based extraction techniques. Emphasis has been 
laid upon the practical application of the proposed ML for theft detection by minimizing FPR and reducing data storage space and
improving time-complexity of the GBTD classifiers. Additionally, this letter proposes an updated version of the existing six 
theft cases to mimic real-world theft patterns and applies them to the dataset for numerical evaluation of the proposed algorithm.