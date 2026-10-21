> 🌐 **Note:** The Spanish version of this README is available as a PDF. Some content (charts, diagrams, screenshots) is easier to follow in the PDF version.
>
> 🌐 **Nota:** La versión en español de este README está disponible en formato PDF. Algunos contenidos (gráficas, diagramas, capturas) se ven más claros en la versión PDF.

---

# Customer and Restaurant Analysis in the United States

## Description

This project covers a complete process of cleaning, exploring and analyzing a database of restaurant customers in the United States. The original dataset contained 30,000 rows and 17 columns, with a high percentage of null and negative values in several columns. The work included multiple data-cleaning stages, statistical analysis and the application of machine learning techniques. Visualizations were developed, along with a document containing the main recommendations.

The project was developed in Python, using libraries specialized in data analysis and visualization.

## Objectives

- Clean and prepare the data for analysis.
- Identify customer consumption patterns.
- Analyze spending behavior in restaurants.
- Study differences between cities and customer segments.
- Integrate external information from Yelp.
- Generate evidence-based business recommendations.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Requests
- Jupyter Notebook
- Seaborn

## Data Cleaning Process

The following activities were carried out:

- Correction of negative ages or ages above 120 years.
- Replacement of missing values using medians.
- Removal of whitespace in text variables.
- Correction of negative values in visit frequency.
- Normalization of phone numbers.
- Handling of records without an email address.
- Data type validation.

## Analyses Performed

- Number of people per city.
- Distribution of customers by socioeconomic level.
- Average restaurant spending per city.
- Relationship between visit frequency and average spending.
- Relationship between monthly income and average spending.
- Customer food preferences.
- Profile of the highest-spending customers.
- Premium membership analysis.
- Relationship between alcohol consumption and age.
- Integration of information from Yelp.

## Files Used

### `base_datos_restaurantes_USA_v2.csv`

Main project file containing information about restaurant customers in the United States. It includes demographic, economic and consumption-behavior variables, such as:

- First and last name.
- Age and gender.
- City of residence.
- Socioeconomic level.
- Monthly income.
- Restaurant visit frequency.
- Average food spending.
- Food preferences.
- Alcohol consumption.
- Most-used payment method.
- Premium membership status.
- Contact information.

This file went through a cleaning, validation and transformation process to guarantee the quality of the analyses performed.

### `yelp_restaurants.csv`

File generated from queries to the Yelp API. It contains real information about restaurants located in different cities across the United States, used to complement the internal customer analysis.

Main variables included:

- Restaurant ID.
- Restaurant name.
- Main food category.
- Average rating.
- Number of reviews.
- City.
- Price level.

This dataset made it possible to run comparative market analyses, identify popular categories and detect partnership opportunities with highly rated restaurants.

## Yelp Integration

The Yelp API was queried to obtain real restaurant information.

The extracted data includes:

- Restaurant name
- Main category
- Price
- Rating
- Number of reviews
- City

This information complements the internal customer analysis with real market data.

## Main Findings

- There are significant differences in average spending between cities.
- Food preferences vary by geographic location.
- Customers with higher incomes tend to show higher spending levels.
- Premium memberships show different behaviors depending on the city.
- Yelp data helps identify strategic partnership opportunities.

## Segmentation Proposals

### Segment 1: High-spending customers

**Characteristics:**
- High average spending
- Frequent visits
- High income

**Strategy:**
- Exclusive programs
- Premium benefits
- Loyalty rewards

### Segment 2: Frequent customers

**Characteristics:**
- High visit frequency
- Medium or high spending

**Strategy:**
- Recurring discounts
- Points accumulation

### Segment 3: Customers by food preference

**Characteristics:**
- Vegetarians
- Vegans
- Meat eaters
- Seafood eaters

**Strategy:**
- Personalized promotions
- Partnerships with specialized restaurants

### Segment 4: Premium customers

**Characteristics:**
- Active membership

**Strategy:**
- Exclusive benefits
- Special events
- Differentiated promotions

## Conclusion

This project made it possible to develop an end-to-end data analysis process, from data cleaning and preparation to the generation of visualizations and business findings. By studying more than 30,000 customer records, it was possible to identify consumption patterns, differences between cities, behaviors associated with spending, and customer segmentation opportunities.

Integrating external Yelp data enriched the analysis by providing real information about the food-service market, making it possible to contrast customer behavior with the characteristics of the restaurants available in each city.
