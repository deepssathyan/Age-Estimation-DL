# Age Estimation from Facial Images: Predictive Analytics  
  
**Date:** December 2024  
  
## Overview  
  
This project focuses on developing an age estimation system from facial images using deep learning techniques. The goal is to improve predictive accuracy by optimizing model architecture and hyperparameters. Key improvements include:  
  
- **ResNet-18 model for age prediction:** A scalable implementation to effectively predict age from facial images.  
- **Bayesian hyperparameter tuning:** Achieved a 20% reduction in Mean Absolute Error (MAE) through effective hyperparameter optimization.  
- **Training efficiency improvements:** Implemented Cyclic Learning Rate and ReduceLROnPlateau in PyTorch to boost training efficiency by 17%.  
- **Robust evaluation:** Utilizes comprehensive evaluation metrics including MAE and confusion matrices for model validation.  
  
## Tech Stack  
  
- Python  
- PyTorch  
- TensorFlow  
- scikit-learn  
- Spark  
- AWS  
  
## Project Structure  
  
- `Final_DL.ipynb`: Jupyter Notebook containing the complete implementation including data loading, model training, hyperparameter tuning, and evaluation.  
- Additional scripts and modules may be added in the future.  
  
## Highlights  
  
- **Model Architecture:**    
  The project utilizes a ResNet-18 based architecture adapted for age estimation tasks.  
    
- **Hyperparameter Tuning:**    
  Bayesian optimization techniques were employed to optimize the model's parameters, reducing the error significantly.  
  
- **Training Optimizations:**    
  Advanced training techniques, such as Cyclic Learning Rate and ReduceLROnPlateau, have been used to ensure faster and efficient training.  
  
- **Evaluation Metrics:**    
  The performance of the model is evaluated using metrics like MAE and confusion matrices to ensure robust results.  
  
## Setup and Usage  
  
1. **Clone the Repository:**  
   ```bash  
   git clone https://github.com/your_username/your_repository.git  
   cd your_repository

## Set Up Your Environment

2. **Create a virtual environment and install the necessary dependencies:**
   ```python -m venv env  
   source env/bin/activate   # On Windows: env\\Scripts\\activate  
   pip install -r requirements.txt

3. **Run the Notebook:**

Open `Final_DL.ipynb` in Jupyter Notebook or Google Colab and execute the cells to run the project.


**Contributing**
Contributions are welcome! Fork this repository and submit a pull request with any improvements, bug fixes, or new features.

**License**
This project is licensed under the MIT License.
