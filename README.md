# 🚘 3D Traffic Density Estimation using PointNet & nuScenes

Implemented and experimented with the **PointNet architecture** for 3D point cloud processing and object detection using the large-scale **nuScenes autonomous driving dataset**. This project processes multi-sensor data (LiDAR, cameras, radar) to detect and classify traffic density in 3D space, leveraging deep learning on raw, unstructured point clouds.

---

## 🚀 Getting Started

To use or explore the project:

git clone https://github.com/Rajatha19/Traffic-density-estimation-using-PointNet.git

cd pointnet_nuscenes

jupyter notebook testmini.ipynb

Follow the notebook for a walkthrough of implementation and results.

🛠 Requirements
Python 3.7+

Jupyter Notebook

PyTorch / TensorFlow

Open3D

NumPy, Matplotlib, Seaborn

nuScenes Python SDK

Install dependencies:

pip install -r requirements.txt

🧠 Tech Stack and Tools
Deep Learning Framework: PyTorch (main) / TensorFlow (alternative)

3D Processing Model: PointNet

Consumes unordered point clouds directly

Permutation invariant and robust to noise

Dataset: nuScenes

6 cameras, 1 LiDAR, 5 RADARs, GPS/IMU

Data Handling:

nuScenes devkit for data loading, preprocessing, fusion

Coordinate normalization and spatial filtering

Visualization: Open3D, Matplotlib

