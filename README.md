# Azure_Vision_Platform

# **ML-Powered Image Accessibility & Search**
### **CS 594 - Homework Assignment 1**
**Name:** Varun Phanindra Shrivathsa  
**UIN:** 678714612  
**GitHub Repository:** [Azure Vision Platform](https://github.com/varunpshrivathsa/Azure_Vision_Platform)  

---

## **1. Running the Moments Application**
### **Dependencies Required**
- `pdm`
- `pip`
- `Flask`

### **Steps to Run**
```sh
# Clone the repository
git clone https://github.com/varunpshrivathsa/Azure_Vision_Platform.git
cd Azure_Vision_Platform

# Install dependencies
pip install pdm
pdm install

# Create dummy data, users, and upload 30 random images
pdm run flask lorem  

# Start the Flask application
pdm run flask run

2. Creating a Microsoft Azure Vision AI Instance
Steps to Set Up
Login to Microsoft Azure with a Student Mail ID.

Create a Vision AI Instance and copy:

API Key
Endpoint URL
Store Credentials Securely in .env File
Create a .env file in the root directory (Do not push this to GitHub):
AZURE_VISION_ENDPOINT="https://<your-region>.api.cognitive.microsoft.com/"
AZURE_VISION_KEY="your-vision-api-key"

