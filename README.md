# AI-Powered Web App for Early Detection of Skin Cancer, Burns, and Diseases

##  Project Description
This project presents an **AI-powered web application** designed for the **early detection and classification of skin conditions**, including **skin cancers, burns, and bacterial/fungal infections**.

Skin diseases represent a significant global health issue, with skin cancer cases, particularly **melanoma** and **basal cell carcinoma**, on the rise. Early and accurate detection is essential for improving treatment outcomes and patient survival rates. This project leverages **deep learning** and **computer vision techniques** to address these challenges by providing a reliable, efficient, and accessible diagnostic tool.

---

##  Problem Statement
Traditional diagnosis of skin conditions can be time-consuming, costly, and dependent on specialist availability. Many patients, especially in developing regions, face limited access to dermatologists, leading to delays in detection and treatment.  
This project aims to **bridge the gap** by providing an AI-based solution capable of analyzing skin images and offering instant diagnostic insights.

---

##  Dataset and Data Preparation
The models were trained on a **diverse and comprehensive dataset** collected from multiple medical sources:
- **HAM10000 Dataset** for skin cancers (seven cancer types: melanoma, basal cell carcinoma, Bowen’s disease, benign keratosis-like lesions, dermatofibroma, melanocytic nevi, vascular lesions).
- **Skin Disease Dataset** covering bacterial and fungal infections such as impetigo, ringworm, athlete’s foot, cellulitis, and shingles.
- **Burn Image Dataset** including 5,000+ labeled images of **first, second, and third-degree burns**.

Preprocessing steps ensured data quality and consistency:
- Image resizing for uniform resolution  
- Data augmentation (rotation, flipping, shifting, zooming) to enrich dataset diversity  
- Pixel normalization to reduce lighting and environmental effects  

---

##  Model Architecture
The project utilized **MobileNetV2** as the core model due to its efficiency and lightweight nature, making it suitable for web and mobile deployment.  
Each task was customized with additional layers:
- **Skin Cancer Detection**: Modified MobileNetV2 with optimized convolutional layers  
- **Burn Severity Classification**: Added fully connected layers for burn grading  
- **Bacterial & Fungal Infection Detection**: Adapted MobileNetV2 for infection classification  

---

##  Performance and Evaluation
The models were evaluated using **accuracy, precision, recall, and F1-score**.  
Key results include:
- **93% accuracy** in skin cancer classification  
- **91% accuracy** in burn severity classification  
- **90% accuracy** in bacterial and fungal infection detection  

These results highlight the potential of AI in achieving dermatologist-level performance for early diagnosis.

---

##  Web Application
A **user-friendly web app** was developed to make the system accessible:
1. Upload a skin image  
2. Select the classification type (cancer, burn, or infection)  
3. Receive instant prediction results with accuracy confidence  

The app serves as a **decision-support tool** for both healthcare professionals and patients.

---

##  Future Enhancements
- Expanding datasets to include rare skin conditions  
- Incorporating **patient metadata** (age, medical history) for multi-modal predictions  
- Cloud deployment for scalability and integration with healthcare systems  
- Exploring explainable AI (XAI) to provide interpretable results for clinicians  

---

##  Impact
This project demonstrates how **AI and machine learning** can transform healthcare by offering:
- **Early detection** of life-threatening conditions  
- **Accessible diagnostics** for underserved populations  
- **Reliable and cost-effective solutions** to complement traditional medical practices  

By achieving **90%+ accuracy** across multiple tasks, this system proves the potential of AI in **revolutionizing dermatological care** and supporting clinicians in making faster, more informed decisions.

---

##  Author
**Mariam Awadallah**  
AI & Data Science Enthusiast | Passionate about applying AI in Healthcare
