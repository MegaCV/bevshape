# bevshape
This method perfroms 3D object detection in bev view, it adopts shape-aware sample points in 3D space for aggregation of pillar based bev feature. Moreover, it uses 8 aligned historical frames features for prediction. We use ConvNeXt-Base as the image backbone and train the model for 24 epochs with CBGS. We also use TTA for testing.

## Results
|   Model   | mAP  | NDS  | SET |
| :-------: | :--: | :--: | :--: |
| BEVShape(res50) | 41.98 | 53.81 | val |
| BEVShape(convnext-base)| 53.08 | 63.16 | test |
