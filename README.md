# EGNet
EGNet:Edge Guidance Network for Salient Object Detection (ICCV 2019)

### For training:
1. Clone this code by `git clone https://github.com/JXingZhao/EGNet.git --recursive`, assume your source code directory is`$EGNet`;

2. Download [training data](https://pan.baidu.com/s/1LaQoNRS8-11V7grAfFiHCg) (fsex);

3. Download [initial model](https://pan.baidu.com/s/1dD2JOY_FBSLzjp5tUPBDBQ) (8ir7); 

4. Change the image path and intial model path in run.py and dataset.py;

5. Start to train with `python3 run.py --mode train`.

### For testing:
1. Download [pretrained model](https://pan.baidu.com/s/1s35ZyGDSNVzVIeVd7Aot0Q) (2cf5);

2. Change the test image path in dataset.py 

3. Generate saliency maps for SOD dataset by `python3 run.py --mode test --sal_mode s`, PASCALS by `python3 run.py --mode test --sal_mode p` and so on;



### Pretrained models, datasets and results:
| [Page](https://mmcheng.net/jxzhao/) |
| [Training Set](https://pan.baidu.com/s/1LaQoNRS8-11V7grAfFiHCg) (fsex) |
| [Pretrained models](https://pan.baidu.com/s/1s35ZyGDSNVzVIeVd7Aot0Q) (2cf5) |
| [Saliency maps](https://pan.baidu.com/s/1M_dqPJ08oaYWge_zZnHSTQ) (54gi)  |


### If you think this work is helpful, please cite
```latex
@inproceedings{zhao2019EGNet,
 title={EGNet:Edge Guidance Network for Salient Object Detection},
 author={Zhao, Jia-Xing and Liu, Jiang-Jiang and Fan, Deng-Ping and Cao, Yang and Yang, Jufeng and Cheng, Ming-Ming},
 booktitle={The IEEE International Conference on Computer Vision (ICCV)},
 month={Oct},
 year={2019},
}
```

### Other related work
Contrast Prior and Fluid Pyramid Integration for RGBD Salient Object Detection. (CVPR2019) [page](https://mmcheng.net/rgbdsalpyr/)



