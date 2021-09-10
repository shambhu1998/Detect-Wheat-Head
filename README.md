# Detect-Wheat-Head

## Problem
The task is to detect wheat heads from outdoor images of wheat plants.
## Dataset
The data is images of wheat fields, with bounding boxes for each identified wheat head. Not all images include wheat heads / bounding boxes.<br>
**Data source:** https://www.kaggle.com/c/global-wheat-detection/data <br>
<p><img align="left" width="450" height="450" src="https://user-images.githubusercontent.com/20660098/132674224-b7382422-cfc3-43a5-aa8a-3770571e48a9.png"></p>
<br clear="left"/>

## Model Building and Training
Created object detection model using pretrained Faster R-CNN model with ResNet50 backbone trained on COCO dataset.<br>
<p><img align="left" width="450" height="450" src="https://user-images.githubusercontent.com/20660098/132678679-02c96a76-609f-4981-8105-a8c1feaed66e.png"></p>
<br clear="left"/>

## Evaluation
Finally, the model was evaluated on the mean average precision at different intersection over union (IoU) thresholds.IoU is a measure of the magnitude of overlap between two bounding boxes (or, in the more general case, two objects). It calculates the size of the overlap between two objects, divided by the total area of the two objects combined. The IoU of a set of predicted bounding boxes and ground truth bounding boxes is calculated as: 

<p><img align="left" width="450" height="300" src="https://user-images.githubusercontent.com/20660098/132680521-dd3da90a-e112-4904-9de3-1b2c82420088.png"></p>



