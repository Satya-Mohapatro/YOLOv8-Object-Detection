#  YOLOv8 Object Detection – End-to-End Training Pipeline

This repository contains a complete, clean, and Google Colab–friendly **YOLOv8 Object Detection Project** using a **custom dataset (COCO128)**.  
It includes dataset preparation, training, evaluation, inference, visualization, and deployment-ready model export.

---

#  Features

###  End-to-end Object Detection workflow  
###  Dataset upload + extraction + preprocessing  
###  YOLOv8 training on custom dataset  
###  Evaluation (mAP, precision, recall)  
###  Inference on images and video  
###  Export to ONNX, TensorRT, CoreML, TFLite  
###  Clean, readable, production-oriented code  

---
#  data.yaml (Required)

```yaml
train: datasets/custom/coco128/images/train
val: datasets/custom/coco128/images/val

nc: 80
names: [
  "person", "bicycle", "car", "motorcycle", "airplane", "bus", "train",
  "truck", "boat", "traffic light", "fire hydrant", "stop sign",
  "parking meter", "bench", "bird", "cat", "dog", "horse", "sheep", "cow",
  "elephant", "bear", "zebra", "giraffe", "backpack", "umbrella",
  "handbag", "tie", "suitcase", "frisbee", "skis", "snowboard",
  "sports ball", "kite", "baseball bat", "baseball glove", "skateboard",
  "surfboard", "tennis racket", "bottle", "wine glass", "cup", "fork",
  "knife", "spoon", "bowl", "banana", "apple", "sandwich", "orange",
  "broccoli", "carrot", "hot dog", "pizza", "donut", "cake", "chair",
  "couch", "potted plant", "bed", "dining table", "toilet", "tv",
  "laptop", "mouse", "remote", "keyboard", "cell phone", "microwave",
  "oven", "toaster", "sink", "refrigerator", "book", "clock", "vase",
  "scissors", "teddy bear", "hair dryer", "toothbrush"
]
```
# Concepts Covered in the Project

### ✔ YOLO dataset structure
### ✔ YOLO annotation format
### ✔ Normalization of bounding boxes
### ✔ Data preprocessing & augmentation
### ✔ Backbone–Neck–Head architecture
### ✔ Loss functions (GIoU, classification, objectness)
### ✔ mAP metrics
### ✔ Non-Maximum Suppression (NMS)
### ✔ Transfer learning
### ✔ Model fine-tuning
### ✔ Model deployment
### Full explanations included in the Colab notebook and comments.
