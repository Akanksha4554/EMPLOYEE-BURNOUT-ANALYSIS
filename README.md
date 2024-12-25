---

<h1 align="center">Employee Burnout Analysis and Prediction</h1>

---

## 📝 Overview  
The **Employee Burnout Analysis** project provides a data-driven approach to understanding and predicting factors that contribute to employee burnout. By leveraging advanced analytics and machine learning models, this repository empowers organizations with actionable insights to enhance workplace well-being, reduce stress, and improve overall productivity.

---

## 🔑 Key Features  
- **Data Exploration & Preprocessing**  
   - Comprehensive handling of missing data, outliers, and feature transformations.  
   - Dataset includes attributes such as job designation, resource allocation, mental fatigue score, company type, WFH setup, and gender.  

- **Machine Learning Models**  
   - Implementation of Linear Regression, Support Vector Regression (Linear and RBF Kernels), and Random Forest Regressor for predictive analysis.  
   - Model performance evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared Score.  

- **Actionable Insights**  
   - Highlights critical factors contributing to employee burnout.  
   - Offers data-driven recommendations for HR teams to design targeted intervention programs.  

- **Visualization**  
   - Interactive and static visualizations using Seaborn and Matplotlib to uncover meaningful patterns, trends, and correlations.  

---

## 📊 Dataset  
The dataset includes the following key features:  
- **Designation**: Role and hierarchy within the organization.  
- **Resource Allocation**: Efficiency of resource utilization based on project demands.  
- **Mental Fatigue Score**: A numeric indicator of stress levels.  
- **Company Type**: Classification as service-based or product-based.  
- **WFH Setup Available**: Availability of remote work options.  
- **Gender**: Demographic attribute indicating male or female employees.  

---

## 🏆 Results  

#### Model Performance Metrics:
1. **Linear Regression**:  
   - **Mean Squared Error (MSE)**: 0.0071  
   - **Root Mean Squared Error (RMSE)**: 0.0845  
   - **Mean Absolute Error (MAE)**: 0.0752  
   - **R-squared Score**: 0.9897  

2. **Support Vector Machine (Linear Kernel)**:  
   - **Mean Squared Error (MSE)**: 0.0077  
   - **Root Mean Squared Error (RMSE)**: 0.0878  
   - **Mean Absolute Error (MAE)**: 0.0760  
   - **R-squared Score**: 0.9888  

3. **Support Vector Machine (RBF Kernel)**:  
   - **Mean Squared Error (MSE)**: 0.0127  
   - **Root Mean Squared Error (RMSE)**: 0.1128  
   - **Mean Absolute Error (MAE)**: 0.0919  
   - **R-squared Score**: 0.9816  

These results demonstrate that **Linear Regression** outperforms other models, achieving the highest accuracy in predicting burnout levels.

---

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Key Libraries**:  
   - Machine Learning: Scikit-learn  
   - Data Analysis: Pandas, NumPy  
   - Data Visualization: Seaborn, Matplotlib  
   - Web Framework: Flask  

---

## 🚀 Installation  

To set up the project locally, follow these steps:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/employee-burnout-analysis.git
   cd employee-burnout-analysis
   ```  

2. Install the dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Run the Flask app:  
   ```bash
   python app.py
   ```  

4. Access the web app at:  
   ```
   http://127.0.0.1:5000/
   ```  

---

## 🎯 Usage  

1. Explore the **`EBAProject.ipynb`** notebook for in-depth data analysis and model building.  
2. Use the web application to input employee data and predict burnout rates.  
3. Leverage actionable insights to optimize resource allocation and implement stress-reducing strategies.  

<div align="center">
  <img src="https://github.com/yourusername/employee-burnout-analysis/assets/example-results" alt="Prediction Results" width="700">
</div>

---

## 🌐 Applications  

- **Identifying Workplace Stressors**: Pinpoint the critical factors contributing to burnout.  
- **Improved Resource Management**: Optimize workloads to reduce stress and improve efficiency.  
- **Employee Wellness Programs**: Develop tailored wellness initiatives based on data-driven insights.  

---

## 🤝 Contribution  

Contributions are welcome! Fork the repository, make improvements, and submit a pull request to help enhance this project.  

---

## 📄 License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

### ⭐ If you found this repository helpful, please give it a star!  

Elevate workplace well-being and productivity with data-driven insights ❤️.  

---
