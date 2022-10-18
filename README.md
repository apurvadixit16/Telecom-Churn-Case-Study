# Telecom Churn Case Study
> The main goal of the case study to predict whether a high-value customer will churn or not, in near future (i.e. churn phase)


The company wants to know:
- Important variables that are strong predictors of churn

## Inference
Models used are as follows - 
Algorithm							Train Accuracy	 Test Accuracy	 Precission	 Recall
	
LR With PCA									0.784200	0.785333	0.307604	 0.872854
Random Forest with Default Parameter		0.999980	0.940286	0.785307	 0.575406
Random Forest with Hyper-Parameter			0.913345	0.908095	0.533353	 0.834803
XGBoost										0.977938	0.940286	0.744438	 0.636659

**On kaggle evaluation data, best accuracy observed with Random Forest with hyper-parameter tunning**

Top 10 variables that are significant in predicting the churn users:

1. total_ic_mou_8 (0.204850)
2. loc_ic_mou_8 (0.081681)
3. total_rech_data_8 (0.081294)
4. roam_og_mou_8(0.023444)
5. last_day_rch_amt_8(0.017483)
6. spl_ic_mou_8(0.015187)
7. av_rech_amt_data_8(0.013041)
8. offnet_mou_8(0.010484)
9. std_og_mou_7(0.010386)
10. total_rech_amt_8(0.009886)

## Libraries Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn

## Acknowledgments - 
- https://towardsdatascience.com/
- https://www.analyticssteps.com/
- https://medium.com/
- https://stackoverflow.com/
- https://www.geeksforgeeks.org/
