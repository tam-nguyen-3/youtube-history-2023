# youtube-history-2023
An exploratory data analysis and visualization of a friend and my YouTube watch history. We crawled data using Google YouTube API. 

## Challenges
- The result from crawling data using Google YouTube API was two HTML files.
- Working with HTML syntax and finding a way to extract data from HTML files.

## Solutions
- We used string manipulation and regex to extract necessary information from the HTML files and export them to csv files, such as the date-time, unique YouTube video IDs, and then look up the duration and categories of the videos using the video IDs.
