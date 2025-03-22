# Report Title:

Visualizing Burmese People's Health Data Clearly with Python

Introduction:

In this project, I used Matplotlib in Python to make simple graphs to clearly show health information about Burmese people. This helps me and others easily understand data through visuals.

Goal of This Project:

I wanted to clearly see how age connects to the number of symptoms people had and how health cases changed from 2020 to 2023.

Scope of This Project:

I used a small dataset of four Burmese people's names, ages, symptoms, temperatures, and health cases over four years.

Advantages:

I learned that Matplotlib makes colorful, clear graphs that help me quickly see important information.

Uses:

I can use Matplotlib to:

•	Create clear graphs and charts

•	Visualize data so it's easy to understand

•	Present data visually

When to Use Matplotlib:

I use Matplotlib whenever I want to show data clearly in graphs for my projects or presentations.

Why I Use Matplotlib:

I use Matplotlib because visuals like graphs help me quickly understand data without reading lots of numbers.

Step-by-Step Process:

Step 1: Define Project / Scope I decided clearly what data I wanted and how I would present it using Matplotlib.

Step 2: Gather Data I collected data about people's names, ages, symptoms, temperatures, and cases from 2020 to 2023.

[burmese_people_symptoms.csv](https://github.com/user-attachments/files/19402449/burmese_people_symptoms.csv)
[burmese_health_cases.csv](https://github.com/user-attachments/files/19402448/burmese_health_cases.csv)


Step 3: Organize Data I neatly organized this data using pandas into easy-to-read tables.

Step 4: Create Graphs I made clear, simple graphs using Matplotlib.

Step 5: Add Titles and Labels I labeled my graphs clearly with titles and labels to explain the data.

Step 6: Analyze the Graphs I carefully looked at the graphs to understand the patterns and results.

Step 7: Asking and Answering Questions About the Project I wrote clear questions and answers about my project to make sure it is understandable.

Differences:

I learned that graphs make understanding data faster and clearer than tables full of numbers.

Images:

I added clear graphs showing:

•	Age compared to the number of symptoms.

•	Health cases over different years (2020-2023).

Code

# Create data with people's names, ages, and symptoms
data = {
    "Name": ["Thi Han Soe", "Aung Zaw Myat", "Zaw Lin Myat", "Tayza Myat"],
    "Age": [28, 55, 46, 58],
    "Symptoms": [3, 1, 4, 2]
}

# Plot age vs symptoms
plt.plot(df['Age'], df['Symptoms'], marker='o', linestyle='-', color='red')
plt.xlabel("Age")
plt.ylabel("Number of Symptoms")
plt.title("Age vs Number of Symptoms (2020-2023)")
plt.grid(True)
plt.show()

 ![image](https://github.com/user-attachments/assets/ebf3a9e5-7ef0-4d44-be67-f75592d6ba11)

Conclusions

I noticed Zaw Lin Myat, who is 46 years old, has more symptoms (4) than Aung Zaw Myat, who is older at 55 but has fewer symptoms (1).
I learned from the graph that younger age doesn't always mean fewer symptoms.


Code

import matplotlib.pyplot as plt  # I import matplotlib for drawing graphs.

years = [2020, 2021, 2022, 2023]  # I list the years clearly.
cases = [500, 650, 800, 700]  # I list the number of cases clearly.

# I draw a simple line graph with dots to show health cases over the years.
plt.plot(years, cases, marker='o', linestyle='-', color='blue', label='Cases')

plt.xlabel("Year")  # I label the bottom axis clearly.
plt.ylabel("Cases")  # I label the side axis clearly.
plt.title("Health Data for Burmese People (2020-2023)")  # I add a clear title.

plt.grid(True)  # I add grid lines for easy reading.
plt.legend()  # I clearly explain the lines on the graph.
plt.show()  # I display the graph clearly.

 ![image](https://github.com/user-attachments/assets/17475f92-f527-446a-8511-f425617b29a0)

Conclusions

I saw that younger people, like Thi Han Soe (28 years old), had more symptoms than older people like Aung Zaw Myat (55 years old). I learned from the chart that age and number of symptoms are connected.

Asking and Answering Questions About the Project:

1.	What did I use to create charts and graphs?

•	I used Matplotlib in Python.

2.	What kind of data did I use?
	
•	I used people's names, ages, symptoms, temperatures, and health cases.


3.	Can I name one column from my data table?
	
•	"Age."

4.	What does the "Age" column tell me?
	
•	It shows how old each person is.

5.	What colors did I use in the first graph?

•	I used red.

6.	What does the x-axis show in the first graph?

•	It shows people's ages.

7.	Why did I add grid lines?

•	They make the graphs easier to read.

8.	What do the bubbles mean on my graphs?
    
•	They represent each person or data points clearly.

9.	What does the title of the first graph explain?
    
•	It explains that I am comparing people's ages with how many symptoms they have.

Conclusion:

I learned how to use Matplotlib to create easy-to-understand graphs. My graphs clearly show relationships and trends in health data, helping anyone understand information quickly and easily.
