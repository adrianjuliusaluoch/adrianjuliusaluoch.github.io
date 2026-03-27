# Portfolio
---
## Economic & Market Analysis

### How the cost of food has changed in Kenya

The problem is simple: families are struggling with rising food costs, and it’s not always clear which items are driving that squeeze. To answer this, I leveraged market price data from the World Food Programme Price Database and built an ‘essentials basket’ — maize flour, sugar, cooking oil, milk, sukuma wiki, tomatoes, and onions — the foods most households actually rely on every day.

[![View on RPubs](https://img.shields.io/badge/RPubs-View_on_RPubs-276DC3?logo=r&logoColor=white)](https://rpubs.com/adrianjuliusaluoch/cost_of_foods_in_kenya)

<center><img src="images/food.png"/></center>

---
### How Can Families Cut Maize Flour Costs?

Maize is a staple food in Kenya, forming the foundation of daily meals for millions of households. For many families, the choice between buying dry maize and milling it locally or purchasing already processed maize flour is an important economic decision. While conventional wisdom suggests that milling your own maize is cheaper, market conditions, milling costs, and grain-to-flour conversion yields may alter the actual cost advantage.

[![View on RPubs](https://img.shields.io/badge/RPubs-View_on_RPubs-276DC3?logo=r&logoColor=white)](https://rpubs.com/adrianjuliusaluoch/saving-on-maize-flour)

<center><img src="images/maize.png"/></center>

---
### Can Kenyan Maize Farmers Afford DAP Fertilizer This Season?

Diammonium Phosphate (DAP) is the go-to fertilizer at planting. Farmers trust it because it consistently delivers higher yields. But while households across the country are paying more for essentials like maize flour and cooking oil, the uncertainity is whether fertilizer prices are also climbing. If they are, farmers face a tough choice - stretch already thin budgets, scale back on fertilizer, or turn to alternatives like locally available manure from subsitence farming.

[![View on RPubs](https://img.shields.io/badge/RPubs-View_on_RPubs-276DC3?logo=r&logoColor=white)](https://rpubs.com/adrianjuliusaluoch/fertilizer_price_in_kenya)

<center><img src="images/fertilizer.png"></center>

---

## Data Engineering & Automation

### Agricultural Market Data Pipeline (14k+ Workflow Runs)

<div style="text-align: justify">Market price data is only useful if it’s consistent and up to date. To solve this, I set up an automated pipeline that continuously collects, processes, and stores agricultural market data in BigQuery. With over 14,000 scheduled runs, the system provides a reliable foundation for tracking price trends across regions over time.</div>
<br>
<center><img src="images/KAMIS.png"/></center>
<br>
[![View Dataset on Kaggle](https://img.shields.io/badge/Kaggle-View_Dataset-blue?logo=kaggle)](https://www.kaggle.com/datasets/adrianjuliusaluoch/global-food-prices)
---
### Property Listings Data Pipeline (Nairobi & Mombasa)

<div style="text-align: justify">Understanding Kenya’s housing market requires consistent and structured data, which is not always readily available. To address this, I built a scheduled scraping pipeline using Kaggle notebooks to collect property listings from Property24 across Nairobi and Mombasa, enabling analysis of pricing patterns and location-based differences in the market.</div>
<br>
<center><img src="images/property.png"/></center>
<br>
[![View Dataset on Kaggle](https://img.shields.io/badge/Kaggle-View_Dataset-blue?logo=kaggle)](https://www.kaggle.com/datasets/adrianjuliusaluoch/daily-google-search-trends-us)
---
### Jumia Product & Reviews Data Pipeline (Async Scraping + PostgreSQL)

<div style="text-align: justify">E-commerce data changes quickly, but tracking those changes over time is not straightforward. To solve this, I developed an asynchronous scraping pipeline that collects product data from Jumia at scale, storing it in PostgreSQL with logic to capture only meaningful updates in prices, discounts, and availability. To better understand customer behavior, I extended the pipeline to also collect product reviews — including ratings, text, and timestamps — making it possible to connect pricing decisions with customer feedback and sentiment over time.    </div>
<br>
<center><img src="images/jumia.png"/></center>
<br>
[![View Dataset on Kaggle](https://img.shields.io/badge/Kaggle-View_Dataset-blue?logo=kaggle)](https://www.kaggle.com/datasets/adrianjuliusaluoch/hourly-crypto-stocks-market-data)
---

## Blogs

[![Read My Articles](https://img.shields.io/badge/Medium-Read_My_Articles-black?logo=medium&logoColor=white)](https://medium.com/@adrianjuliusaluoch)

<div style="text-align: justify">Besides building data projects, I enjoy writing data stories that explain real-world trends using data. Through these articles I explore topics like food prices, agriculture, household costs, and market trends in Kenya, translating data analysis into insights that anyone can understand.</div>
<br>

- [How I Built a Data Pipeline That Ran 14,000+ Automated Workflows](https://www.youtube.com/watch?v=-5esqvmPnHI)
- [Detecting Suspicious M-PESA Transactions Using Time Series Decomposition](https://www.youtube.com/watch?v=vfZwdEWgUPE)
- [Is Milling Maize Cheaper Than Buying Flour?](https://www.youtube.com/watch?v=YdXufiebgyc)
- [How Food Prices Changed in Kenya (2024–2025)](https://www.youtube.com/watch?v=jzfcM_iO0FU)

---
<center>© 2026 Adrian Julius Aluoch. Powered by Jekyll and the Minimal Theme.</center>
