# TrainingProject
Fruit360 Dataset – Classification with ResNet, Detection with YOLO, and Image Generation with GAN This project classifies fruits using a ResNet-based CNN, detects them with YOLOv8, and generates realistic fruit images using a GAN model.

## This project contains solutions for the following tasks:

1. **Image Classification (Transfer Learning)**  
   - Uses ResNet50 for fruit classification.
   - Fine-tunes the last layers.
   - Evaluates using accuracy and confusion matrix.

2. **Object Detection (YOLO)**  
   - Trains a YOLO model to detect fruits in images.
   - Uses 20–30 manually annotated images.
   - Displays detection results.

3. **Image Generation (GAN)** *(Bonus)*  
   - Implements a simple GAN to generate synthetic fruit images.

### Prerequisites

* **Python:** Ensure you have Python installed. The notebook uses Python 3.11.13.
* **Jupyter:** You will need Jupyter Notebook or JupyterLab to open and run the `.ipynb` file.
* **Dependencies:** The following libraries are imported and are required to run the code:
    * numpy
    * pandas
    * matplotlib
    * seaborn
    * tensorflow
    * keras



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
