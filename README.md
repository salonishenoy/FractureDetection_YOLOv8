# Fracture Detection using YOLOv8 

![val_batch2_labels](https://github.com/salonishenoy/FractureDetection_YOLOv8/blob/main/val_batch2_labels.jpg)

* This repository provides a complete solution for detecting 7 bone fractures in the human arm using YOLOv8. It includes model weights and the code for training the model.
* The annotated dataset was taken from object detection dataset from kaggle (here, https://www.kaggle.com/datasets/pkdarabi/bone-fracture-detection-computer-vision-project/data)
* This model is trained using YOLOv8n (nano) for 3 epochs (more epochs couldn't run due to hardware constraints)

The model detects the following types of bone fractures:
  1. Elbow Positive
  2. Fingers Positive
  3. Forearm Fracture
  4. Humerus Fracture
  5. Shoulder Fracture
  6. Wrist Positive
