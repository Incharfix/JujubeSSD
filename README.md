JujubeSSD

1. 1. Installation
Follow the mmdet installation process

2.Data Preparation
We provide the sample data set in./mydata

3.Train
Run the following commands for training.
python ./tools/train.py    /home/mmdetection/configs/ssd/JujubeSSD.py

4.Other functional paths
test:    ./tools/test.py
curve:  ./tools/analysis_tools/analyze_logs.py
confusion matrix:  ./tools/analysis_tools/confusion_matrix.py
