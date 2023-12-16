# Matplotlib_function_Python_project_about_Myanmar

                                        TITLE OF THE REPORT
Report Title: Sample data for Burmese people's
Matplotlib In Python

Introduction:
This report is about Matplotlib, which is a library of Python programming used for creating graphs and visualizations.

Advantages:
Matplotlib allows us to create colorful images and charts with our data in a different way.

What can we use Matplotlib to do? :
We can use Matplotlib to create colorful images charts, and plots and visualize the data in a different way.

When to use Matplotlib? :
We can use Matplotlib when we want to create our visual data information in a visual way we can do it.

Why do we use Matplotlib in Python? :
Because it will show us the data information of the graph that we create and understand the data easily.


# This is the code that I did
import pandas as pd
import matplotlib.pyplot as plt

# Sample data for Burmese people's AEFI Case Line Listing
data = {
    "Name": ["Thi Han Soe", "Aung Zaw Myat", "Zaw Lin Myat", "Tayza Myat"],
    "Age": [28, 55, 46, 58],
    "Symptoms": [3, 1, 4, 2],
    "Temperature": [99.5, 100.2, 98.9, 101.0]
}

# Create a DataFrame using the sample data
df = pd.DataFrame(data)

# Create a line chart to visualize the age and number of symptoms over time
plt.plot(df['Age'], df['Symptoms'], marker='o', linestyle='-', color='red')
plt.xlabel("Age")
plt.ylabel("Number of Symptoms")
plt.title("Age vs Number of Symptoms (2020-2023)")  # Updated title
plt.grid(True)  # Add grid lines for better visualization

# Add labels to the bubble representing people's names
for i, name in enumerate(df['Name']):
    plt.annotate(name, (df['Age'][i], df['Symptoms'][i]), textcoords="offset points", xytext=(0,10), ha='center')

# Show the line chart with bubbles
plt.show()


These are all questions and images of the line chart of Matplotlib for the Python Project.

[seperate_questions_and_images_Matplotlib_project.docx](https://github.com/AuntBawHein/Matplotlib_function_Python_project_about_Myanmar/files/13692212/seperate_questions_and_images_Matplotlib_project.docx)


And these are all Python codes sir, thank you very much.
[report_matplotlib_python_presentation (1).docx](https://github.com/AuntBawHein/Matplotlib_function_Python_project_about_Myanmar/files/13692219/report_matplotlib_python_presentation.1.docx)






























 
 
                                   


