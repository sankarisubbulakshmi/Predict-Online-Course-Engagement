# Predict Online Course Engagement Dataset
## Overview
This dataset contains information about user engagement in online courses. 
It includes details such as the time spent on courses, the number of videos watched, quizzes taken, quiz scores, completion rates, and device types.

## Data Description
The dataset includes the following columns:

1. UserID: Unique identifier for each user.
2. CourseCategory: Category of the course (e.g., Health, Arts, Science).
3. TimeSpentOnCourse: Total time spent on the course by the user (in hours).
4. NumberOfVideosWatched: Total number of videos watched by the user.
5. NumberOfQuizzesTaken: Total number of quizzes taken by the user.
6. QuizScores: Average score of the quizzes taken by the user.
7. CompletionRate: Percentage of the course completed by the user.
8. DeviceType: Type of device used to access the course (e.g., 1 for Desktop, 0 for Mobile).
9. CourseCompletion: Indicates whether the user has completed the course (1 for Yes, 0 for No).

## Learning outcomes
This dataset can be used for various analytical tasks:

The "Predict Online Course Engagement" dataset is primarily suited for supervised learning. 
This is because it contains labeled data (e.g., CourseCompletion), which can be used to train models to predict outcomes based on the other features.

You can build models to predict whether a user will complete a course (CourseCompletion) based on their engagement metrics like TimeSpentOnCourse, NumberOfVideosWatched, NumberOfQuizzesTaken, etc.
You can also predict QuizScores or CompletionRate based on other features.

However, you can also use this dataset for unsupervised learning tasks, such as clustering users based on their engagement patterns to identify distinct user segments or behavior patterns.

Therefore, the dataset can be used for both supervised and unsupervised learning tasks, but its primary use case aligns more with supervised learning.

## Data Source
The dataset was sourced from kaggle
