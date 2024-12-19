
Bank Churn Prediction

Project Overview
This project is a Neural Network-based model to predict customer churn in banks using Python, TensorFlow, and Keras. The project includes data analysis, visualization, model development, and evaluation to identify customers likely to churn, enabling banks to take proactive measures.

Table of Contents
Project Description
Tools & Technologies Used
Data Analysis
Model Development
Project Structure
How to Use
Results
Contributing
License


## Table of Contents
Project Description

Tools & Technologies Used

Data Analysis

Model Development

Project Structure

How to Use

Results

Contributing

License
## Project Description

The project uses machine learning techniques and neural networks to analyze a customer churn dataset. Key steps include:

Exploratory Data Analysis (EDA)

Feature Selection

Building Neural Network Models with different optimizers (SGD, Adam)

Visualizing loss curves and confusion matrices

Evaluating model performance on imbalanced data


## Tools & Technologies Used
Languages: Python
Libraries:

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: TensorFlow, Keras, Scikit-learn

Environment: Jupyter Notebook, Google Colab

Version Control: GitHub
## Data Analysis

Univariate Analysis: Understanding individual features like age, balance, credit score, and tenure.

Bivariate Analysis: Analyzing feature relationships, such as "Exited vs Geography" and "Exited vs Balance".

Correlation Heatmap: Visualizing correlations among numerical features.

Key Visualizations Saved:


Univariate plots (Age, Balance, CreditScore, etc.)

Bivariate plots (Exited vs Features)

Confusion Matrices

Loss Curves
## Model Development

Neural Network:

Input: Preprocessed data

Layers: Dense layers with activation functions (ReLU, Sigmoid)

Optimizers Tested: SGD, Adam

Loss Function: Binary Cross-Entropy

Evaluation:

Loss curves for training and validation

Confusion matrices for prediction results
## Deployment

Prerequisites
Install Python (3.8 or above)

Install required libraries using:

pip install pandas numpy matplotlib seaborn tensorflow keras

Steps to Run the Code
Clone the repository:

git clone https://github.com/DeyPoulomi-cmd/bank-churn-prediction.git
cd bank-churn-prediction

Open Jupyter Notebook:

Run Bank_Churn_Prediction_Full_code.ipynb to view and execute the code step by step.
Visualize Results:

Loss curves, confusion matrices, and data visualizations will be saved in the images/ folder.










## Results

Model Performance: The Neural Network achieved an accuracy of X% with room for improvement on imbalanced data.

Insights:
Customers with low balance and high tenure are more likely to churn.

Geography and Credit Score are significant factors influencing churn.
## Contributing

Contributions are welcome!

Fork the repository.

Create a new branch: git checkout -b feature/YourFeatureName.

Commit your changes and push: git commit -m "Add feature" > git push origin feature/YourFeatureName.

Submit a pull request.
## License

This project is licensed under the MIT License.
## Contact

For any questions or feedback, please reach out:

GitHub: DeyPoulomi-cmd
## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

Building the Bank Churn Prediction project was an enriching experience that helped me gain deeper insights into both the technical and analytical aspects of data science and machine learning.

Understanding Customer Churn:

I learned how crucial it is to analyze customer behavior, especially in industries like banking, where predicting churn can make or break business success. Through this project, I understood the impact of features like balance, credit score, and tenure on customer decisions.

Working with Imbalanced Data:

One of the major challenges I faced was class imbalance—the dataset had far more non-churning customers compared to churning ones. This imbalance initially caused the model to predict most customers as "non-churners," ignoring the minority class. To overcome this, I tried techniques like adjusting class weights in the neural network and evaluation metrics such as F1-Score and confusion matrices to measure performance beyond accuracy.

Neural Network Optimization:

Tuning neural networks was another challenge. I experimented with different optimizers like SGD and Adam, which helped me understand how gradient descent methods affect training performance. Observing loss curves taught me to identify overfitting and underfitting, enabling me to make informed adjustments to the model architecture.

Data Visualization and EDA:

I realized that Exploratory Data Analysis (EDA) is the backbone of any machine learning project. By visualizing relationships, such as "Exited vs Geography" or "Exited vs Balance," I uncovered patterns that were not obvious initially. Visualizing a correlation heatmap further helped me identify redundant or less useful features.

Project Workflow and Organization:

Organizing the project properly—such as saving visualizations in folders, documenting my code clearly, and structuring files in GitHub—was a new habit I developed. It made the project easy to revisit and share with others.

Challenges and How I Overcame Them

Overfitting and Poor Generalization:

Challenge: Initially, the model performed very well on the training set but failed to generalize on the validation data.
Solution: I implemented Dropout layers and regularization to reduce overfitting. Monitoring the loss curves helped me adjust the number of epochs.

Class Imbalance:

Challenge: The dataset had significantly fewer positive cases (churning customers), which biased the model predictions.
Solution: I experimented with class weights and adjusted the threshold for predictions. I also evaluated performance using metrics like F1-Score and confusion matrices rather than relying on accuracy alone.

Choosing the Right Optimizer:

Challenge: I initially struggled to decide between optimizers like SGD and Adam because training convergence varied.
Solution: I compared the results by plotting loss curves and found that Adam optimized faster and performed better for this dataset.

Learning GitHub for Collaboration:

Challenge: Managing code, creating folders, and uploading images in GitHub was a bit overwhelming at first since I wasn’t very familiar with version control tools.
Solution: I took small steps—starting with uploading individual files, creating structured folders, and updating commits. I now feel much more confident working with GitHub.

Key Takeaway

This project taught me the importance of problem-solving, attention to detail, and consistency in the machine learning workflow. From data cleaning and analysis to model evaluation and deployment preparation, I learned to approach challenges systematically.

Most importantly, I realized that projects like these are not just about building models but about extracting meaningful insights and presenting them in a clear, actionable manner.







## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@PoulomiDey](https://github.com/DeyPoulomi-cmd)


## Deployment

To deploy this project run

```bash
  pip install pandas numpy matplotlib seaborn tensorflow keras
```

Steps to Run the Code Clone the repository:

git clone https://github.com/DeyPoulomi-cmd/bank-churn-prediction.git cd bank-churn-prediction

Open Jupyter Notebook:

Run Bank_Churn_Prediction_Full_code.ipynb to view and execute the code step by step. Visualize Results:

Loss curves, confusion matrices, and data visualizations will be saved in the images/ folder.





## Documentation

[Documentation](https://linktodocumentation)


## 🔗 Links
[![portfolio](https://github.com/DeyPoulomi-cmd)](https://github.com/DeyPoulomi-cmd)
[![linkedin](https://www.linkedin.com/in/poulomi-d-209aa2218/)](https://www.linkedin.com/)


