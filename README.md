# 🧹 Data Preprocessing Module

This folder contains projects related to **data preprocessing** — preparing raw data for machine learning and deep learning models.

## Projects

### 1. License Plate Preprocessing
- Dataset: Algerian License Plate Dataset (private source)  
- Techniques:
  - Image resizing & grayscale conversion
  - Histogram equalization
  - Thresholding & edge detection
  - Bounding box extraction
- Tools: OpenCV, NumPy, Matplotlib  
- Example:
  | Original | Preprocessed |
  |----------|--------------|
  | ![Before](images/sample_before.png) | ![After](images/sample_after.png) |

### 2. **NLP Preprocessing Techniques** (`notebooks/NLP_and_Preprocessing_Techniques.ipynb`)  
   - Focus: preparing raw text data for Natural Language Processing tasks.  
   - Steps:
     - Tokenization and stopword removal  
     - Stemming and Lemmatization  
     - Text normalization (lowercasing, punctuation removal)  
     - Bag-of-Words (BoW) and TF-IDF representations  
   - Tools: NLTK, Scikit-learn  
   - Example: preprocessing raw sentences into clean tokens ready for machine learning models.
