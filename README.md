# Tweets-Classification

## Overview
This project comes from my course in Codecademy, `Build a Machine Learning Model with Python - Skill Path`. The project consists of two machine learning models: `K-Nearest Neighbors` and `Naïve Bayes`. `tweet-location-classifier` uses a `K-Nearest Neighbors` classifier, where it aims to predict whether a tweet comes from `New York`, `London`, or `Paris`, based on the language used on the tweet. `viral-tweets-classifier` uses a `Naïve Bayes` classifier, where it predicts whether a given tweet will become viral or not based on the `length of that tweet`, the `number of followers`, and the `number of friends` that the account has. This project helps users learn about `supervised learning`, and use classifiers like `K-Nearest Neighbors` and `Naïve Bayes`.  

## Requirements
* Python
* scikit-learn
* NumPy
* Pandas
* Matplotlib
* seaborn

## Getting Started
If you want to learn more about K-Nearest Neighbors and Naive Bayes' classifiers and how they work, feel free to use this project for learning purposes. Here's how to get started.
1. Download and install Python - You can visit [Real Python](https://realpython.com/installing-python/) to learn how to install Python on Windows/macOS/Linux.
2. Download and install Jupyter Notebook or Jupyter Lab - You can visit [jupyter.org](https://jupyter.org/install) for more information. You can also install Anaconda, a distribution for Python and R that simplifies package management and deployment. Here's the link: [anaconda.com](https://www.anaconda.com/)
3. Clone the repository on your desired directory path - I recommend having this project on the Desktop or somewhere easily accessible.

```bash
cd Desktop
git clone https://github.com/WilhenAlbertoHM/Tweets-Classification/
cd Tweets-Classification
jupyter lab
```

Note: `code .` opens Visual Studio Code IDE. If you decide to use other IDEs, you can open the IDE of your choice and access the folder that way. 

3. Install the required libraries to run the program (assuming you have Python installed). The commands below can be written inside your IDE's terminal:

```bash
pip install pandas
pip install numpy
pip install scikit-learn
pip install seaborn
```

4. To run `tweet_location_classifier.ipynb` and `viral_tweets_classifier.ipynb`, you can run each cell sequentially, or click on `Run All` button on the top.

## How to use
1. Open `tweet_location_classifier.ipynb` and `viral_tweets_classifier.ipynb` in your Jupyter Notebook/Lab.
2. Explore relevant data before diving into the models.
3. Train the model using the training data. You can explore different models and features from the data to see how they work and check which performs best.
4. Evaluate the model on the test data and print the results.

## Results and Analysis
After running the classifiers, various metrics are calculated and printed:
* A graph displaying the relationship between the number of neighbors and the accuracy score of the model. Note that the best number of neighbors lies between ~60-70, and if we use more neighbors, the model will start to underfit.
* A confusion matrix displaying correct and incorrect predictions from the model, based on each of the labels of New York, London, and Paris.

### K-Nearest Neighbors Tweet Location 
![image](https://github.com/WilhenAlbertoHM/Tweets-Classification/assets/92064680/cfd4b6a7-dc72-4b3f-ac52-6d1edb6784f0)

### Naïve Bayes Viral Tweets
![image](https://github.com/WilhenAlbertoHM/Tweets-Classification/assets/92064680/b83af012-2816-4fa2-b86b-952f8a05e849)

## Future Improvements
We can check other classifiers for future improvements to see how they perform with our data. Also, we can explore the data and see if there are any other relationships we might've missed, especially for the viral tweet classifier - maybe we can check if the account that wrote the tweet has the blue check or not, the number of comments, and many more features.

## Acknowledgements
This project comes from the Codecademy course I'm currently taking, `Build a Machine Learning Model with Python - Skill Path`. This was published on GitHub for educational purposes regarding the topics of machine learning.
