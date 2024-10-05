# Sales Dashboard

A dynamic, interactive sales analytics dashboard built with **Streamlit** and **Plotly Express**. This dashboard provides comprehensive visualization and analysis of sales data, allowing users to explore various metrics and patterns through multiple interactive charts and filters.

## Features

### 1. Interactive Filtering
Users can analyze data by different dimensions:

- **Ship Mode**
- **Segment**
- **Category**
- **Sub-Category**
- **State**
- **City**
- **Region**

### 2. Multiple Visualizations

- **Bar Charts**: Compare sales and profit across different categories.
- **Donut Charts**: Visualize the distribution of sales and profit.
- **Line Charts**: Track sales and profit trends over time.
- **Geographic Heatmap**: View sales/profit distribution across the United States.

## Data Structure

The dashboard expects the following columns in your Excel file:

- Ship Mode
- Segment
- Category
- Sub-Category
- State
- City
- Region
- Sales
- Profit
- Order Date
- Latitude
- Longitude
- Discount
- Quantity
- Postal Code

## Features Breakdown

### 1. Data Overview

- Displays raw data in a table format.
- Shows key metrics about the dataset, such as:
  - Number of Categories
  - Number of Sub-Categories
  - Total Regions

### 2. Bar Chart

- Visualizes sales data with profit indicated by color.
- Dynamically updates based on selected grouping.

### 3. Donut Charts

- Two side-by-side donut charts showing the distribution of:
  - Sales
  - Profit

### 4. Time Series Analysis

- Line chart displaying sales or profit over time.
- Filterable by region.

### 5. Geographic Heatmap

- Visualizes sales or profit density across the United States.
- Includes detailed hover information, such as:
  - Sales/Profit amount
  - Discount
  - Quantity
  - Region
  - State
  - City
  - Postal Code

## How to Run

1. Clone the repository.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
