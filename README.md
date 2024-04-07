# Movie-Correlation-Project

The core objective of this project is to identify which factors most strongly correlate with a movie's commercial and critical success. Understanding these correlations can help filmmakers, producers, and studios make informed decisions to maximize both revenue and positive reception.

### Data Source
The analysis is based on a dataset that includes a wide range of movie information, sourced from Kaggle. This comprehensive dataset provides key features such as budget, revenue, popularity scores, and critical ratings, among others. It offers a broad spectrum of data points, from financial aspects of the movies to their reception, both critically and among the audience, allowing for a nuanced analysis of what factors may contribute to a movie's success or failure.

The dataset from Kaggle is instrumental in facilitating this project's exploration of correlations between different movie features. By leveraging this dataset, i aim to uncover hidden patterns and insights that can predict a movie's performance, both commercially and critically.

### Results
The core analysis of the project centered on uncovering correlations between different movie features to understand what factors might influence a movie's success. Here are the significant findings:

Correlation Analysis : Using Pearson, Kendall, and Spearman correlation methods, the analysis explored relationships between numeric features within the movie dataset. Notable correlations were observed, particularly when examining the relationship between a movie's gross revenue and other features.

Visual Representation: The project included a heatmap of the correlation matrix, visually representing the strength of correlations between movie features. This heatmap highlights how certain features are more closely related to each other.

Factorized Correlation Analysis: To extend the correlation analysis to categorical features, the project applied factorization, assigning numeric values to each unique categorical value before recalculating the Pearson correlation. This approach allowed for the examination of correlations between categorical features and others, providing a more comprehensive view of the data.

#### Key Correlation Findings:

The correlation between a movie's score and its gross revenue was visualized, suggesting a relationship worth further investigation.
The heatmaps and correlation matrices provided evidence of significant relationships between various features. Notably, these include (but are not limited to) correlations between budget and gross revenue, popularity and gross revenue, and possibly between critical ratings and commercial success.
Analysis of sorted correlation pairs revealed strong correlations (with an absolute value greater than 0.5), indicating significant relationships worthy of further exploration and analysis.
These results suggest that certain movie features, such as budget, popularity scores, and critical ratings, may have a notable impact on a movie's financial success. The detailed correlation analysis, both numeric and categorical, provides a solid foundation for predicting movie success and guiding future filmmaking and marketing decisions.

