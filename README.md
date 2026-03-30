Note on YOLO26 Naming:

The term "YOLO26" used in this project refers to a YOLO-format annotated dataset exported from Roboflow. 
It is not an official YOLO version. The dataset follows standard YOLO annotation format and is compatible 
with models like YOLOv8.

This naming is used internally to distinguish between different dataset versions in our experiments.

Datasets Used:

Dataset 1 (YOLO26 Format):
- 2468 images
- Grayscale with histogram equalization
- Used as baseline dataset

Dataset 2 (YOLOv8 Format):
- 6794 images
- RGB images
- Used as improved dataset

Dataset 3 (COCO Format):
- Same images as Dataset 2
- Used for Faster R-CNN

Note:
Dataset 2 and Dataset 3 contain identical images but different annotation formats.
