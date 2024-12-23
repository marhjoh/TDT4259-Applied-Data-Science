# Olympic Impact on Rental Markets: Paris

## Project Overview

This data science project aims to analyze the impact of the Olympic Games on the Paris rental market and use these insights to forecast potential changes in large cities' rental market for future similar events. The primary focus is on using Airbnb data to understand market dynamics, predict challenges, and propose strategies for handling increased tourism and accommodation demands.

## Objectives

1. Analyze the Paris rental market before, during, and after the Olympic Games.
2. Identify patterns and trends in rental prices, availability, and demand.
3. Assess Airbnb's capacity to handle increased tourism during major events.
4. Develop predictive models for rental market changes during large-scale events.
5. Apply insights from Paris to forecast potential scenarios for other cities, such as Los Angeles having its Olympic games in 2028.
6. Provide recommendations to Airbnb for managing similar situations in future Olympic host cities.

## Data Sources

Our primary data source is Airbnb, which provides comprehensive datasets for Paris. The datasets include:

1. Summary Listings: Contains key metrics for each listing (id, name, host information, location, price, etc.)
2. Detailed Listings: Provides in-depth information about each listing
3. Detailed Reviews: Contains individual reviews for listings
4. Detailed Calendar: Offers day-by-day availability and pricing data for listings
5. Summary Reviews: Provides a timeline of reviews for each listing

Additional data sources include:
- Tourism statistics for Olympic Games and other major events
- Demographic and economic data for both cities

### Ideal file structure
All data is expected to be of .csv file format. Ideally, add all data as found in the image below. Airbnb har archived data which should be included into the corresponding folder. Expand in a similar manner.
![image](https://github.com/user-attachments/assets/065c6bb0-7960-4011-9377-ac55ef78a5d6)

## Project Structure

The project is primarily developed in Jupyter Notebooks, with the following structure:

1. `data_cleaning.ipynb`: Data preprocessing and cleaning
2. `exploratory_data_analysis.ipynb`: Initial data exploration and visualization
3. `paris_analysis.ipynb`: In-depth analysis of the Paris rental market
4. `visualization.ipynb`: Advanced data visualization and insights presentation

## Data Processing

Our data processing pipeline involves:

1. Merging the summary and detailed listings datasets
2. Incorporating review data to analyze customer satisfaction and host performance
3. Using calendar data to study pricing strategies and availability patterns
4. Leveraging the summary reviews data for time-based analytics

## Setup and Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/olympic-rental-impact.git
   ```

2. Navigate to the project directory:
   ```
   cd olympic-rental-impact
   ```

3. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

5. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

## Usage

Open the Jupyter Notebooks in order (1 to 4) and run the cells sequentially. Each notebook contains detailed comments and markdown cells explaining the analysis process.

## Key Visualizations

Our analysis will include various visualizations, such as:
- Price distribution by neighborhood
- Review scores over time
- Availability patterns throughout the year
- Correlation between price, number of reviews, and location
- Host performance metrics

## Results and Recommendations

The final results, insights, and recommendations will be summarized in the `visualization.ipynb` notebook and in a separate report document (to be added upon project completion).

## Contributing

This project is part of a data science study. If you have any suggestions or find any issues, please open an issue in the repository.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- Airbnb for providing the comprehensive datasets
- The Olympic committees of Paris and Los Angeles for public information on the Games
