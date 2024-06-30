# Zomato Data Manipulation and Reporting with Power BI

## Project Overview

This project involves creating a consolidated and interactive Power BI report for Zomato, a restaurant aggregation and meal delivery service. The goal is to help Zomato assess their business performance by analyzing data from various restaurants worldwide. The report provides insights into restaurant counts, customer ratings, average costs, and cuisine counts, with the ability to drill down to granular levels.

## Features

1. **Global Restaurant Data:**
   - Total number of restaurants worldwide, including continents, countries, and cities.
   - Data visualization on a global scale with drill-down capabilities.

2. **Customer Ratings:**
   - Derive data on restaurants with the highest average customer ratings.
   - Display average ratings using a color-coded system.

3. **Cost Analysis:**
   - Identify restaurants with the lowest average costs.

4. **Filters and Views:**
   - Filter and view information based on geographical dimensions (continent, country, city).
   - Filter based on services provided (online ordering, reservation services).
   - Filter based on average rating slabs by color.

5. **Cuisine Analysis:**
   - Identify restaurants with the most cuisines served.

6. **Multi-Page Report:**
   - Design a multi-page report matching Zomato's theme.
   - Easy navigation across sections.

7. **Accessibility:**
   - Accessible from both web browsers and mobile devices.

## Steps to Complete the Project

### Data Import and Transformation

1. **Import Data:**
   - Import data from all available Excel files.

2. **Data Transformation:**
   - Correct city column names (e.g., "Sí£o Paulo" to "São Paulo").
   - Remove ambiguous city names (e.g., "Cedar Rapids/Iowa City" to "Cedar Rapids").
   - Remove unused columns.
   - Create columns for Restaurant Name and Restaurant Address.
   - Create a separate table for the list of cuisines each restaurant serves.
   - Ensure the Country-Code table contains only unique and non-blank values.

### DAX Calculations

1. **Rating Color Column:**
   - Add a Rating color column with the following format:
     - Aggregate rating > 4.5: Dark Green
     - Aggregate rating 4 to 4.4: Green

2. **Measures:**
   - Create the following measures:
     - Restaurant count
     - Average cost
     - Average rating
     - Cuisine count

3. **Continent Mapping:**
   - Create a "Continent" column in the Country Code table using the mapping convention (e.g., "Africa – South Africa").

## License
This project is licensed under the Apache License Version 2.0

Author:
Kanchan Verma
