# Weighted-Grade-Computation-and-Goodreads-Dataset-Cleaning-in-Python
Completed lab project demonstrating matrix operations with NumPy to calculate student grades and data cleaning with Pandas on a Goodreads dataset, highlighting understanding of machine learning concepts as well as core skills in linear algebra, data preparation, and exploratory analysis.

Purpose

This project was completed as part of my Machine Learning Foundations course in Purdue University’s Cybersecurity Workforce Certification Training program. It builds upon earlier work with matrix operations by applying them to compute student final grades, while also introducing real-world data cleaning using a Goodreads dataset.

This project deepened my understanding of:

Applying matrix multiplication to weighted grade calculations

Normalizing datasets to a common scale

Cleaning messy datasets (handling NaNs, invalid values, and type conversions)

Using Pandas for aggregation and exploratory analysis

Project Structure

Machine Learning Foundations - Lab 2 Final Code File.ipynb: Colab Notebook containing all code, explanations, and results

lab2-hw.txt, lab2-test.txt, lab2-quiz.txt, lab2-project.txt: Student grade text files

lab2-T2-data.pkl: Goodreads dataset

Tasks Completed

✅ Part One: Matrix Grade Computation

Load student grade data from text files

Normalize scores to percentages

Build a grade matrix and apply a weight vector

Compute final grades via matrix multiplication

Present results in a Pandas DataFrame

✅ Part Two: Goodreads Data Cleaning and Analysis

Explore dataset structure and missing values

Drop rows missing critical fields (ratings, year published)

Fill non-critical fields with blanks

Convert columns to correct types

Remove invalid entries (negative years, ratings outside 0–5)

Group by author and identify the most prolific writer

Technologies Used

Python

NumPy

Pandas

Jupyter Notebook / Google Colab
