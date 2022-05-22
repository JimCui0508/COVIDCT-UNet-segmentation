# COVIDCT-UNet-segmentation

The data set is from http://medicalsegmentation.com/covid19/
COVID-19 CT segmentation dataset
This is a dataset of 100 axial CT images from >40 patients with COVID-19 that were converted from openly accessible JPG images found HERE. The conversion process is described in detail in the following blogpost: Covid-19 radiology — data collection and preparation for Artificial Intelligence

In short, the images were segmented by a radiologist using 3 labels: ground-glass (mask value =1), consolidation (=2) and pleural effusion (=3). We then trained a 2d multilabel U-Net model, which you can find and apply in MedSeg. NEW (from 2nd April 2020): Try the Beta fully automated report HERE (DICOM only).

I implemented a 2.5D U-Net architecture to predict the ground-glass, you may change the label in the code in order to your need.
