# Instagram Bot 2 Notebook

This Jupyter Notebook automates various tasks on Instagram using the Selenium library.

## Overview

Instagram Bot 2 is designed to automate specific tasks on Instagram. It includes the following functionalities:

1. **Analyzing Top Instagram Handles:**
    - **Task 1:** Opens the first 10 handles when any keyword is searched and finds the top 5 with the highest number of followers.
    - **Task 2:** Calculates the number of posts these handles have done in the previous 3 days.
    - **Task 3:** Plots a graph of the number of followers (of the obtained top 5 accounts) vs the number of posts in the last 3 days.

2. **Finding Most Used Hashtags:**
    - **Task 1:** Opens the 5 handles obtained in the last automation and scrapes the content of the first 10 posts of each handle.
    - **Task 2:** Prepares a list of all words used in all the scraped posts and calculates the frequency of each word.
    - **Task 3:** Creates a CSV file `wordFreq.csv` with two columns: the word and its frequency.
    - **Task 4:** Finds hashtags that were most popular among these accounts.
    - **Task 5:** Plots a pie chart of the top 5 hashtags obtained and the number of times they were used by these bloggers (accounts) in the scraped posts.

3. **Calculating Average Followers:Likes Ratio:**
    - **Task 1:** Finds out likes of the top 10 posts of handles obtained earlier.
    - **Task 2:** Calculates average likes.
    - **Task 3:** Divides the average likes obtained by the number of followers of the handle to get the average followers:like ratio of each handle.
    - **Task 4:** Creates a bar graph to depict obtained information (Top 5 (searched keyword-related handles) vs Average followers to like ratio).

## Usage

1. **Installation:**
    - Install the required dependencies:
        ```bash
        pip install selenium matplotlib pandas
        ```
    - Download the appropriate WebDriver (e.g., ChromeDriver) and set the path.
    - Open the notebook in Jupyter and run each cell.

2. **Setup:**
    - Update credentials and other necessary details within the notebook.

3. **Run the Notebook:**
    - Open the notebook in Jupyter.
    - Run each cell to execute the Instagram automation tasks.



## Acknowledgements

- This notebook utilizes the Selenium library for web automation.
- Additional dependencies include Matplotlib and Pandas for data visualization and manipulation.
