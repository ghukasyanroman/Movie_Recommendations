# Movie Recommendations

This project is a collaborative effort by a group of first-year Data Science students during the Introduction to Computer Science course. It represents our first significant project using Python.

## Overview

The Movie Recommendation System is designed to help users discover new movies based on their interests and preferences. Users provide their interested categories, and then select their preferred category from the given options. The system then searches a CSV dataset containing information about movies and provides the top 3 recommendations based on the user's input.

## Features

- **User Input**: Users specify their favorite movie categories and their preferred category.
- **Recommendations**: The system generates the top 3 movie recommendations based on the user's preferences.
- **HTML Report**: The system creates an HTML report containing analytical graphs based on the dataset and the top 3 movie recommendations personalized to the user's preferences.


## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)

## Installation

To run this project, you need to install two libraries: Pandas and Matplotlib. You can install them using the following commands:

```bash
pip install pandas
pip install matplotlib
```


## Usage

To use the Movie Recommendation System, follow these steps:

1. Download the CSV file containing the movie dataset.

2. Open the `MovRec_Project.ipynb` file in Jupyter Notebook or any compatible notebook viewer.

3. Locate the cell containing the `file_path` variable and update it with the path to the folder containing your CSV dataset.

4. After updating the `file_path`, find the section (usually at the bottom) containing the code to generate the HTML report. Update the paths to specify the location from which the generated images should be taken.

5. Run each cell in the notebook by pressing Shift + Enter, or use the "Run All" option from the menu to execute the entire notebook.

6. Follow the prompts to provide your interested categories and preferred category.

7. Once the notebook finishes execution, access the generated HTML report to view analytical graphs and insights with the photos correctly linked.

That's it! You're ready to explore movie recommendations based on your preferences.


