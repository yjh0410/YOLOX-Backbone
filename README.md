# YOLOX-Backbone
The backbone CSPDarkNet of YOLOX.

In this project, you can enjoy:

- CSPDarkNet-S
- CSPDarkNet-M
- CSPDarkNet-L
- CSPDarkNet-X
- CSPDarkNet-Tiny
- CSPDarkNet-Nano

# Requirements
- Torch >= 1.9.1

# Motivation
As far as I know, it is difficult for many researchers to train YOLOv5 or YOLOX from scratch because they, including me, do not have sufficient computing resources. Therefore, a pre-trained backbone is still important. 

In addition, since YOLOv5 and YOLOX are excellent object detectors, their backbones theoretically perform better than imagenet pretrained weights. 

Therefore, based on the above two reasons, I deliberately extracted this CSPDarkNet backbone code from the YOLOX project, including CSPDarkNet-S, CSPDarkNet-M, CSPDarkNet-L, CSPDarkNet-X, CSPDarkNet-Tiny and CSPDarkNet-Nano.

Since they are all COCO pretrained weights, they are more suitable for object detection tasks and other tasks related to detection.

# weight
## BaiduYun:
Link: https://pan.baidu.com/s/1o4X_VaTByRAFGZtGDqEAiQ 

Code：6uk8 

## Github release
- CSPDarkNet-S: https://github.com/yjh0410/YOLOX-Backbone/releases/download/YOLOX-Backbone/yolox_cspdarknet_s.pth
- CSPDarkNet-M: https://github.com/yjh0410/YOLOX-Backbone/releases/download/YOLOX-Backbone/yolox_cspdarknet_m.pth
- CSPDarkNet-L: https://github.com/yjh0410/YOLOX-Backbone/releases/download/YOLOX-Backbone/yolox_cspdarknet_l.pth
- CSPDarkNet-X: https://github.com/yjh0410/YOLOX-Backbone/releases/download/YOLOX-Backbone/yolox_cspdarknet_x.pth
- CSPDarkNet-Tiny: https://github.com/yjh0410/YOLOX-Backbone/releases/download/YOLOX-Backbone/yolox_cspdarknet_tiny.pth
- CSPDarkNet-Nano: https://github.com/yjh0410/YOLOX-Backbone/releases/download/YOLOX-Backbone/yolox_cspdarknet_nano.pth
