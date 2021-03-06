# Tito's Vodka Market Analysis
## Overview
- The competitiors as well as the opportunities for Tito's Vodka are identified.
- The project provides a customer segmentation using Recency-Frequency-Monetary (RFM) segmentation.
-  Marketing plans and Market Basket Analysis for each segment are proposed.
- A probabilistic predictive model is proposed to predict the Customer Lifetime Value.

## Conclusions
- US Vodka is the most sold liquor category; there is a lot of competition and opportunity.
- US Vodka is sold for a fairly cheap price as compared to other popular categories.
- Marketing campaigns and promotions to be intensified in February, May and October.
- Low value stores are out of the marketing analysis; they are likely out of business.
- Medium value stores are very competitive with Hawkeye Vodka.
- Tito’s is winning in the high value stores (wholesale/club stores)
- Beta Geometry/Negative Binomial Distribution (BG/NBD) model predicts the alive probability with an accuracy of 94.8% and a risk of 5.2%
- RFM segmentation and Customer Lifetime Value Prediction are together beneficial to plan and to evaluate marketing campaigns.


More details on the outcome are found in the [slides deck](https://github.com/iba13001/Titos-Vodka-Market-Analysis/blob/main/TitosMarketAnalysis.pptx).

## The Code
- LiquorCleaningEDA: cotains the data cleaning, building relational databases, clustering of customers and analysis of each customer segment.
- CLV_Prediction: contains building BG/NBD model to predict the alive probability.

## Data and Databases
- This [zipped folder](https://drive.google.com/file/d/1O_puKf2dzk7nBOQDDomx5N6YObWzdrF9/view?usp=sharing) contains the data used in this project and the Sqlite databases.
- The data is collected from [Iowa Data Portal](https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy).
