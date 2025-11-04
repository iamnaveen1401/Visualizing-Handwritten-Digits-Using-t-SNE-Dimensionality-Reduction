# ✍️ Visualizing Handwritten Digits Using t-SNE Dimensionality Reduction

## 📘 Project Overview
This project demonstrates how **t-SNE (t-distributed Stochastic Neighbor Embedding)** can be used for **dimensionality reduction** and visualization of high-dimensional data.  
Using the **Digits dataset** from `sklearn.datasets`, this project visualizes handwritten digits (0–9) in a 2D space to observe natural groupings and relationships between classes.

---

## 🧩 Dataset Information
- **Dataset Source:** `sklearn.datasets.load_digits`
- **Samples:** 1,797  
- **Features:** 64 (8×8 pixel grayscale images)  
- **Target Classes:** Digits 0–9  

Each sample represents a small grayscale image of a handwritten digit. The pixel values (0–16) denote the intensity of each pixel.

---

## 🧠 Methodology
1. **Load the digits dataset** from scikit-learn  
2. **Normalize** or **standardize** the pixel values  
3. Apply **t-SNE** to reduce 64-dimensional data into **2D** or **3D** space  
4. **Visualize clusters** of digits using scatter plots  
5. Color-code each point according to its true label for interpretation  

plt.ylabel("t-SNE Feature 2")
plt.show()
