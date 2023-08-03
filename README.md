# Module 6 Web Scraping and NLP with Requests, BeautifulSoup, and spaCy


## Description

This GitHub repository contains code and scripts to extract, process, and analyze the content of an article about laser headlights from Hackaday. The project involves web scraping, text processing, and data visualization using Python and various libraries including BeautifulSoup, spaCy, and matplotlib. The goal of the project is to find the most frequent tokens and lemmas in the article, as well as to score sentences based on interesting tokens and lemmas.

## Complete the tasks in the Python Notebook in this repository.

Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Table of Contents

- Rubric
- Requirements
- Installation
- Usage
- Methods
- Results
- Conclusion

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt


## Requirements
To run the code in this repository, you'll need the following:

- Python (version 3.x)
- Required Python libraries: requests, pickle, BeautifulSoup, spacy, collections, string, matplotlib

## Installation

To use this project, make sure you have Python 3.8 installed on your system. Create and activate a virtual environment. Run the following commands to install these into your virtual environment:

python -m pip install beautifulsoup4
python -m pip install html5lib
python -m pip install requests
python -m pip install spacy
python -m pip install spacytextblob

## Usage

- Run the code provided in the repository to extract the article HTML and save it to a .pkl file.
- Process the article HTML to obtain text and analyze it using spaCy.
- Visualize the results using histograms.

## Methods

1. Extracting Article HTML
2. Processing Article Text
3. Data Visualization

## Results
The analysis reveals the most frequent tokens and lemmas in the article. It also scores sentences based on interesting tokens and lemmas. The histograms visualize the distribution of sentence scores, providing insights into the occurrence of interesting words.

Conclusion
The Laser Headlights Analysis project demonstrates how to extract, process, and analyze text data from a web article. By using various Python libraries, the project offers valuable insights into the content of the article and allows for data-driven conclusions.

For any inquiries or feedback, please contact S556427@nwmissouri.edu.


