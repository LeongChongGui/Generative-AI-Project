# Generative-AI-Project

# Airline Sentiment Analysis: Pre- vs Post-COVID Impact

## 📋 Project Overview
This project analyzes passenger sentiment from airline reviews before and after the COVID-19 pandemic. Using machine learning techniques, we investigate how passenger recommendations have changed and build an SVM model to predict whether passengers would recommend an airline based on various service factors during these two distinct periods.

## 🎯 Objective
To compare the performance of a Support Vector Machine (SVM) model in predicting airline recommendations before and after COVID-19, and to understand how the pandemic affected passenger sentiment and service priorities.

## 📊 Dataset
- **Source**: Airline review data with passenger ratings and text reviews
- **Key Features**: Flight dates, service ratings, review text, recommendation status
- **Time Periods**: Pre-COVID (before March 2020) and Post-COVID (after March 2020)
- **Target Variable**: Binary recommendation (Recommended/Not Recommended)

## 🔧 Methodology

### 1. Data Preprocessing
- **Date Conversion**: Convert flight dates to datetime objects
- **Data Segmentation**: Split data into pre-COVID and post-COVID periods
- **Noise Removal**: Eliminate duplicates, outliers, and irrelevant characters
- **Missing Value Handling**: Implement statistical imputation methods
- **Data Balancing**: Address class imbalance with resampling techniques

### 2. Feature Engineering
- **Feature Selection**: Identify key predictors of recommendation
- **Label Encoding**: Convert categorical variables to numerical
- **Feature Scaling**: Apply standardization for SVM compatibility

### 3. Model Development
- **Algorithm**: Support Vector Machine (SVM)
- **Hyperparameter Tuning**: Optimize C and gamma parameters
- **Training**: Separate models for pre-COVID and post-COVID data

### 4. Evaluation Metrics
- **Accuracy**: Overall prediction correctness
- **Precision**: Correct "recommended" predictions
- **Recall**: Actual "recommended" reviews correctly identified
- **F1-Score**: Balance between precision and recall
- **ROC-AUC**: Model discrimination capability
- **Confusion Matrix**: Visualization of predictions vs actuals

## 🛠️ Technology Stack
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Tools**: Jupyter Notebook, Git
- **GAI Assistance**: ChatGPT for code generation and optimization

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/airline-sentiment-analysis.git
cd airline-sentiment-analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the Analysis
Execute the notebooks in sequence:
1. `01_data_preprocessing.ipynb`
2. `02_feature_engineering.ipynb`
3. `03_model_training.ipynb`
4. `04_evaluation.ipynb`

## 🤖 GAI Integration
This project incorporates Generative AI tools to enhance the learning and development process:
- **Code Generation**: Automated implementation of common functions
- **Hyperparameter Optimization**: AI-assisted tuning suggestions
- **Error Debugging**: AI-powered troubleshooting assistance
- **Documentation**: Automated code explanation and documentation

## 📈 Key Findings
1. **Model Performance**: Comparison of SVM accuracy between pre- and post-COVID periods
2. **Feature Importance**: Identification of service factors most predictive of recommendations
3. **Sentiment Shift**: Analysis of how passenger priorities changed after COVID-19
4. **Temporal Patterns**: Seasonal or trend-based variations in airline satisfaction

## ⚖️ Ethical Considerations
1. **Data Privacy**: Anonymization of passenger information
2. **Bias Mitigation**: Addressing potential biases in review data and model predictions
3. **Transparency**: Clear documentation of AI-assisted development
4. **Academic Integrity**: Proper attribution of AI-generated code and concepts

## 📚 Learning Outcomes
This project demonstrates:
- End-to-end data science workflow
- SVM implementation and optimization
- Comparative analysis across temporal periods
- Ethical use of AI tools in academic work
- Critical evaluation of model performance and limitations

## 📝 License
This project is for academic purposes as part of NUS coursework.

## 🙏 Acknowledgments
- National University of Singapore for course materials and guidance
- Course instructors for project supervision
- Open-source Python community for development tools
- AI tool providers for educational support

---

*Note: This project was developed as part of an academic course at NUS, incorporating both traditional data science methods and AI-assisted development techniques.*
