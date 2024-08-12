# 911 Calls Capstone Project

This project analyzes 911 call data from Montgomery County, Pennsylvania, sourced from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). The primary goal is to explore patterns and trends in emergency call data to gain insights into public safety and emergency services.

## Dataset Description

The dataset includes the following fields:

- **lat**: Latitude
- **lng**: Longitude
- **desc**: Description of the emergency call
- **zip**: Zip code
- **title**: Type of emergency
- **timeStamp**: Date and time of the call (YYYY-MM-DD HH:MM:SS)
- **twp**: Township
- **addr**: Address
- **e**: A constant identifier column

## Key Objectives

The project aims to:

- Analyze the distribution of 911 calls across different townships.
- Identify the most common reasons for emergency calls.
- Visualize trends in emergency calls over time.
- Explore geographical patterns in call data using latitude and longitude.

## Tools and Libraries

The following libraries are used in this project:

- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For data visualization.

## How to Run

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook and run the cells to reproduce the analysis.
