# Machine Learning Workshop for Psychologists

### September 14-16

![image](https://danielmiessler.com/images/Screen-Shot-2016-12-21-at-9.05.14-PM.png)



## Concept

Machine learning is a powerful technique effectively used across many fields for data analysis. As psychgologists much of our work involves the analysis of data, so adding this tool to our repetoire has the potential to facilitate our research goals, or even provide us with ideas for new avenues of inquiry.

While there are plenty of machine learning tutorials online, not to mention classes in the U of T computer science department, it is easy to lose momentum (i.e. get busy) with online classes, and a full-on upper level computer science course can be daunting (and it may be hard to see direct links to psychology research). For these reasons we felt that providing an intensive, hands on, approach focussed on applications in the field of psychology could help overcome many of the limitations of these alternate learning approaches. 

#### Goals

* Provide conceptual **understanding/intuition** of machine learning to psychology students
* Develop the rudiments of ML techniques in Python adopting a **hands-on** approach
* Consider **how ML can be applied** to attendees’ research practice
* Provide understanding of how to **continue progressing in ML**, post workshop
* **Build a community** of U of T psychology researchers applying ML techniques to their work



## Prep/Prerequisites

The machine learning workshop will involve the use of the programming software Python. 

In order to prepare students for the workshop, it will be strongly recommended that students engage in a variety of learning exercises in order to become familiar with the use of Python. 

Note that we may provide a pre-workshop session where we go over Python/Anaconda installation, Jupyter notebooks, and some Python basics on the THURSDAY (changed from Wednesday) evening before the workshop. More info on this will be provided to workshop attendees.



**Recommended preparation**:

1. Exercises 1-7, 13, 18-21, 27-35, 38, 39 of [Learn Python The Hard Way](https://learnpythonthehardway.org/book/ )
2. An additional, more advanced resource that has been suggested by Dr. Fogelson is [Google's Python Class](https://developers.google.com/edu/python/). 

Completion of this class will not be considered a requirement for the workshop, but will be recommended to individuals who are looking to gain particularly advanced background knowledge of Python.


**Python Installation**

1. Download the [Anaconda installer](https://www.anaconda.com/download/). We recommend Python 3.
2. Choose `Install for me only`.
3. By default, Anaconda will prepend itself to your PATH – leave this as is.
4. When Anaconda has finished installing, open a terminal (Linux, OSX), or the Anaconda Prompt (Windows).
5. Type `conda update conda`, hit enter, and then type "y" (and hit enter).
6. Type `conda update anaconda`, hit enter, and then type "y" (and hit enter).



**Jupyter Notebooks**

With Jupyter, you intersperse code, output, explanatory text, and figures in one big file called a "notebook." Notebooks are a convenient format to explore a language and to share examples of code.

To run a notebook:

1. Open the Terminal (Linux, OSX) or Anaconda Prompt (Windows) and type `jupyter notebook`.
2. The notebook will open a new tab in your default browser. **Do not close the terminal**, as this will also shutdown the notebook.
3. When it has loaded, click on "New" (at the top right) and then "Python3" to create a new notebook.



**Valuable Resources**:

1. Short on time? Try this [10-minute tutorial](https://try-python.appspot.com/). When it loads, type `tutorial` and press Enter to start.
2. [Useful exercises](https://bids.github.io/2016-01-14-berkeley/python/00-python-intro.ipynb) to get acquainted with Python in Jupyter notebook format. Save this file in a directory, navigate in terminal to that directory, and then enter at the command prompt `$ jupyter notebook`.
3. Want to go further? Check out the free online book by Jean Mark Gawron [Python for the Social Sciences](http://www-rohan.sdsu.edu/~gawron/python_for_ss/course_core/book_draft/Preface/Preface.html). 

> Installation and resource suggestions taken from Berkeley's [Python Practice](http://python.berkeley.edu/) working group.



## Sign Up

Please sign up [here](https://goo.gl/forms/1jR81XTKAF9kixBe2) ASAP. 

We hope to be able to accommodate all that are interested, but space is limited.



## Instructor

The course is being taught by Dr. Sergey Fogelson.

Sergey received his [PhD in cognitive neuroscience](https://scholar.google.com/citations?user=PeJIVXgAAAAJ&hl=en) from Dartmouth College and since that time has been working both as a data-scientist (currently he is the VP of data science at Viacom) and machine learning educator.

Here is a bit of info on [one of the classes he teaches at Metis](https://www.thisismetis.com/blog/instructor-sergey-fogelson-on-importance-of-machine-learning-ai-principles) in New York.



## Questions

Email `daniel.j.wilson@gmail.com` with any questions.



## Schedule

* Note: Where **Break**, **Lunch**, and **Dinner** are included in the schedule they **will be provided** for all participants.

#### Day 1: Friday

| Time          | Topic                  | Session                                     |
| ------------- | ---------------------- | ------------------------------------------- |
| 09:00 - 10:30 | Intro to ML in Python  | Data preprocessing and handling             |
| 10:30 - 10:45 |                        | **Break** (coffee/snacks)                   |
| 10:45 - 12:15 | Intro to ML in Python  | Using linear and nonlinear models in Python |
| 12:15 - 12:30 |                        | **Break** (coffee/snacks)                   |
| 12:30 - 13:00 | Intro to ML in Python  | Overflow time/questions                     |
| 13:00 - 14:00 |                        | **Lunch**                                   |
| 14:00 - 15:30 | Applying ML techniques | Bias/variance tradeoff, regularization      |
| 15:30 - 15:45 |                        | **Break** (coffee/snacks)                   |
| 15:45 - 17:00 | Applying ML techniques | Apply techniques to a new dataset OYO       |
| 17:30 - 18:30 | Panel Discussion       | Machine Learning in Psychology              |
| 18:30 - ...   |                        | **Drinks**                                  |

#### Details

##### Data preprocessing and handling

> Using an example dataset, the first 90 minutes of the course will be spent to build comfort with data manipulation in Python and the typical ML workflow on non-psychology data. Material that will be covered during this time includes basic data handling, selection, visualization and inspection, and preprocessing strategies for all datasets (normalization, centering, missing value handling/imputation). 

[Proposed Dataset](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease)

##### Using linear and nonlinear models in Python

> Now that this dataset has been explored and processed, we will learn to build and interpret 3 different models on that dataset:
>
> 1. logistic regression
> 2. support vector machines
> 3. random forests.
>
> Each algorithm’s benefits and weaknesses will be discussed.

##### Bias/Variance tradeoff, regularization

> Discuss bias/variance tradeoff and model complexity (ca. 45 minutes).
>
> Regularization as a way to pare down model complexity for complicated models (ca. 45 minutes)

##### Apply techniques to a new dataset OYO

> Using everything you’ve learned to build an ML model on another example dataset. What’s the best you can do?
>
> **Goal**: predict whether a given person makes more than 50K given demographic data.

[Proposed Dataset](https://archive.ics.uci.edu/ml/datasets/Census+Income) 

##### Machine Learning in Psychology

> General presentation on the applications of Machine Learning in Psychology, with examples that span social psychology to cognitive neuroscience, and including examples from EEG, MEG and fMRI.
>
> This presentation would be **open to students & faculty not participating in the workshop**.

##### Drinks

> Location TBD



#### Day 2: Saturday

| Time          | Topic                       | Session                                      |
| ------------- | --------------------------- | -------------------------------------------- |
| 10:00 - 12:00 | Natural Language Processing | Sentiment analysis of tweets                 |
| 12:00 - 13:00 |                             | **Lunch**                                    |
| 13:00 - 14:30 | Supervised Classification   | Decoding models, confusion matrices          |
| 14:30 - 14:45 |                             | **Break** (coffee/snacks)                    |
| 14:45 - 15:30 | Supervised Regression       | Predicting a continuous value                |
| 15:30 - 15:45 |                             | **Break** (coffee/snacks)                    |
| 15:45 - 16:30 |                             | Encoding and regularization                  |
| 16:30 - 17:30 | Applying ML techniques      | Apply techniques OYO                         |
| 17:30 - 18:00 |                             | **Dinner**                                   |
| 18:00 - 19:00 | Presentations               | Students introduce data they plan to work on |
| 19:00 - ...   | Hack Night                  | Apply ML analyses to your data               |

#### Details

##### Sentiment analysis of tweets

> We will use a twitter sentiment analysis task to explore preprocessing strategies for text data.
>
> Three example preprocessing strategies will be used:
>
> Count-based transformations:
>
> * countvectorizer
> * TFIDF
>
> Word-embedding based approach:
>
> * word2vec

[Dataset](https://www.dropbox.com/s/byzr8yoda6bua1b/2017_English_final.zip)

##### Decoding models, confusion matrices

> Replication of Haxby 2001
>
> Using nilearn package to start by building a decoding model - faces vs. houses, using an ROI approach., ask students to do the same with other categories.
>
> Now, extend this to all categories within an ROI, look at confusion matrix; understand what a confusion matrix is; Multidimensional scaling to visualize confusion matrices.
>
> Using a “searchlight” to uncover local information.

##### Predict a continuous value

> Replication of Jimura 2012
>
> Using preprocessed neural data to predict a continuous value (amount of expected gain on a gambling task) 

##### Encoding and regularization

> Replication of Miyawaki 2008
>
> Example of using encoding techniques with Miyawaki 2008 problem - applying regularization in ML; compare different regularization approaches to the same dataset. 

##### Apply techniques OYO

> Can you do the same thing with another dataset?
>
> For example, predicting age from structural data?

##### Students introduce data they plan to work on

> Informal presentation/discussion of data and analysis plans by all students

##### Hack Night

> Students are encouraged to remain around and try to make progress on their dataset



#### Day 3: Sunday

| Time          | Topic                   | Session                            |
| ------------- | ----------------------- | ---------------------------------- |
| 9:00 - 10:30  | Dimension reduction     | ICA/PCA                            |
| 10:30 - 10:45 |                         | **Break** (coffee/snacks)          |
| 10:45 - 11:30 | Programming efficiently | Intro to Pipelines for ML          |
| 11:30 - 13:30 | Project work            | Apply ML analyses to your data     |
| 13:30 - 14:00 |                         | **Lunch**                          |
| 14:00 - 16:00 | Presentations           | Summary of data analyses performed |
| 16:00 - 17:00 |                         | Wrap-up                            |

#### Details

Note that students can opt to spend their time working on their project instead of following the morning classes.

##### ICA/PCA 

> An introduction to independent and principal components analysis.

##### Intro to pipelines for ML 

> Facilitator will spend some time teaching students about ML pipelines using an example dataset.

##### Project Work 

> Facilitator will float, providing help/tips as needed.

##### Presentations 

> Students will present analyses that they’ve conducted during the group work periods of the workshop (this will be pretty informal).  
>
> During presentations, students will be encouraged to reflect on what they’ve gained from the workshop and to express ways in which they may be able to use ML techniques in the future.

##### Wrap-up 

> Course wrap-up and general discussion on how to apply ML techniques in the future.

