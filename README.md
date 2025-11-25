# YOLOv5-Object-Detection
Object Detection system for Self-Driving Cars using YOLOv5. Trained YOLOv5s, YOLOv5n, and YOLOv5m models on the Roboflow OpenImages dataset (627 images, 1194 annotations) to detect and classify vehicles such as ambulances, buses, cars, motorcycles, and trucks. Includes dataset visualization, ground truth bounding boxes, model training, inference on images/videos, and performance comparison.

## Tools & Technologies Used
- **Google Colab** (GPU runtime for faster training)
- **YOLOv5** (models: YOLOv5s, YOLOv5n, YOLOv5m)
- **Roboflow OpenImages Dataset**
- **Python Libraries**:
  - `torch`, `torchvision`
  - `opencv-python (cv2)`
  - `matplotlib`
  - `numpy`
  - `pandas`
- **Visualization Tools**:
  - Dataset visualization (first 10 images)
  - Ground truth bounding boxes
  - Prediction visualization on images and videos
Datasets used in the project - https://drive.google.com/drive/folders/1WijzvSrQ8mVU8Szar6LW8Ei1kA7tZr_5

## Project Workflow
1. **Dataset Preparation**
   - Downloaded dataset from Olympus platform
   - Organized into train, validation, and test sets
   - Configured dataset YAML file

2. **Data Visualization**
   - Visualized first 10 images
   - Visualized ground truth bounding boxes using `cv2`

3. **Model Training**
   - Trained three YOLOv5 models:
     - YOLOv5s (small)
     - YOLOv5n (nano)
     - YOLOv5m (medium)
   - Used GPU runtime for faster training

4. **Inference**
   - Performed inference on images
   - Performed inference on videos
   - Visualized predictions with bounding boxes and class labels

5. **Model Comparison**
   - Compared YOLOv5s, YOLOv5n, and YOLOv5m in terms of accuracy, speed, and performance

6. **Conclusion & Scope**
   - Demonstrated high accuracy in detecting vehicles
   - Potential applications in:
     - Autonomous driving systems
     - Traffic monitoring
     - Smart city solutions

## Results
- Successfully trained YOLOv5 models on the dataset
- Achieved accurate detection and classification of vehicles
- Clear comparison of YOLOv5s, YOLOv5n, and YOLOv5m
- Inference performed on both images and videos
