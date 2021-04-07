# Project 4: Causal Inference

### [Project Description](doc/project4_desc.md)

Term: Spring 2021

+ Team 2
+ Projec title: Causal Inference Algorithms Evaluation
+ Team members
	+ Wendy Doan (ad3801)
	+ Yibai Liu (yl4616)
	+ Shuqi Yu (sy2950)
	+ Yiwen Fang (yf2560)
	+ Zhihang Xia (zx2338)

+ Project summary:  In this project, we implemented and compared different algorithms for Causal Inference on both low dimension data and high dimension data. We compared the following algorithms and dataset with different combination:
+ For propensity score: We have both GBM and XGB for boosted stump and we tuned the hyperparameter for PS prediction
+ For Algorithm: we have Regression Adjusted, Stratification and combination of Regression Adjustment and Stratification which regression on each bin of the stratification 
+ For data preprocessing for imbalance: we have the original data, resampled data with oversampling and SMOTE


**Contribution statement**: 
Wendy: She initialized the pipeline from data exploration, propensity score (PS) prediction, to ATE estimation; developed basic baseline logistic regression and GBM models for PS prediction, and three base ATE estimation algorithms assigned; prepared and delivered project presentation. 

Yibai: She tuned the hyperparameters of GBM and XGboost models for PS prediction; wrapped up functions and procedures to generate one-click pipelines for algorithm evaluation and result reporting; prepared results summary. 

Shuqi: She developed resampling methods; organized project descriptions and helped with presentation powerpoint; Contributed to final report writing; tried different method for regression adjustment.

Yiwen: He investigated/wrote codes of propensity score estimation by boosted stumps (GBM and XGBoost) with/without weight parameters, the algorithm of stratification, and ATE estimations. He tune the model parameters of the boosted stump of GBM to make the best high dim and low dim ATE relative errors < 1% compared with true values. He helped re-write the reference part of the final Jupyter Notebook.

Zhihang: He wrote codes of propensity score estimation by adaboost and stratification. 


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
