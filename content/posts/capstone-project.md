---
title: "Marine AIS Capstone Project"
date: 2023-08-20T12:18:45+10:00
draft: false 
---

## Introduction
In the final leg of my university bachelor's degree, I embarked on an intriguing capstone project that combined my passion for technology and fascination with marine data. The goal was to develop a powerful yet user-friendly Python Flask application capable of uploading and analyzing CSV files containing Automatic Identification System (AIS) data, all with the aim of calculating the number of vessels passing through a designated maritime area. This project brought together a medley of technologies, including Python Flask, Dropzone.js, and Docker, resulting in an application that demonstrated the fusion of data analysis, web development, and containerization.

## Understanding the Challenge
Marine AIS data is a goldmine of information about vessel movements, enabling maritime authorities and researchers to gain insights into traffic patterns, route planning, and safety measures. Our challenge was to create an application that could process and analyze these data-rich CSV files to deduce the number of vessels traversing a specific geographic region. This required not only a solid understanding of data manipulation but also the creation of an intuitive interface to cater to users from various backgrounds.

## The Power of Python Flask
Python Flask emerged as the framework of choice for building the application's backend. Flask's lightweight nature, combined with its flexibility, made it an excellent candidate for handling the intricate logic behind AIS data analysis. The Flask application was designed to accept uploaded CSV files, parse their content, and apply the necessary algorithms to extract meaningful insights.

## The Web Interface: Dropzone.js
A crucial component of our project was the user interface, where users could effortlessly upload their CSV files. To achieve this, we integrated Dropzone.js, a popular JavaScript library that provided an intuitive drag-and-drop file upload experience. Dropzone.js seamlessly integrated with our Flask backend, allowing users to visualize their uploaded files and triggering the analysis process.

## Processing and Analysis
Once a CSV file was uploaded, the Flask app worked behind the scenes to process and analyze the AIS data. We employed Python's data manipulation libraries, such as pandas, to cleanse and organize the data. By filtering the data based on geographic coordinates, we could determine vessel movements within the specified area. The algorithm efficiently calculated vessel counts, and the results were then presented to users in a clear and comprehensible format.

## Containerization with Docker
To simplify deployment and ensure consistency across different environments, we turned to Docker. Docker containers encapsulated the entire application along with its dependencies, making it easy to deploy on different systems without worrying about compatibility issues. This approach streamlined the deployment process and allowed us to focus more on improving the app's functionality.

## Conclusion
The capstone project turned out to be an incredible journey into the realms of data analysis, web development, and containerization. The Python Flask application we built successfully merged these disciplines to create a user-friendly tool for maritime AIS data analysis. By combining technologies like Dropzone.js and Docker, we not only enhanced the application's usability but also ensured its efficient deployment.

As I reflect on this project, I am reminded of the power of technology to transform complex data into actionable insights. The experience taught me not only about the technical aspects of development but also the importance of designing with users in mind. This project stands as a testament to the symbiotic relationship between technology and creativity, resulting in a tool that has the potential to contribute significantly to maritime safety and research.

