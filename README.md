# 📰 Named Entity Recognition (NER) and Predictive Modeling for News Articles 📊

## 🎯 Objective
The goal of this task is to analyze a set of news articles through **Named Entity Recognition (NER)** and to engineer numerical features based on these entities for **predictive modeling**. The task involves:
- Extracting named entities from articles using an open-source LLM model.
- Creating insightful features.
- Building a predictive model to determine article popularity based on engagement metrics.

This task assesses skills in **natural language processing (NLP)**, **feature engineering**, and **predictive analytics**. 🧠

## 📂 Data Collection
- The provided dataset of news articles can be accessed here: [News Articles Dataset](https://www.kaggle.com/datasets/sbhatti/news-articles-corpus)

## 🧹 Text Preprocessing
1. **Cleaning the Text**:
   - Remove unnecessary whitespace, HTML tags, and special characters.
   - Normalize text (convert to lowercase).
2. **Tokenization & Stop Words Removal**:
   - Tokenize the text and remove stop words using libraries like **NLTK** or **SpaCy**.

## 🤖 Named Entity Recognition (NER)
1. **Entity Extraction**:
   - Use an open-source LLM model **SpaCy** to extract named entities from the cleaned articles.
2. **Entity Categorization**:
   - Ensure entities are categorized correctly into types such as **Organizations (ORG)**, **Locations (GPE)**, and **People (PERSON)**.
3. **Entity Frequency**:
   - Create numerical features based on the frequency of each entity type in each article (e.g., count of organizations, locations, and people).

## 🔧 Feature Engineering
1. **Additional Features**:
   - Article length (number of words).
   - Sentiment scores (using **TextBlob** or **VADER**).
   - Engagement metrics (likes, shares, comments) if available in the dataset.
2. **Innovation**:
   - Derive creative features beyond the basic entity counts to enhance the feature set.

## 📈 Predictive Modeling
1. **Model Selection**:
   - Train a predictive model using the engineered features to predict article popularity. Possible models include **Linear Regression**, **Random Forest**, etc.
2. **Model Evaluation**:
   - Evaluate the model performance using **accuracy scores**, **F1-scores**, or **mean absolute error (MAE)**.

## 📊 Visualization
1. **Visualizations**:
   - Create visualizations to show the relationship between named entities and article popularity.
   - Use libraries like **Matplotlib** or **Seaborn** to generate:
     - Bar charts for entity frequency.
     - Scatter plots illustrating correlations.
     - Heatmaps for the relationship between entity counts and engagement metrics.

### Example Visualizations:

#### 🏆 Popularity vs. Named Entity Count

(![image](https://github.com/user-attachments/assets/03feb778-fb00-4b24-aac0-e43f12ed1e40)
)

#### 📊 Heatmap

(![image](https://github.com/user-attachments/assets/7c7e4fc4-39b6-47db-a995-4fe27b453e58)
)

## 📝 Findings & Insights
- **Named Entities Impact**: The frequency of **organizations** and **locations** in news articles tends to correlate positively with **engagement metrics** such as likes and shares.
- **Sentiment Analysis**: Articles with more **positive sentiment** tend to receive higher engagement compared to those with **neutral or negative sentiment**.
- **Article Length**: Articles with a higher word count tend to have more **named entities**, which in turn leads to better engagement.

## 🚀 Next Steps
- Experiment with more sophisticated **NLP techniques** for **entity extraction** and **feature engineering**.
- Explore different **predictive models** and **evaluation metrics** to improve accuracy and generalizability.

## 📅 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📢 Acknowledgements
- Dataset: [News Articles Dataset](https://www.kaggle.com/datasets/sbhatti/news-articles-corpus)
- Libraries: **SpaCy**, **TextBlob**, **NLTK**, **Matplotlib**, **Seaborn**

---

Feel free to open an issue or submit a pull request if you have any suggestions or improvements! 💬

