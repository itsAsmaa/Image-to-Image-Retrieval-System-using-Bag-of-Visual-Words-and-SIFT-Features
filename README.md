# Image-to-Image-Retrieval-System-using-Bag-of-Visual-Words-and-SIFT-Features


##  Overview

This project explores **classical computer vision techniques** applied to the **Caltech-101 dataset**, a well-known benchmark containing images from 101 object categories.
The notebook demonstrates a **complete vision pipeline**, starting from dataset acquisition to feature extraction, representation, and evaluation.

The work emphasizes **understanding visual features and representations**, rather than end-to-end deep learning, making it ideal for academic computer-vision coursework.

---

##  Dataset

* **Dataset:** Caltech-101
* **Source:** Kaggle
* **Categories:** 101 object classes
* **Image Type:** RGB natural images with varying resolutions

The dataset is downloaded automatically using `kagglehub`, so **no manual download is required**.

---

##  Project Pipeline

The notebook is organized into clear stages:

### 1️⃣ Dataset Download

* Uses `kagglehub` to fetch the latest version of Caltech-101
* Ensures reproducibility and portability

### 2️⃣ Data Loading & Exploration

* Loads images from class-specific directories
* Displays sample images
* Verifies class distribution

### 3️⃣ Image Preprocessing

* Image resizing and normalization
* Conversion to suitable formats for feature extraction
* Noise and dimension handling

### 4️⃣ Feature Extraction

* Classical computer-vision feature descriptors (e.g. SIFT-style or handcrafted features)
* Converts images into numerical representations
* Enables similarity comparison and classification

### 5️⃣ Representation & Analysis

* Feature vectors organized per image
* Distance-based or statistical analysis
* Ready for retrieval or classification tasks

### 6️⃣ Evaluation

* Qualitative visualization of results
* Quantitative performance metrics (where applicable)
* Discussion of strengths and limitations

---

##  Technologies Used

* **Python 3**
* **NumPy**
* **OpenCV**
* **Matplotlib**
* **scikit-learn**
* **kagglehub**
* **Jupyter Notebook**

---

##  How to Run

### Option 1: Google Colab (Recommended)

1. Upload the notebook to Colab
2. Run all cells from top to bottom
3. Dataset downloads automatically

### Option 2: Local Machine

```bash
pip install kagglehub opencv-python numpy matplotlib scikit-learn
```

Then open:

```bash
jupyter notebook Project1_vision.ipynb
```

---

## 📊 Results & Observations

* Visual features capture **shape and texture information**
* Performance depends heavily on:

  * Feature type
  * Image resolution
  * Intra-class variation
* Classical methods remain competitive for **small/medium datasets**

---

##  Key Takeaways

* Demonstrates a **full classical CV workflow**
* Highlights the importance of **feature representation**
* Serves as a foundation for:

  * Image retrieval
  * Object classification
  * Hybrid classical + deep learning systems

---

## 📁 Repository Structure

```
├── Project1_vision.ipynb
├── README.md
```

---


Electrical & Computer Engineering
Computer Vision Coursework





Just tell me 👍
