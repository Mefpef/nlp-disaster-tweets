
# NLP with Disaster Tweets (group project)
Group solution to the Kaggle problem titled "Natural Language Processing with Disaster Tweets". The problem is to classify text data from 10,000 tweets into one of two groups: representing tweets about real natural disaster (1), tweets that are not about actual disaster (0).

## Contents
1. [🚀 How to run](#-How-to-run)
2. [👨‍💻 Contributing](#-Contributing)
3. [📂 Directory Structure](#-Directory-Structure)
4. [🔗 Related Projects](#-Related-Projects)
5. [🎓 Learning Materials](#-Learning-Materials)
6. [📅 Development Schedule](#-Development-Schedule)
7. [🆕 Changelog](#-Changelog)
8. [🤖 Stack](#-Stack)
9. [⭐ Theory](#-Theory)
10. [📝 Examples](#-Examples)
11. [⚙ Configurations](#-Configurations)
12. [💡 Tips](#-Tips)
13. [🚧 Warnings](#-Warnings)
14. [🧰 Troubleshooting](#-Troubleshooting)
15. [📧 Contact](#-Contact)
16. [📄 License](#-License)

## 🚀 How to run
In the first iteration of the project, all there is to running the project is downloading a Jupyter notebook from directory "notebooks" and launching it with Jupyter.
Jupyter is available for download as a part of Anaconda suite from https://www.anaconda.com/.

When feeding a Jupyter notebook with data, use data provided in directory "train_split" [here](https://github.com/SzymkowskiDev/nlp-disaster-tweets/tree/master/data/train_split).

### Setup
<li>Create a virtual environment using <code> virtualenv venv </code>
<li>Activate the virtual environment by running <code> venv/bin/activate </code>
<li>On Windows use <code> venv\Scripts\activate.bat </code>
<li>Install the dependencies using <code> pip install -r requirements.txt </code>

## 👨‍💻 Contributing
* [SzymkowskiDev](https://github.com/SzymkowskiDev)
* [OlegTkachenkoY](https://github.com/OlegTkachenkoY)
* [laplasjan](https://github.com/laplasjan)
* [PanNorek](https://github.com/PanNorek)

## 📂 Directory Structure
    ├───dashboard
    ├───data
    │   └───original
    │   │   ├───test.csv
    │   │   └───train.csv
    │   └───train_split
    │       ├───python
    │       ├───test_new.csv
    │       └───train_new.csv
    ├───models
    │   └───production
    │       └───best_performing.py
    ├───notebooks
    └───reports
        ├───EDA.ipynb/.doc
        ├───Preprocessor_comparison.ipynb/.doc
        └───Tests_of_pre_preprocessing.ipynb/.doc

## 🔗 Related Projects
* Kaggle problem: ["Natural Language Processing with Disaster Tweets"](https://www.kaggle.com/competitions/nlp-getting-started/overview)

## 🎓 Learning Materials
❗ More resources are available on Team's google drive: discordnlp7@gmail.com, ask a team member for password ❗
❗ Also check [the repo's wiki](https://github.com/SzymkowskiDev/nlp-disaster-tweets/wiki)
* A wonderful book on the basics of NLP ["Speech and Language Processing"](https://web.stanford.edu/~jurafsky/slp3/)
* Kaggle's introductory tutorial to NLP [NLP Getting Started Tutorial](https://www.kaggle.com/code/philculliton/nlp-getting-started-tutorial/notebook)
* How does CountVectorizer work? [towardsdatascience.com article](https://towardsdatascience.com/basics-of-countvectorizer-e26677900f9c)


## 📅 Development Schedule
**Version 1.0.0**

- [X] First Solution to the Kaggle's problem as a Jupyter notebook
    
 **Version 1.1.0**

- [ ] Improved production model
    - [ ] Selecting current best performing model
    - [ ] Exploratory Data Analysis
    - [ ] Comparison of preprocessors (vectorizers)
    - [ ] Testing influence of data pre preprocessing methods
    - [ ] Assembling a better model
    
**Version 2.0.0**

- [ ] Deployment of a blank dashboard
- [ ] Web app representing the solution to the problem

## 🆕 Changelog
A changelog is a file which contains a curated, chronologically ordered list of notable changes for each version of a project.

## 🤖 Stack
* Python
* pandas
* scikit-learn

## ⭐ Theory
This section deals with the theory behind NLP classification relevant to our twitter data.

⭐ **Choosing data preprocessing method**

Machines cannot understand characters and words. So when dealing with text data we need to represent it in numbers to be understood by the machine. Countvectorizer is a method to convert text to numerical data.
    
* CountVectorizer from scikit learn module
* tf–idf ["Td-idf is a better method to vectorize data"](https://towardsdatascience.com/basics-of-countvectorizer-e26677900f9c)
    
⭐ **Choice of a classifier**
    
* linear_model.RidgeClassifier()

## 📝 Examples
**Example 1. Title**

Description of the example.
```javascript
CODE GOES HERE
```
  
## ⚙ Configurations
Sth

## 💡 Tips
💭 **Tip 1**

Description of tip 1.

## 🚧 Warnings

⚠️ **Warning 1**

Description of warning 1.

## 🧰 Troubleshooting
🚩 **Error 1**

Solution to error 1.

``` SOLUTION CODE ```

## 📧 Contact
[![](https://img.shields.io/twitter/url?label=/SzymkowskiDev&style=social&url=https%3A%2F%2Ftwitter.com%2FSzymkowskiDev)](https://twitter.com/SzymkowskiDev) [![](https://img.shields.io/twitter/url?label=/kamil-szymkowski/&logo=linkedin&logoColor=%230077B5&style=social&url=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fkamil-szymkowski%2F)](https://www.linkedin.com/in/kamil-szymkowski/) [![](https://img.shields.io/twitter/url?label=@szymkowskidev&logo=medium&logoColor=%23292929&style=social&url=https%3A%2F%2Fmedium.com%2F%40szymkowskidev)](https://medium.com/@szymkowskidev) [![](https://img.shields.io/twitter/url?label=/SzymkowskiDev&logo=github&logoColor=%23292929&style=social&url=https%3A%2F%2Fgithub.com%2FSzymkowskiDev)](https://github.com/SzymkowskiDev)

 [![](https://img.shields.io/twitter/url?label=/joanna-michalska/&logo=linkedin&logoColor=%230077B5&style=social&url=https%3A%2F%2Fwww.linkedin.com%2Fin%2FJoanna-Michalska%2F)](https://www.linkedin.com/in/joannamichalska17/) [![](https://img.shields.io/twitter/url?label=/laplasjan&logo=github&logoColor=%23292929&style=social&url=https%3A%2F%2Fgithub.com%2Flaplasjan)](https://github.com/laplasjan)
## 📄 License
[MIT License](https://choosealicense.com/licenses/mit/) ©️ 2019-2020 [Kamil Szymkowski](https://github.com/SzymkowskiDev "Get in touch!")

[![](https://img.shields.io/badge/license-MIT-green?style=plastic)](https://choosealicense.com/licenses/mit/)





