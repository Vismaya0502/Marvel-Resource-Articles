# Introduction to Machine Learning

## 1. Gentle Introduction to Machine Learning

Machine learning (ML) is a study of models or algorithms that helps computers predict outcomes or classify things based on data.The two major application of ML is prediction and classification.To make such predictions and classifications ML models need data. There are generally two kinds of data in machine learning *Training* and *Testing* data.ML models learn patterns from *training data* and make predictions on *testing data*, which is used to check how well the model works. Sometimes, a model can perform very well on the *training data* but make poor predictions on testing data. This difference between performance on training and testing data is called the **bias–variance tradeoff**.

A models performance should be evaluated based on how well the model works for testing data, not for the training data. A model might perform well on the training data, but testing data is the one shows whether or not the model can can generalize to new, unseen situations and predict the outcomes.

And choosing the right machine learning model depends on how well the model fits the data, not on how complex or fancy it is.Sometimes the simple model can work best for the given data, it does not necessarily need some complex model to make predictions. Even a very advanced model can perform poorly if it does not match the type of data it is trained on. Therefore, the success of a machine learning model depends on the match between the model and the data, rather than the algorithm’s complexity.

## 2. Data Preparation for Machine Learning

This video explains the importance of preparing data before giving it to a machine learning model. High-quality, well-prepared data is essential because the model can only learn from the data it receives. Poor or biased data can lead to bad predictions, for example Amazon's AI recruiting tool,ranked male resumes higher because most of the training data it had trained had resumes of male applicants.

So,the data preparation process starts with defining the problem for which the model is being built on and collecting relevant data. To determine how much data is good to call a dataset good, there is no metric. While larger datasets are generally better, there is no fixed “enough” size. What matters most is the *quality* and *adequacy* of the data. The dataset should be relavent to the underlying problem, for example, using only California meat sales to predict meat prices across America would not be proper.

Once data is collected, the next step is **labeling**. This involves telling the model about the features of data, so it can learn patterns correctly. Pre-built datasets may have incorrect labels, so manual labeling is often necessary.

After labeling, data undergoes **reduction and cleansing**. Irrelevant or low-variance features are removed because they do not help the model and can reduce its performance. This step, called dimensionality reduction,this ensures the dataset contains only useful information.

**Sampling** is another important step, where the data is balanced to prevent bias. For example, in Amazon’s case, the model needed equal representation of male and female resumes. Next is **Cleaning** where  missing or blank data is handeled by filling gaps rather than leaving them empty, which could cause problems for the model.

The next step is **data wrangling**, which includes *formatting and normalization*. **Formatting** converts datasets into a consistent structure, usually .csv, so the model can process the data. Normalization scales the data so all the instances are comparable. A common technique is min-max normalization, which sets the minimum value to 0 and the maximum value to 1, with all other values in between.

Next comes, **feature engineering**,it means creating new features from existing data by breaking down complex variables into simpler, more meaningful ones. This helps the model recognize patterns more effectively.

In conclusion, a machine learning model’s success depends entirely on the training data. The model cannot improve or biased on its own. If the training data is good, the model will perform well. If the data is poor or biased, the model will produce poor predictions. This shows that building an effective machine learning model is not only about choosing the right algorithm, but also about using good data to train your model.