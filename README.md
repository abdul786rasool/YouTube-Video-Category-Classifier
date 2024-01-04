# YouTube-Video-Category-Classifier

This project presents a comprehensive approach to classifying YouTube videos into eight distinct categories: Music, Sports, Gaming, Education, Film/Animation, Entertainment, News & Politics, and Comedy. This classification is primarily based on the video descriptions. Utilizing various machine learning techniques and models, this repository offers a deep dive into the realm of video categorization.

# Project Structure
The project is organized into several Jupyter Notebook files, each serving a unique purpose in the development and evaluation of the models:

### 1. DataScraping.ipynb: 
This notebook outlines the process of data collection using the YouTube API. It involves scraping URLs and relevant data from YouTube videos and manually labeling each video into one of the predefined categories.

### 2. data_analysis_and_visualisation.ipynb:
This file focuses on the data analysis and visualization aspect, providing insights into the dataset. It includes plots and charts showcasing various parameters like views, likes, and the number of comments across different categories.

### 3. category_classifier_1.ipynb: 
The first classification model, based on the Naive Bayes algorithm, is presented here. This probabilistic model serves as an initial approach to categorizing YouTube videos.

### 4. category_classifier_2.ipynb: 
The second model in this series is a vanilla neural network featuring an embedding layer, offering a more nuanced approach to classification.

### 5. category_classifier_3.ipynb: 
The third model elevates the classification strategy by fine-tuning a BERT model from Hugging Face, leveraging advanced NLP techniques for enhanced accuracy.

### 6. Final_Ensemble_Model.ipynb: 
This notebook represents the culmination of the project, where an ensemble method combines the strengths of the previous three models. This final model can classify YouTube video categories directly from URLs, integrating all necessary components and files for ease of use.

# Key Features
• Comprehensive data scraping and labeling process 
• In-depth data analysis and visualization
• Multiple classification models including Naive Bayes, Vanilla Neural Network, and BERT
• Ensemble method for improved prediction accuracy

• Direct category prediction from YouTube URLs
# Technologies Used
• Python
• YouTube API
• Jupyter Notebook
• Libraries: Pandas, NumPy, Matplotlib, TensorFlow, Hugging Face Transformers, etc.
# Usage
The project can be utilized by researchers, data scientists, and enthusiasts interested in video content categorization, machine learning model comparisons, or ensemble method implementations. The 'Final_Ensemble_Model.ipynb' is the go-to file for directly classifying YouTube videos into categories.

Feel free to explore, fork, or contribute to this project. Your insights and contributions are highly appreciated!

