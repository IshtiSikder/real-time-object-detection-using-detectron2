# real-time-object-detection-using-detectron2
A pretrained Detectron2 model for real time object detection using webcam on google colab

Steps:
1. Detectron2 is installed first, along with compatible version of Pytorch. 
2. Detectron2 runs on GPU so google colab's GPU is used.
3. A pre-trained Detectron2 model (mask_rcnn_R_50_FPN_3x.yaml) trained on COCO dataset is loaded for instance segmentation.
4. Functions are defined to conduct live webcam streaming on google colab, collecting frames from the video stream and processing them to feed into the pretrained model where segmentation overlays would be placed upon them.
5. Frames are shown in the order of the video stream with segmentation/detection overlays and probabilities of assurance 
6. Recording of a given demo is stored in the repository as 'obj det final demo'
