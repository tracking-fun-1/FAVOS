# Fast and Accurate Online Video Object Segmentation via Tracking Parts

![Alt Text](https://github.com/JingchunCheng/FAVOS/blob/master/framework.png) 

Project webpage: <br />
Contact: Jingchun Cheng (chengjingchun14 at 163 dot com)

## Paper
[Fast and Accurate Online Video Object Segmentation via Tracking Parts]() <br />
Jingchun Cheng, Yi-Hsuan Tsai, Wei-Chih Hung, Shengjin Wang and Ming-Hsuan Yang <br />
IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018.

This is the authors' demo (single-GPU-version) code for the DAVIS 2016 dataset as described in the above paper. Please cite our paper if you find it useful for your research.

```
@inproceedings{
}
```

## FAVOS Results
[Segmentation Comparisons with Fast Online Methods]()

[Example of Part Tracking]()


## Requirements
* Install `caffe` and `pycaffe` (`opencv` is required). <br />
`cd caffe` <br />
`make all -j8` (paths are needed to change in the configuration file) <br />
`make pycaffe` <br />

* Download pre-computed results. <br />
Download [segmentation results](https://www.dropbox.com/s/9zwob31bz91u75h/favos.tar?dl=0) and put them in folder "results".
Download trained [ROISegNet model](https://www.dropbox.com/s/tkfa22j0ypq8ncq/ROISegNet_2016.caffemodel?dl=0) and put them in folder "models".
Download [tracker parts](https://www.dropbox.com/s/tkfa22j0ypq8ncq/ROISegNet_2016.caffemodel?dl=0) and put them in foler "siamese-fc-master/tracking/".

## Tracker
We use SiaFC tracker in "Fully-Convolutional Siamese Networks for Object Tracking" [here](https://github.com/bertinetto/siamese-fc)
Please download parts and tracking results from [here](https://www.dropbox.com/s/tkfa22j0ypq8ncq/ROISegNet_2016.caffemodel?dl=0).

## Download Our Segmentation Results on the DAVIS datasets
* FAVOS on DAVIS2016 [here](https://www.dropbox.com/s/9zwob31bz91u75h/favos.tar?dl=0)
* FAVOS on DAVIS2017 [here]()


## Note
The model and code are available for non-commercial research purposes only.

