# 🚘 3D Traffic Density Estimation using PointNet & nuScenes

Implemented and experimented with the **PointNet architecture** for 3D point cloud processing and object detection using the large-scale **nuScenes autonomous driving dataset**. This project processes multi-sensor data (LiDAR, cameras, radar) to detect and classify traffic density in 3D space, leveraging deep learning on raw, unstructured point clouds.

---
🧠 Tech Stack and Tools
Deep Learning Framework: PyTorch (main) / TensorFlow (alternative)

3D Processing Model: PointNet

Consumes unordered point clouds directly

Permutation invariant and robust to noise

Dataset: nuScenes

Data Handling:

nuScenes devkit for data loading, preprocessing, fusion

Coordinate normalization and spatial filtering

Visualization: Open3D, Matplotlib



## 🚀 Getting Started

To use or explore the project:

```bash
git clone https://github.com/Rajatha19/Traffic-density-estimation-using-PointNet.git
cd pointnet_nuscenes
jupyter notebook testmini.ipynb
pip install -r requirements.txt
