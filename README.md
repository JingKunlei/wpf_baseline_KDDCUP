# wpf_baseline_KDDCUP
This is a executable-version baseline code of 2022KDD_CUP for Wind Power Prediciton
The office website is https://aistudio.baidu.com/aistudio/competition/detail/152/0/introduction
# training and testing
python train.py 
python evaluation.py
# prepare operation environment
This code is copy from https://github.com/PaddlePaddle/PaddleSpatial/tree/main/apps/wpf_baseline_gru with debugging.
Please refer https://github.com/PaddlePaddle/PaddleSpatial/blob/main/installation_guide.md
# result of baseline code
Using 245days dataset divided by 200:20:25 for training, validation, and testing for evaluation
Evaluation criterion  Accuracy	 RMSE	    MAE	     Score
Value	                64.5125%   44.7528	38.1389	 41.4459
Metric formulas of RMSE and MAE can be found in the report from https://aistudio.baidu.com/aistudio/competition/detail/152/0/task-definition, the accuracy metric can refer the code definition.
