
 
To deploy a FastAPI Machine Learning application for Heart Disease Detection on Google Cloud Run, follow these steps

1. Prepare Your FastAPI Application
Before deployment, ensure that your FastAPI app is functional and ready to serve the heart disease detection model. The app should:
•	Accept input data (e.g., patient attributes such as age, blood pressure, cholesterol).
•	Use a pre-trained machine learning model to make predictions (e.g., classify if a patient has heart disease).
•	Return the prediction in JSON format.

2. Set Up Google Cloud
•	Create a Google Cloud Project
•	Go to the Google Cloud Console.
•	Create a new project or select an existing on

3. Dockerize the Application
Cloud Run requires Docker containers for deployment. Create a Dockerfile in project directory

4. Deploy to Google Cloud Run
Push Docker Image to Google Container Registry
Output:
 
5.Set Up CI/CD Pipeline (Optional)
•	To automate the deployment, set up a CI/CD pipeline with GitHub Actions.
•	Create a .github/workflows/deploy.yml file in your GitHub repository


This is the URL of the deployed application: - https://fastapi-134094032952.us-central1.run.app

Published this on platforms Medium :- https://medium.com/@thepath936/how-to-deploy-a-fastapi-machine-learning-application-in-google-cloud-run-edd52c30b60e

This is my Github account: - https://github.com/SafranThawfeek/FastAPI.git

