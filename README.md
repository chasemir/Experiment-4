## Experiment-3: Exploring Data with Pandas and Matplotlib

### I. The Experiment

In this experiment, we used Python's Pandas Library to dive into data, exploring how to load, filter, and visualize it. The focus was on working with a student dataset and using a Jupyter Notebook to analyze it interactively. By the end of it, we wanted to understand how Pandas can help in finding patterns by selecting specific rows and columns, and how graphs could make sense of those patterns at a glance.
The tools we used were Anaconda for launching Jupyter Notebook and GitHub to store and share our work.

###II. Objectives
	•	Learn how to use Pandas to filter and manipulate datasets effectively.
	•	Use Seaborn and Matplotlib to create visualizations that can reveal trends in the data.
 
### III. Problem 1: Working with the Data
Guidlines
	•	I uploaded a CSV file that contained scores of students across several subjects and filtered the data to look at specific aspects.
	•	Created visualizations that showed:
	•	How average scores compare across different Tracks.
	•	Whether there is a difference in scores based on Gender.
	•	How scores vary based on the students’ Hometowns.
 
    I. Discussion
      Uploading the CSV File:
      	•	The CSV file was loaded into a DataFrame called board using Pandas. This allowed us to store all the data (like scores in Math, Electronics, and other subjects) in one structure.
      Filtering the Data:
      	- I filtered the data to answer questions like:
      	- Who are the students in the Instrumentation track from Luzon with high Electronics scores?
      	- Then, we calculated the average score for each student across several subjects, which gave us a clearer picture of their overall performance.
      Visualizing the Data:
      	- I used three key graphs to analyze our data:
      	1.	Violin Plot: Showed how the average scores were spread across different tracks.
      	2.	Bar Plot: Compared the average scores of male and female students.
      	3.	Line Plot: Tracked the average scores of students from different hometowns for both males and females.
     
### IV. Problem 2: Digging Deeper into the Data
  Guidlines
  	•	I created filters to find very specific student groups. For example, we looked for:
  	•	Students in the Instrumentation track from Luzon with Electronics scores over 70.
  	•	Female students from Mindanao who had an overall average score above 55.
   
      I. Discussion
        Using Pandas made it easy to zoom in on specific groups in the dataset and answer detailed questions like which students were excelling in certain subjects or how well specific groups were doing overall.
 
  ### V. Does Track, Gender, or Hometown Make a Difference in Average Scores?
  Here’s what I found based on the visualizations:
  	•	Track: From the violin plot, the average scores across the three tracks (Instrumentation, Communication, and Microelectronics) were pretty similar. This tells us that the chosen track in college doesn’t really         impact the average score much.
  	•	Gender: The bar plot showed that male and female students had nearly identical average scores, meaning gender doesn’t have much effect on the average score.
  	•	Hometown: The line plot revealed that students from Luzon had slightly higher average scores than those from Mindanao and Visayas, but the difference wasn’t drastic. This suggests that hometown may have a small         influence, but it’s not a major factor.
   
      In Short:
      	•	Track and Gender don’t seem to play a big role in determining average scores.
      	•	Hometown shows a slight difference, with Luzon students doing a little better on average, but it’s not a huge gap.
