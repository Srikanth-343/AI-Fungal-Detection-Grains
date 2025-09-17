# AI-Driven Model for Early Detection of Fungal Spoilage in Stored Grains

## 📌 Objective
This project develops a **low-cost AI-powered fungal detection system** to identify mold in post-harvest stored grains. Instead of relying on expensive equipment like hyperspectral imaging, the system leverages **deep learning models** and **affordable imaging devices**.

## 🛠️ Methods
- **Data Collection:**  
  - Captured fungal contamination images using a **Vivo V29 Pro (50MP Sony IMX663 sensor)** with a **200x smartphone microscope lens**.  
  - Simulated grain storage conditions to study mold growth under controlled environments.
<img width="794" height="1022" alt="image" src="https://github.com/user-attachments/assets/0018819a-af49-4015-aa6d-cf0c1d623558" />

    Figure 1: Observations of Mold Growth on Stored Rice Grains

- **Models Used:**  
  - **YOLO** → for spatial object detection & mold localization.  
  - **ResNet-50** → for image classification of mold-infected vs. healthy grains.

- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score.


## 📊 Findings
- **YOLO**: Effective in localizing mold regions.  
- **ResNet-50**: Achieved **97% classification accuracy**, proving AI’s effectiveness in fungal detection.  
- Demonstrated that **affordable alternatives** can replace costly hyperspectral imaging solutions.
  <img width="625" height="331" alt="image" src="https://github.com/user-attachments/assets/1cdcc8c3-7118-43a1-b776-efb36303d9ed" />

    Figure 2: Predictions from yolo11n


  <img width="254" height="308" alt="image" src="https://github.com/user-attachments/assets/bf27aadd-ee6a-46b2-a446-fd194d6bc740" />

    Figure 3: ResNet50 result report

## ✅ Conclusion
- Simulated storage setup minimized data collection challenges and proved to be a reliable alternative.  
- AI-driven fungal detection can **improve food safety, reduce financial losses, and enhance monitoring of grain storage**.  
- Future work: Integration with **multispectral sensors**, **IoT-based monitoring**, and **autonomous bots** for large-scale deployment.

## 🚀 Future Scope
- Enhance dataset diversity with real-world storage environments.  
- Explore **lightweight AI models** for on-device detection.  
- Develop **mobile app integration** for real-time monitoring.

---

### 🔧 Tech Stack
- Python, TensorFlow/PyTorch  
- YOLO for object detection  
- ResNet-50 for classification  
- OpenCV for preprocessing & visualization  

---

### 📂 Repository Structure
