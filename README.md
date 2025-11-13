# Sajiin Dong - AI Personalized Food Recommendation 🍽️

![Bangkit Academy](https://img.shields.io/badge/Bangkit%20Academy-2024-red?style=for-the-badge)
![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android)
![TensorFlow](https://img.shields.io/badge/ML-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow)
![GCP](https://img.shields.io/badge/Cloud-Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud)

**Sajiin Dong** is a mobile application designed to redefine the culinary experience by integrating advanced AI technology. It provides personalized food and beverage recommendations tailored to individual health needs (Diet/Bulking) and taste preferences.

This project was built as a **Capstone Project** for Bangkit Academy 2024 by a cross-functional team of Mobile, Cloud, and Machine Learning cohorts.

## 🎯 Key Features

* **Personalized Recommendations:** AI-driven suggestions based on user health goals.
* **Health Programs:** Dedicated support for **Diet** and **Bulking** programs.
* **Smart Filtering:** Machine Learning-based food filtering.
* **User Profiling:** Customized profile management for precise tracking.
* **Multi-Language Support:** Accessible for wider audiences.

## 🏗️ System Architecture

### 🤖 Machine Learning
The core recommendation engine utilizes **Deep Learning** with Artificial Neural Networks (ANN).
* **Dataset:** Combined dataset of **5,000 food items** and **2,500 drink items** sourced from Kaggle and Google.
* **Model Config:** Dense layers with `relu` and `softmax`, Dropout layers, and L2 regularization for optimization.
* **Deployment:** Converted to **TFLite** for on-device mobile inference.

### ☁️ Cloud Computing
The backend infrastructure is built on **Google Cloud Platform** to ensure scalability and reliability.
* **Compute Engine:** Hosts the Flask API server.
* **Cloud Storage:** Stores datasets and model files.
* **Containerization:** Docker used for deploying applications.
* **API:** RESTful Endpoints for serving food and beverage recommendations.

### 📱 Mobile Development
* **Language:** Kotlin
* **Framework:** Native Android with Jetpack Components.
* **Tools:** Android Studio & Gradle.

## 👥 The Team

| Role | Name |
| :--- | :--- |
| **Mobile Dev** | **Adam Syahputra** ([LinkedIn](https://linkedin.com/in/adamsputra/)) |
| **Mobile Dev** | Gideon Aprileo |
| **Cloud Computing** | M. Daffa A. M. |
| **Cloud Computing** | Iqbal Dwi N. |
| **Machine Learning** | Rey Aji Darusalam |
| **Machine Learning** | Bella Melati W. D |
| **Machine Learning** | Sariwati |


## 🚀 Getting Started

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/adamsptech/SajiinDong-App.git](https://github.com/adamsptech/SajiinDong-App.git)
    ```
2.  **Open in Android Studio**
    * Ensure you have the latest Android Studio version installed.
    * Wait for Gradle Sync to finish.
3.  **Run the App**
    * Connect a physical device or use an Emulator.
    * Press `Run`.

---
*© 2024 Sajiin Dong Team - Bangkit Academy Capstone Project*