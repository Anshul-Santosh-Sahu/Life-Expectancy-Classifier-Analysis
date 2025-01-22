# Life Expectancy Classification Analysis  

This project involves applying and comparing various classification algorithms on a selected dataset to analyze and predict outcomes effectively.  

## Dataset  
The dataset used for this project is titled **Life Expectancy Data**. It contains various health, economic, and demographic indicators for different countries, which are used as features to predict outcomes.  

## Project Workflow  
1. **Data Preprocessing**  
   - Loaded and cleaned the dataset to handle missing values, outliers, and categorical data.  
   - Performed exploratory data analysis (EDA) to understand the relationships between variables.
  
2. **Train-Test Split**
   - Split the dataset into training and testing sets, typically with a ratio like 80-20 or 70-30.

3. **Classification Algorithms Applied**  
   - Logistic Regression (LR)  
   - Naive Bayes (NB)  
   - K-Nearest Neighbors (KNN)  
   - Decision Tree (DT)  
   - Random Forest (RF)  
   - K-Means Clustering  

4. **Evaluation Metrics**  
   The performance of each algorithm was evaluated using the following classification metrics:  
   - **Accuracy**  
   - **Precision**  
   - **Recall**  
   - **F1-Score**  

5. **Comparison**  
   The results of the classification algorithms were compared in a table format, summarizing the recall, precision, F1-score, and accuracy for each algorithm.  

## Repository Structure  
- **LifeExpectancy.ipynb**: Jupyter Notebook containing the implementation of the project.
- **LifeExpectancy.pdf**: Detailed documentation and additional information related to the project. 
- **Life Expectancy Data.csv**: Dataset used for the analysis.  
- **README.md**: Project documentation.  

## How to Run the Project  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Anshul-Santosh-Sahu/Life-Expectancy-Classifier-Analysis.git
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd life-expectancy-classification  
   ```  
3.Open the Jupyter Notebook and run the cells sequentially:  
   ```bash  
   jupyter notebook LifeExpectancy.ipynb  
   ```  

## Results  
The table below summarizes the performance of each classification algorithm:  

| Algorithm       | Accuracy | Precision | Recall | F1-Score |  
|-----------------|--------|-----------|----------|----------|  
| Logistic Regression |  0.755102   | 0.815873       | 0.755102      | 0.755959      |  
| Naive Bayes       | 0.988095    | 0.986071       | 0.988095      | 0.985733      |  
| K-Nearest Neighbors | 0.615646    | 0.690063       | 0.615646      | 0.619155      |  
| Decision Tree     | 0.976190    | 0.978225       | 0.976190      | 0.974226      |  
| Random Forest     | 0.994898    | 0.992687       | 0.994898      | 0.993445      |  
| K-Means Clustering | 0.005102    | 0.000027       | 0.005102      | 0.000054      |  

## Contributing  
Feel free to fork the repository and make contributions. Open a pull request for any enhancements or bug fixes.  

## License  
This project is licensed under the MIT License.  
