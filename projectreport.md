# 🗓️ Week 2 Progress Report – Smart Waste Classifier Internship

## ✅ Summary of Tasks Completed

### 📁 Dataset & Preprocessing Enhancements
- Applied **image data augmentation** (rotation, zoom, flip) using `ImageDataGenerator` from Keras.
- Rebalanced dataset to handle class imbalance more effectively.
- Improved image pipeline with real-time augmentation during model training.

### 🧠 Model Improvements
- Tuned CNN hyperparameters:
  - Increased number of filters in Conv layers
  - Added dropout layers to reduce overfitting
  - Optimized learning rate
- Trained new model with augmentation and got improved performance:
  - Validation Accuracy: **~89%**
  - Reduced overfitting compared to Week 1

### 📊 Evaluation
- Used confusion matrix to evaluate class-wise performance.
- Visualized training vs validation accuracy and loss graphs for better insights.

---

## 🔬 Key Learnings This Week
- Understanding the importance of data augmentation to improve generalization
- Effects of dropout and regularization in CNNs
- Hands-on with evaluation techniques like confusion matrix and classification reports
- Model tuning strategies: learning rate, optimizer, layers, dropout

---

## 📁 Files Generated
- `garbage_classifier_week2.ipynb`: Colab notebook with updated model
- `trash_classifier_v2.h5`: Improved model with better accuracy
- `graphs/`: Contains training graphs and confusion matrix (optional folder)

---

## 🔜 Week 3 Plans
- Create a user-friendly **Streamlit web application** for image upload and prediction
- Load trained model and perform live predictions
- Add UI enhancements: upload box, prediction label, confidence score

---

## 📌 Notes
- Continue monitoring model for further improvements
- Document code and create `requirements.txt` for deployment

---

🧪 **Model File:** `trash_classifier_v2.h5`  
📒 **Notebook:** `garbage_classifier_week2.ipynb`
