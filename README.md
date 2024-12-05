# **Tag-Identification-using-NLP**

This project demonstrates a simple pipeline for extracting and analyzing text data from a web page. The script fetches content from the Wikipedia page of "Tata Group," cleans the data to remove unnecessary elements (stopwords, digits, special characters, etc.), and identifies the most frequent words in the text. The output is visualized in a plot showing the top 10 word frequencies.

## **Features**

- Scrapes text content from a given URL using BeautifulSoup.
- Removes stopwords, digits, hyphens, and special characters.
- Computes word frequency using nltk.FreqDist.
- Visualizes the top 10 most frequent words in a plot.
- Saves the frequency plot as a PNG image.
  
## **Technologies Used**

- Python 3.x: Programming language for implementing the script.
- Libraries:
  - urllib: For fetching the HTML content of the webpage.
  - BeautifulSoup (from bs4): For parsing and extracting text from the HTML.
  - nltk: For text processing and stopword removal.
  - matplotlib: For visualizing the word frequency distribution.
  - re: For filtering words using regular expressions.
 
 ## **How the Code Works**  

- Web Scraping:
  - Fetches HTML content from the specified URL.
  - Extracts text from the HTML using BeautifulSoup.

- Text Cleaning:
  - Splits the extracted text into tokens.
  - Removes stopwords using the NLTK stopwords corpus.
  - Uses a regular expression to exclude tokens containing digits, hyphens, or special characters.
    
- Word Frequency Analysis:
  - Calculates the frequency distribution of the cleaned tokens using nltk.FreqDist.
    
- Visualization:
  - Plots the top 10 most frequent words.
  - Saves the plot as a high-resolution PNG image.
 
## **Output Example**

- Text Plot: A frequency plot showing the top 10 most frequently occurring words in the text.
  ![word_frequency_plot](https://github.com/user-attachments/assets/22541191-be15-412b-9e0d-3c0b19bf3195)

- Saved Image: word_frequency_plot.png in the current directory.

## **Acknowledgements**

- Wikipedia for providing the data source.
- Python's nltk, BeautifulSoup, and matplotlib libraries for enabling seamless text analysis and visualization.   

