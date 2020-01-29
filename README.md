# crawler-crane-detector


images link: https://drive.google.com/open?id=13X6Yf3QasbNGJJzMO3RylvnMOdMTdxKb

>*Model description:*

In Speed/accuracy trade-offs for modern convolutional object detectors by Jonathan Huang et.al, accuracy(mAP) vs time was plotted for different obect detectors on COCO. Faster-RCNN with Resnet-101 is hitting the sweet spot between accuracy and time.

Recent improvements from on this model with Inception-V2 as feature extractor is reducing run time from around 150ms to 60ms with slight reduce in mAP from 30 to 28.

Where as the lightest model, ssd_mobilenet_v1_0.75_depth_quantized_coco is running at a speed of 29ms but with only 16mAP.

Hence, I choose the Faster-RCNN with Inception V2 as feature extractor
