# Gojek App Review Scraper & Analyzer

A tool to scrape Gojek app reviews from the Google Play Store. This project includes scripts for data collection, preprocessing (case folding, tokenization, stopword removal, stemming), and initial data analysis to gain insights from user feedback.

## 📜 About The Project

This project was created to collect and analyze user reviews of the Gojek application from the Google Play Store. The primary goal is to gather a dataset that can be used for various Natural Language Processing (NLP) tasks, such as sentiment analysis, topic modeling, or feature request identification. The collected data is cleaned and preprocessed to be ready for analysis.

## ✨ Features

* **Data Scraping**: Collects reviews directly from the Google Play Store using the `google-play-scraper` library.
* **Text Preprocessing**: Includes a comprehensive text cleaning pipeline:
    * Case Folding
    * Tokenization
    * Stopword Removal (using NLTK and Sastrawi)
    * Stemming (using Sastrawi)
* **Data Analysis**: Generates a word cloud to visualize the most frequent words in the reviews.
* **CSV Export**: Saves the cleaned data into a `review_gojek.csv` file for further use.

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 installed on your system. You will also need to install the required libraries.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/gojek-app-review-scraper.git](https://github.com/your-username/gojek-app-review-scraper.git)
    cd gojek-app-review-scraper
    ```

2.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1.  Open the `file_scrapping_gojek_review.ipynb` notebook in Jupyter Notebook or Google Colab.
2.  Run the cells sequentially to start the scraping and preprocessing.
3.  The final dataset will be saved as `review_gojek.csv`.

## ⚙️ Dependencies

* pandas
* numpy
* matplotlib
* google-play-scraper
* nltk
* sastrawi
* wordcloud

A full list of dependencies can be found in the `requirements.txt` file.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

---