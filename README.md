# Hotel Booking Analysis
The project aims to analyze hotel booking data, identify trends, predict revenue, and develop machine learning models for forecasting.

## Project Structure

- **data/**: Contains the dataset used for analysis.
- **notebooks/**: Contains the Jupyter Notebook with the full analysis.
- **scripts/**: Contains Python scripts for data preprocessing, model training, and making predictions
- **README.md**: Project documentation.
- **requirements.txt**: List of dependencies.

## Data Description

The dataset used in this project is `hotel_bookings.csv`, which contains information about hotel bookings. Key features include:
- `hotel`
- `lead_time`
- `stays_in_weekend_nights`
- `stays_in_week_nights`
- `adults`
- `children`
- `babies`
- `meal`
- `market_segment`
- `adr` (Average Daily Rate)
- `revenue` (calculated as `adr * stay_duration`)

## Analysis and Findings

1. **Data Preprocessing**:
   - Cleaned and transformed the data.
   - Handled missing values and combined relevant columns.
   - Calculated `revenue` for each booking.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of bookings by hotel type.
   - Examined the average daily rate (ADR) and stay duration.
   - Identified top market segments by total revenue.

3. **Model Training**:
   - Trained multiple models to predict revenue, including Linear Regression, Random Forest, and Gradient Boosting.
   - Evaluated model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

### Model Performance

- **Linear Regression**:
  - MAE: 122.45
  - MSE: 42473.76
  - R-squared: 0.64

- **Random Forest**:
  - MAE: 86.50
  - MSE: 29648.63
  - R-squared: 0.75

- **Gradient Boosting**:
  - MAE: 102.13
  - MSE: 30215.29
  - R-squared: 0.74

## Industry Suggestions

Based on the analysis and model results, here are some suggestions for the hospitality industry:

1. **Focus on Top Market Segments**:
   -  To maximize revenue, invest in marketing and promotional activities targeting the top-performing segments.

2. **Optimize Pricing Strategies**:
   - Use predictive models to forecast demand and adjust pricing strategies accordingly, especially for high lead time bookings.

3. **Enhance Customer Experience**:
   - Improve services and facilities for market segments with high ADR which leads to an increase of the customer satisfaction and repeat bookings.

4. **Utilize Predictive Analytics**:
   - Use predictive analytics to anticipate booking patterns and optimize resource allocation.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/hotel-booking-analysis.git
   cd hotel-booking-analysis
