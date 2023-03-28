# LiveBirthPrediction_Data_Code
Data and code needed to reproduce the findings of the live birth prediction study:

Liu, Hang, Zhuoran Zhang, Yifan Gu, Changsheng Dai, Guanqiao Shan, Haocong Song, Daniel Li, Wenyuan Chen, Ge Lin, and Yu Sun. "Development and evaluation of a live birth prediction model for evaluating human blastocysts: a retrospective study." Elife 12 (2023): e83662.

Figure 1-Source Data 1:
This directory contains the code to reproduce the model.

Figure-2-Code-Data: 
This directory contains the data and code used for generating ROC curves shown in Figure 2 of the manuscript.

Figure 3-Source Data 1:
This directory contains the data and code used for generating the AUC ranking chart shown in Fgiure 3 of the manuscript.

Figure-4-Data:
This directory contains the data and code used for generating the heatmaps shown in Figure 4 of the manuscript.

Codes and software used to analyze the data:
1) P-value analysis of clinical features: Python 3.6, scikit-learn 1.1;
2) Sequential forward feature selection: MLXTEND 0.21.0 (http://rasbt.github.io/mlxtend/);
3) Model development: PyTorch 1.10.1, PyTorch Image Models(timm)(https://github.com/rwightman/pytorch-image-models);
4) ROC curve comparison: MedCalc 20.
