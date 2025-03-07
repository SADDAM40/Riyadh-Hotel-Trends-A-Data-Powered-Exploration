# Riyadh Hotel Trends: A Data-Powered Exploration

This project explores the hotel market in Riyadh—the capital of Saudi Arabia—using data from Kaggle. The analysis focuses on hotel pricing, availability, geolocation, ratings, and other key attributes that shape the hospitality industry in the city.

## Overview
Riyadh is a prominent destination for business travelers, tourists, and pilgrims. This analysis examines detailed hotel data from multiple booking platforms such as Booking.com, Hotels.com, Expedia, Agoda.com, and Trip.com. It provides a short-term outlook by focusing on hotel bookings for the next two months, which is crucial for understanding current trends in the hospitality market.

## Dataset Details
- **Source:** [Kaggle - Riyadh Hotels](https://www.kaggle.com/datasets/mohammedalsubaie/riyadh-hotels)
- **Description:** This dataset includes detailed information on hotel pricing, availability, geolocation, ratings, and more. The data offers a comprehensive view of the hotels sector in Riyadh.

## Dataset Limitations
- **Time Frame:** The dataset covers only three months (December, January, and February), limiting the ability to capture long-term trends, seasonal variations, or special events.
- **Geographical Bias:** Data is concentrated in Riyadh’s western, northern, and north-eastern regions, excluding the southern and central parts of the city.
- **Limited Platform Representation:** Some platforms (e.g., Expedia, Hotels.com) are underrepresented, potentially skewing the view of overall market options and pricing strategies.

## Summary of Findings
- **Hotel Price Range:**  
  - Luxury hotels (e.g., Ritz-Carlton) exceed 3,500 SAR.  
  - Budget options (e.g., Sands Inn) are below 150 SAR.
- **Hotel Ratings:**  
  - Joudyan Hotel has a perfect 5.0 rating.  
  - Other hotels generally have solid 4.5 ratings.
- **Hotel Location:**  
  - Most hotels are concentrated in the western, northern, and north-eastern areas of Riyadh, highlighting key commercial zones.
- **Stay Duration:**  
  - Most stays last between 1 to 4 days, with 4 days being the most common, likely due to business travel patterns.
- **Booking Platforms:**  
  - Booking.com dominates with 622 listings, while official sites tend to have higher prices.  
  - Trip.com shows an outlier with an extremely high price.
- **Check-in/Check-out Trends:**  
  - Highest check-ins occur on Saturdays (248), while check-outs peak on Tuesdays (213), indicating an early week departure trend.
- **Monthly Trends:**  
  - January exhibits the most consistent booking and check-out numbers, December shows fewer bookings, and February has higher check-out counts.

## How to Run
1. **Data Preparation:**  
   Ensure that the `Riyadh_Hotels.csv` file is present in the repository root.
2. **Notebook Execution:**  
   Open `Riyadh_Hotels_Analysis.ipynb` using [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyterlab.readthedocs.io/).
3. **Run the Analysis:**  
   Execute the notebook cells sequentially to perform data cleaning, exploratory data analysis, visualization, and to generate the results.

## Repository Structure
```bash
├── Riyadh_Hotels.csv                 # Dataset file containing the hotel data
├── Riyadh_Hotels_Analysis.ipynb        # Jupyter Notebook for the hotel analysis

