# ✍️ Handwritten Digit Recognition  
*Nhận diện chữ số viết tay với SVM và Random Forest*

This project demonstrates handwritten digit classification using the **MNIST** dataset and traditional **machine learning models**:  
- 🧠 Support Vector Machine (SVM)  
- 🌲 Random Forest (RF)  

Dự án này nhận diện chữ số viết tay từ bộ dữ liệu MNIST bằng các mô hình học máy cổ điển:  
- 🧠 Máy vector hỗ trợ - Support Vector Machine (SVM)  
- 🌲 Rừng ngẫu nhiên (Random Forest)

---

⚡ You don’t need deep learning to get high accuracy on MNIST!  
⚡ Bạn không cần học sâu vẫn có thể đạt độ chính xác cao trên MNIST!

👉 [Run on Colab](https://colab.research.google.com/drive/1fBjoshWg9BxiaDxBQPQOuCaCWA4SSyIj?usp=sharing)  

🎓 **Author's Note | Lưu ý từ tác giả:**  
> This notebook is designed for ML beginners:  
> - Learn how to load and visualize MNIST  
> - Train and compare SVM vs Random Forest  
> - Save models and use them for real-world image prediction  

> Notebook này dành cho người mới học ML:  
> - Tìm hiểu cách tải và trực quan hóa dữ liệu MNIST  
> - Huấn luyện và so sánh hai mô hình SVM và RF  
> - Lưu mô hình và dự đoán chữ viết tay thực tế

💡 A solid stepping stone before diving into deep learning.  
💡 Một bước đệm tốt trước khi học deep learning.

🚫 This is not a production OCR system.  
🚫 Đây không phải hệ thống OCR chuyên nghiệp.

---

## 🔍 Demo

- ▶️ [YouTube Explanation] (https://youtube.com/live/lWpv9HCT6Y8?feature=share)  
- 💻 [Try on Google Colab](https://colab.research.google.com/drive/1fBjoshWg9BxiaDxBQPQOuCaCWA4SSyIj?usp=sharing)

---

## ⚙️ Requirements

### Libraries:
- `scikit-learn`  
- `numpy`  
- `matplotlib`  
- `joblib`

## 📄 Dataset

**Dataset**: MNIST Handwritten Digits  
- **Source**: [OpenML MNIST 784](https://www.openml.org/d/554)  
- **Description**:  
  - 60,000 training images  
  - 10,000 test images  
  - Grayscale format (28x28 pixels)  
  - Each image represents a handwritten digit (0–9)

---

## 🧪 Features

✅ Load and preview MNIST digits  
✅ Train classification models using **SVM** and **Random Forest**  
✅ Evaluate model performance using accuracy score  
✅ Save trained models to `.pkl` files using `joblib`  
✅ Build a simple **Streamlit app** to upload and predict digit images

