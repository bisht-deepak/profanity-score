# Tweet Profanity Score Calculator

## Introduction
This is a Python program that calculates the profanity score of tweets made by US politicians. The program processes the tweets and provides insights into the use of profane language by different political figures. It also includes visualizations that illustrate the relationship between Twitter handles and their respective profanity scores, as well as the distribution of profanity scores across different political parties.

## Getting Started
### Prerequisites
- Python 3.x
- Required libraries: re, pandas, bokeh

### Installation
1. Clone the repository: `git clone https://github.com/bisht-deepak/profanity-score.git`
2. Navigate to the project directory: `cd profanity-score`

## Functionality
The program includes a function `calculate_profanity_score(tweet)` that calculates the profanity score of a given tweet. It converts the tweet to lowercase, removes punctuation marks, and then counts the occurrences of profane words. The profanity score is calculated as a ratio of profanity words to the total number of words in the tweet. In the case of a ZeroDivisionError, it returns a profanity score of 0.

## Visualizations
The project provides visualizations that demonstrate the following relationships:
- The profanity scores for different Twitter handles.
- The distribution of profanity scores across different political parties.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- [Democrat Vs. Republican Tweets](https://www.kaggle.com/datasets/kapastor/democratvsrepublicantweets/).
- [Bad Bad Words](https://www.kaggle.com/datasets/nicapotato/bad-bad-words/)

## Contributing
Contributions are welcome. Please fork the repository and create a pull request for any suggested changes.

## Project File
Access the Jupyter Notebook (.ipynb) file for this project on [Kaggle](https://www.kaggle.com/code/thethirdchapter/profanity-score).

## Contact
For any questions or suggestions, feel free to contact the project maintainer at \href{mailto:bishtdeepak8469@gmail.com}{bishtdeepak8469@gmail.com}.
