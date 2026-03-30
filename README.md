# Heart Disease Exploratory Data Analysis (EDA) 

## Project Overview
I dug into the Heart Disease dataset from Kaggle, cleaned it up, visualized the main features, and tried to pull out some real insights about heart health. My main goal was to figure out what actually drives heart disease and how these patterns look in real patients—not just in theory.

## Dataset Highlights
The data started out pretty hefty: 1,025 rows and 14 columns. After scrubbing out all the duplicates, I ended up with a much cleaner set—**302 rows**. The columns I really paid attention to were:

* age: Basically, how old each patient was.
* sex: Gender (1 means male, 0 means female).
* cp: Chest pain type (split into four groups).
* thalach: The highest heart rate recorded during testing.
* target: Whether a doctor diagnosed heart disease (1 for yes, 0 for no).

## Purpose of Study
Honestly, I picked this dataset because I wanted to see where AI could make a dent in helping doctors spot heart disease early. Plus, I wanted to roll up my sleeves and work with real medical numbers. Cleaning and visualizing data like this gives us a window into what’s actually happening behind clinic doors.

## Files Included
* code_file.ipynb: All the Python code and graphics, wrapped up in a Jupyter notebook.
* Dataset_Description.pdf: More info on the columns and what the project is trying to achieve.
* heart.csv: The raw data.

## Key Insights from EDA
A few things really jumped out during the analysis:
* Age: Most patients were in their 50s or hitting 60.
* Correlation: Chest pain types and max heart rate were tightly linked to heart disease. These turned out to be pretty strong predictors.
* Visuals: I made **seven plots**—heatmaps, histograms, boxplots, and more—to help make sense of it all.

It feels good to sift through actual medical numbers—patterns get clear fast, and the visuals make spotting risk factors a breeze.
