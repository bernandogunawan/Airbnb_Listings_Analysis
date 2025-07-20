# Airbnb Listings Bangkok Analysis

## Project Overview
This project analyzes Airbnb listings in Bangkok to uncover insights into local consumer preferences and provide strategic recommendations for Airbnb's market expansion in the region. The analysis focuses on geographical distribution, room type preferences, pricing patterns, minimum length of stay, and recent consumer behavior.

## File Description
- **File Name**: `capstone_2.ipynb`
- **Purpose**: This Jupyter Notebook contains the complete data analysis workflow, including data preprocessing, exploratory data analysis, visualization, and strategic recommendations based on the findings.
- **Dataset**: The dataset used is `Airbnb Listings Bangkok.csv`, which includes information on approximately 16,000 Airbnb listings in Bangkok, covering attributes such as pricing, location, room type, and booking behavior.

## Dependencies
To run the notebook, the following Python libraries are required:
- `pandas`
- `matplotlib`
- `folium`
- `branca`
- `seaborn`

Install these dependencies using:
```bash
pip install pandas matplotlib folium branca seaborn
```

## Structure of the Notebook
The notebook is organized into the following key sections:
1. **Business Context**: Outlines the objectives and problem statements, focusing on understanding local consumer preferences to support Airbnb's strategic expansion in Bangkok.
2. **Data Understanding and Cleaning**: Includes steps for:
   - Initial data exploration
   - Handling missing values
   - Resolving inconsistencies in categorical columns
   - Managing outliers in numerical columns
   - Dropping irrelevant columns
   - Feature engineering
3. **Data Analysis and Visualization**: Explores key dimensions such as:
   - Geographical distribution of listings
   - Room type preferences
   - Pricing patterns
   - Minimum length of stay
   - Recent consumer behavior
4. **Conclusion**: Summarizes key insights from the analysis.
5. **Recommendations**: Provides actionable strategies for Airbnb to enhance its market presence in Bangkok.

## Key Insights
- **Geographical Distribution**: High-density neighborhoods like Ratchathewi, Vadhana, and Khlong Toei are preferred due to their proximity to attractions and transport hubs.
- **Room Type Preferences**: Private rooms and entire homes/apartments are the most popular among local consumers.
- **Pricing Patterns**: Listings priced between 800 and 1905 per night are most likely to be booked.
- **Minimum Length of Stay**: Short-term stays (1-7 nights) dominate, with medium-term stays (8-30 nights) showing growth potential.
- **Recent Consumer Behavior**: Recent bookings favor short-term stays in popular neighborhoods.

## Recommendations
- Focus marketing efforts on high-demand neighborhoods.
- Encourage hosts to offer more private rooms and entire homes/apartments.
- Implement dynamic pricing tools to guide hosts in setting competitive rates.
- Promote short-term stay listings to align with consumer preferences.

## How to Run
1. Ensure all dependencies are installed.
2. Place the `Airbnb Listings Bangkok.csv` dataset in the same directory as the notebook.
3. Open `capstone_2.ipynb` in a Jupyter Notebook environment.
4. Run the cells sequentially to perform the analysis and generate visualizations.

## Notes
- The dataset contains some missing values in columns like `name`, `host_name`, `last_review`, and `reviews_per_month`, which are handled during the cleaning process.
- Visualizations include pie charts to compare stay types across booking categories (Not Booked, Booked, Popular, Recent).
- Ensure you have sufficient memory and computational resources to handle the dataset and visualizations.

## Author
Bernando Virto Gunawan
