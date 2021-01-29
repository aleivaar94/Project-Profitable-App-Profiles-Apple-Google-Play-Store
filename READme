# Understanding Profitable App Profiles from the Apple and Google Play Store
Analyse Android and iOS app data to help developers understand what type of apps are likely to attract more users.

## Context

Most apps are free to download and use; therefore, the main source of revenue is from in-app adds. This means that revenue is directly proportional to the number of users that use our app. The more users, the more revenue.

## Objective

The objective of this project is to analyse Android and iOS app data to help developers understand what type of apps are likely to attract more users to make data-driven decisions with respect to the kind of apps they build.

## Approach
1. Data Collection
    - Google Play Store is sourced from [Dataquest](https://dq-content.s3.amazonaws.com/350/googleplaystore.csv).
    - Apple Store data is sourced from [Dataquest](https://dq-content.s3.amazonaws.com/350/AppleStore.csv).
2. Open and Explore the Data
    - Data is opened and explored as a list of lists.
3. Delete wrong data
    - The Google Play dataset has a discussion highlighting some errors in the data. These errors will have to be deleted.
4. Removing Duplicate Entries
    - Some data is collected at different time points. The data point with the highest number of reviews will be kept.
    - A dictionary is used to store the app name and select the one with the highest number of reviews.
5. Removing Non-English Apps
    - Each character we use in a string has a corresponding number associated with it. For instance, 'a' is 97, character 'A' is 65. Therefore, each app with a name containing a symbol that is not commonly used in English text will be removed.
    - A function is built to detect whether a character belongs to the set of common English characters or not. If the number is equal to or less than 127, then the character belongs to the set of common English characters (ASCII range).
6. Isolating Free Apps
    - A For Loop with a conditional statement is used. If the price is 0, it is stored in a list.
7. Understanding Apps by Genre
    - A frequency table is created to count the genres in the dataset.

## Results
-  Building an app around a popular book can be profitable. However, special features besides the raw version of the book must be added. This might include daily quotes from the book, an audio version of the book, quizzes on the book, a forum where people can discuss the book, etc.
