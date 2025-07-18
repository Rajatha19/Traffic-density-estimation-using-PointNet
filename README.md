# 🚘 3D Traffic Density Estimation using PointNet & nuScenes

Implemented and experimented with the **PointNet architecture** for 3D point cloud processing and object detection using the large-scale **nuScenes autonomous driving dataset**. This project processes multi-sensor data (LiDAR, cameras, radar) to detect and classify traffic density in 3D space, leveraging deep learning on raw, unstructured point clouds.

---

## 🚀 Getting Started

To use or explore the project:

```bash
git clone https://github.com/Rajatha19/Traffic-density-estimation-using-PointNet.git
cd pointnet_nuscenes
jupyter notebook testmini.ipynb

Requirements
Python 3.7+
Jupyter Notebook
PyTorch / TensorFlow
Open3D
NumPy, Matplotlib, Seaborn
nuScenes Python SDK

Install dependencies:
pip install -r requirements.txt

Tech Stack and Tools
Deep Learning Framework: PyTorch (main) / TensorFlow (alternative)
3D Processing Model: PointNet
Consumes unordered point clouds directly
Permutation invariant and robust to noise
Dataset: nuScenes
Data Handling:
nuScenes devkit for data loading, preprocessing, fusion
Coordinate normalization and spatial filtering
Visualization: Open3D, Matplotlib

Conclusion
This project showcases how PointNet can effectively estimate traffic congestion from 3D point clouds. It demonstrates the feasibility of deep learning for LIDAR-based traffic analytics and serves as a step toward robust autonomous perception systems in smart cities.
