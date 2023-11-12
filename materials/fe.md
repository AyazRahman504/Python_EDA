<a href="https://github.com/drshahizan/Python_EDA/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/Python_EDA" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/Python_EDA/network/members"><img src="https://img.shields.io/github/forks/drshahizan/Python_EDA" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/Python_EDA/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/Python_EDA" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/Python_EDA/issues"><img src="https://img.shields.io/github/issues/drshahizan/Python_EDA" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/Python_EDA/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/Python_EDA?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2FPython_EDA&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

🌟 Hit star button to save this repo in your profile

# Feature Engineering in Data Science

Feature engineering is a **crucial step** in the data science and machine learning workflow that involves **creating, transforming, and selecting relevant features** or variables from raw data to improve the performance of predictive models. It is an **art** as well as a **science**, where **domain knowledge, creativity, and statistical techniques** come together to extract meaningful information from the data.

<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*CyK1miQfy1OHmv2wUcjT1w.png"  height="200" />
</p>


## Why is Feature Engineering Important?

Feature engineering is important for several reasons:

1. **Improving Model Performance**: Well-engineered features can **significantly enhance the performance** of machine learning models by providing them with **relevant and informative input**.

2. **Reducing Dimensionality**: By selecting or creating the right features, you can **reduce the dimensionality** of the data, making it easier to work with and reducing the risk of **overfitting**.

3. **Interpretable Models**: Feature engineering can make models more **interpretable**, allowing us to gain insights into the **underlying patterns and relationships** in the data.

4. **Handling Missing Data**: Feature engineering techniques can help address **missing data issues**, making the data more suitable for analysis.

## Feature Engineering Techniques

There are various techniques and methods for feature engineering, including:

### 1. **Feature Selection**

Feature selection involves choosing the **most relevant features** and discarding irrelevant ones. This can be done using **statistical tests**, **feature importance scores**, or **domain knowledge**.

### 2. **Feature Extraction**

Feature extraction involves creating new features by applying **mathematical transformations** to the existing data. Common techniques include **Principal Component Analysis (PCA)**, **Singular Value Decomposition (SVD)**, and **t-Distributed Stochastic Neighbor Embedding (t-SNE)**.

### 3. **One-Hot Encoding**

One-hot encoding is used to convert **categorical variables** into binary (0/1) features, allowing machine learning models to work with **categorical data**.

### 4. **Binning and Discretization**

Binning involves grouping continuous variables into **bins or intervals**, while discretization converts continuous variables into **discrete categories**, making them more amenable to analysis.

### 5. **Feature Scaling**

Scaling ensures that features are on a **similar scale**, preventing some features from **dominating others**. Common scaling techniques include **Min-Max scaling** and **Z-score normalization**.

### 6. **Time Series Features**

For time series data, creating features like **moving averages**, **lag values**, or **seasonal decomposition** can provide valuable information for modeling.

### 7. **Text Feature Engineering**

In natural language processing, text data can be transformed using techniques like **TF-IDF (Term Frequency-Inverse Document Frequency)** or word embeddings (e.g., **Word2Vec**, **GloVe**).

## Steps in Feature Engineering

Feature engineering is a systematic process that involves several key steps to prepare and create relevant features from raw data. These steps are crucial for building effective predictive models in data science. The primary steps involved in feature engineering:

1. **Data Collection**: The first step is to collect the raw data from various sources, which may include databases, APIs, files, or other data repositories. High-quality data is the foundation of effective feature engineering.

2. **Exploratory Data Analysis (EDA)**: Before diving into feature engineering, it's essential to perform exploratory data analysis. EDA involves understanding the data's structure, distribution, missing values, outliers, and relationships between variables. This helps in identifying potential areas for feature engineering.

3. **Data Preprocessing**: Data preprocessing includes cleaning the data, handling missing values, and dealing with outliers. Imputing missing data and transforming variables to address skewness or outliers can significantly impact feature quality.

4. **Feature Selection**: In this step, you decide which features are most relevant for your modeling task. Feature selection techniques can be based on statistical tests, feature importance scores, or domain knowledge. The goal is to reduce dimensionality by retaining only the most informative features.

