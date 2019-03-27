
## MegaFace Evaluation Tool for MXNet Models

MegaFace is a set of public face datasets published and maintained by the University of Washington's Computer Science and Engineering Laboratory. It is a benchmark of 1 million-scale facial recognition algorithm. The dataset contains 690,572 images with 1,027,060 images. This repository contains a simple tool to evaluate your models on Megaface Challenge 1 benchmark. All the codes are implemented in Python and Mxnet in this repo.


## Environment

This repository has been tested under the following environment:

-   Python 2.7 
-   Ubuntu 18.04
-   Mxnet-cu90 (==1.3.0)
-   OpenCV 2.4.9

## Usage

1.  Prepare the environment. OpenCV 2.4 is required by the official devkit, for convenience, you can download it from [BaiduCloud](https://pan.baidu.com/s/1By4yIds0hEnw6_Ihh75R5w) or [GoogleDrive](https://drive.google.com/open?id=1Ifjj6zJQaXzuggr0tVcaMe21F7hd1PZk) and unzip to ``/usr/local/lib/opencv2.4``.

2.  Clone the repository and put your models to be evaluated in ``models/``.

3.  Download megaface testpack data from [BaiduCloud](https://pan.baidu.com/s/1kUXItYfHowpczk-80FLoGg) and unzip it to ``data/``.

4.  Download megaface official devkit from [BaiduCloud](https://pan.baidu.com/s/1M7KF8IrcWCmzRprtahszcA) or [GoogleDrive](https://drive.google.com/open?id=1ESr2PzPg5c2trzlkr_ZqtKeaRkmvjeNi) and unzip to ``devkit/``.
    
5.  Edit and call ``run.sh`` to evaluate your face recognition model performance.

6.  Edit and run ``plot_result.py`` if you want to visualize the final results.
    


## License

MIT LICENSE


## Reference

```
@inproceedings{kemelmacher2016megaface,
title={The megaface benchmark: 1 million faces for recognition at scale},
author={Kemelmacher-Shlizerman, Ira and Seitz, Steven M and Miller, Daniel and Brossard, Evan},
booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
pages={4873--4882},
year={2016}
}
```


## Acknowledgment

The code is adapted based on an intial fork from the [insightface](https://github.com/deepinsight/insightface) repository.
