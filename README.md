# Tag-Identification-Using-NLP 

This project fetches the text from a Wikipedia page, removes stopwords, and plots the frequency distribution of the remaining words using Python. Specifically, the script is configured to analyze the Wikipedia page for "Microsoft"

## A) Prerequisites
Before you begin, ensure you have met the following requirements:
You have installed Python 3.6 or later.
You have a working internet connection to fetch the webpage and download necessary NLTK resources.
You have the following Python packages installed:
1. nltk
2. beautifulsoup4
3. html5lib
You can install the required packages using pip on the command prompt of your admin system - pip install nltk beautifulsoup4 html5lib

## B) Installation
1. Clone this repository or download the script directly.
2. Ensure you have the required packages installed as mentioned above.
   
## C) Usage
1. Open a terminal or command prompt.
2. Navigate to the directory where the script is located.
3. Run the script using Python: python script_name.py
Note: Replace script_name.py with the actual name of your script.

## D) How It Works:
1. The script fetches the HTML content from the Wikipedia page for "Microsoft"
2. It parses the HTML to extract the text content using BeautifulSoup.
3. The text is tokenized into individual words.
4. Common English stopwords are removed from the tokens.
5. The frequency distribution of the remaining words is calculated.
6. The frequency distribution is printed and plotted.

## E) Example Output
The script will print the frequency of each word and display a plot showing the frequency distribution of the 30 most common words (excluding stopwords).

## F) Contact
If you have any questions or feedback, please contact Jugal Deshmukh at mrjugaldeshmukh@gmail.com.

### This README file provides a detailed overview of your project, from prerequisites and installation to usage and a brief code explanation.


