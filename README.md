# Sugarcane Leaf Disease Detection

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)

Deep learning system that detects **six sugarcane leaf conditions** — Bacterial Blights, Healthy, Mosaic, Red Rot, Rust, Yellow — using **MobileNetV2** transfer learning, with **Grad-CAM & Grad-CAM++** explainable AI so every prediction comes with a visual explanation of *where* on the leaf the model looked.

## Results

- **95.13%** validation accuracy / **91.60%** training accuracy
- 26,000+ leaf images, 20 epochs of transfer learning
- Grad-CAM / Grad-CAM++ heatmaps make every prediction interpretable

## What's inside

| File | Description |
|---|---|
| `SugarCane_Disease_detection_Project.ipynb` | Full training notebook — data prep, MobileNetV2 transfer learning, evaluation, Grad-CAM visualizations (built for Kaggle) |
| `Sugarcane_Research_Report_Final.docx` | Complete research report — abstract, methodology, results |
| `Sugarcane_Proposal_Final__1.pptx` | Project proposal presentation |

## Tech stack

- **MobileNetV2** — transfer learning backbone
- **TensorFlow / Keras** — model training
- **Grad-CAM & Grad-CAM++** — explainable AI heatmaps
- **OpenCV, NumPy, Matplotlib** — image processing & visualization

## Run it

The notebook is built for [Kaggle](https://www.kaggle.com/): it reads the dataset from `/kaggle/input/` (`akilesh253/sugarcane-plant-diseases-dataset`). Open the `.ipynb` in a Kaggle notebook, attach that dataset, and run all cells.

## About

Research project — Department of Artificial Intelligence, Aror University. Supervised by Dr. Faheem Akhtar Rajput.