5. **Feature Extraction**: Feature extraction involves creating new features from the existing ones. This can be achieved through various mathematical transformations, such as principal component analysis (PCA), singular value decomposition (SVD), or dimensionality reduction techniques like t-distributed stochastic neighbor embedding (t-SNE).

6. **Feature Engineering**: This is the heart of the feature engineering process. It includes creating new features based on domain knowledge, understanding the problem, and applying creative transformations to enhance the data's predictive power. For example, generating interaction terms, polynomial features, or time-based features for time series data.

7. **Encoding Categorical Variables**: Categorical variables often need to be encoded into a numerical format for machine learning models to use. Common techniques include one-hot encoding, label encoding, or using embeddings for text data.

8. **Feature Scaling**: Ensure that the features are on a similar scale, especially when using algorithms sensitive to feature magnitudes. Common scaling methods include min-max scaling (normalization) and z-score scaling (standardization).

9. **Time Series Features**: For time series data, consider creating time-related features, such as lag values, rolling statistics, or seasonal decomposition. These features can capture temporal patterns.

10. **Text Feature Engineering**: In natural language processing (NLP) tasks, text data requires specialized feature engineering techniques. Common approaches include TF-IDF, word embeddings (Word2Vec, GloVe), and n-grams.

11. **Cross-Validation**: After feature engineering, assess the effectiveness of your features using cross-validation. Cross-validation helps estimate the model's performance on unseen data and ensures that the features generalize well.

12. **Iterative Process**: Feature engineering is often an iterative process. You may need to revisit and refine your feature engineering steps based on feedback from model performance evaluation.

13. **Domain Knowledge**: Leverage domain knowledge whenever possible. Experts in the field can provide valuable insights into which features are likely to be meaningful and how they should be engineered.

14. **Automated Feature Engineering**: Explore automated feature engineering tools and libraries, such as Featuretools or TPOT, to streamline the process and discover new features more efficiently.

These steps collectively contribute to creating a feature set that enables machine learning models to make accurate predictions and extract valuable insights from the data. Effective feature engineering requires a combination of data analysis, domain expertise, and creativity to identify and craft the most informative features for the specific problem at hand.

## Best Practices

When performing feature engineering, consider the following **best practices**:

- **Understand the Data**: Gain a deep understanding of the data and the problem domain. This will guide your feature engineering choices.

- **Iterate and Experiment**: Feature engineering is often an **iterative process**. Experiment with different features and observe their impact on model performance.

- **Cross-Validation**: Assess the effectiveness of your features using **cross-validation** to ensure that they **generalize well** to unseen data.

- **Domain Knowledge**: Leverage **domain knowledge** whenever possible. Experts in the field can provide valuable insights into which features are likely to be meaningful.

- **Automated Feature Engineering**: Explore **automated feature engineering tools and libraries** that can help in the process, such as **Featuretools** and **TPOT**.

Feature engineering is a **creative and data-driven process** that plays a crucial role in the success of data science projects. By carefully selecting, creating, and transforming features, data scientists can unlock the hidden patterns in data, leading to more **accurate** and **robust** machine learning models.

## Automated Feature Engineering Tools for Data Science and Machine Learning
Automated Feature Engineering tools are software and libraries designed to assist data scientists and machine learning practitioners in the process of feature engineering. These tools automate various aspects of feature creation and selection, making it easier and more efficient to work with large and complex datasets.

Certainly, here's a table summarizing popular automated feature engineering tools with columns for the tools, descriptions, key features, links to their official websites, and links to their GitHub repositories:

