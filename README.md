# Booking.com Hotel Reviews Analysis

This project analyzes over 515,000 guest reviews and ratings of almost 1500 hotels across Europe, scraped from Booking.com. The goal is to understand customer sentiment and key hotel features through various data analysis and visualization techniques.

## Dataset

The dataset used in this analysis is provided as `BookingDotCom_HotelReviews.xlsx`, which contains:
- Guest reviews and ratings.
- Hotel metadata (e.g., location).
- Traveler type and review dates.

You can download the dataset from : https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe

## Project Summary

- **Dataset**: Guest reviews from Booking.com hotels in Europe, with cleaned text data for the reviews and metadata about hotel addresses and review dates.
- **Tools**: Python, Pandas, Matplotlib, Seaborn, SpaCy, Scikit-learn.
- **Objective**: Analyze and visualize customer sentiment, most mentioned features in positive and negative reviews, and highlight hotel performance over time.

## Key Insights

### 1. Top Hotel Features in Reviews

- **Positive Features**:
    - Staff
    - Location
    - Room
    - Breakfast
    - Bed

- **Negative Features**:
    - Room
    - Service
    - Staff
    - Breakfast
    - Floor

### 2. Customer Preferences by Traveler Type

- **Solo Travelers**:
    - Positive: Staff, Location, Room, Breakfast, Bed
    - Negative: Room, Service, Staff, Breakfast, Floor

- **Group Travelers**:
    - Positive: Staff, Location, Room, Breakfast, Station
    - Negative: Room, Staff, Service, Breakfast, Bed

- (Add other traveler categories here)

### 3. Country-wise Insights

- **United Kingdom**:
    - Positive: Location, Breakfast, Bed, Station, Comfortable
    - Negative: Breakfast, Bed, Floor, Bar, Area

- **France**:
    - Positive: Location, Breakfast, Bed, Tower, Station
    - Negative: Breakfast, Bed, Floor, Area, Water

- (Add other countries here)

### 4. Hotel Ratings Analysis

- **Top 5 Hotels**:
    - Ritz Paris
    - Hotel Casa Camper
    - 41
    - Hotel de La Tamise Esprit de France
    - Le Narcisse Blanc Spa

- **Bottom 5 Hotels**:
    - Hotel Liberty
    - Kube Hotel Ice Bar
    - Villa Eugenie
    - Savoy Hotel Amsterdam
    - Holiday Inn Paris Montparnasse Pasteur

### 5. Most Improved Hotels (2015-2017)

- Le Lavoisier
- Mercure Paris Bastille Saint Antoine
- L Edmond Hotel
- MiHotel
- Villa Lutce Port Royal

## Dashboard Visualizations

This project includes the following visualizations:
1. **Top Five Hotels Overall**: Bar chart showing the top 5 hotels with the highest average ratings.
2. **Bottom Five Hotels Overall**: Bar chart displaying the bottom 5 hotels with consistently low ratings.
3. **Five Most Improved Hotels**: Line plot showing the rating improvements from 2015 to 2017 for the top 5 most improved hotels.

## How to Run This Project

1. **Install dependencies**:

    ```bash
    conda create -n hotel_reviews python=3.8
    conda activate hotel_reviews
    pip install -r requirements.txt
    ```

2. **Open the Jupyter Notebook**:

    ```bash
    jupyter notebook BookingDotCom_HotelReviews.ipynb
    ```

3. **View the visualizations**: Follow the instructions in the notebook to run the data analysis and generate the visualizations.

