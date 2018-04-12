# V4RL Urban Place Recognition Dataset
This dataset provides outdoors sequences especially recorded for place recognition applications using both flying and hand-held setups. This dataset was made publicly available with the paper "Viewpoint-tolerant Place Recognition combining 2D and 3D information for UAV navigation", by Fabiola Maffra, Zetao Chen and Margarita Chli, published in the Proceedings of the IEEE International Conference on Robotics and Automation (ICRA) 2018 [[paper](https://doi.org/10.3929/ethz-b-000249607)].

#### Video:
<a href="https://www.youtube.com/embed/8VkR_nSbR34" target="_blank"><img src="https://i.imgur.com/QZ6YTMr.png" 
alt="intro" width="240" height="180" border="10" /></a>


If you use this dataset, please cite the following publication:
 
```
@inproceedings{FMaffra:etal:ICRA2018,
    title     = {Viewpoint-tolerant Place Recognition combining 2D and 3D information for UAV navigation},
	author    = {Maffra, Fabiola and Chen, Zetao and Chli, Margarita},
	booktitle = {Proceedings of the {IEEE} International Conference on Robotics and Automation ({ICRA})},
	year      = {2018}
}
```

## Shopping Street 1 & 2 Dataset

The Shopping Street sequences 1 and 2 were recorded using a hand-held setup with the camera facing perpendicular to the direction of motion (i.e. sideways) when walking down a busy shopping street with many pedestrians. Shopping Street 1 was recorded with the sensor held at eye-level and exhibits loops with small viewpoints changes, perceptual aliasing and changes in the scene appearance. Shopping Street 2 was recorded along the same street a few months later with the sensor mounted at the top of a 4m-long rod held vertically in order to capture a part of the street that is visible in Shopping Street 1, but from different viewpoints. Combining these two sequences a very challenging place recognition dataset is created, where the scene is not only revisited from very different viewpoints, but due to the large time interval between recordings, major changes in the appearance of the scene can be observed with most of the restaurants and shop windows in different configurations; e.g. shutters closed, window displays and even store logos changed. Moreover, parts of Shopping Street 2 exhibit large variance in illumination conditions, making it hard even for humans to detect that it is the same place visited in the first sequence.

### Examples
<a href="https://youtu.be/e5OXCt2HBQQ" target="_blank"><img src="https://i.imgur.com/supAYBR.png" 
alt="shop1_seq1" width="200"  border="10" /></a>
<a href="https://youtu.be/RQjw9zUALSM" target="_blank"><img src="https://i.imgur.com/QKTyEWl.png" 
alt="shop1_seq2" width="200"  border="10" /></a>
<a href="https://youtu.be/u0VNov7QB4w" target="_blank"><img src="https://i.imgur.com/xir0Ryu.png" 
alt="shop2_seq1" width="200"  border="10" /></a>

### Data

**Shopping Street 1 Sequence 1** - [Bagfile](https://drive.google.com/open?id=1u1NSCzk-zxM2So9eYqxDMgv2bMnABGAL) - [Youtube](https://youtu.be/e5OXCt2HBQQ)

**Shopping Street 1 Sequence 2** - [Bagfile](https://drive.google.com/open?id=1ok9Sau2RRizAb_ug6P5H_CI91Hqsy7Xr) - [Youtube](https://youtu.be/RQjw9zUALSM)
 
**Shopping Street 2**            - [Bagfile](https://drive.google.com/open?id=1sBDoWiilaPmteUIDp6p54frIXypHfA_u) - [Youtube](https://youtu.be/u0VNov7QB4w)

### Ground truth

The ground truth for each dataset was manually annotated using 2 different sequences, a query sequence and a reference sequence. The sequences used as reference and query for the available ground truth are:

* Shopping Street 1:

  - Reference Dataset: Shopping Street 1 sequence 1
  - Query Dataset    : Shopping Street 1 sequence 2

* Shopping Street 1 & 2:

  - Reference Dataset: Shopping Street 1 sequence 1
  - Query Dataset    : Shopping Street 2

More details about the ground truth are available on the links below.

**Shopping Street 1** - [Ground truth](https://drive.google.com/open?id=1PzQtk39eUdf6QbGR7Vr0OdPbnPVdHB6F)

**Shopping Street 1 & 2** - [Ground truth](https://drive.google.com/open?id=1NxfrqvjiYxvMNLKdM9qkyXfiZakF4NqZ)
                                           
## UAV dataset

This sequence was recorded along a residential street using the Visual-Inertial sensor mounted on the bottom of an AscTec Neo UAV in a front-looking configuration, while performing lateral movements with the UAV in both directions. This sequence exhibits perceptual aliasing as well as large variance in viewpoints and difficult lighting conditions.

### Examples
<a href="https://youtu.be/xe8gySTZfsw" target="_blank"><img src="https://i.imgur.com/8qRsDFM.png" 
alt="uav_seq1" width="200"  border="10" /></a>
<a href="https://youtu.be/WkTvdD9xxTE" target="_blank"><img src="https://i.imgur.com/VEI7M14.png" 
alt="uav_seq2" width="200"  border="10" /></a>

### Data

**UAV dataset Sequence 1** - [Bagfile](https://drive.google.com/open?id=1E4rBqWzBeQ0c2ofsKib7lccI3sCDPkA8) - [Youtube](https://youtu.be/xe8gySTZfsw)

**UAV dataset Sequence 2** - [Bagfile](https://drive.google.com/open?id=1XIVGezQGWDNACcr_nwHy2rzotFY1xuLJ) - [Youtube](https://youtu.be/WkTvdD9xxTE)


### Contact

For any questions or bug reports, please create an issue or contact me at fmaffra@mavt.ethz.ch.