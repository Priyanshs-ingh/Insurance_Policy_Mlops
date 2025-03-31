

---

# 🚀 Vehicle Insurance MLOps Pipeline  

## 📌 Overview  
This project demonstrates a **complete MLOps pipeline** for managing and deploying a **vehicle insurance ML model**. It covers **end-to-end ML lifecycle management**, including:  

- **Data ingestion, validation, and transformation**  
- **Model training and evaluation**  
- **Cloud deployment (AWS, Docker, and GitHub Actions)**
- **CI/CD automation for continuous integration and deployment**  

---

## 🛠️ Tech Stack  

### **Programming & Data Processing:**  
- **Python** (NumPy, Pandas, Scikit-learn)  

### **Database & Storage:**  
- **MongoDB Atlas** (NoSQL Database)  
- **AWS S3** (Model storage)  

### **Model Training & Deployment:**  
- **Scikit-learn** (Machine learning framework)  
- **AWS EC2** (Cloud instance for deployment)  

### **CI/CD & Automation:**  
- **GitHub Actions** (Automated CI/CD pipelines)  
- **Docker** (Containerization)  
- **AWS ECR** (Docker image repository)  

### **Infrastructure & Environment Management:**  
- **Conda** (Virtual environment)  
- **Environment Variables** (Configuration management)  

### **Logging & Exception Handling:**  
- **Python logging module** (Robust error tracking)  

### **Web UI & API Integration:**  
- **FastAPI / Flask** (For building model prediction API)  

---

## 📁 Project Structure  

### **1️⃣ Project Setup**  
- Created a well-defined **project template** using `template.py`  
- Managed dependencies using `setup.py` and `pyproject.toml`  
- Set up a **virtual environment** and installed required dependencies  

### **2️⃣ Data Pipeline & Storage**  
- Configured **MongoDB Atlas** for cloud-based data storage  
- Developed scripts to **ingest, validate, and transform data**  
- Implemented **logging and exception handling** for better debugging  

### **3️⃣ Model Training & Evaluation**  
- Preprocessed data using **Feature Engineering & EDA**  
- Built a **Scikit-learn-based ML model** for vehicle insurance predictions  
- Automated **model evaluation and performance tracking**  

### **4️⃣ AWS Cloud Deployment & CI/CD**  
- Configured **AWS S3** for storing trained models  
- Set up **AWS EC2** instance for model hosting  
- Implemented **GitHub Actions-based CI/CD pipeline**, integrating:  
  - **Docker** (Containerized the app)  
  - **AWS ECR** (Hosted Docker images)  
  - **GitHub Secrets** (Managed AWS credentials securely)  

### **5️⃣ Model Deployment & API**  
- Built a **FastAPI/Flask-based prediction pipeline**  
- Hosted the model on AWS with API access  
- Developed a **simple web UI** for interaction  

---

## 🚀 How to Run the Project?  

### **Step 1: Clone the Repository**  
```sh
git clone <repo-url>
cd vehicle-insurance-mlops
```

### **Step 2: Set Up Virtual Environment**  
```sh
conda create -n vehicle python=3.10 -y
conda activate vehicle
pip install -r requirements.txt
```

### **Step 3: Configure MongoDB**  
1. Sign up for **MongoDB Atlas**  
2. Create a **database & collection**  
3. Set up a **MongoDB connection string** as an environment variable  

### **Step 4: Run the Pipeline**  
```sh
python main.py
```

---

## 🌍 Deployment & Access  
- **Dockerized application** deployed on **AWS EC2**  
- Accessible at: **`http://<public_ip>:5080`**  

---

## 🎯 Project Workflow Summary  
✔ **Data Ingestion ➔ Data Validation ➔ Data Transformation**  
✔ **Model Training ➔ Model Evaluation ➔ Model Deployment**  
✔ **CI/CD Automation using GitHub Actions, Docker, AWS EC2, and ECR**  

---

## 💡 Key Learnings & Impact  
- Built a **production-ready ML pipeline** from scratch  
- Gained hands-on experience with **MLOps best practices**  
- Integrated **Cloud, CI/CD, and Automation** for real-world scalability  

---


