🚀 Vehicle Insurance MLOps Pipeline
Overview
This project demonstrates a complete MLOps pipeline for managing and deploying a machine learning model on vehicle insurance data. It covers end-to-end ML lifecycle management, including data ingestion, validation, transformation, model training, deployment, and CI/CD automation using AWS, Docker, and GitHub Actions.

🔧 Tech Stack
Programming: Python (NumPy, Pandas, Scikit-learn, PyTorch/TensorFlow)

Data Handling: MongoDB Atlas (NoSQL Database)

Model Training & Deployment: Scikit-learn, AWS S3, AWS EC2

CI/CD & Automation: GitHub Actions, Docker, AWS ECR, EC2

Infrastructure: Virtual Environment (Conda), Environment Variables

Logging & Exception Handling: Python logging module

Web UI & API Integration: FastAPI/Flask (for the prediction pipeline)

📁 Project Structure
1️⃣ Project Setup
Created a well-defined project template using template.py

Managed package dependencies in setup.py and pyproject.toml

Set up a virtual environment and installed dependencies from requirements.txt

2️⃣ Data Pipeline & Storage
Configured MongoDB Atlas for data storage

Developed scripts to ingest, validate, and transform data before model training

Implemented data logging and exception handling for better debugging

3️⃣ Model Training & Evaluation
Preprocessed data using Feature Engineering & EDA techniques

Developed a machine learning model using Scikit-learn

Automated model evaluation and performance tracking

4️⃣ AWS Cloud Deployment & CI/CD
Configured AWS S3 for storing trained models

Set up AWS EC2 instance for deploying the model via a web API

Implemented GitHub Actions for CI/CD automation, integrating:

Docker: Containerized the application

AWS ECR: Hosted Docker images for deployment

GitHub Secrets: Managed AWS credentials securely

5️⃣ Model Deployment & API
Built a prediction pipeline with FastAPI/Flask

Hosted the model on AWS, accessible via an API endpoint

Set up a web UI for user interaction

🚀 How to Run the Project?
Step 1: Clone the Repository
sh
Copy
Edit
git clone <repo-url>
cd vehicle-insurance-mlops
Step 2: Set Up Virtual Environment
sh
Copy
Edit
conda create -n vehicle python=3.10 -y
conda activate vehicle
pip install -r requirements.txt
Step 3: Configure MongoDB
Sign up for MongoDB Atlas

Create a database & collection

Set up a MongoDB connection string as an environment variable

Step 4: Run the Pipeline
sh
Copy
Edit
python main.py
🌍 Deployment & Access
Dockerized application hosted on AWS EC2

Accessible at: http://<public_ip>:5080

📌 Key Learnings & Impact
Built a production-ready ML pipeline from scratch

Gained hands-on experience with MLOps best practices

Integrated Cloud, CI/CD, and Automation for real-world scalability

If you find this project useful, ⭐ star this repository and connect with me!
