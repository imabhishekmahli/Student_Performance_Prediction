# Student_Performance_Prediction

## 1. Project Description

The ultimate goal of any educational institution is offering the best educational experience and knowledge to the students.

Identifying the students who need extra support and taking the appropriate actions to enhance their performance plays an important role in achieving that goal.

In this Model , linear regression have been used to predict the performance of the student

Keywords: Linear Regression , Student performance prediction.

## 2.Introduction

The economic success of any country highly depends on making higher education more affordable and that considers one of the main concerns for any government. One of the factors that contributes to the educational expenses is the studying time spent by students.

ML techniques can be used to forecast the performance of the students and identifying the at risk students as early as possible so appropriate actions can be taken to enhance their performance.

One of the most important steps when using these techniques is choosing the attributes or the descriptive features which used as input to the machine learning algorithm. The attributes can be GENDER,RACE/ETHNICITY,PARENTAL LEVEL OF EDUCATION,WEATHER THEY TOOK COACHING OR NOT,THEIR PAST SCORE IN SUBJECTS , STUDY TIME THEY SPENT ETC.

The activities of this research include feature engineering to create the students dataset, data collecting, data pre-processing, creating and evaluating four machine learning models, and finding the best model and analyzing the results.

## 3.The Proposed System

3.1.The first would be to collect the data from the data source.

3.2.That data would be the raw data, that contains many unwanted or missing data so we have to deal with it by data cleaning.

3.3.we have to preprocess and level the data.

3.4.The ML algorithm build a model using the train data and test data.

3.5.The ML Algorithm produces a trained model or a trained classifier that can take as an input a new data row and predicts its label.

In [2]:
df=pd.read_csv('student_data.csv')
df.head()
Out[2]:
	school	sex	age	address	famsize	Pstatus	Medu	Fedu	Mjob	Fjob	...	famrel	freetime	goout	Dalc	Walc	health	absences	G1	G2	G3
0	GP	F	18	U	GT3	A	4	4	at_home	teacher	...	4	3	4	1	1	3	6	5	6	6
1	GP	F	17	U	GT3	T	1	1	at_home	other	...	5	3	3	1	1	3	4	5	5	6
2	GP	F	15	U	LE3	T	1	1	at_home	other	...	4	3	2	2	3	3	10	7	8	10
3	GP	F	15	U	GT3	T	4	2	health	services	...	3	2	2	1	1	5	2	15	14	15
4	GP	F	16	U	GT3	T	3	3	other	other	...	4	3	2	1	2	5	4	6	10	10
5 rows × 33 columns![image](https://user-images.githubusercontent.com/107021877/197200962-a3bc128e-b42d-4f5c-b6cc-0d0789494e19.png)


