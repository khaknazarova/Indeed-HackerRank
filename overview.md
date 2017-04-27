### Readme

This is code for HackerRank Indeed contest:
https://www.hackerrank.com/contests/indeed-ml-codesprint-2017/challenges/tagging-raw-job-descriptions
The contest has already finished when I found it, but the problem was interested. So I explored train data and tried to predict solutions at hold-out set from train.

This challenge asks for a machine learning solution to accurately assign tags given the information in the job descriptions. We are interested in only these twelve tags:

part-time-job
full-time-job
hourly-wage
salary
associate-needed
bs-degree-needed
ms-or-phd-needed
licence-needed
1-year-experience-needed
2-4-years-experience-needed
5-plus-years-experience-needed
supervising-job

Steps of data preprocessing, model calculating, my assumptions and conclusions are below.

indeed.ipynb contains the main solution and prediction evaluations with LinearSVC classifier.

base_indeed.ipynb is "work in progress" and will provide a predictions using basic vocabulary.

