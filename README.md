# UAVH

This repository will be updated after a competition organized in Turkey.

[A Hybrid Method for Tracking of Objects by UAVs](http://openaccess.thecvf.com/content_CVPRW_2019/html/UAVision/Saribas_A_Hybrid_Method_for_Tracking_of_Objects_by_UAVs_CVPRW_2019_paper.html)

Hasan Saribas, Bedirhan Uzun, Burak Benligiray, Onur Eker, Hakan Cevikalp

*{hasansaribas48, eee.bedirhan, bbenligiray, onureker34, hakan.cevikalp}@gmail.com*

**CVPR2019_UAVision**

## Introduction

UAVH proposes hybrid method to track UAVs in real-time. For this cause, the kernelized correlation filter (KCF), which is particularly fast at tracking, is used along with the accurate and relatively fast detection models YOLOv3. Specifically, the detector acts as a localization initializer and a self-correction mechanism whenever the tracker loses the target. The resulting method both delivers good tracking accuracy, and is also lightweight enough to run onboard within a UAV. 

Although there are many datasets to test methods for tracking objects in videos such as OTB (Object Tracking Benchmark) and VOT (Visual Object Tracking), these datasets are not solely composed of UAV videos. To this end, , we labeled 7500 frames to create a dataset for our specific application, which is tracking of UAVs by using a camera mounted on another flying UAV. Additionally, to compare our method with state of the art methods in the literature, we conducted extensive experiments on UAV123 dataset and its long-term subset UAV20L. 

## Results

![on UAV123](https://raw.githubusercontent.com/bdrhn9/hybrid-tracker/master/uav123.png)

![on UAV20L](https://raw.githubusercontent.com/bdrhn9/hybrid-tracker/master/uav20l.png)

All results can be downloaded from [Drive](https://drive.google.com/open?id=1dfnjJS-RfcgvYwrFRD-47HuZ8kZC5eB8)

## Citation

	@inproceedings{saribas2019hybrid,
	  title={A Hybrid Method for Tracking of Objects by UAVs},
	  author={Saribas, Hasan and Uzun, Bedirhan and Benligiray, Burak and Eker, Onur and Cevikalp, Hakan},
	  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops},
	  pages={0--0},
	  year={2019}
	}
