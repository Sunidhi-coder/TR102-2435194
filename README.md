# TR102-2435194
**Training Daily Diary**
<br>
**Training Topic: Next-Gen Data Exploration with ML and GenerativeAI**
<br>
---
**DAY: 1        Date: 30-06-26**
<br>
|Topics Covered | Description|
| ---- | ---- |
|`Data`|  Data is a collection of raw facts, figures, or observations that has not yet been processed.|
|`Information`| Information is processed and organized data that is meaningful and useful for making decisions.Eg: If we want to take all the datails of accidents on a particular Highway then our data is newspapers.|
|`Data Sources`|Data sources are places from which data is collected.  Common data sources:Databases,CSV/Excel files,Websites,Sensors and IoT devices,Social media,Surveys,APIs etc.|
|`Types of data`| Structured Data: Organized in rows and columns (e.g., SQL database).| Unstructured Data: No predefined format (e.g., images, videos, emails).|
|`Data Exploration`|Data exploration is the process of examining data to understand its structure, identify patterns, detect missing values, and discover relationships before analysis or model building.|
|`Data Modality`|Data modality refers to the type or format of data used in AI and machine learning. data representations: Text,Images,Audio,Video,Tabular data.|
|`Machine Learning (ML) Model`|A Machine Learning model is an algorithm that learns patterns from data to make predictions or decisions without being explicitly programmed.|
|`Generative AI (Gen AI)`|Generative AI is a type of artificial intelligence that creates new content such as text, images, music, videos, or code by learning patterns from existing data.  Eg:ChatGPT (text generation),GitHub Copilot.|


---
**DAY: 2        Date: 01-07-26**
<br>
|Topics Covered|Description|
|----|----|
|`Data Types`|Before analyzing data, Python needs to know what kind of information it is handling. eg ***int,float,string,bool***|
|`Python Data Structures`|***List-*** Ordered, mutable collections of items. Created using square brackets []. Allows duplicate elements and mixed data types.<br>***Tuples*** Ordered, immutable sequences of items. Created using parentheses (). Cannot be changed after creation, making them memory-efficient.<br>***Dictionaries (dict)*** Unordered, mutable key-value maps. Created using curly braces {key: value}. Keys must be unique and immutable.<br>***Sets*** Unordered collections of unique elements. Created using curly braces {} or set(). Automatically eliminates duplicates; ideal for membership testing.|
|`Pandas Data Strcuture`|Pandas is a python library <br> ***Pandas Series*** Series = Single column of data.<br>***Pandas Dataframes*** A DataFrame is similar to an Excel sheet.|

---
**DAY: 3       Date: 02-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Data Pipeline`|Raw Data -> Import Data -> Understand Data -> Data Cleaning -> Data Transformation -> Data Analysis ->Visualization -> Insights|
|`Data Cleaning`|Data cleaning is the process of identifying and correcting errors, inconsistencies, and inaccuracies in raw data before analysis.|
|`Common Data Quality Issues`|**1. Missing values:** Missing values occur when no data is recorded for a particular observation. *Methods to Handle the Missing Value:* Remove Row ,Fill the Mean ,Fill the Median ,Fill the Mode <br> **2. Duplicate records** <br> **3. Incorrect data types** <br> **4. Inconsistent text formatting** <br> **5. Outliers** <br> **6. Invalid values** <br> **7. Extra spaces**|
|`Outlier`|An outlier is an observation that is significantly different from the rest of the data.|

---
**DAY: 4       Date: 03-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`EDA - Exploratory Data Analysis`|EDA is an essential step in data analysis that focuses on understanding patterns, relationships and distributions within a dataset using statistical methods and visualizations.|
|`Univariate Analysis`|Univariate = One Variable|
|`Bivatiate Analysis`|Relationship between TWO variables|
|`Multivariate Analysis`|Relationship among multiple variables|
|`Feature Engineering`|Generating entirely new variables from existing data. For example, extracting "Day of the Week" and "Is Holiday" columns from raw date|

---
**DAY: 5      Date: 06-07-26**
<br>
|Topic Covered|Description|
|---|---|
|`Data Visualization`|Data visualization is the graphical representation of data to communicate patterns, trends, relationships, and insights effectively.|
|`Visualization helps us:`|Understand large datasets quickly. <br> Identify trends. <br> Detect outliers. <br> Compare groups. <br> Discover hidden relationships. <br> Support business decisions.|
|`Matplotlib `|Basic plotting library,Highly customizable,Good for simple charts.|
|`Seaborn`|Built on Matplotlib,More attractive default styles,Easier statistical plots,Better integration with Pandas.|
|`Histogram Chart`|Used for Distribution|
|`Boxplot`|Outliers & Spread|
|`Countplot`|Frequency Count|
|`Bar Chart`|used for Comparison|
|`Pie chart`|used for Percentage|
|`Line chart`|used for Trend|
|`Scatter Plot`|used for Relationship|
|`Heatmap`|used for Correlation|
|`Pair Plot`|used for Multiple Relationships|
|`Violin Plot`|used for Distribution Comparison|
|`KDE Plot`|used for Probability Distribution|
|`Area chart`|used for Cumulative Trend|

---
**DAY: 6     Date: 07-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Feature Engineering`|Feature engineering is all about transforming raw data into useful features that help make better predictions with machine learning models. It’s a crucial step that can improve your models and make your data easier to understand.|
|`There are seven common techniques of Feature Engineering`|Create,Tranform,Encode,Scale,Bin,Extract,Combine|
|`Technique 1 - Feature Creation`|Creating completely new columns from existing columns.|
|`Technique 2 Feature Transformation`|Sometimes data exists but in the wrong form.|
|`Technique 3: Feature Scaling`|
|`Technique 4 Encoding`|Computers understand Numbers Not words.|

