# EGNet
EGNet:Edge Guidance Network for Salient Object Detection (ICCV 2019)

### For training:
1. Clone this code by `git clone https://github.com/JXingZhao/EGNet.git --recursive`, assume your source code directory is`$EGNet`;

2. Download [training data](https://pan.baidu.com/s/1LaQoNRS8-11V7grAfFiHCg) (fsex)

3. Download [initial model](https://pan.baidu.com/s/1dD2JOY_FBSLzjp5tUPBDBQ) (8ir7) 

4. Change the image path and intial model path in run.py and dataset.py

5. Start to train with `python3 run.py --mode train`.

### For testing:
1. Download [pretrained model](https://drive.google.com/open?id=1rM2g5j3PNr3GAUe_8ii5uY5N5s47Zpp0) `$ContrastPrior/Model/`;

2. Generate saliency maps by `python test.py`; 

3. Run `$ContrastPrior/evaluation/main.m` to evaluate the saliency maps.


### Pretrained models, datasets and results:
| [Page](https://mmcheng.net/jxzhao/) |
| [Training Set](https://pan.baidu.com/s/1vbKLwNA4dZYKMT8WV2ylrQ) (rmhn) |
| [All RGBD Datasets](http://mc.nankai.edu.cn/datasets/rgbd_saliency_datasets.zip)  |
| [Evaluation results](https://drive.google.com/open?id=17Fmngs0nxF0pEYFGTHAOA2C1akVegwg6)  |


### If you think this work is helpful, please cite
```latex
@inproceedings{zhao2019Contrast,

title={Contrast Prior and Fluid Pyramid Integration for RGBD Salient Object Detection},

author={Zhao, Jia-Xing and Cao, Yang and Fan, Deng-Ping and Cheng, Ming-Ming and Li, Xuan-Yi and Zhang, Le},

booktitle=CVPR,

year={2019}

}

@inproceedings{fan2017structure,

title={{Structure-measure: A New Way to Evaluate Foreground Maps}},

author={Fan, Deng-Ping and Cheng, Ming-Ming and Liu, Yun and Li, Tao and Borji, Ali},

booktitle={IEEE International Conference on Computer Vision (ICCV)},

pages = {4548-4557},

year={2017},

note={\url{http://dpfan.net/smeasure/}},

organization={IEEE}

}
```



