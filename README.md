# EMPLOYEE-BURNOUT-ANALYSIS
# Overview
The Employee Burnout Analysis project provides a data-driven approach to understanding and predicting factors leading to employee burnout. By leveraging machine learning models and advanced analytics, this repository offers actionable insights for organizations to improve workplace well-being and productivity.
After analyzing the uploaded files, I'll revise the description and incorporate verified results for the **Employee Burnout Analysis** project. Here's the updated version:

---

### Key Features
- **Data Exploration & Preprocessing**  
   - Comprehensive handling of missing data, outliers, and feature transformations.
   - Dataset includes attributes like job designation, resource allocation, mental fatigue score, company type, WFH setup, and gender.  

- **Machine Learning Models**  
   - Linear Regression, Support Vector Regression, and Random Forest Regressor for predictive analysis.  
   - Model evaluation with metrics including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared Score.  

- **Actionable Insights**  
   - Highlights critical factors contributing to employee burnout.  
   - Offers insights for HR and management to design intervention programs.  

- **Visualization**  
   - Interactive and static visualizations using Seaborn and Matplotlib to uncover data trends and correlations.  

---

### Dataset  
The dataset includes key features:
- **Designation**: Role and hierarchy in the organization.  
- **Resource Allocation**: Allocation of resources based on project demands.  
- **Mental Fatigue Score**: A numeric representation of stress levels.  
- **Company Type**: Service or product-based organization.  
- **WFH Setup Available**: Availability of remote working infrastructure.  
- **Gender**: Male or Female.

---

### Results  
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

These results demonstrate that Linear Regression outperforms other models in predicting burnout levels with high accuracy.

---

### Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
   - **Machine Learning**: Scikit-learn  
   - **Data Analysis**: Pandas, NumPy  
   - **Visualization**: Seaborn, Matplotlib  
   - **Web Framework**: Flask  

---

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/employee-burnout-analysis.git
   cd employee-burnout-analysis
   ```
2. Install dependencies from the `requirements.txt`:  
   ```bash
   pip install -r requirements.txt
   ```

---

### Usage  
1. Open the **`EBAProject.ipynb`** Jupyter Notebook for a step-by-step walkthrough of the analysis.
2. Optionally, launch the Flask web app for an interactive dashboard.

---

### Applications  
- Identifying key stressors in the workplace and optimizing resource allocation.  
- Designing personalized wellness programs.  
- Supporting HR teams in creating a healthier and more productive environment.  

---

### Contribution  
Contributions are welcome! Fork the repository, make changes, and submit a pull request.  

---

### License  
This project is licensed under the MIT License.  

---

