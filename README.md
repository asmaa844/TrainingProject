# TrainingProject
Fruit360 Dataset – Classification with ResNet, Detection with YOLO, and Image Generation with GAN This project classifies fruits using a ResNet-based CNN, detects them with YOLOv8, and generates realistic fruit images using a GAN model.

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

### Data

* The code assumes the "fruits-360" dataset is located at `/kaggle/input/fruits/fruits-360_100x100/fruits-360/`. You will need to download this dataset and place it in the correct directory, or update the file paths (`train_dir` and `test_dir`) in the notebook to match your local file structure.

### How to Run the Code

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <your-project-directory>
    ```
3.  **Install dependencies:**
    * It is recommended to use a virtual environment.
    * You can install the required libraries using pip:
        ```bash
        pip install numpy pandas matplotlib seaborn tensorflow keras
        ```
4.  **Open the Jupyter notebook:**
    ```bash
    jupyter notebook maim-assignment-4.ipynb
    ```
5.  **Run the cells:** Once the notebook is open in your browser, you can run each cell sequentially by selecting the cell and pressing `Shift + Enter` or by clicking the "Run" button in the toolbar.
