# TartesiaDS
Article repository: Automated damage assessment of automobiles using computer vision: Case of use in insurance companies.

To obtain the public dataset of vehicle damage, access the following link: https://docs.google.com/forms/d/e/1FAIpQLSdOm86Tn3hH2TQNlvQS6ghzFgEvSJoj9Tp_QpAlVXDrLhYFyQ/viewform?usp=sf_link


The article details the process of merging boxes to take advantage of the use of various models.

![plot](Fusion.png)

We start from the use of several versions of YOLOv5 testing with various image resolutions.

![plot](yolov5_all_models_test.png)

We compare the model ensemble against a version of yolov5 in different metrics.

<p align="center">
  <img src="ensemble_yolov5l_68_test_precision.png"  width="33%"/>
  <img src="ensemble_yolov5l_68_test_recall.png"  width="33%"/>
  <img src="ensemble_yolov5l_68_test_auc.png"  width="33%"/>
</p>

We share a small sample of the different types of damage that are part of the dataset that can be obtained through the form.

## Terms of use
This dataset can be used free of charge for academic research, citing the document as explained below. If you wish to use the data for commercial purposes, please contact us.

## Citation

To be published
