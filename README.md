# Introduction
This an executable-version baseline code of 2022KDD_CUP with official website https://aistudio.baidu.com/aistudio/competition/detail/152/0/task-definition. The code is copied from https://github.com/PaddlePaddle/PaddleSpatial/tree/main/apps/wpf_baseline_gru with debugging.
# User Guide
## Environment Setup   
Following https://github.com/PaddlePaddle/PaddleSpatial/blob/main/installation_guide.md to prepare environment.
## Dataset
We use wtbdata_245days.csv divided by 200:20:25 for training, validation, and testing.
## Model Training and Testing
Place wtbdata_245days.csv into folder .\wpf_baseline_gru.zip\wpf_baseline_gru\kddcup22-sdwpf-evaluation\data before running.
```
    python train.py 
    python evaluation.py
```
## Evaluation metric
Refer the metric definition of RMSE and MAE in sdwpf_report_v2.2 in this repository.
## Results
Accuracy	RMSE	 MAE	    Score
64.5125%	44.7528	 38.1389	41.4459
(Rfer the accuracy metric in the baseline code)

    
