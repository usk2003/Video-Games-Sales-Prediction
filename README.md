# Video Games Sales Prediction 🎮

This repository contains a project focused on predicting global video game sales using various machine learning models. By analyzing a comprehensive dataset, we explore the factors that influence video game sales and develop predictive models to estimate sales figures with high accuracy.

## 📂 Repository Link  
[Video Games Sales Prediction](https://github.com/usk2003/VideoGamesSalesPrediction)

---

## 📜 Project Overview  
Video game sales data from Kaggle was analyzed using machine learning techniques to understand the factors influencing sales. The project aims to assist stakeholders in the gaming industry by providing actionable insights and accurate predictions.

---

## 🎯 Goals  

1. Develop powerful machine learning models to predict global sales of video games.  
2. Explore and compare the performance of various regression models.  
3. Gain insights into key factors influencing video game sales for better decision-making.

---

## ⚙️ Methodology  

### Data Preprocessing  
- Handled missing values and ensured consistent data types.  
- Transformed categorical features like `Platform` and `Genre` into numerical values using Label Encoding.

### Model Development  
The following machine learning models were employed:  
- **K-Nearest Neighbors (KNN)**  
- **Multiple Linear Regression (MLR)**  
- **Decision Tree Regression (DTR)**  
- **Random Forest Regression (RFR)**  
- **Gradient Boosting Regression (GBR)**  

### Evaluation Metrics  
- Mean Squared Error (MSE)  
- R-squared Score  

---

## 🏆 Results  

The performance of all models was evaluated, and the **Gradient Boosting Regression** model was identified as the most effective for sales prediction.  

### Key Findings  
- Gradient Boosting Regression achieved the highest R-squared score, demonstrating superior predictive ability.  
- Insights from feature analysis revealed the significant impact of platform and genre on sales performance.

---

## 📊 Visualizations  

- Scatter plots comparing actual vs. predicted values for all models.  
- Bar chart showcasing R-squared scores for all models.  

---

## 🚀 Technologies Used  

- **Programming Language**: Python  
- **Libraries**:  
  - Pandas  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  

---
## 📂 Dataset Overview  

The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com). It provides detailed information about video games, including their platform, genre, release year, and sales data across various regions.

### 📊 Dataset Features  

The dataset contains the following columns:  

| **Column Name**      | **Description**                                                   |  
|-----------------------|-------------------------------------------------------------------|  
| `Name`               | Name of the video game.                                           |  
| `Platform`           | Platform on which the game was released (e.g., PS4, Xbox, PC).   |  
| `Year_of_Release`    | Year the game was released.                                       |  
| `Genre`              | Genre of the video game (e.g., Action, Sports, Strategy).         |  
| `Publisher`          | Publisher of the game.                                            |  
| `NA_Sales`           | Sales in North America (in millions of units).                   |  
| `EU_Sales`           | Sales in Europe (in millions of units).                          |  
| `JP_Sales`           | Sales in Japan (in millions of units).                           |  
| `Other_Sales`        | Sales in other regions (in millions of units).                   |  
| `Global_Sales`       | Total global sales (in millions of units).                       |  

### 🔍 Dataset Insights  

1. **Sales Data**:  
   The `Global_Sales` column serves as the target variable for this project. Regional sales (NA, EU, JP, Other) are analyzed to identify their contributions to global sales.  

2. **Categorical Features**:  
   Features like `Platform` and `Genre` were encoded to make them usable for machine learning models.  

3. **Missing Data**:  
   Missing values in `Year_of_Release` and `Publisher` were carefully handled during preprocessing to maintain data integrity.

4. **Temporal Trends**:  
   The dataset includes data spanning several years, allowing for the analysis of trends over time.  

---

### 📥 Dataset Source  

The dataset can be accessed on Kaggle: [Video Game Sales Dataset]((https://www.kaggle.com/datasets/gregorut/videogamesales)).

## 📧 Contact  

For questions or suggestions, feel free to reach out:  
[GitHub Profile](https://github.com/usk2003)  

🌟 If you found this project helpful, please give it a ⭐ on GitHub!

## 📖 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/usk2003/VideoGamesSalesPrediction.git
   cd VideoGamesSalesPrediction

2. Run the script in Jupyter Notebook or in Google Colab.
