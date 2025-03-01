# Brain Tumor Detection using Unsupervised Learning

## Overview
This project focuses on detecting brain tumors using unsupervised learning techniques. The goal is to analyze MRI images and segment potential tumor regions without labeled data, leveraging clustering algorithms for anomaly detection.

## Features
- Unsupervised learning approach for brain tumor detection
- Image preprocessing using OpenCV and NumPy
- Feature extraction for clustering
- Implementation of clustering algorithms (e.g., K-Means, DBSCAN)
- Visualization of segmentation results using Matplotlib

## Technologies Used
- Python
- NumPy
- OpenCV (for image processing)
- Scikit-Learn (for clustering algorithms)
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook (for experimentation and analysis)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/arush18/Brain-Tumor-Detection.git
   cd Brain Tumor Detection
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Dataset
The dataset is not included in this repository. You can use publicly available MRI datasets from Kaggle or your own data. Ensure the dataset is structured as follows:
```
/dataset
    ├── Image1.jpg
    ├── Image2.jpg
    ├── ...
```
Modify the script to specify the correct dataset path.

## Usage
Run the Jupyter Notebook to execute the detection pipeline:
```sh
jupyter notebook main.ipynb
```

## Results
- The project outputs segmented tumor regions from MRI scans.
- Visualizations of clustered tumor regions are generated.
- Evaluation metrics include cluster separability and silhouette scores.

## License
This project is licensed under the MIT License.

## Author
Arush