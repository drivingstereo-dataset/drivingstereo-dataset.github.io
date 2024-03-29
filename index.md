---
youtubeId: LzRSfs6oaCA
layout: default
---

## DrivingStereo

{% include youtubePlayer.html id=page.youtubeId %}

### News

2020-09-20: &nbsp; For the test dataset, the full-resolution data releases.

2020-01-23: &nbsp; Calibration files release.

2020-01-22: &nbsp; 2000 selected frames with different weathers release.

2019-11-12: &nbsp; Testing dataset releases.

2019-11-10: &nbsp; Training dataset releases.

2019-06-13: &nbsp; Demo images release. [Download link](https://drive.google.com/open?id=1T_qjjtX6UvQtLsr03EtFhBz8ZIPII7WO)

2019-06-08: &nbsp; Our paper makes public on open access. [Paper link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_DrivingStereo_A_Large-Scale_Dataset_for_Stereo_Matching_in_Autonomous_Driving_CVPR_2019_paper.pdf)

2019-05-04: &nbsp; Demo video is uploaded to youtube. [Video Link](https://www.youtube.com/watch?v=LzRSfs6oaCA)

### Download

**Google Drive** and **Baidu Cloud** links are available for the downloading of left images, right images, disparity maps, and depth maps. The total number of our dataset is 182188, where the training set has 174437 pairs and the testing set has 7751 pairs. For convenience, we compress the images by sequences. Different from the original resolution reported in the paper, all of the images and maps are downsampled to the half resolution. The average size of image is 881x400. In addition to the sequential training data, we also select 2000 frames with **4 different weathers (sunny, cloudy, foggy, rainy)** for specific requests.

As KITTI stereo dataset, both of the disparity maps and depth maps are saved as **uint16 PNG images**. The disparity value and depth value for each pixel can be computed by converting the uint16 value to float and dividing it by 256. The zero values indicate the invalid pixels.

#### Training data

|    Data Type   | Google Drive | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Baidu Cloud |
|  :----------:  | :----------: | :---------: |
|  Left images   | [*Download*](https://drive.google.com/drive/folders/1KN8BSF5KovPuNpKf0W2hScVpo70bRewI?usp=sharing) | [*Download (Extraction Code: ijyc)*](https://pan.baidu.com/s/1ZrOqBjLscc4U1Wy7eezZ7A)|
|  Right Images  | [*Download*](https://drive.google.com/drive/folders/1UG1U6iZVKsSk3Amn84bE1iFN53OKlsps?usp=sharing) | [*Download (Extraction Code: bc4k)*](https://pan.baidu.com/s/1I3ZxsKxZef2LZqDopWKf6Q) |
| Disparity Maps | [*Download*](https://drive.google.com/drive/folders/18obNjqFMzPuga6ZLN4UwCAqUjP7tQlKg?usp=sharing) | [*Download (Extraction Code: ma6a)*](https://pan.baidu.com/s/1lJpMk1nWdxKjJ7cK5dPTZA) |
|   Depth Maps   | [*Download*](https://drive.google.com/drive/folders/1kXOa9hgKfzyFeO7CxWiIia1OL7lqQEoI?usp=sharing)  | [*Download (Extraction Code: njpc)*](https://pan.baidu.com/s/1Zuzw3rhFEaP0pLE1Nb_K0w)  |

The training dataset contains 38 sequences and 174431 frames. Each sequence is compress into an individual zip file which can be downloaded from above links. The attributes of each sequence are given in [our supplementary materials](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Yang_DrivingStereo_A_Large-Scale_CVPR_2019_supplemental.pdf).

#### Different weathers

|    Weather     | Google Drive | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Baidu Cloud |
|  :----------:  | :----------: | :---------: |
|  Sunny   | [*Download*](https://drive.google.com/drive/folders/1Fugpyu29fZABySlnF9g9s9BjiQ2MXu0O?usp=sharing) | [*Download (Extraction Code: xh86)*](https://pan.baidu.com/s/1yaxKHwjKG-BrRUTSWi-jnw)|
|  Cloudy  | [*Download*](https://drive.google.com/drive/folders/10tvMmnQJ-8ESsG4FwxhgfUwke_s9CtTu?usp=sharing) | [*Download (Extraction Code: 7iqh )*](https://pan.baidu.com/s/1CAyDEzAgjl2OdtNjmKHxwg) |
|  Foggy   | [*Download*](https://drive.google.com/drive/folders/1Fh4m1DuWtca65_QkWrhvpNSZcZGt1EBX?usp=sharing) | [*Download (Extraction Code: 5k5b )*](https://pan.baidu.com/s/1skbi9AVckA_8KVZ9YuHqRg) |
|  Rainy   | [*Download*](https://drive.google.com/drive/folders/1Dmplo4Ct4XBT2zibKpJRXt6GPfWvUwmm?usp=sharing) | [*Download (Extraction Code: 1rrd )*](https://pan.baidu.com/s/1R_oqcd8P8OE7St4KTCBc_A)  |

For specific requirements (image dehaze, image derain, or image restoration), 2000 frames with different weathers (sunny, cloudy, foggy, and rainy) from sequences are selected, where each class of weather contains 500 frames. In addition to half-resolution data, we also release full-resolution data for these frames. Different from half-resulution disparity maps, the disparity value for each pixel in the full-resolution map is computed by converting the uint16 value to float and dividing it by 128.

#### Testing data

|    Data Type   | Google Drive | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Baidu Cloud |
|  :----------:  | :----------: | :---------: |
|  Left images   | [*Download*](https://drive.google.com/drive/folders/1VjxCnOeEIGKF6GqDqrpWvDTM4keTWAC_?usp=sharing) | [*Download (Extraction Code: kf56 )*](https://pan.baidu.com/s/1NgYeZazipNJFvUH_qoIVRw) |
|  Right Images  | [*Download*](https://drive.google.com/drive/folders/1Bjo__50Ugq-PgjZyumUKgxnRXB7RdqLu?usp=sharing) | [*Download (Extraction Code: b6r7 )*](https://pan.baidu.com/s/1Jgwjaqoj-faZfKsjbneSMQ) |
| Disparity Maps | [*Download*](https://drive.google.com/drive/folders/1m6gJawtGrmrpO6DhC6jrrrDd6WMWOJCS?usp=sharing) | [*Download (Extraction Code: qerd )*](https://pan.baidu.com/s/1QTw-UtJCDRrm_sCAPM36Qw) |
|   Depth Maps   | [*Download*](https://drive.google.com/drive/folders/1bKtlM-1JaG1YYR6yBDKFOH6r8yoUyDNm?usp=sharing)  | [*Download (Extraction Code: ax7f )*](https://pan.baidu.com/s/1bk9kEpS_NIIo2ic8X458Kg)  |

The testing dataset contains 4 sequences and 7751 frames. In addition to the half-resolution data, the full-resolution data is also provided for evaluation.

#### Calibration Parameters

|    Data Type   | Google Drive | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Baidu Cloud |
|  :----------:  | :----------: | :---------: |
|     Train      | [*Download*](https://drive.google.com/drive/folders/19e-qWaOXS5L2pLtYv7T_cJX2c6a4lOaf?usp=sharing) | [*Download (Extraction Code: vfcf )*](https://pan.baidu.com/s/1e82taDNYy3j_zjT6_WSQWw) |
|      Test      | [*Download*](https://drive.google.com/drive/folders/1cP6zOsHJUh7u3m4Sufq23ccoZmDIJrHp?usp=sharing) | [*Download (Extraction Code: 88fp )*](https://pan.baidu.com/s/1zzfW3ZE7eNsH6gaK0BA6Xw) |

The format of calibration files is similar to KITTI. We provide the calibration paramters for both half-resolution and full-resolution images.

### Overview

We construct a large-scale stereo dataset named DrivingStereo. It contains over 180k images covering a diverse set of driving scenarios, which is hundreds of times larger than the KITTI stereo dataset. High-quality labels of disparity are produced by a model-guided filtering strategy from multi-frame LiDAR points. Compared with other dataset, the deep-learning models trained on our DrivingStereo achieve higher generalization accuracy in real-world driving scenes. The details of our dataset are described in [our paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_DrivingStereo_A_Large-Scale_Dataset_for_Stereo_Matching_in_Autonomous_Driving_CVPR_2019_paper.pdf).

![Examples](images/drivingstereo_examples.jpg)

### Authors

Guorun Yang, Xiao Song, Chaoqing Huang, Zhidong Deng, Jianping Shi, Bolei Zhou

### Contact

yangguorun91@gmail.com, songxiao@sensetime.com

### License

This dataset is released under the [MIT license](https://github.com/drivingstereo-dataset/drivingstereo-dataset.github.io/blob/master/LICENSE).

### Citation

If you use our DrivingStereo dataset in your research, please cite this publication:
```
@inproceedings{yang2019drivingstereo,
    title={DrivingStereo: A Large-Scale Dataset for Stereo Matching in Autonomous Driving Scenarios},
    author={Yang, Guorun and Song, Xiao and Huang, Chaoqin and Deng, Zhidong and Shi, Jianping and Zhou, Bolei},
    booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2019}
}
```
