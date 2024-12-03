```markdown
# Israeli Coin Detection Project

This project leverages the YOLOv8 model, a cutting-edge object detection architecture, to identify and classify Israeli coins with remarkable accuracy. The model was trained on a custom dataset of Israeli coins using Roboflow for dataset preparation and hosting.

## Project Overview

- **Objective**: Detect and classify Israeli coins in images, achieving a high prediction accuracy of 91%.
- **Model**: YOLOv8 (Ultralytics) for robust object detection.
- **Dataset**: Prepared using Roboflow, containing annotated images of Israeli coins.

## Features

- **High Accuracy**: Achieves an impressive prediction accuracy of 91% on the test set.
- **Custom Dataset**: Trained on a diverse dataset of Israeli coins.
- **Adaptability**: Easily adaptable for other object detection tasks.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Matanitzan/Israeli-Coin-Detection.git
   cd Israeli-Coin-Detection
   ```

2. **Install Dependencies**
   Ensure you have Python 3.7+ installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Add the API Key**
   Create a `.env` file in the root directory and add your Roboflow API key:
   ```env
   ROBOFLOW_API_KEY=your_api_key_here
   ```

4. **Run the Notebook**
   Open `Israeli_coin_detected.ipynb` in Jupyter Notebook or Google Colab and follow the steps to train and evaluate the model.

## How It Works

1. **Data Preparation**:
   - Dataset hosted on Roboflow.
   - Automatically fetched via the API during training.

2. **Training**:
   - Model is fine-tuned on the Israeli coin dataset.
   - YOLOv8's training pipeline is utilized.

3. **Evaluation**:
   - Achieves a 91% prediction accuracy.
   - Confusion matrix and additional metrics are provided.

## Important Notes

- The `.env` file containing the Roboflow API key is ignored in the repository for security purposes. Ensure you do not share your API key publicly.
- If you'd like to use the dataset locally, it is included in the `Dataset` folder.

## Results

The trained model demonstrates:
- High accuracy in classifying coin denominations.
- Robustness across different image qualities and conditions.


```

