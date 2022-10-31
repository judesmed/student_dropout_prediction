# student_dropout_prediction

# Student Dropout prediction (churn)

- Type of challenge: Learning
- Duration: `2 days`
- Deadline : `dd/mm/yy H:i AM/PM`
- Team challenge: Solo project

## Mission objectives

- Build a machine learning model for dropout classification.
- Select the right performance metrics for your model.
- Tuning parameters of the model for better performance.
- Describe the results from supervised learning.

## The Mission

The human resources department of your university just got funding for a "No student left behind" program. They ask your research department to help identify the students most likely to dropout so they can reach out and provide mentorship.

As part of your preliminary research, you come across a recent paper whose dataset seems to match the data at your disposal. You decide to replicate, compare and maybe improve their study:

M. V. Martins, D. Tolledo, J. Machado, L. M. T. Baptista, V. Realinho. (2021) "Early prediction of student’s performance in higher education: a case study" Trends and Applications in Information Systems and Technologies, vol.1, in Advances in Intelligent Systems and Computing series. Springer. DOI: [10.1007/978-3-030-72657-7_16](http://www.doi.org/10.1007/978-3-030-72657-7_16) ([incomplete paper here](https://books.google.be/books?hl=en&lr=&id=K_cqEAAAQBAJ&oi=fnd&pg=PA166&ots=ZtFtOMLYDN&sig=gA5-ox1d1ZRuhsJTHJ6XFumTLOY#v=onepage&q&f=false))
 

## The dataset
A dataset created from a higher education institution (acquired from several disjoint databases) related to students enrolled in different undergraduate degrees, such as agronomy, design, education, nursing, journalism, management, social service, and technologies.

The dataset includes information known at the time of student enrollment (academic path, demographics, and social-economic factors) and the students' academic performance at the end of the first and second semesters.

The data is used to build classification models to predict students' dropout and academic success. The problem is formulated as a three category classification task **(dropout, enrolled, and graduate)** at the end of the normal duration of the course.
 

### Feature information
You can find detailed information about features used in the following [link](assets/student_dropout_features_information.pdf).

## Kaggle
For this challenge, we leverage the [Kaggle](https://www.kaggle.com/) platform to organize a friendly [competition](https://www.kaggle.com/docs/competitions) between the teams. We have already uploaded the training dataset for your convenience. However, we have held out the test set.

Here is the link to the [Student Dropout competition](https://www.kaggle.com/competitions/students-dropout).

Read the submission instructions carefully to be able to submit your work and see how your model does against the test set!


## Must-have features

- Implementation of relevant machine learning models.
- The performance metrics of the model must be clearly defined.
- Evaluation of the model's performance and definition of its limitations.
- Explanation of the results obtained.


## Deliverables

1. Publish your source code on the GitHub repository.
2. **Small powerpoint presentation (5 minutes + 5 minutes Q&A) about your findings**
3. Pimp up the README file:
   - Description
   - Installation
   - Usage
   - ⚠️ **DATA SOURCES**
   - (Visuals)
   - (Contributors)
   - (Timeline)


## Evaluation criteria

| Criteria       | Indicator                                                | Yes/No |
| -------------- | -------------------------------------------------------- | ------ |
| 1. Is complete | Relevant but short EDA.                                  | [ ]    |
|                | README is pimped.                                        | [ ]    |
|                | Your model is trained and can predict a result.          | [ ]    |
|                | Classification report.                                   | [ ]    |
|                | Comparison of your protocol and results with the paper.  | [ ]    |
| 2. Is good     | The repo doesn't contain unnecessary files.              | [ ]    |
|                | You used typing.                                         | [ ]    |
|                | **Professional** slides.                                 | [ ]    |

![You've got this!](https://media.giphy.com/media/pSktcTgdswAo0/giphy.gif)

## Useful links
- [https://www.datacamp.com/blog/top-python-libraries-for-data-science](https://www.datacamp.com/blog/top-python-libraries-for-data-science)
- [https://www.datacamp.com/tutorial/xgboost-in-python](https://www.datacamp.com/tutorial/xgboost-in-python)
- [https://www.theanalyticslab.nl/no-data-scientist-is-the-same-good-model-by-default-using-xgboost/
](https://www.theanalyticslab.nl/no-data-scientist-is-the-same-good-model-by-default-using-xgboost/)
- [https://educationaltechnologyjournal.springeropen.com/articles/10.1186/s41239-020-0177-7](https://educationaltechnologyjournal.springeropen.com/articles/10.1186/s41239-020-0177-7)
