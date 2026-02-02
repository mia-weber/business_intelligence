# Airbnb Market Analysis: Columbus vs New York

## Author
Mia Weber

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to understand how listing characteristics, host status, location, and room type impact pricing and availability. Ultimately, this will support market-specific decisions related to pricing strategy, market entry, and neighborhood selection.

## Research Questions

1. What listing characteristics are most strongly associated with higher prices in each city?
2. How does listing availability differ between Columbus and New York, and what factors are associated with higher availability?
3. How does minimum stay length impact nightly price and availability in Columbus compared to New York?
4. Which neighborhoods in each city offer the best combination of high review scores and relatively low prices?
5. How does room type (entire home, private room, shared room) influence pricing in Columbus versus New York?

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | What listing characteristics are most strongly associated with higher prices in each city? | price, room_type, minimum_nights, availability_365, number_of_reviews , etc. | listings.csv | Structured |
| 2 | How does listing availability differ between Columbus and New York, and what factors are associated with higher availability? | availability_365, room_type, minimum_nights, number_of_reviews_ltm | listings.csv | Structured |
| 3 | How does minimum stay length impact nightly price and availability in Columbus compared to New York? | price, minimum_nights, availability_365 | listings.csv | Structured |
| 4 | Which neighborhoods in each city offer the best combination of high review scores and relatively low prices? | price, neighborhood, number_of_reviews, reviews_per_month | listings.csv | Structured |
| 5 | How does room type influence pricing in Columbus versus New York? | room_type, price, city | listings.csv | Structured |

## Data Overview
- **Columbus, Ohio:** 2119 listings (as of Sept 26, 2025)
- **New York City:** 5248 listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created