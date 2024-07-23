# Student Performance Analysis

For a detailed video recording of the entire workflow of continuous delivery (CD), including setup and deployment processes, [click here](https://drive.google.com/file/d/1UaRAXpavmRXLuoK0jt8q6FpiepOG34t0/view?usp=sharing).

## Project Overview

I developed an innovative web application aimed at analyzing student performance using advanced machine learning techniques. This project was an exciting blend of data science, web development, and cloud deployment, resulting in a powerful tool for educational insights.

## Project Highlights

- **Data Pipelines:** Designed and implemented robust pipelines for data preprocessing and machine learning model training. The final model, trained and validated, was saved as a `.pkl` file for efficient usage.
- **Backend Integration:** Utilized Flask to create a dynamic backend capable of processing data and predicting student performance outcomes based on inputs received from the HTML frontend.
- **Version Control & Hosting:** Hosted the version-controlled codebase on GitHub, ensuring easy collaboration and code management.
- **AWS Deployment:** Deployed the application on AWS Elastic Beanstalk, providing a reliable and scalable hosting environment.
- **Continuous Delivery:** Set up an AWS CodePipeline to automate the deployment process. Any changes committed to the master branch on GitHub are automatically deployed to the live environment, ensuring continuous delivery and seamless updates.

## Technologies Used

- Python
- Pandas
- NumPy
- Flask
- HTML
- GitHub
- AWS Elastic Beanstalk
- AWS CodePipeline

## Why This Project Stands Out

This project demonstrates my ability to create end-to-end solutions that not only leverage cutting-edge machine learning techniques but also ensure seamless integration and deployment in a cloud environment. It highlights my proficiency in managing data pipelines, developing web applications, and implementing continuous delivery practices.

## Data Preprocessing

The dataset includes various features related to student performance. Data preprocessing steps are documented in the `notebooks/data_preprocessing.ipynb` notebook. This includes handling missing values, feature engineering, and data normalization.

## Model Training

The machine learning model is trained using Python libraries such as Pandas, NumPy, and Scikit-learn. The final model is saved as a `.pkl` file.

## Backend Development

The backend is developed using Flask. The `application.py` file contains the Flask application code that processes incoming data and uses the trained model to predict student performance. The HTML templates for the frontend are located in the `templates/` directory.

## Deployment

- **AWS Elastic Beanstalk Deployment:**
    - Create a new Elastic Beanstalk environment.
    - Deploy the Flask application using the AWS Management Console or AWS CLI.

- **AWS CodePipeline Setup:**
    - Create a new pipeline in AWS CodePipeline.
    - Connect the pipeline to your GitHub repository.
    - Configure the pipeline to deploy to AWS Elastic Beanstalk upon each commit to the master branch.

## Conclusion

This project showcases the development of a web application that integrates data science and web development with cloud deployment. The use of AWS services ensures a scalable and reliable environment for the application, while continuous delivery practices facilitate seamless updates.