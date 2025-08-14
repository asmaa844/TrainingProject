### TrainingProject – Main Assignment 4

This project implements **fruit image classification**, **object detection**, and **image generation** as part of Main Assignment 4.

It uses **ResNet50** for classification, **YOLOv8** for object detection, and a **GAN** to generate synthetic fruit images.

***

### Tasks Overview

* **Image Classification (Transfer Learning)**
    * Uses ResNet50 pre-trained on ImageNet.
    * Fine-tunes the last layers for fruit classification.
    * Evaluates performance with accuracy scores and confusion matrix plots.

* **Object Detection (YOLOv8)**
    * Trains a YOLO model to detect fruits in images.
    * Dataset: ~60–85 manually annotated fruit images.
    * Visualizes bounding boxes and detection results.

* **Image Generation (GAN) **
    * Implements a simple GAN architecture.
    * Generates synthetic fruit images for augmentation or visualization.

***

### Project Structure


- **GANModel/**: Generates fruit images using a GAN.  
- **YOLOModel/**: Performs object detection using YOLO. Includes model files, weights, and dataset config.  
- **ResnetModel/**: Performs fruit classification using ResNet, with the model and its pretrained weights.  
- **main_assignment_4.ipynb**: Notebook that combines the code for all three models.  


***

### Requirements

* **Python:** 3.11.13
* **Jupyter Notebook or JupyterLab**
* **Dependencies:**
    * numpy
    * pandas
    * matplotlib
    * seaborn
    * tensorflow
    * keras
    * torch
    * torchvision
    * opencv-python
    * pillow
    * scikit-learn
      
Install with:
```bash
pip install tensorflow keras opencv-python pillow matplotlib seaborn numpy pandas scikit-learn torch torchvision
```

### Dataset 
   - Download Fruits360 Dataset from Kaggle:  
     https://www.kaggle.com/datasets/moltean/fruits  
   - Place it in a `data/` folder.

### How to Run the Code

1.  **Clone the repository:**
    ```bash
    git clone <https://github.com/asmaa844/TrainingProject.git>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <TrainingProject>
    ```
3.  **Install dependencies:**
    * It is recommended to use a virtual environment.
    * You can install the required libraries using pip:
        ```bash
        pip install tensorflow keras opencv-python pillow matplotlib seaborn numpy pandas scikit-learn torch torchvision
        ```
4.  **Open the Jupyter notebook:**
    ```bash
    jupyter notebook maim-assignment-4.ipynb
    ```
5.  **Run the cells:** Once the notebook is open in your browser, you can run each cell sequentially by selecting the cell and pressing `Shift + Enter` or by clicking the "Run" button in the toolbar.
