
# Wikipedia Article Analysis

This project contains a comprehensive analysis of a dataset comprising Wikipedia articles. The analysis includes data cleaning, exploratory data analysis, sentiment analysis, topic modeling, clustering, named entity recognition, principal component analysis, and advanced visualizations.

## Project Description

The dataset comprises around 5000 raw data extracted from Wikipedia, encompassing various types of content including articles, metadata, and user interactions. The dataset is in its unprocessed form, providing an excellent opportunity for data enthusiasts and professionals to engage in data cleaning and preprocessing tasks. This project aims to perform comprehensive data analysis to uncover insights and patterns within the dataset.

## Project Files

- `Advanced_Analysis_Wikipedia_Dataset.ipynb`: The Jupyter Notebook containing the complete analysis.
- `articles.xlsx`: The dataset file.

## Analysis Overview

1. **Data Cleaning and Preprocessing**
   - Handling missing values and normalizing the dataset.

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics.
   - Distribution of articles across categories.
   - Word clouds for titles and bodies.

3. **Sentiment Analysis**
   - Sentiment analysis using TextBlob to understand the general sentiment of the articles.

4. **Topic Modeling**
   - Using Latent Dirichlet Allocation (LDA) to identify key topics discussed in the articles.

5. **Clustering**
   - Applying K-means clustering to group similar articles.

6. **Named Entity Recognition (NER)**
   - Extracting named entities using spaCy.

7. **Principal Component Analysis (PCA)**
   - Dimensionality reduction for visualization.

8. **Advanced Visualizations**
   - Sentiment distribution by category.
   - Interactive PCA plot.
   - Interactive sentiment distribution plot.

## Setup Instructions

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/debjit-mandal/Wikipedia-Article-Analysis.git
   ```


2. **Navigate to the Project Directory**

   ```sh
   cd Wikipedia-Article-Analysis
   ```

3. **Install Dependencies**

   Use the following command to install the required dependencies:

   ```sh
   pip install pandas numpy matplotlib seaborn wordcloud textblob sklearn spacy plotly
   ```

4. **Download spaCy Model**

   Download the spaCy model needed for Named Entity Recognition:

   ```sh
   python -m spacy download en_core_web_sm
   ```

## Usage

1. **Open the Jupyter Notebook**

   Start Jupyter Notebook from the project directory:

   ```sh
   jupyter notebook Advanced_Analysis_Wikipedia_Dataset.ipynb
   ```

2. **Run the Notebook**

   Execute the cells in the notebook to perform the analysis.


### Insights

- **Data Overview**: The dataset contains various articles extracted from Wikipedia, with detailed metadata including titles, URLs, summaries, bodies, sections, references, categories, and infoboxes.
- **Data Cleaning**: Missing values were handled appropriately, and the dataset was preprocessed to ensure consistency and completeness.
- **Exploratory Data Analysis (EDA)**:
  - The distribution of articles across different categories revealed a diverse range of topics covered in the dataset.
  - Word clouds for titles and bodies highlighted the most frequently used words, providing a quick visual summary of the content.
- **Sentiment Analysis**: Using TextBlob, sentiment analysis was performed on the article bodies, revealing a range of sentiment scores across different articles and categories. This analysis helps in understanding the general sentiment conveyed in the articles.
- **Topic Modeling with LDA**: Latent Dirichlet Allocation (LDA) was used to identify key topics discussed in the articles. This technique helped in uncovering hidden themes and patterns within the text data.
- **Clustering with K-means**: K-means clustering grouped similar articles based on their TF-IDF features, providing insights into how articles can be categorized into distinct clusters.
- **Named Entity Recognition (NER)**: Named entities were extracted using spaCy, identifying and categorizing various entities mentioned in the articles.
- **Principal Component Analysis (PCA)**: PCA was applied to reduce the dimensionality of the TF-IDF matrix, enabling visualization of the articles in a 2D space and revealing inherent structure and patterns.
- **Advanced Visualizations**: Various visualizations, including sentiment distribution and interactive PCA plots, provided deeper insights into the dataset.

### Conclusion

The analysis of the Wikipedia dataset revealed several interesting insights into the structure, content, and sentiment of the articles. By employing advanced techniques such as sentiment analysis, topic modeling, clustering, NER, and PCA, we were able to gain a comprehensive understanding of the dataset. This analysis not only highlights the richness and diversity of the Wikipedia content but also demonstrates the power of data science techniques in extracting meaningful insights from textual data. Future work could involve applying more sophisticated models and expanding the dataset for a more comprehensive analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset can be found on Kaggle: https://www.kaggle.com/datasets/ismaeldwikat/raw-wikipedia-8000-articles
  
- The open-source community for providing the tools and libraries used in this analysis.

----------------------------------------------------------------

Feel free to suggest any kind of improvements.