---
**DAY: 7  Date: 08-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Principal Component Analysis (PCA)`|A dimensionality reduction technique that converts many correlated features into a smaller number of new features (called Principal Components) while retaining as much information (variance) as possible.|
|`Why Do We Need PCA?`|Suppose our dataset has 100 Features Some are useful. Some are duplicates. Some are highly correlated.|

---
**DAY: 8  Date: 09-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Imbalanced data`|when one class has far more samples than others, causing models to favour the majority class and perform poorly on the minority class. This often results in misleading accuracy, especially in critical applications like fraud detection or medical diagnosis.|
|`Random oversampling`|Random oversampling is a technique used in machine learning to balance imbalanced datasets. It works by randomly duplicating existing examples from the minority class—often with replacement—until the class distribution is equal to the majority class.|
|`Random undersampling `|Random undersampling is a technique used in machine learning to balance imbalanced datasets by randomly deleting examples from the majority class. While it speeds up training time, it risks discarding potentially valuable information needed for the model to learn accurately.|
|`SMOTE `|SMOTE (Synthetic Minority Over-sampling Technique) is an algorithm used to fix class imbalance in machine learning datasets. Instead of duplicating existing minority data, which leads to overfitting, SMOTE creates new, realistic synthetic data points by calculating distances between existing minority examples and interpolating new points along the lines connecting them.|
|`ADASYN`|ADASYN (Adaptive Synthetic) is a machine learning technique used to handle imbalanced datasets by generating synthetic samples for the minority class. It differs from basic oversampling by focusing on the "harder-to-learn" examples, shifting the model's decision boundary to better classify difficult data points.|

---
**DAY: 9  Date: 10-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Pattern Detection `|process of discovering meaningful and recurring relationships or trends in data. |
|`Z-score method for anomalies`|A z-score, also called a standard score, indicates the position of a raw score relative to the mean of a dataset, expressed in terms of standard deviations. A z-score of 0 means the value is exactly at the mean, a positive z-score indicates the value is above the mean, and a negative z-score indicates it is below the mean. Z-scores allow comparison across different datasets or scales by standardizing values on a common scale, making raw numbers easier to interpret and compare.|
|`Detecting a Pattern with a Pivot Table`|Pivot Tables allow you to summarize and analyze large datasets efficiently, making it easier to detect patterns, trends, and anomalies.|
|`Finding Patterns with Clustering`|Clustering is an unsupervised machine learning technique used to group similar data points together without using labelled data. |

---
**DAY: 10 Date:13-07-26**
<br>
|Topics Covered|Desc|
|---|---|
|`pip install ydata-profiling`|
|`pip install sweetviz`|

---
**DAY: 11 Date:14-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Supervised learning`|machine learning in which a model is trained using a dataset that contains both the input features and the corresponding correct outputs (labels).|
|`Classification:`| Predicting categories (e.g., placement status).|
|`Regression`|Predicting continuous values (e.g., expected salary package).|


---
**DAY: 12    Date:15-07-26**
<br>
|Topics Covered|Desciption|
|---|---|
|`Naïve Bayes`|probabilistic supervised learning algorithm based on Bayes' Theorem.|
|`KNN`|predicts the class by looking at the K nearest neighbors.|
|`SVM`|finds the best boundary that separates different classes.|

---
**DAY:  13  Date:16-07-26**
<br>
Project Progress check

---
**DAY: 14  Date:17-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`decision tree `|A decision tree is a supervised machine learning algorithm that breaks down a dataset into smaller subsets while building an upside-down, flowchart-like tree structure.|
|`Entropy`|Measures the randomness or disorder within a node.|
|`Information Gain`|Calculates the drop in entropy after a split. The algorithm naturally picks the feature with the highest information gain.|
|`Random Forest`|powerful supervised machine learning algorithm that builds an ensemble (collection) of multiple decision trees to make more accurate and stable predictions. |

---
**DAY: 15  Date:20-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Linear Regression`|supervised learning algorithm used to predict a continuous numerical value by finding the best-fit straight line between the input features and the target variable.|
|`Ridge Regression`|regularized version of Linear Regression that adds an L2 penalty to the cost function. This penalty shrinks coefficient values but does not remove any features.|
|`Lasso Regression`|regularized version of Linear Regression that adds an L1 penalty to the cost function. It shrinks coefficients and can reduce some of them exactly to zero, automatically performing feature selection.|

---
**DAY: 16  Date:21-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Feature Selection `|process of selecting only the most important features (columns) from a dataset while removing irrelevant, redundant, or less useful features before training a machine learning model.|
|`Variance Thresholding`|Variance Threshold removes features with very low variance, as they contribute little useful information to the learning process. Features with almost constant values are typically discarded.|
|`Correlation Coefficient`|The Correlation Coefficient measures the strength and direction of the relationship between a feature and the target variable. Features with higher absolute correlation values are generally considered more relevant.|
|`Chi Squared Test`|Chi-Square test evaluates the dependency between categorical features and the target variable. Features with higher Chi-Square scores are considered more important.|

---
**DAY: 17  Date:22-07-26**
<br>
|Topics Covered|Description|
|---|---|
|`Wrapper Method`|feature selection technique in which a machine learning algorithm is used to evaluate different subsets of features and select the combination that gives the best model performance.|
|`RFECV (Recursive Feature Elimination with Cross Validation)`|This is the smart version of RFE. Instead of asking How many features should I keep? RFECV automatically decides.|













