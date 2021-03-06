# Object-Detection-Knowledge

## Object Detection
- [reference 1](https://handong1587.github.io/deep_learning/2015/10/09/object-detection.html#retinanet)
- [one stage & two stage](https://www.zhihu.com/question/266143762)


## Faster RCNN (Facebook AI Research)
- [reference 1](https://blog.csdn.net/u013010889/article/details/78574879)
- [python detail training](https://blog.csdn.net/u011956147/article/details/53053381)
- [HermannHesse/faster_rcnn_cplusplus](https://github.com/HermannHesse/faster_rcnn_cplusplus)
- [reference 2 important](http://www.360doc.com/content/17/0303/14/10408243_633634497.shtml)
- [paper transfer](https://blog.csdn.net/ture_dream/article/details/52896452)
- [SmoothL1Loss](https://blog.csdn.net/wfei101/article/details/79809332)
- [SmoothL1Loss](https://blog.csdn.net/wfei101/article/details/79252021)

## NMS - Non-Maximum Suppression 
- [reference 1](https://www.cnblogs.com/makefile/p/nms.html)
- 目標檢測中提取分數最高的窗口的。
- 例如在行人檢測中，滑動窗口經提取特徵，經分類器分類識別後，每個窗口都會得到一個分數。
- 但是滑動窗口會導致很多窗口與其他窗口存在包含或者大部分交叉的情況。
- 這時就需要用到NMS來選取那些鄰域里分數最高（是行人的概率最大），並且抑制那些分數低的窗口。

## R-FCN
- [reference 1](https://zhuanlan.zhihu.com/p/30867916)
- R-CNN、SPP、Fast R-CNN、Faster R-CNN、YOLO、SSD、R-FCN、YOLO9000、DSSD、Mask R-CNN、FPN、RetinaNet、MegDet、Light-Head R-CNN。
- 按這個順序看論文就行。知乎上都有講解。
- [two-stage Faster R-CNN](https://zhuanlan.zhihu.com/p/24916624?refer=xiaoleimlnote)
- [one-stage YOLO](https://zhuanlan.zhihu.com/p/24916786)

## Mask RCNN (Facebook AI Research)
- [reference 1](https://blog.csdn.net/xiamentingtao/article/details/78598511)
- [reference 2](https://blog.csdn.net/u013010889/article/details/78588227)

## YOLO v3
- [reference 1](https://read01.com/zh-tw/O3xaRJ0.html#.WzLnNaczaUm)

## SSD
- [reference 1](https://www.cnblogs.com/xuanyuyt/p/7447111.html)

## Light-Head R-CNN (Face++)
- [reference 1](http://www.sohu.com/a/212814713_610300)
- [reference 2](https://blog.csdn.net/zealoe/article/details/78606116)
- [paper](https://arxiv.org/abs/1711.07264)

## RPN - Regional Proposal Networks
- [reference 1](https://blog.csdn.net/happyflyy/article/details/54917514)
- [reference 2](https://www.zhihu.com/question/265345106)
- [reference 3](https://blog.csdn.net/YZXnuaa/article/details/79221189)

## FPN - Feature Pyramid Networks (Facebook AI Research)
- [reference 1](https://blog.csdn.net/u014380165/article/details/72890275)
- [reference 2](https://blog.csdn.net/BEHIND_YOU/article/details/79714164)
- [reference 3](https://blog.csdn.net/sloanqin/article/details/51545125)
- [paper](https://arxiv.org/abs/1612.03144)
- [implement 參數共享](https://github.com/unsky/FPN/blob/master/models/pascal_voc/FPN/FP_Net_end2end/train.prototxt)
- [implement fpn](https://github.com/makefile/frcnn/blob/master/examples/FRCNN/fpn/fpn-vgg16-train.proto)

## Focal Loss for Dense Object Detection (Facebook AI Research)
- [reference 1](https://blog.csdn.net/u014380165/article/details/77019084)
- [reference 2](https://data-sci.info/2017/08/10/%E4%BE%86%E8%87%AAfacebook-research%E7%89%A9%E9%AB%94%E5%81%B5%E6%B8%AC%E7%9A%84%E6%9C%80%E6%96%B0%E9%80%B2%E5%B1%95%EF%BC%9Afocal-loss-dense-object-detection-2/)
- [reference 3](https://www.zhihu.com/question/63581984)
- [paper](https://arxiv.org/abs/1708.02002)

## DenseNet (Facebook AI Research)
- [reference 1](https://www.zhihu.com/question/60109389/answer/173011950)

## DetNet: A Backbone network for Object Detection (Face++)
- [reference 1](https://blog.csdn.net/JNingWei/article/details/80004070)
- [reference 2](https://www.zhihu.com/question/273770471)
- [paper](https://arxiv.org/abs/1804.06215)
- [zengarden/light_head_rcnn(extand from 2)](https://github.com/zengarden/light_head_rcnn)
- [chenyilun95/tf-cpn(COCO skeleton 1st)(extand from 2)](https://github.com/chenyilun95/tf-cpn)

## ROI Align
- [reference 1](http://blog.leanote.com/post/afanti.deng@gmail.com/b5f4f526490b)
- [reference 2](http://www.cnblogs.com/wangyong/p/8523814.html)


## Implement
- [D-X-Y/caffe-faster-rcnn](https://github.com/D-X-Y/caffe-faster-rcnn/tree/dev)
- [huaze555/windows-caffe-faster-rcnn](https://github.com/huaze555/windows-caffe-faster-rcnn)
- [makefile/frcnn](https://github.com/makefile/frcnn/tree/fpn)
- [mmclkv/caffe-mask-rcnn](https://github.com/mmclkv/caffe-mask-rcnn)
- [jasjeetIM/Mask-RCNN](https://github.com/jasjeetIM/Mask-RCNN)
- [nqanh/affordance-net](https://github.com/nqanh/affordance-net)
- [unsky/FPN](https://github.com/unsky/FPN)
- [chuanqi305/FocalLoss](https://github.com/chuanqi305/FocalLoss)
- [zuokai/roialign](https://github.com/zuokai/roialign)
- [happynear/caffe-windows](https://github.com/happynear/caffe-windows)

## Caffemodel
- [Caffemodel&Protocol Buffer](https://blog.csdn.net/zyazky/article/details/52229539)
- [Tensorflow2Caffe](https://blog.csdn.net/jiongnima/article/details/72904526)
- [Caffemodel Read](https://blog.csdn.net/foolsnowman/article/details/50846754)

## CaffeLayer
- [Solver Parameter](https://blog.csdn.net/JNingWei/article/details/78863446)
- [Fully Connection](http://www.cnblogs.com/JZ-Ser/p/7150950.html)
- [Fully Connection](https://www.zhihu.com/question/41037974)
- [SigmodCrosEntropyLoss](http://www.caffecn.cn/?/question/25)
- [Slice 1](https://zhuanlan.zhihu.com/p/22492036)
- [Slice 2](https://blog.csdn.net/u012235274/article/details/52438479)
- [Slice 3](https://blog.csdn.net/wfei101/article/details/78449265)
- [Slice 4](http://vra.github.io/2016/12/13/siamese-caffe/)
- [MTCNN concat & slice](http://www.nanjixiong.com/thread-122530-1-1.html)

## Network Slimming (BatchNorm)
- [reference 1](https://blog.csdn.net/u014380165/article/details/79969132)
- [reference 2](https://blog.csdn.net/cookie_234/article/details/71093903)
- [reference 3](https://blog.csdn.net/qq_25737169/article/details/79048516)
- [reference 4](https://blog.csdn.net/mao_xiao_feng/article/details/54317852)
- [reference 5](https://www.zhihu.com/question/45270958)
- [paper](https://arxiv.org/abs/1708.06519)

## DeepLearning Knowledge
- [experience 1](https://blog.csdn.net/dongapple/article/details/75499390)
- [experience 2](https://www.zhihu.com/question/41631631)
- [finetuning](https://www.zhihu.com/question/35754716)
- [caffe kernal](http://caffecn.cn/?/question/158)
- [caffe num_output](http://www.caffecn.cn/?/question/534)
- [interview](https://github.com/elviswf/DeepLearningBookQA_cn)
- [basic concept](https://www.imooc.com/article/23802)

## FCN - Fully Convolutional Networks 
- [reference 1](http://simtalk.cn/2016/11/01/Fully-Convolutional-Networks)
- [reference 2](https://zhuanlan.zhihu.com/p/22976342)
- [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf)

## Tool
- [labelme](https://github.com/wkentaro/labelme)

## VAE-GAN
- [reference 1](https://github.com/JeremyCCHsu/tf-vaegan)
- [paper](http://www.iwait2018.org/Paper%20IWAIT2018/IWAIT2018_paper_164.pdf)

## TX2
- [reference 1](https://mp.weixin.qq.com/s?__biz=MjM5NTE3Nzk4MQ==&mid=2651233122&idx=2&sn=1432ec9259b21f15e4ed2a605663e336&chksm=bd0e4ff08a79c6e6de57fccbb2252b5153616d923ced475601b914499df0ffdfbf32bedef610#rd)

## MobileFaceNet
- [reference 1](https://github.com/imistyrain/MobileFaceNet)

## Face Recognition Series
- [blogs](https://blog.csdn.net/fire_light_/article/list/1)


## Caffe 2
- [Caffe2 with C++](https://caffe2.ai/docs/cplusplus_tutorial.html)
- [Caffe2 C++](http://caffecn.cn/?/article/47)
- [Caffe2](https://www.zhihu.com/question/58698158)
- [Detectron](https://www.zhihu.com/question/266026480)
- [Caffe2 into PyTorch](https://www.zhihu.com/question/270578639)
- [Caffe&Caffe2](https://juejin.im/entry/58fd79b9da2f60005dc93411)
- [Build Caffe2 win10 GPU](https://research.wmz.ninja/articles/2017/05/build-caffe2-on-windows-10-gpu.html)
- [Build PyTorch win10 GPU](https://caffe2.ai/docs/getting-started.html?platform=windows&configuration=compile)
- [Detectron in C++](https://github.com/facebookresearch/Detectron/issues/199)
- [Detectron in win10](https://github.com/facebookresearch/Detectron/issues/276)
- [Detectron in win10](https://github.com/facebookresearch/Detectron/issues/25)
- [jhjin/caffe2-cpp](https://github.com/jhjin/caffe2-cpp)
- [Caffe2 C++ predict](https://www.cnblogs.com/zhonghuasong/p/7297696.html)
- [Caffe2 C++ predict](https://blog.csdn.net/Joson_yuan/article/details/79380130)
- [Caffe2 C++ method](http://caffecn.cn/?/article/47)

