# ♻️ Waste Classification Using CNN  

A deep learning-based waste classification system using CNN (Convolutional Neural Networks) to categorize waste into **organic and recyclable** for improved waste management and recycling efficiency.  

**📂 Dataset for the project:**  
[Waste Classification Dataset (Kaggle)](https://www.kaggle.com/datasets/techsash/waste-classification-data)  

---

## 📅 Project Timeline (Week-wise Progress)  

### **Week 1: Data Collection & Preprocessing 📊**  
✅ Collected **waste classification dataset** from KaggleHub with labeled images (**Organic & Recyclable**).  
✅ Organized dataset into **TRAIN and TEST directories** for model training.  
✅ Resized images to **224x224 pixels** for uniform input size.  
✅ Applied **normalization (rescale pixel values to [0,1])** to improve training efficiency.  
✅ Visualized dataset distribution using a **pie chart** (Organic: **55.69%**, Recyclable: **44.31%**).  
✅ Displayed **sample images** from each category for dataset verification.  

---

### **Week 2: CNN Model Implementation & Training 🏗️**  
✅ Built a **CNN model** with:  
   - **Three Convolutional Layers** (32, 64, 128 filters).  
   - **MaxPooling Layers** for spatial feature extraction.  
   - **Fully Connected Layers** with **dropout** to prevent overfitting.  
   - **Sigmoid activation** for binary classification.  

✅ Compiled the model using **Adam optimizer** & **Binary Crossentropy loss**.  
✅ Trained the model for **10-15 epochs** with a batch size of **32**.  
✅ Plotted **accuracy and loss graphs** to evaluate model performance over epochs.  

---

### **Week 3: Model Evaluation, Testing & Deployment Planning 🚀**  
✅ Tested the **trained model** on unseen test images.  
✅ Created a **predict function** to classify new waste images into **Organic or Recyclable**.  
✅ Evaluated model performance using **accuracy and loss plots**.  
✅ Identified **overfitting issues** and proposed **hyperparameter tuning solutions**.  
✅ Planned **web deployment** using **Streamlit or Flask** to make the model accessible.  

✅ **Future Improvements:**  
   - Expand dataset to include **plastic, metal, glass**.  
   - Use **pre-trained models (ResNet, VGG16)** for better accuracy.  
   - Integrate with **IoT smart bins** for automated waste sorting.  

---

## 🛠 Technologies Used  
- **Python** 🐍  
- **TensorFlow & Keras** (Deep Learning)  
- **OpenCV** (Image Processing)  
- **Matplotlib & Pandas** (Data Visualization)  
- **Jupyter Notebook / Google Colab** (Development Environment)  

---

## 📬 Future Scope  
✔ **Improve model accuracy** with **advanced architectures** like **ResNet, VGG16**.  
✔ **Deploy a web app** for **real-time waste classification**.  
✔ **Enhance dataset** to classify **multiple waste categories** beyond organic & recyclable.  
