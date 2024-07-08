# Data-Analysis-and-ML-with-MATLAB

This repository contains two tasks:

## Task 1

### Problem Statement

The objective is to create a labeled dataset for the detection of blue whale sounds. This involves collecting audio signals containing blue whale sounds and signals without blue whale presence. Using Matlab's Signal Labeler app this task involves collecting, annotating, and organizing audio data from various sources, labeling specific features of blue whale sounds such as moans and trills, and extracting relevant acoustic features for classification. 

### Methodology

- Data Collection : Audio signals were sourced from online databases, field recordings.

- Annotation and Labeling: Using Matlab's Signal Labeler app, each audio signal was labeled. Moan and trill regions of blue whale sounds were marked with their start and end times. If no trill was discernible, the trill annotation was assigned values of 0 for start time, end time, and duration.

- Feature Extraction: Moan and trill timings, durations, and average spectral centroid, were extracted from each audio signal using Matlab scripts. These features are crucial to distinguish between blue whale and non-blue whale sounds.

- Dataset Organization: The dataset was structured in CSV format, with each row representing an audio recording and its corresponding annotations and extracted features. A "Label" column was included to classify each recording as either containing blue whale sounds (1) or not (0).


## Task 2

### Problem Statement

Build a predictive data model to analyze and understand the socio-demographic influences on student grades on a given data set  containing attributes of 396 Portuguese students. The goal is to identify which socio-demographic properties influence the grades(G3) of the students and if we can do something about it to influence the grades of the students.

### Description Of Dataset

This data approach student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school-related features and it was collected by using school reports and questionnaires. Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). 

### Methodology

There is a great need to develop an appropriate solution to assist students retention at higher education institutions. Early grade prediction is one of the solutions that have a tendency to monitor students’ progress and will lead to improving the students’ learning process.

Different models can be developed to predict students’ grades in the enrolled courses, which provide valuable information to facilitate students’ retention in those courses. This information can be used to early identify students at-risk based on which a system can 1 suggest the instructors to provide special attention to those students.

Various packages such as cufflinks, seaborn & matplotlib used to represent the data along with different attributes graphically to analyse the dataset for predicting the Final Grade(G3).

### Machine Learning Algorithms used

1. Linear Regression
2. ElasticNet Regression
3. Random Forest
4. Extra Trees
5. SVM
6. Gradient Boosted
7. Baseline

### Experimental Results

- Count Plot for Student Gender Attribute
- Kernel Density Estimation for Age of Students.
- Count PLot for Male & Female students in different age groups.
- Count Plot for students from Urban & Rural Region.
- Does age affect final grade?
- Do urban students perform better than rural students?
- Previous Failures vs Final Grade(G3)
- Family Education vs Final Grade(G3)
- Higher Education vs Final Grade(G3)
- Go Out vs Final Grade(G3)
- Does gender affect grades?
- Reason vs Students Count
