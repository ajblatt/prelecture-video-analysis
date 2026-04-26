---
# Do not edit the text between these lines!
layout: default
---
<span style='font-family:Times New Roman'>

# Summary:

## Introduction:
This analysis investigates whether students with less prior programming experience are more likely to support the implementation of pre-lecture videos in the University of North Carolina at Chapel Hill’s COMP 110 (Introduction to Programming) course.

Pre-lecture videos can offer significant benefits by allowing students to learn the concepts at their own pace, making class time more interactive, and providing an additional resource for reviewing material before quizzes.


## Method:
Using survey data from two sections of COMP 110 (n = 764), taught by Dr. Hinks and Dr. Alyssa, I examine the relationship between prior programming experience and the students’ ratings of pre-lecture videos.

The variable prior_exp categorizes students by experience level: None to less than one month, 2-6 months, 7-12 months, 1-2 years, and Over 2 years. The variable pre_lecture_videos measured perceived helpfulness of pre-lecture videos on a scale from 1 to 7, where 1 indicates the lowest preference, and 7 the highest.

To analyze this relationship, I applied a helper function I created, average_by_category, which calculates the average for each experience grouping. I then use the seaborn package to visualize the relationship between these variables.


## Hypothesis:
If students have less prior programming experience, then they will, on average, rate pre-lecture videos as more helpful compared to students with more experience.


# Data:

## *Count* Function:
Prior Experience:
{'None to less than one month!': 478, '2-6 months': 184, '7-12 months': 52, '1-2 years': 35, 'Over 2 years': 15}

Pre-Lecture Videos Rating:
{'1': 30, '2': 27, '3': 50, '4': 94, '5': 169, '6': 144, '7': 250}

## *Average* Function:
{'None to less than one month!': 5.527, '2-6 months': 5.016, '7-12 months': 5.212, '1-2 years': 4.8, 'Over 2 years': 4.333}


<!-- # This is a big header

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="<custom-path>/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

<!-- ## This is a small header

This is basic paragraph text.