# Prodigy InfoTech Data Science Internship

Welcome to my repository for the Prodigy InfoTech Data Science Internship. This repository documents the tasks and projects I completed during the program.

## Project Overview: Task 4 - Sentiment Analysis on Twitter Data
The objective of this project is to analyze and visualize sentiment patterns in social media data to gauge public opinion regarding various entities and brands. By leveraging a large-scale Twitter dataset, this task categorizes conversations into **Positive, Negative, Neutral, or Irrelevant** sentiments.

### Dataset
The analysis is performed on the **Twitter Training Dataset** (`twitter_training.csv`), which contains over 71,000 unique entries after preprocessing, including:
- **ID:** Unique identifier for each tweet.
- **Entity:** The brand or topic mentioned (e.g., Microsoft, Nvidia, Borderlands).
- **Sentiment:** The labeled sentiment of the post.
- **Tweet Content:** The raw text of the social media post.

### Implementation Steps
1. **Data Preprocessing:** Handling missing values in tweet content and removing duplicate entries (2,340 duplicates removed) to ensure data integrity.
2. **Data Exploration:** Inspecting dataset shape, descriptive statistics, and sentiment counts.
3. **General Sentiment Visualization:** - Generating bar charts to show the global distribution of sentiments.
   - Identifying that **Negative** (21,698) and **Positive** (19,713) are the most frequent categories.
4. **Brand-Specific Analysis (Microsoft):** - Filtering data specifically for the "Microsoft" entity.
   - Visualizing the brand's sentiment breakdown using a distribution pie chart.
5. **Insights:** Observing that for Microsoft, **Neutral** (816) and **Negative** (748) sentiments are more prevalent than **Positive** (573) feedback.

### Technologies Used
- **Python** (Pandas)
- **Natural Language Processing:** TextBlob
- **Visualization:** Matplotlib

## How to Run
1. Clone the repository.
2. Ensure you have Jupyter Notebook or Google Colab installed.
3. Install dependencies: `pip install pandas matplotlib textblob`
4. Place `twitter_training.csv` in the project directory.
5. Run the `Task 4 # Datascience.ipynb` file to see the analysis and results.

## Author
**Susmita Choudhury**
*Data Science Intern at Prodigy InfoTech*
