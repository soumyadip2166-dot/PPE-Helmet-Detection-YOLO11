# PPE and Helmet Detection Using YOLO11

This repository contains a Personal Protective Equipment (PPE) and Helmet Detection project designed for construction sites, industrial environments, and other workplaces where worker safety is critical.

The project uses the YOLO11 architecture for computer vision-based detection of safety equipment and helmets worn by workers. A pretrained yolo11n-cls.pt model is used as the base model for the implementation.

**Project Overview:** Construction and industrial sites require workers to use appropriate Personal Protective Equipment (PPE), including safety helmets and other protective equipment. Manual monitoring of PPE compliance can be time-consuming and may not provide continuous coverage.

This project explores an automated computer vision approach for identifying workers and detecting PPE/helmet-related classes from images using a YOLO11-based deep learning model.

**Key Features:**
PPE and helmet detection using YOLO11
Utilization of the pretrained yolo11n-cls.pt model
Image-based computer vision analysis
Suitable for construction and industrial site safety applications
Deep-learning-based automated safety monitoring
Dataset organized for machine-learning experimentation
Can be extended for real-time video and CCTV-based monitoring

**Model:** The project is based on the YOLO11 family of models.

**Pretrained Model:** yolo11n-cls.pt

The n variant represents the lightweight/nano configuration, making it suitable for applications where computational efficiency and faster inference are important.

**Note:** yolo11n-cls.pt is a classification model. If the objective is to obtain bounding boxes around helmets or individual PPE items, a YOLO11 detection model such as yolo11n.pt should be used and trained with an appropriately annotated detection dataset.

**Application:** The proposed system can be used as a component of automated workplace safety monitoring systems, including:

Construction site monitoring
Industrial safety surveillance
Worker PPE compliance monitoring
Safety helmet detection
CCTV-based worker monitoring
Smart-site safety systems
Automated safety inspection systems

**Technologies Used:**
Python
YOLO11
Ultralytics
PyTorch
OpenCV
Deep Learning
Computer Vision
Dataset

The dataset consists of images related to construction/site workers and PPE/helmet usage. The dataset can be used for training, validation, and testing of the computer vision model.

**Dataset Source:** https://universe.roboflow.com/new-workspace-w7psa/construction-site

**Installation:** Install the required Python packages:  pip install ultralytics


**Future Improvements:** Possible extensions of this project include:

Training a dedicated YOLO11 object-detection model for bounding-box-based PPE detection
Detection of multiple PPE categories such as helmets, safety vests, gloves, and safety shoes
Real-time CCTV/video surveillance
Worker-level PPE compliance assessment
Integration with IoT-based safety monitoring systems
Automatic safety alerts for PPE violations
Deployment on edge devices
Development of a web-based safety monitoring dashboard


**Disclaimer:** This project is intended for research, educational, and experimental purposes. Model predictions should not be considered a replacement for established workplace safety procedures, trained safety personnel, or applicable occupational safety regulations.

**Acknowledgements:** This project uses the Ultralytics YOLO11 framework and pretrained model.

Ultralytics: https://github.com/ultralytics/ultralytics
YOLO11 Documentation: https://docs.ultralytics.com/
