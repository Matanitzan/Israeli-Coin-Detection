Israeli Coin Detection Project
This project utilizes YOLOv8, an advanced object detection model, to identify and classify Israeli coins in images with a high accuracy rate of 91%. By leveraging a custom dataset and optimized training, this project showcases the practical applications of deep learning for precise object detection tasks.

Features
High Accuracy: Achieves 91% accuracy in predicting coin types in images.
Custom Dataset: Trained on a dataset of Israeli coins.
YOLOv8 Implementation: Employs state-of-the-art object detection techniques.
Setup Instructions
Prerequisites
Python 3.8 or later
Install required packages:
bash
Copy code
pip install ultralytics python-dotenv
Environment Variables
Store your API key securely in a .env file:

Create a .env file in the project directory.
Add your API key:
makefile
Copy code
ROBOFLOW_API_KEY=your_api_key_here
Data
The dataset is stored in the Dataset folder.
Alternatively, access it using the RoboFlow API (requires API key).
Usage
Clone this repository:
bash
Copy code
git clone https://github.com/Matanitzan/Israeli-Coin-Detection.git
cd Israeli-Coin-Detection
Ensure the .env file is properly configured.
Run the notebook:
bash
Copy code
jupyter notebook Israeli_coin_detected.ipynb
Key Files
Israeli_coin_detected.ipynb: Main notebook for training, testing, and evaluating the model.
Dataset folder: Contains the dataset for model training and validation.
