# Deploying a Live Weather App on Cloud Run

Within this repository, you'll discover the essential source code and deployment files needed to orchestrate a live weather app on Cloud Run using Docker. 🌐🚀

## Overview

This project follows a streamlined DevOps workflow, ensuring a seamless process from development to deployment. The key components involved are GitHub, Google Cloud Build, Docker, Artifact Registry, and Cloud Run.

## Tools and Technology

- **Docker:** 🐳
- **Cloud Run:** ☁️
- **GitHub:** 🐙
- **Python:** 🐍
- **Google Cloud Build:** 🛠️
- **OpenWeather API:** 🌦️

## Workflow Steps:

1) API Key Creation:
Obtain an API key from the OpenWeather API to fetch real-time weather data.

2)Python Application Development:
Develop a Python application that interacts with the OpenWeather API to retrieve and process weather data.

3)Local Testing:
Test the Python application locally to ensure it functions as expected.

4)Container Testing:
Containerize the application using Docker and perform local testing on the container to validate its behavior.

5)Push to Artifact Registry:
Push the Docker container image to Google Artifact Registry for secure storage and management.

6)Deploy on Cloud Run:
Deploy the containerized application on Google Cloud Run, enabling scalable and efficient hosting.

7)Automate CI/CD Process:
Implement a CI/CD pipeline using Google Cloud Build. The process is automated via build triggers, which monitor the GitHub repository for changes, ensuring continuous integration and deployment.
