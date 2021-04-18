# Project 4: Causal Inference

### [Project Description](doc/project4_desc.md)

Term: Spring 2021

+ Team 2
+ Projec title: Stratification and Regression Adjustment for Causal Inference
+ Team members
	+ Wendy Doan (ad3801)
	+ Yibai Liu (yl4616)
	+ Shuqi Yu (sy2950)
	+ Yiwen Fang (yf2560)
	+ Zhihang Xia (zx2338)

+ Project summary:  In this project, we implemented and compared different algorithms for Causal Inference on both low-dimensional data and high-dimensional data. We evaluated the following algorithms and datasets with different combinations:
+ For propensity scores prediction: We experimented with GBM and XGB boosted stumps algorithms and tuned the hyperparameters for PS prediction
+ For ATE estimation: We have Regression Adjustment, Stratification and the combination of Regression Adjustment and Stratification which the regression is adjusted on each stratum 
+ For data imbalance treatment: we used the original data as well as resampled data with random oversampling and SMOTE


**Contribution statement**: 

Wendy: Initialized the pipeline from data exploration, propensity score (PS) prediction, to ATE estimation; developed basic baseline logistic regression and GBM models for PS prediction, and three base ATE estimation algorithms assigned; wrote functions to calcuate ATE scores for stratification, regression adjustment; sketched out and finalized project report; prepared and delivered project presentation. 

Yibai: Tuned the hyperparameters of GBM and XGboost models for PS prediction; wrapped up functions and procedures to generate one-click pipelines for algorithm evaluation and result reporting; prepared results summary. 

Shuqi: Developed resampling methods; organized project descriptions and helped with presentation powerpoint; contributed to final report writing; tried different methods for regression adjustment.

Yiwen: Finished algorithms of stratification, ATE estimations; contributed in tuning parameters of GBM; helped organize references.

Zhihang: Tuned the hyperparameters of AdaBoost model for propensity score estimation, contributed in finishing the function of stratification to compute ATE based on the scores predicted by the AdaBoost model for the datasets.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
