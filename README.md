# A-cross-modal-edge-guided-salient-object-detection-for-RGB-D-image  

## Abstract  

Salient object detection simulates the attention mechanism of human behavior to grasp the most attractive objects in the images. Recently edge information has been introduced to enhance the sharp contour in RGB image saliency detection. Inspired by it, we probe into the edge-guided RGB-D image saliency detection. There are two key problems need to be solved. One is how to extract edge information from cross-modal color and depth information, the other is how to fuse the edge feature into double-stream saliency detection network. To solve these two issues, a cross-modal edge-guided salient object detection for RGB-D image is proposed. Based on double-stream U-Net framework, edge information is extracted from the deep and shallow block of both modalities. The feature in deep layer contains sematic information implying where are the object boundaries, so the features of both modalities are directly fused. The feature in shallow layer provides more detailed spatial information, so a gated fusion layer is utilized to fuse the feature of both modalities to filter out the depth image noise. Extracted edge feature is fed into decoder combining with color and depth feature to achieve edge-guided cross-modal decoding process. Experimental results show our model outperforms SOTA models based on the edge guidance and gated fusion strategies in cross-modal double-stream network.

## Architecture
VGG-SSM Architecture
![](./EdgeRGBD.eps)
