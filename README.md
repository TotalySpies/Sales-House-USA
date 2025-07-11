# Sales-House-USA
Show which factors influence the price and speed of selling a property.
## 📐 2. Feature Engineering

New signs created:

- **Price per sq. m** = ‘Price / Area’
- **Age of home** = ‘Current year - Year Built’
-**Area category** (Low / Median / Top) - based on quartiles:
  - Q1: '=QUARTILE(...)', Q2, Q3
  - Categorization via ARRAYFORMULA(...)
- **Sales speed** - Fast vs Slow:
  - Based on the median `Days on Market’

📄 See more details in [Feature Engineering в Google Таблице](https://docs.google.com/spreadsheets/d/1aBOW2PClKZx7JJnHqUM_PQJkWhDc8Kmuj6VcTnFED0I/edit?usp=sharing) 

## 📈 3. EDA (Exploratory Data Analysis)

The following dependencies were analysed:

- Average price per city/ state
- Relationship between number of bedrooms/bathrooms and price
- Breakdown by type of property
- Time of sale by regions
- Impact of year on price

📊 Google Sheets used 

📄 Read more - [Visualization](https://docs.google.com/spreadsheets/d/1aBOW2PClKZx7JJnHqUM_PQJkWhDc8Kmuj6VcTnFED0I/edit?usp=sharing)
