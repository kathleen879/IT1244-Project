# IT1244-Project
This project focuses on sentiment classification using a movie review dataset. The primary objective is to build and evaluate a machine learning model that accurately predicts the sentiment of movie reviews, categorising them as either positive or negative.

### 1. Movie Review Dataset

•
Description: This dataset contains movie reviews designed as a benchmark for sentiment classification tasks. It contains 50000 positive reviews and 50000 negative reviews.

•
Structure:

o
The positive reviews are stored in data/pos.zip, and the negative reviews are in data/neg.zip.

o
Each review is stored as a separate text file within these ZIP archives.

•
Purpose: To train and evaluate the sentiment classification model.

### 2. Additional Dataset: Spotify User Reviews

•
Description: This dataset consists of over 51,000 user reviews of the Spotify application, scraped from the Google Play Store between January and July 2022.

•
Labelling: Each review is labelled as either "Positive" or "Negative" based on its sentiment.

•
Sample Size: For analysis, we extracted 20,000 positive and 20,000 negative reviews.

•
Purpose: To supplement the movie review dataset and enhance the model’s ability to generalize sentiment classification across different domains.

### Set Up Instructions 
Setting Up the Google Colab project environment
1.
Upload Datasets to Google Drive: Upload the Movie Review and Spotify datasets to a designated folder in your Google Drive, ensuring they are in the correct location for easy extraction.

2.
Mount Google Drive: Start by mounting your Google Drive to access the dataset files.

3.
Install Required Libraries: Make sure to install the necessary libraries, including nltk and wordcloud.

4.
Import Libraries: Import all required libraries for data processing and visualization, including zipfile, os, nltk, matplotlib, seaborn, and wordcloud.

5.
Extract the Movie Review Datasets: Extract the positive and negative movie reviews from their respective ZIP files using the zipfile library.

6.
Load the Extracted Data: Load the text files from the extracted folders into a pandas DataFrame for analysis.

7.
Analyze and Visualize: Proceed with your analysis and visualization tasks, such as generating word clouds or conducting sentiment analysis.
