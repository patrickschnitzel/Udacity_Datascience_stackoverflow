# Stackoverflow user base survey data study
## Motivation

This study is a part of a project in Udacity Data Scientist Nanodegree. The analyzed dataset is the 2017 study from stackoverflow: https://www.kaggle.com/stackoverflow/so-survey-2017. The challenging thing of this project is that you have to come up with your own business questions. I am curious about the differences of programming languages. This dataset has been analysed often and a lot of the serious questions were already asked. So the decision is to take a less serious aproach in giving advice on what programming language to learn. This is a good use case where analysing the difference of languages is required.

Looking at the survey the following questions are viable:
What language to learn when
- it is all about money? Currently financial freedom and early retirement are hot topics. Interesting questions to answer this are *Salary*, *ExpectedSalary* and *Overpaid*
- you want to care for your family, your private hobby and still be accepted? Interesting questions to answers this are *ProgramHobby*, *JobSecurity* and *CompanySize*
- you want to be special and stand out? This can be answered by looking at how different the answers of all questions are grouped by programming language

## Content

- Jupyter Notebook of the study.
- Data set downloaded from Kaggle.

## Libraries

The following Python libraries used

- Numpy
- Pandas
- Matplotlib
- Seaborn

## Conclusion
The difference regarding different languages is quite interesting:
![Alt text](plots/language_diffs.png?raw=true)

### Answers to the questions
You want to be special and stand out? Then VB.NET or Scala is your language of choice
You want to earn a lot of money? Then PHP, VB.NET and Assembly are languages to avoid. Your choice should be Go, Perl or Scala
You want to a safe and chill 9 to 5 job? Then avoid Go and CoffeeScript

## Licensing, Acknowledgements

This project is published in 2021 under MIT license. Credits to Kaggle for the data and to Udacity for the task :)

Summary of the study can be found here: https://medium.com/@patrick.schnizel/chose-your-programming-language-2603366dfb53