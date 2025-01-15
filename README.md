# what-should-you-cook-tonight
# Recipe Recommendation System

## Project Overview
This project implements a recipe recommendation system by scraping data from [Skinnytaste](https://www.skinnytaste.com). The system helps users find recipes based on their caloric and nutritional preferences, making meal planning easier and more personalized.

## Features
- Web scraping of recipe data from Skinnytaste (first 50 pages)
- Data collection of key recipe attributes:
  - Recipe name
  - Food image
  - Caloric content
  - Personal Points
  - Recipe summary
  - Recipe key
- Interactive user interface allowing:
  - Calorie range specification
  - Points range input
  - Display of top 10 matching recipes with images and summaries
- Data visualization and analysis:
  - Calories distribution
  - Recipe key distribution
  - Points distribution

## Technical Implementation

### 1. Data Collection
- Web scraping implementation using Python
- Data extraction from multiple pages
- Structured storage of recipe information

### 2. Data Processing
- Filtering and cleaning of scraped data
- Organization of recipe attributes
- Storage optimization for quick access

### 3. Analysis & Visualization
- Statistical analysis of recipe attributes
- Visual representations of data distributions
- Insights generation from collected data

### 4. User Interface
- Interactive input system
- Recipe filtering based on user preferences
- Sorted output of matching recipes

## Requirements
- Python 3.x
- Required packages (specified in code)
- Google Colab environment

## Usage
1. The code runs in Google Colab environment
2. Input your desired calorie and points range
3. View the top 10 recommended recipes
4. Explore data visualizations and analysis

## Project Structure
```
project/
│
├── code/
│   └── recipe_recommendation.ipynb    # Main Colab notebook
│
└── README.md                          # Project documentation
```

## Limitations and Future Improvements
- Currently limited to first 50 pages of recipes
- Potential for additional filtering criteria
- Opportunity for recommendation algorithm enhancement

## Acknowledgments
Data source: [Skinnytaste](https://www.skinnytaste.com)
