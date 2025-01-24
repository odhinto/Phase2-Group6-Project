<h1 align="center">Hi 👋, We're Group 6</h1>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/anthony-odhiambo-47167a15b/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="anthony-odhiambo-47167a15b/" height="30" width="40" /></a>
</p>

Github Repository: [Click to Open the Project Github Repository](https://github.com/odhinto/dsc-phase-1-project-v3)

Tableau Dashboard: [Click to Open the Tableau Dashboard](https://public.tableau.com/views/Phase1_EDA/Dashboard2?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


# **Problem Definition**

A recent profitable trend across most big companies is creation of original video content. Our company's expansion and diversification plans include getting in on this fun by creating a new movie studio. 
An analysis of box office performance is critical to identify a profitable formula for operating a profitable studio.

## Business Understanding

The primary objective of this exercise is to generate an accurate model for predicting box office success as a blueprint for running our proposed new movie studio

*   The highest rated movies with respect to attributes such as Genre, Region, Writers, Directors, Actors etc.
*   The most watched/voted movies with respect to attributes such as Genre, Region, Writers, Directors, Actors etc.
*   The highest grossing movies with respect to attributes such as Genre, Region, Writers, Directors, Actors etc.

The insights from this analysis will determine the kind of movies our studio focuses on and the people we approach to partner with us to ensure our studio is successful and profitable.

# **Data Preprocessing**

This section prepare the provided movie data for analysis. We intend to do the following:

*   Dataset Overview - Load and understand the data
*   Handling Missing Values using derived domain knowledge and imputation
*   Data Cleaning e.g. standardizing categorical values, deriving useful date data, removing duplicates etc

## **Dataset Overview**

It is imperative for us to understand the movie database first i.e.:

*   The data structure e.g. available tables, their columns, data types and presence of missing values
*   Establish the relevance of the data to our study
*   Identify useful columns to focus on

Data Understanding will prescribe subsequent cleaning steps to be done in the **Data Cleaning** subsection

### Python Libraries Initialization
First, we initialize common libraries we project to utilize in this exercise:

*   pandas to create and manipulate dataframes
*   seaborn and matplotlib to facilitate any requisite visualizations within the notebook
*   numpy for mathematical calculations
*   sqlite3 to navigate the movie database
*   etc

### Data Loading
We then load the dataset into python as a dataframe and embark on a data understanding exercise.

### Data Understanding

The movie database contains the following tables with shown columns

*   **principals**: insert description and data summary
*   **persons**: insert description and data summary
*   **known_for**: insert description and data summary
*   **directors**: insert description and data summary
*   **writers**: insert description and data summary
*   **movie_basics**: insert description and data summary
*   **dmovie_ratings**: insert description and data summary
*   **movie_akas**: insert description and data summary

<div align="center">
    <img src="pictures/movie_data_erd.jpeg" alt="Database Schema" width="800">
    <p><em>Movie Database Schema</em></p>
</div>
