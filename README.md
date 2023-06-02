# CXR: End-to-End Deep Learning Solution

Our project aims to address two key challenges in chest X-ray (CXR) diagnostics through deep learning techniques. The first problem is the presence of foreign objects in CXR images, which can obscure important anatomical structures and lead to diagnostic errors. To tackle this, the project uses advanced object detection models, including Region-based Convolutional Neural Networks (R-CNN) and You Only Look Once (YOLO), to identify and alert about these objects. The second issue revolves around the difficulty of differentiating between viral and bacterial pneumonia through CXR images, given their subtle differences. This distinction is important for appropriate treatment. For this, the project uses Convolutional Neural Networks (CNN) and the Visual Geometry Group (VGG) model through transfer learning to classify between types of pneumonia and normal lungs. The project's deep learning solution aims to improve diagnostic accuracy, expedite processes, and conserve medical resources, particularly in resource-limited settings. This work showcases how deep learning could significantly transform healthcare, especially CXR diagnostics, and align with the goal of universal healthcare accessibility.


## Directory structure 

```
├── README.md                                 <- You are here
│
├── EDA/                                      <- Exploratory Data Analysis for classification and object detection
│   ├── Classification_EDA.ipynb              <- EDA for classification
│   ├── Object_Detection_EDA.ipynb            <- EDA for Object Detection
│
├── Classification/                           <- Source Code for pneumonia classification
│   ├── CNN.ipynb                             <- CNN model
│   ├── VGG16.ipynb                           <- VGG16 transfer learning model
│ 
├── Object_Detection/                         <- Source Code for object detection
│   ├── sampling.ipynb                        <- sampling datasets
│   ├── YOLO_v5.ipynb                         <- YOLO v5 transfer learning model
│   ├── BBR_in_house.ipynb                    <- in-house object detection
│ 
├── reports/                                  <- Result analysis
│   ├── Deep Learning Report.pdf              <- report for result analysis
│   ├── Deep Learning Presentation.pdf        <- PPT for result analysis
│ 
├── data/                                     <- Data summary
│   ├── data_source.txt                       <- Data source link
```
