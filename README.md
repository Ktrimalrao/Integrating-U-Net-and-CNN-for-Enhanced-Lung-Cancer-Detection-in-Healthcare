# Integrating U-Net and CNN for Enhanced Lung Cancer Detection in Healthcare

## Project Overview
This project integrates U-Net for image segmentation and CNN for classification to enhance the detection of lung cancer using CT scan images. It aims to improve diagnostic accuracy in the healthcare domain by automating lung health assessment.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Objective](#project-objective)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [How to Run](#how-to-run)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)


---

## Project Overview
This project integrates two deep learning models for lung cancer detection:
- **U-Net**: For segmenting lung regions from CT scan images.
- **CNN**: For classifying segmented lung regions into various cancer types or healthy cells.

The goal is to provide a reliable deep learning-based diagnostic tool for early lung cancer detection.

---


## Dataset
- **Source:** Lung cancer CT scan dataset
- **Classes:** 
   - Cancerious
   - Normal
- **Data Split:** 
   - Training
   - Testing
   - Validation

---

## Project Objective
The objectives of this project are to:
- **Segment** lung regions using U-Net.
- **Classify** lung conditions using CNN models.
- **Enhance** lung cancer detection accuracy using deep learning techniques.

---

## Methodology
### 1. Data Preprocessing
- Image normalization and resizing.
- Data augmentation for improved model generalization.

### 2. Model Architecture
- **U-Net:** Applied for segmenting lung regions.
- **CNN:** Applied for classifying segmented regions into cancerous and non-cancerous categories.

### 3. Training and Evaluation
- Models trained on labeled CT scan datasets.
- Evaluated using performance metrics: 
   - Accuracy
   - Precision
   - Recall
   - F1-Score

---

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- Matplotlib / Seaborn

## Results
- Achieved **97% accuracy** in lung cancer detection.
- U-Net successfully segmented lung regions, enhancing classification performance.
- Authored a research paper based on this project, highlighting the advancements in lung cancer detection using deep learning techniques.

## How to Run
1. Clone the repository: [link](https://github.com/Ktrimalrao/Integrating-U-Net-and-CNN-for-Enhanced-Lung-Cancer-Detection-in-Healthcare)
2. Install dependencies: pip install -r requirements.txt
3. Run Each Cell in Notebook


## Future Improvements
- Web Application Integration: Implement a Flask web app for real-time predictions.
- Attention Mechanisms: Explore advanced models with attention layers for better feature extraction.
- Dataset Expansion: Apply the model to larger and more diverse medical imaging datasets.


## Contact
- **Author:** K. Trimal Rao
- **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/k-trimal-rao-397924253)
- **GitHub:** [My GitHub Profile](https://github.com/Ktrimalrao)

