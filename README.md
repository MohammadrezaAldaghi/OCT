# Retinal OCT Image Analysis Using Deep Learning

## Project Overview

This project focuses on the **automatic analysis of retinal OCT (Optical Coherence Tomography) images** using **state-of-the-art machine learning and deep learning techniques**. The primary objective is to develop robust models capable of **detecting and classifying retinal diseases**, providing a **computer-aided diagnostic tool** for ophthalmologists.

---

## Datasets

The project utilizes high-quality, annotated OCT datasets:

1. **Retinal OCT C8**
   - Contains 24,000 retinal images distributed across 8 classes, including healthy and diseased cases.
   - Images are labeled by certified ophthalmology specialists.
   - Dataset link: [Kaggle - Retinal OCT C8](https://www.kaggle.com/datasets/obulisainaren/retinal-oct-c8)

2. **Kermany2018**
   - Contains over 84,000 B-scan OCT images of the retina.
   - Four classes: NORMAL, CNV (Choroidal Neovascularization), DME (Diabetic Macular Edema), DRUSEN.
   - Dataset link: [Kaggle - Kermany2018](https://www.kaggle.com/datasets/paultimothymooney/kermany2018)

---

## Methodology

### Model Architectures

Multiple deep learning architectures were explored to achieve high classification accuracy:

- **Convolutional Neural Networks (CNNs)**
  - VGG16, InceptionResNetV2
- **Transformer-Based Architectures**
  - Vision Transformer (ViT), Swin Transformer
- **Hybrid Models**
  - Combining CNN and Transformer layers for enhanced feature extraction

### Data Preprocessing

- Removal of noise and imaging artifacts
- Resizing images to standardized dimensions suitable for model input
- Normalization of pixel intensities
- Dataset splitting into:
  - Training set
  - Validation set
  - Test set

### Training and Evaluation

- Models were trained using **cross-entropy loss** for multi-class classification
- Performance metrics include:
  - Accuracy
  - Precision, Recall, and F1-score per class
  - Confusion Matrix
- Visualization techniques such as **Grad-CAM** were employed to highlight regions of interest influencing model predictions.

---

## Results and Insights

- Models achieved **high classification accuracy** on test sets, demonstrating strong capability in identifying both normal and pathological retinal conditions.
- Analysis of Grad-CAM visualizations provided insights into model decision-making, highlighting clinically relevant retinal structures.
- Performance is highly dependent on **dataset quality and diversity**, emphasizing the importance of comprehensive annotated data for generalization.

---

## Applications

- **Clinical Decision Support:** Assists ophthalmologists in early detection and diagnosis of retinal diseases.
- **Research:** Enables large-scale analysis of OCT data for academic and clinical studies.
- **Screening Tools:** Can be integrated into automated eye screening systems.

---

## Companies and Tools in the Field

Notable companies and platforms utilizing AI for OCT analysis include:

- **Altris AI** (Chicago, IL) – Deep learning-based OCT analysis platform.
- **RetInSight** (Vienna, Austria) – OCT diagnostic software for retinal disease monitoring.
- **RetinAI** (Zurich, Switzerland) – AI-driven OCT image analysis platform.
- **iCare RETCAD** (Finland) – AI for early detection of retinal disorders.
- **Eyenuk** (Los Angeles, CA) – EyeArt AI system for diabetic retinopathy screening.
- **Mediwhale** (Seoul, South Korea) – Multi-disease diagnosis via retinal scans.
- **DeepMind + Moorfields Eye Hospital** (London, UK) – AI for detecting multiple retinal conditions.
- **Clarifai** (Wilmington, DE) – AI-powered computer vision tools for medical images.

---

## Disclaimer

- This project is **intended for research and educational purposes only**.
- **Clinical deployment requires regulatory approval and validation by certified ophthalmologists**.

---

## References

- [Retinal OCT C8 - Kaggle](https://www.kaggle.com/datasets/obulisainaren/retinal-oct-c8)
- [Kermany2018 - Kaggle](https://www.kaggle.com/datasets/paultimothymooney/kermany2018)
- **Deep Learning for Retinal Disease Detection**, Nature Scientific Reports: [link](https://www.nature.com/articles/s41598-018-24029-8)

---

## License

All dataset usage must comply with the respective **licenses and privacy regulations**. Users are responsible for ethical use of medical images.