| Tool                               | Description | Key Features |  Website | GitHub  |
|------------------------------------|---------------------------------|---------------------------|:------------------------:|:-------------------------------:|
| **Featuretools**                   | Featuretools is an open-source Python library for automated feature engineering from structured data. It handles complex data relationships and creates feature matrices for machine learning.                                                                  | - Automated feature engineering<br>- Complex data relationships<br>- Feature matrix creation | [🌐](https://www.featuretools.com/) | [:octocat:](https://github.com/alteryx/featuretools) |
| **TPOT (Tree-Based Pipeline Optimization Tool)** | TPOT is an open-source Python library that automates the entire machine learning pipeline, including feature engineering, algorithm selection, and hyperparameter optimization. It uses genetic programming to evolve and optimize machine learning pipelines.                                           | - Automated ML pipeline optimization<br>- Genetic programming<br>- Hyperparameter tuning | [🌐](http://epistasislab.github.io/tpot/) | [:octocat:](https://github.com/EpistasisLab/tpot) |
| **AutoML Tools (e.g., H2O.ai, AutoML by Google Cloud, DataRobot)** | AutoML platforms like H2O.ai, AutoML by Google Cloud, and DataRobot offer automated feature engineering as part of their comprehensive suite of tools. These platforms streamline the entire machine learning workflow, from data preprocessing to model selection.                         | - End-to-end automation<br>- Comprehensive ML workflow<br>- Model selection and tuning | [🌐](https://www.h2o.ai/), [🌐](https://cloud.google.com/automl), [🌐](https://www.datarobot.com/) | [:octocat: H2O.ai](https://github.com/h2oai)<br> [:octocat: Automl ](https://github.com/googleapis/python-automl)<br>[:octocat: DataRobot](https://github.com/datarobot) |
| **tsfresh (Time Series Feature Extraction on Basis of Scalable Hypothesis tests)** | tsfresh is a Python library specifically designed for automated feature extraction from time series data. It conducts statistical tests and transformations to generate a comprehensive set of features from time series sequences.                                | - Automated time series feature extraction<br>- Statistical tests and transformations | [🌐](https://tsfresh.readthedocs.io/en/latest/) | [:octocat:](https://github.com/blue-yonder/tsfresh) |
| **Feature Engineering for Time Series (FEAST)** | FEAST is an open-source Python library specializing in feature engineering for time series data. It automates the process of creating features based on various statistical and domain-specific methods.                                             | - Automated time series feature generation<br>- Support for various feature types<br>- Integration with ML pipelines | [🌐](https://feast.dev/) | [:octocat:](https://github.com/feast-dev/feast) |
| **TransmogrifAI**                   | TransmogrifAI is an open-source AutoML library developed by Salesforce. It automates feature engineering and machine learning pipeline creation, particularly suitable for tabular data. It integrates with Apache Spark for scalability.| - Automated feature engineering for structured data<br>- Integration with Apache Spark<br>- Automated feature transformation and selection | [🌐](https://transmogrif.ai/) | [:octocat:](https://github.com/salesforce/TransmogrifAI) |

These automated feature engineering tools can significantly expedite the process of preparing data for machine learning and are particularly helpful for handling complex data structures and large datasets. You can find more detailed information on each tool by visiting their official websites or exploring their GitHub repositories.


## 📖 Notes
### Basic Concept
* [Introduction to Feature Engineering – Everything You Need to Know!](https://www.analyticsvidhya.com/blog/2021/10/a-beginners-guide-to-feature-engineering-everything-you-need-to-know/)
* [Feature Engineering — Automation and Evaluation — Part 1](https://medium.com/ki-labs-engineering/feature-engineering-automation-and-evaluation-part-1-a34fb42e0bd4)
* [Step by Step process of Feature Engineering for Machine Learning Algorithms in Data Science](https://www.analyticsvidhya.com/blog/2021/03/step-by-step-process-of-feature-engineering-for-machine-learning-algorithms-in-data-science/)
* [Automate feature engineering pipelines with Amazon SageMaker](https://aws.amazon.com/blogs/machine-learning/automate-feature-engineering-pipelines-with-amazon-sagemaker/)

## 📖 Lab
| No | Title   |  File |
| -----: | -----  | ------ | 
| 1. | Exploratory Data Analysis of 7 Million Companies |  [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/zelalemgetahun/eda-of-7-million-company-dataset) |
| 2. | AMEX EDA |  [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/ambrosm/amex-eda-which-makes-sense/notebook) |
| 3. | How to Work with BIG Datasets on 16G RAM (+Dask) |  [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/yuliagm/how-to-work-with-big-datasets-on-16g-ram-dask) |
| 4. | Cleaning and Analyzing the kiva dataset |  [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/omaymaali/cleaning-data-eda/notebook) |


## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/Python_EDA/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)




