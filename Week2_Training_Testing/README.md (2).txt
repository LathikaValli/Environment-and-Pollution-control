# Week 2 - Model Training and Testing

This folder contains the Jupyter notebook and files related to training and testing the YOLOv8 object detection model on the underwater plastics dataset.

- `Week2_Training_Testing.ipynb`:  
  The main notebook where the YOLOv8 model is trained, validated, and tested. It includes:
  - Installation of required libraries.
  - Loading the YOLOv8 pre-trained model.
  - Training on the dataset specified by `data.yaml`.
  - Validation and inference steps.

- Dataset location: The dataset is organized under the `archive/underwater_plastics` folder as images and labels with a `data.yaml` file.

- Training results and model weights are saved automatically in the `runs/detect/yolov8n_custom_training/` folder.

To rerun the training or testing, simply open the notebook and execute the cells in order.
