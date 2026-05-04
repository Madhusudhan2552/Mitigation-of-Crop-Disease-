# 🌱 Mitigation of Crop Disease Detection using Deep Learning

📌 Overview:
Agriculture plays a crucial role in feeding more than 58% of the global population. However, crop diseases significantly affect productivity and yield.

This project presents an **automated crop disease detection system** using **Deep Learning (CNN)** and image processing techniques. It enables fast, accurate, and real-time identification of plant diseases, helping farmers take timely action.
🎯 Objectives:
- Detect plant diseases using leaf images
- Improve accuracy compared to traditional methods
- Provide real-time prediction using an API
- Reduce crop loss through early detection

🚀 Features:
- 🌿 Disease detection from leaf images
- ⚡ Fast prediction using **FastAPI**
- 📊 High accuracy model (~99%)
- 🧠 Deep Learning based CNN model
- 📱 User-friendly interface (web-based)

🧠 Tech Stack:
- **Programming Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Matplotlib  
- **Framework:** FastAPI  
- **Environment:** Anaconda  
- **Hardware:** GPU (NVIDIA)  

📂 Dataset:
- **Dataset Used:** PlantVillage Dataset  
- **Total Images:** ~20,645  
- **Classes:** 15 plant disease categories  
- **Split:**
  - Training: 80%
  - Validation + Testing: 20%
The dataset includes both **healthy and diseased plant images** for accurate classification. :contentReference[oaicite:0]{index=0}

⚙️ Methodology:
🔹 Steps Involved:
1. Image Acquisition  
2. Preprocessing (resize, normalization)  
3. Data Augmentation (rotation, flipping, zooming)  
4. Feature Extraction  
5. Classification using CNN  

🔹 Model Details:
- Architecture: Convolutional Neural Network (CNN)
- Activation: ReLU  
- Optimizer: SGD  
- Learning Rate: 0.001  
- Epochs: 30  
- Dropout: 0.5 :contentReference[oaicite:1]{index=1}  

📊 Results:
- ✅ Achieved **~99.17% accuracy** in crop disease classification  
- Improved performance using:
  - Transfer Learning  
  - Data Augmentation  
  - Hyperparameter tuning :contentReference[oaicite:2]{index=2}  

🧪 Testing:
- Black Box Testing  
- Regression Testing  
- Integration Testing  
- GUI Testing  

🖥️ System Features:
- Disease prediction with confidence score  
- Image upload functionality  
- Information pages (Details, Gallery, Contact)  
- Feedback system for users :contentReference[oaicite:3]{index=3}

⚠️ Limitations:
- Accuracy depends on image quality
- Requires large dataset for better generalization
- High computational resources needed

🔮 Future Enhancements:
- Mobile application for farmers
- Integration with IoT devices
- Real-time field monitoring
- Multi-language support
- Pest + disease combined detection

📸 Sample Output:
- Disease classification with label & confidence
- Visual representation of results

👨‍💻 Contributors:
- Karthik Reddy  
- Neetha Reddy  
- Madhusudhan Kumar  
- Sumalini Goud

📚 References:
- PlantVillage Dataset  
- Various research papers on CNN and plant disease detection

📢 Conclusion:
This project demonstrates how **AI + Agriculture** can solve real-world problems. By leveraging CNN models, we achieved high accuracy in detecting plant diseases, making it a scalable and practical solution for farmers.
