# Multiple Disease Prediction Application

This repository contains a machine learning application for predicting multiple diseases. It includes datasets, Colab files for model training, and the main application file.

## Getting Started

Follow these steps to set up and run the application:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mishrark0145/Disease-Prediction-Application.git
   cd Disease-Prediction-Application
   ```
2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Update file paths:**
   Open multipleDiseasePred.py and update the file paths for the .sav model files to match your 
   local directory structure.

4. **Run the application:**

   ```bash
   streamlit run "{working_directory}\multipleDiseasePred.py"
   ```
## Repository Structure

-> Dataset/: Contains the datasets used for training the models  
-> Colab files to train models/: Jupyter notebooks for model training  
-> saved_models/: Saved model files (.sav)  
-> multipleDiseasePred.py: Main application file  
-> requirements.txt: List of Python dependencies
   
## Model Training
The Colab files in the Colab files to train models/ directory can be used to train the disease prediction models. These files provide step-by-step instructions for data preprocessing, model selection, training, and evaluation.

## Web Application

You can access the live web application here: [Multiple Disease Prediction Application](https://webappmultiplediseaseprediction.streamlit.app/)
