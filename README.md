Chloe Fugle (chloe.m.fugle.23@dartmouth.edu), 6/7/22, CS72 Final Project 

A searchable database of the Dartmouth College courses and their descriptions to allow students to more easily find classes related to their interests. The search uses a TF-IDF and WordNet algorithm to return the most relevant courses.  

### Instructions:  
To run the program, select Runtime -> Run all. Please note that due to the structure of the Dartmouth Timetable website, the program will take about 15 minutes to compile a searchable database.   
To avoid this wait time, a file "course_desc.txt" has been included with the submission. This file contains the scraped and processed text. Upload the file to the Google Colab runtime using the file icon to the left and run every cell except for the cell titled "Full web-scraper."  
Once the pre-processing functions have been run, the search function (the last cell) can be run as many times as desired to search for courses. Courses are listed in order of relevance to the user's search.
