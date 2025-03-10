# Mycotoxin Prediction using Hyperspectral Imaging Data

**Enhance agricultural safety with cutting-edge machine learning techniques!**

This project leverages hyperspectral imaging data to predict mycotoxin levels in corn samples. By processing spectral reflectance data, reducing its dimensions via PCA, and training a 1D CNN for regression (with an optional classification adaptation), this solution provides actionable insights into potential contamination levels.

## Features

- **Data Exploration & Preprocessing**  
  - Load and inspect hyperspectral data for missing values and inconsistencies.
  - Standardize spectral reflectance values across multiple wavelength bands.
  - Visualize spectral characteristics using line plots and heatmaps.

- **Dimensionality Reduction**  
  - Apply Principal Component Analysis (PCA) to reduce feature dimensions.
  - Visualize the reduced data with 2D scatter plots and assess variance explained.

- **Model Training & Evaluation**  
  - Build and train a 1D Convolutional Neural Network (CNN) for regression.
  - Evaluate model performance with MAE, RMSE, and R² score.
  - (Optional) Adapt the model for classification with Accuracy, Precision, Recall, F1-Score, and a confusion matrix.
 
  - 
## Prerequisites

- **Python 3.x**
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow (with Keras)

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/ImagoAI-Task.git
   cd your-repo-name

2. **Create and Activate a Virtual Environment:**
   
   ```bash
    python -m venv venv
    source venv/bin/activate   # For Windows: venv\Scripts\activate
   
3. **Install Dependencies:**

    ```bash
    Copy
    pip install -r requirements.txt

4. **Running the Application:**
   
   Jupyter Notebook:

      ```bash
      Copy
      jupyter notebook notebook.ipynb
    
  Python Script:
  Alternatively, run the script directly:

      Copy
      python script.py

## Usage Examples

**Data Visualization:**
- Inspect average spectral reflectance trends with line plots.
- Explore feature correlations via heatmaps.

**Dimensionality Reduction:**
- Visualize the 2D PCA-reduced data to understand clustering and variance.

**Model Training:**
- Train the 1D CNN to predict mycotoxin levels (vomitoxin_ppb).
- Evaluate regression metrics and compare actual vs. predicted values.
- (Optional) Convert to a classification problem and assess performance with classification metrics and a confusion matrix.

## Contributing
Contributions are welcome! If you have suggestions, improvements, or find issues, please open an issue or submit a pull request.

## Contact
For any questions or feedback, please reach out to [rahulrelhan13@gmail.com](mailto:rahulrelhan13@gmail.com).



