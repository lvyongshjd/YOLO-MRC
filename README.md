**An Optimised Lightweight YOLO-MRC Framework for Enhanced Obstacle Detection in Service Robots**

1. About YOLO-MRC

   Object detection, particularly for small and deformed targets in complex backgrounds,  remains a significant challenge for service robots. To address this,  we propose a novel lightweight YOLO-MRC 

   (You Only Look Once-MobileViT-RepPoints-CTAM) network. Our contributions include an improved C3-RepPoints module for finer localization and classification of objects of varying scales and deformation, a lightweight hybrid architecture combining convolutional neural networks (CNNs) and vision transformers (ViTs) for efficient small object detection,  and a convolutional triplet attention mechanism (CTAM) to aggregate crucial semantic information. An efficient decoupled head (EDH) further enhances detection performance by separating classification and regression tasks. Experimental results on the ODSR-HIS dataset show that YOLO-MRC reduces model parameters by 21.3% while improving mean average precision (mAP@0.5) by 1.3%, with notable gains for small-scale and deformed objects. YOLO-MRC also demonstrates excellent generalisation on PASCAL VOC and COCO datasets, improving mAP@0.5 by 4.4% and 10.7% respectively compared to YOLOv5n, all achieved with only 1.4M parameters and 5.5G FLOPs. This underscores YOLO-MRC's balance between model size, latency, and accuracy, making it well-suited for service robots.

2. Improvement methods

   Based on YOLOv5n,  we use MobileViT and C3-PR in the backbone and neck, introduce CTAM at the end of the backbone network and use EDH.

3. Robot Dataset 

   Due to the large size of the files, we have adopted the sharing method of Baidu Netdisk. The specific link is as follows：[https://pan.baidu.com/s/1y8tWlsduJO1yaWllyV-aYQ](https://pan.baidu.com/s/1mJRI5-n2SRSugyXcHvgT6A) and extraction code：sif7.

   

   

   

   


