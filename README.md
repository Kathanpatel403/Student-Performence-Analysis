# 🚀 **Student Performance Analysis**

This project demonstrates the seamless integration of **machine learning**, **web development**, and **cloud deployment** to analyze student performance. By utilizing **AWS Elastic Beanstalk** for cloud deployment and **AWS CodePipeline** for continuous delivery, this application is designed to predict student performance outcomes based on various input features using a machine learning model.

🎥 **Watch the full demo of the project workflow, including setup and deployment processes:**  
[Click here to watch the video](https://drive.google.com/file/d/1UaRAXpavmRXLuoK0jt8q6FpiepOG34t0/view?usp=sharing)

---

## 📦 **Project Overview**

I developed an innovative web application aimed at analyzing student performance using machine learning techniques. This project blends **data science**, **web development**, and **cloud deployment** to create an impactful tool for educational insights.

The application is built with **Flask**, and it processes student data to predict performance outcomes. It leverages AWS for hosting and automating deployment, ensuring scalability and reliability for real-world usage.

---

## ✨ **Project Highlights**

- **🔧 Data Pipelines:**  
    - Designed robust pipelines for data preprocessing and machine learning model training.  
    - The final model, trained and validated, is saved as a `.pkl` file for efficient usage.
    
- **⚙️ Backend Integration with Flask:**  
    - Used **Flask** to create a dynamic backend that processes incoming data and predicts student performance outcomes based on the data received from the frontend.
    
- **📂 Version Control & Hosting:**  
    - Hosted the version-controlled codebase on **GitHub**, ensuring smooth collaboration and code management.
    
- **☁️ AWS Deployment:**  
    - Deployed the application on **AWS Elastic Beanstalk**, providing a reliable and scalable hosting environment for the app.
    
- **🔄 Continuous Delivery (CD):**  
    - Set up **AWS CodePipeline** to automate the deployment process, ensuring that any changes committed to the master branch on GitHub are automatically deployed to the live environment.
    
---

## 🛠 **Technologies Used**

- **Backend:**  
    - Python (3.8), Flask
    - Pandas, NumPy, Scikit-learn
    
- **Cloud Services:**  
    - AWS Elastic Beanstalk
    - AWS CodePipeline
    
- **Version Control & Hosting:**  
    - GitHub, Docker (for local development and testing)

- **Frontend:**  
    - HTML (Frontend Templates)
    
---

## 📊 **Technologies Stack**

- **Python 3.8**  
- **Flask**  
- **Docker**  
- **GitHub Actions**  
- **HTML (Frontend Templates)**  
- **Scikit-learn (Model)**  

---

## 🔄 **Data Preprocessing**

The dataset used for this project includes various features related to student performance. Key preprocessing steps include:

- Handling **missing values**
- **Feature engineering** to derive meaningful insights
- **Data normalization** to scale input features for the machine learning model

---

## 🧠 **Model Training**

The **machine learning model** is built using **Python**, **Pandas**, **NumPy**, and **Scikit-learn**. Once trained and validated, the model is saved as a `.pkl` file for later predictions.

---

## ⚙️ **Backend Development**

The backend is developed using **Flask**. The `application.py` file contains the Flask application code that processes incoming data and uses the trained machine learning model to predict student performance.

- **Main Routes:**
    - `/`: Home page route
    - `/predictdata`: Handles student data and prediction based on the form input

The **HTML templates** for the frontend are located in the `templates/` directory.

---

## 🚀 **AWS Elastic Beanstalk Deployment**

1. **Create an Elastic Beanstalk Application**  
    - Log in to the AWS Management Console and create an Elastic Beanstalk environment with the **Python** platform.

2. **Configure Elastic Beanstalk:**  
    - Set up environment variables and specify `WSGIPath` in the `.ebextensions/python.config` file to guide Elastic Beanstalk in recognizing your application.

    Example `.ebextensions/python.config`:
    ```yaml
    option_settings:
      "aws:elasticbeanstalk:container:python":
        WSGIPath: application:application
    ```

---

## 🔄 **AWS CodePipeline for Continuous Delivery**

1. **Create a CodePipeline**  
    - Set up a new pipeline in AWS CodePipeline.
    - Link it to your **GitHub** repository for continuous integration.

2. **Automatic Deployment:**  
    - Every time a change is pushed to the **master branch** on GitHub, AWS CodePipeline automatically deploys the updated application to **AWS Elastic Beanstalk**.

---

## 📂 **File Structure**

