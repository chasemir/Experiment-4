## Experiment-3: Exploring Data with Pandas and Matplotlib

### I. The Experiment

In this experiment, we used Python's Pandas Library to dive into data, exploring how to load, filter, and visualize it. The focus was working with a student dataset and using a Jupyter Notebook to analyze it interactively. By the end of it, we wanted to understand how Pandas can help find patterns by selecting specific rows and columns and how graphs could make sense of those patterns at a glance.
I used Anaconda to launch Jupyter Notebook and GitHub to store and share our work.

### II. Objectives
1. Learn how to use Pandas to filter and manipulate datasets effectively.
2. Use Seaborn and Matplotlib to create visualizations that can reveal trends in the data.
 
### III. Problem 1: Working with the Data
Guidelines: 

1. Upload the CSV file containing students' scores across several subjects and filter the data to look at specific aspects.   
2. Created visualizations that showed:
	- How do average scores compare across different tracks?
	- Whether there is a difference in scores based on Gender.
	- How scores vary based on the students’ Hometowns.

   I. Discussion

   		Uploading the CSV File:
	  	- The CSV file was loaded into a board data frame using Pandas. This allowed us to store all the data 
	    	(like scores in Math, Electronics, and other subjects) in one structure.

     		Filtering the Data:
	      	- Who are the students in the Instrumentation track from Luzon with high Electronics scores?
	      	- Then, we calculated the average score for each student across several subjects, which gave us a clearer 
	       	picture of their overall performance.
   
	      	Visualizing the Data:
	  		- Violin Plot: Showed how the average scores were spread across different tracks.
	  		- Bar Plot: Compare the average scores of male and female students.
	  		- Line Plot: Tracked the average scores of male and female students from different hometowns.
     
### IV. Problem 2: Digging Deeper into the Data
  Guidelines
  1. Find students in the Instrumentation track from Luzon with Electronics scores over 70.
  
  2. Find Female Mindanao students with an overall average score above 55.
   
   	I. Discussion
       	 Pandas made it easy to zoom in on specific groups in the dataset and answer detailed questions like which students excelled in 
	 certain subjects or how well specific groups were doing overall.
 
  ### V. Does Track, Gender, or Hometown Make a Difference in Average Scores?
 	
   	I. Discussion 
  		Track:
   		- From the violin plot, the average scores across the three tracks (Instrumentation, Communication, and Microelectronics) 
   		were pretty similar. This tells us that the chosen track in college doesn’t impact the average score much.
     
  		Gender:
   		- The bar plot showed that male and female students had nearly identical average scores, meaning gender doesn’t have 
    		much effect on the average score.
      
  		Hometown:
   		- The line plot revealed that students from Luzon had slightly higher average scores than those from Mindanao and Visayas, 
    		but the difference wasn’t drastic. This suggests that hometown may have a small influence, but it’s not a major factor.
   
	      I.I Summary:
	      	- Track and Gender don’t play a big role in determining average scores.
	      	- Hometown shows a slight difference, with Luzon students doing a little better on average, but it’s not a huge gap.
