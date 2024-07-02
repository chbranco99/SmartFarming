# Dataset Repository

This repository contains a comprehensive dataset of 200 images featuring whiteflies in a tomato greenhouse. The images were captured under varying light exposures and lens focuses, offering variability in the scenarios. The dataset is divided into 160 images for **Training and Validation** and 40 images for **Testing**.

## Structure

The dataset is organized as follows:

### Annotations

The annotations are divided into two subfolders: **Test**, and **Train and Validation**.

#### Test
The **Test** set folder contains a folder named 'YOLO' with 40 .txt files, each corresponding to one of the 40 images in the test set. Each text file includes the bounding box annotations in YOLO format (`<object-class> <x_center> <y_center> <width> <height>`), with one object per line.

#### Train and Validation
For the **Train and Validation** set folder, there are two types of annotations: **Human** and **Machine Enhanced**.

- **Human Annotations**: These were manually created and are therefore prone to human error; whiteflies may be missed, others incorrectly annotated, and inaccuracies may exist in the bounding boxes.
- **Machine Enhanced Annotations**: These are predictions made by an ML model.

In each subfolder of **Train and Validation**, there is a folder named 'YOLO' containing the '.txt' files for the annotations of each image. There is one '.txt' file for each image; each text file includes the bounding box annotations in YOLO format (`<object-class> <x_center> <y_center> <width> <height>`), with one object per line.

![Sem título](https://github.com/chbranco99/SmartFarming/assets/45609008/930693c5-7f9e-4224-af0f-64ee2669f297)

### Images

The images are similarly divided into subfolders within **Test**, and **Train and Validation**, aligning with the structure of the annotations.
