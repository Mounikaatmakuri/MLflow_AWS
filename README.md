## 🚀 MLflow on AWS Setup Guide
This guide provides step-by-step instructions to set up MLflow Tracking Server on AWS, using S3 for artifact storage and EC2 (Ubuntu) as the backend server.

# 📦 Overview
MLflow is an open-source platform for managing the end-to-end machine learning lifecycle, including experiment tracking, model packaging, and deployment.

This setup enables:
Remote MLflow server accessible via EC2
Artifact storage in Amazon S3
Experiment tracking from local machine to cloud

# ✅ Prerequisites
AWS account
IAM User with AdministratorAccess
AWS CLI installed on your local machine
SSH access to EC2 instance

<img width="1440" height="900" alt="Screenshot 2025-07-19 at 1 33 48 PM" src="https://github.com/user-attachments/assets/a43cecb2-0dc6-4811-9cc3-c0b244effc25" />
<img width="1440" height="900" alt="Screenshot 2025-07-19 at 1 33 43 PM" src="https://github.com/user-attachments/assets/900882f7-cc9f-4d49-90e9-663791bd4d8b" />
<img width="1440" height="900" alt="Screenshot 2025-07-19 at 1 33 34 PM" src="https://github.com/user-attachments/assets/83cfbe97-dfaa-412c-84af-961f9f250910" />
<img width="1440" height="900" alt="Screenshot 2025-07-19 at 1 33 21 PM" src="https://github.com/user-attachments/assets/dcfe34b6-d6c4-40f4-a920-d8caf046b954" />
<img width="1440" height="900" alt="Screenshot 2025-07-19 at 1 33 04 PM" src="https://github.com/user-attachments/assets/352bd405-46fe-40cf-8459-9dbe406c8a02" />
<img width="2880" height="1800" alt="Screenshot 2025-07-19 at 1 33 01 PM" src="https://github.com/user-attachments/assets/d57aff25-9011-4802-a551-e0da51613534" />
