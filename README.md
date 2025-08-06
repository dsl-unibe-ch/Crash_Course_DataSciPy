# Crash course in Data Science with Python

This repository contains material for the Crash course in Data Science with Python offered by the Data Science Lab at the University of Bern. The goal of the course is to provide a quick introduction to Python and the Python ecosystem for data science. The course is designed for students with no prior programming experience. We insist here on the fact that this is a **crash course** not aiming to be exhaustive but rather to help participants getting started and e.g. to be able to follow more advanced courses in data science or machine learning. 

The course is composed of sequences of short lectures followed by practical exercises. In the short lectures, important concepts and functionalities are demonstrated via slides and live coding sessions. Participants can then practice these new concepts in coding exercises in their own interactive notebooks. Most of the course material is available in the form of Jupyter notebooks that participants can use to review concepts or as starting point for the exercises. 

## Course structure

The course is organized in four days, roughly covering the following topics:

### Day 1: Introduction

The first day of the course covers Python tooling and basic Python syntax. The goal here is to get participants ready to write Python code, and use existing libraries. THe topics covered include:
- Python installation and setup using conda
- Writing and executing Python code: VSCode and Jupyter notebooks
- Basic Python syntax: variables, data types, control flow, functions and classes
- Helping yourself: Documentation and LLMs

### Day 2: Numerical computing with arrays

Virtually all data science applications represent data as arrays, i.e. multi-dimensional lists of numbers meant to be processed efficiently. The most prevalent library for numerical computing in Python is NumPy but other libraries provide almost identical data structures for specialized applications, e.g. PyTorch for Deep Learning. The second day of the course focuses on handling these data structures and performing operations on them. The topics covered include:
- Introduction to arrays: purpose, dimensions, types etc.
- Creating arrays and importing data as arrays
- Extracting parts of arrays: slicing, indexing, logical indexing
- Playing with dimensions: reshaping, assembling, broadcasting etc.
- Applying functions to arrays: element-wise operations, reductions, aggregations
- From NumPy to PyTorch: introduction to PyTorch tensors

### Day 3: Data Science with Pandas and Seaborn

NumPy arrays are great for numerical computing but are unable to handle heterogeneous data, i.e. data that contains different types of values (e.g. numbers, strings, dates). The Pandas library provides a powerful data structure called DataFrame that can handle such heterogeneous data and is widely used in data science applications. Crucially, DataFrames are based on many of the same concepts as arrays (dimensions, indexing etc.) so that knowledge from Day 2 can be directly recycled. The third day of the course focuses on using Pandas for data manipulation and Seaborn for data visualization. The topics covered include:
- Importing data as DataFrames and basic exploration (head, describe etc.)
- Basic manipulation of DataFrame: adding and removing columns, changing column names etc.
- Indexing and slicing DataFrames
- Assembling DataFrames: concatenation, merging, joining
- Grouping and aggregating data and basic statistics
- Data visualization with Seaborn: scatter plots, histograms, box plots etc.

### Day 4: Mathematical concepts

The last day is a bit different as it does not focus on a specific library but rather on mathematical concepts that are important for data science and machine learning. The goal is to provide participants with a basic understanding of these concepts so that they can better understand the algorithms and models used in data science applications. The topics covered include:

- Linear algebra: vectors, matrices, matrix operations
- Probability and statistics: distributions, distance between distributions, sampling
- Optimization: gradient descent, loss 
- Frequency analysis: Fourier transform

## Course material

You can obtain this course material by clicking on the green "Code" button at the top of this page and then selecting "Download ZIP". Alternatively, you can clone the repository using Git.

If you download the material as a ZIP file, you will need to extract the contents of the ZIP file to a directory on your computer. On Windows you can peer in the ZIP file without unzipping it, so make sure you *actively extract the material* as otherwise you won't be able to run the notebooks.

## Prerequisites

The course is designed for beginners and has no prerequisites in terms of programming experience. The course uses primarily VSCode for writing and executing Python code. Please install VSCode from [the official website](https://code.visualstudio.com/) before the course.