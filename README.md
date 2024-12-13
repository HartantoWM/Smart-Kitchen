# Smart-Kitchen

Welcome to the group documentation - C242PS459

  This project is designed to solve a solution to help users find food recipes from their ingredients. This documentation aims to help users understand, configure, and utilize this project easily.
  
** Backgrounder **
  In an era of ever-evolving technology, innovation in the digital field provides great opportunities to increase efficiency and convenience in everyday life. This project focuses on the development of the Smart Kitchen application, a technology-based solution that integrates machine learning, mobile application development, and cloud computing services. Through this approach, the project aims to provide a better experience in food management, waste reduction, and ease in finding food recipes that suit the user's needs.

1. Machine Learning
building models with TensorFlow.js using fine-tuned EfficientNetB3 for high-accuracy image classification. Feature       extraction is enhanced through VGG16 vectorization, ensuring robust preprocessing and efficient training. The model is optimized for mobile deployment, enabling seamless performance and scalability. This approach ensures a reliable and adaptive solution for classifying food ingredients, with future-proofing for dataset expansion and refinement.
notes :CNN, cosine similarity, pre trained model with fine tuning.

![Machine Learning - Documentation](https://github.com/user-attachments/assets/b1b9a0a8-5a28-417a-98a8-836c87905734)

2. Cloud Computing
Building a Smart Kitchen application backend to support login, registration, profile, food ingredient image scanning, recipe recommendations, and recipe details integrated with machine learning services and mobile applications. This backend is implemented using Google Cloud Platform (GCP) by utilizing Compute Engine to run the server and Firestore as data storage for recipe recommendation results. This solution is designed to ensure reliable communication between ML models, mobile applications, and backends to provide an optimal user experience in managing food ingredients and searching for recipes.

![Cloud Computing - Documentation](https://github.com/user-attachments/assets/1c14bca9-4158-4ed0-b760-8960b406fe0b)

3. Mobile Development
Develop an Android-based mobile application using Kotlin programming language that can help users find food recipes easily and quickly. The application will utilize machine learning technology to identify food ingredients sent through images photographed through mobile phones and provide appropriate recipe recommendations.

-- doc

Smart Kitchen App Usage Guide

1. Opening the App
Open the Smart Kitchen app on your device.

2. Login to Account
Enter your email and password to log in to the app.
If you don't have an account, follow these steps:
Go to the Register page.
Enter your username, email, and password.
Press the Register button.
After successfully registering, you will be directed to the Login page. Enter the registered email/username and password.

3. Main Page (Home)
After successfully logging in, you will enter the main page of the application.
On this page, there are various food recipe recommendations available.

4. Viewing Recipe Details
If you select one of the recipes, you will be directed to the recipe details page.
This page displays:
The ingredients of the food required.
How to cook the food in detail.

5. Using the Scan Feature
This feature allows users to get recipe recommendations based on the ingredients they have:
Take a photo of the ingredients using your device's camera.
Enter the Scan page.
Tap the Gallery icon to select an ingredient photo you have taken.
The app will process the image to analyze the ingredients.
Once the analysis is complete, the app will display the recipe recommendation results based on the available ingredients.



