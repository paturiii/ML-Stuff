# 🏡 Housing Price Prediction with Linear Regression  

This project demonstrates a **Linear Regression model built from scratch** using **Gradient Descent** to predict housing prices based on multiple features.  

## 📌 Project Overview  
- **Dataset**: `Housing.csv`  
- **Features**:  
  - `area`  
  - `bedrooms`  
  - `bathrooms`  
  - `stories`  
- **Target**: `price`  

The model is trained with **gradient descent** and evaluated using:  
- Mean Squared Error (MSE)  
- R² Score  

## ⚙️ Tech Stack  
- Python 3  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn (metrics only)  

## 🚀 How It Works  
1. Load dataset and standardize features.  
2. Initialize weights and bias.  
3. Apply **gradient descent** to minimize error.  
4. Track and visualize **loss over iterations**.  
5. Evaluate predictions using MSE and R².  
6. Plot relationships such as *Actual Price vs Area*.  

## 📊 Results  
- Prints **MSE** and **R² Score** after training.  
- Shows a **loss curve** to illustrate training progress.  
- Scatter plots for data visualization.  

## ▶️ Running the Project  
Clone the repository and open the notebook:  
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
jupyter notebook regression.ipynb
