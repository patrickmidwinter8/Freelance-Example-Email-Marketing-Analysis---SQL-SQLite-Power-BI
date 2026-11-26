# Travel Business X | Email Marketing & Customer Analytics

> **Privacy & Data Notice:** The business name used throughout this project, Travel Business X, is a pseudonym and is not the actual company name. The original company name has been replaced for privacy reasons. This is an independent portfolio project using a constructed, illustrative dataset. All customer records, campaign activity, bookings and revenue figures are simulated and do not represent actual commercial results.

## 1. Project Overview

This project investigates email marketing performance and customer behaviour for Travel Business X, a travel business offering holiday packages and travel experiences.

Using SQL and Microsoft Power BI, I explored email campaign effectiveness, customer segmentation, geographical distribution, destination preferences, bookings and revenue.

The objective was to transform raw data into meaningful insights and present findings that could help the business make more informed marketing and customer engagement decisions.

## 2. Business Background

Travel Business X uses email marketing to communicate with customers, promote travel destinations and encourage holiday bookings.

Email campaigns provide an opportunity to engage existing customers, attract new subscribers and encourage previous customers to book further holidays.

However, the business needs a clearer understanding of which campaigns are performing well, which customer groups are generating bookings and revenue, and which destinations are attracting the greatest customer interest.

This project takes the perspective of a data analyst investigating these areas and identifying opportunities to improve marketing performance.

## 3. Business Problem

The business wants to understand how effectively its email marketing activity is performing and how customer characteristics and preferences relate to engagement, bookings and revenue.

The analysis focuses on the following questions:

- Which email campaigns generate the highest booking revenue?
- Which campaigns achieve the strongest open and click rates?
- Which customer segments contribute most to bookings and revenue?
- Which customer groups demonstrate the strongest email engagement?
- Which countries contribute the most customers, bookings and revenue?
- Which travel destinations attract the greatest customer interest?
- Are the most popular destinations also associated with the highest booking revenue?
- What marketing opportunities can be identified from the results?

## 4. Project Objectives

1. Evaluate email campaign performance using delivery, open, click, booking and revenue metrics.
2. Identify differences in engagement and booking behaviour across customer segments.
3. Analyse customer distribution and commercial performance across geographical markets.
4. Investigate customer preferences for different travel destinations.
5. Use SQL to extract, aggregate and analyse relevant data.
6. Develop interactive Power BI dashboards to communicate findings.
7. Translate the results into practical marketing recommendations.

## 5. Tools & Technologies

- **SQLite / DB Browser for SQLite:** Database management and data exploration.
- **SQL:** Data extraction, joins, aggregation, calculations and analysis.
- **Microsoft Power BI Desktop:** Dashboard development and data visualisation.
- **CSV:** Exporting analysed datasets for use in Power BI.

## 6. Dataset & Analysis Approach

The project uses a relational dataset containing customer information, email campaign information and email engagement events.

The analysis explores three main areas of data:

- Customer information, including customer segments, countries and preferred destinations.
- Campaign information, including campaign names and campaign identifiers.
- Email event information, including delivery, opens, clicks, unsubscribes, bookings and booking values.

SQL queries were used to combine relevant tables, calculate performance metrics and produce summary datasets for visualisation in Power BI.

The analysis uses a constructed, illustrative dataset. All customer records and business performance figures are simulated and are not actual commercial results.

## 7. Power BI Dashboard Overview

The Power BI report contains four analytical pages.

### Page 1 – Campaign Performance

This dashboard evaluates the performance of five email marketing campaigns.

Key measures include:
- Emails sent and delivered.
- Email open rates.
- Email click rates.
- Bookings generated.
- Booking revenue.
- Campaign-level performance comparisons.

The purpose is to identify which campaigns are generating the strongest engagement and commercial results.

### Page 2 – Customer Insights

This dashboard explores customer behaviour across four customer segments:

- Previous Travellers.
- New Subscribers.
- Inactive Subscribers.
- Frequent Travellers.

The analysis compares customer numbers, email engagement, bookings and revenue to identify differences between customer groups.

### Page 3 – Geographic Insights

This dashboard investigates the geographical distribution of customers across four countries:

- United Kingdom.
- Ireland.
- France.
- Germany.

The analysis compares customer numbers, bookings and booking revenue to identify the strongest geographical markets.

### Page 4 – Destination Insights

This dashboard explores customer preferences across eight travel destinations.

The analysis compares customer interest, destination popularity, bookings and associated revenue.

It helps identify which destinations attract the greatest customer interest and how booking outcomes and revenue vary across customer preference groups.

## 8. Key Findings

### 8.1 Campaign Performance

The analysis identified differences in performance across the five email campaigns.

- **Travel Business X Welcome Campaign** generated the highest booking revenue at £1,045, with two bookings.
- **Summer Sun Sale** generated £906 in revenue and achieved the highest click rate at 6.58%.
- **European City Breaks** achieved the highest open rate at 25%, with two bookings and £901 in revenue.
- **Adventure Awaits** generated £771 in booking revenue, with two bookings.
- **We Miss You** generated the lowest booking revenue at £469 and recorded the lowest open rate at 14.46%.

Across all five campaigns:
- 605 emails were sent.
- 588 emails were delivered.
- 124 emails were opened.
- 32 clicks were recorded.
- 9 bookings were generated.
- Total booking revenue was £4,092.

The results suggest that campaign performance varies depending on the type of engagement measure being considered. The campaign generating the most revenue was not necessarily the campaign achieving the highest open or click rate.

### 8.2 Customer Insights

The customer segment analysis identified differences in engagement and revenue contribution.

**Previous Travellers**
- 228 customers.
- £1,807 booking revenue.
- 4 bookings.
- 20.91% open rate.

Previous Travellers represented the largest customer segment and generated the highest total booking revenue.

**New Subscribers**
- 160 customers.
- £1,253 booking revenue.
- 3 bookings.
- 24.36% open rate.
- 7.69% click rate.

New Subscribers achieved the highest open and click rates, suggesting comparatively strong engagement with email communications.

**Inactive Subscribers**
- 90 customers.
- £1,032 booking revenue.
- 2 bookings.
- 19.32% open rate.

Although this segment was smaller, it generated a notable amount of booking revenue. Its average booking value of £516 was the highest across the segments that generated bookings.

**Frequent Travellers**
- 127 customers.
- £0 booking revenue.
- No bookings.
- 18.55% open rate.

Despite having the second-largest customer count, this segment generated no bookings in the dataset. This presents an opportunity to investigate why engagement has not translated into booking activity.

### 8.3 Geographic Insights

The geographical analysis compared customer numbers, bookings and revenue across four countries.

**United Kingdom**
- 233 customers.
- 4 bookings.
- £1,850 revenue.

The United Kingdom had the highest customer count and generated the greatest booking revenue.

**Ireland**
- 163 customers.
- 3 bookings.
- £1,328 revenue.

Ireland was the second-largest market in terms of customer numbers and revenue.

**France**
- 80 customers.
- 1 booking.
- £688 revenue.

France generated more revenue than Germany despite having fewer customers.

**Germany**
- 129 customers.
- 1 booking.
- £226 revenue.

Germany had a relatively large customer base but generated the lowest revenue of the four countries.

Overall, the United Kingdom and Ireland represented the strongest markets by total booking revenue. The difference between customer numbers and revenue across countries suggests that customer volume alone does not determine commercial performance.

### 8.4 Destination Insights

The destination analysis explored customer preferences across eight destinations.

**Spain** was the most popular destination:
- 137 customers.
- 22.64% of all customers.
- 3 associated bookings.
- £998 associated revenue.

**Italy** ranked second in customer preferences:
- 119 customers.
- 2 associated bookings.
- £1,143 associated revenue.

Italy generated the highest revenue of all destination preference groups, despite having fewer customers than Spain.

Other findings included:

- Croatia attracted 103 customers and generated £688 in associated revenue.
- Iceland attracted 87 customers and generated £680.
- Greece attracted 62 customers and generated £357.
- France attracted 23 customers and generated £226.
- Portugal attracted 43 customers but generated no associated bookings.
- Turkey attracted 31 customers but generated no associated bookings.

These results highlight that the most popular destination in terms of customer interest is not necessarily the destination group generating the highest revenue.

**Important analytical consideration:** The destination field represents customers' preferred destinations. It does not confirm the actual destination booked by each customer. Therefore, booking and revenue figures are associated with customers who expressed a particular preference, rather than confirmed sales for that destination.

## 9. Business Recommendations

Based on the findings, the following recommendations could be considered by the marketing team.

### 9.1 Improve Underperforming Email Campaigns

The We Miss You campaign recorded the lowest open rate and lowest booking revenue.

Recommendations:
- Test alternative email subject lines.
- Experiment with different messaging and promotional offers.
- Review the timing and frequency of emails.
- Test different calls to action.
- Monitor whether changes improve opens, clicks and bookings.

### 9.2 Develop More Targeted Customer Segmentation

The analysis shows that customer groups behave differently.

Recommendations:
- Develop targeted campaigns for Previous Travellers using relevant holiday offers and returning-customer incentives.
- Nurture New Subscribers with introductory content, destination inspiration and booking incentives.
- Investigate the reasons behind the lack of bookings among Frequent Travellers.
- Test re-engagement campaigns for Inactive Subscribers.

### 9.3 Investigate High-Value Geographical Markets

The United Kingdom and Ireland generated the highest total booking revenue.

Recommendations:
- Continue developing marketing activity in these markets.
- Investigate which campaign types and destination promotions perform particularly well in each country.
- Review Germany's relatively low revenue compared with its customer base.
- Explore whether different offers or more relevant destination content could improve conversion.

### 9.4 Use Destination Preferences to Inform Campaign Content

Spain attracted the greatest number of customer preferences, while Italy generated the highest associated revenue.

Recommendations:
- Consider using Spain as a prominent destination in customer engagement campaigns because of its popularity.
- Investigate the higher revenue associated with customers preferring Italy.
- Use destination preference information to personalise email content.
- Test different destination promotions with relevant customer segments.

### 9.5 Investigate Customer Interest That Has Not Converted Into Bookings

Portugal, Turkey and the Frequent Travellers segment generated no bookings in the dataset.

Recommendations:
- Investigate potential barriers to booking.
- Review whether the available offers match customer interests.
- Test targeted incentives and relevant promotional content.
- Monitor future engagement and booking activity to identify whether these interventions improve results.

## 10. Limitations & Further Analysis

There are several limitations to consider when interpreting the results.

- The dataset is illustrative and does not represent real commercial activity.
- The analysis covers a defined dataset and does not establish long-term marketing trends.
- Customer destination preferences do not confirm actual booked destinations.
- The results identify associations and patterns but do not establish that a particular campaign or customer characteristic caused a booking.
- Further analysis could explore campaign timing, customer lifetime value, repeat bookings and longer-term engagement.

## 11. Project Files

The repository will contain the supporting materials used throughout the project:

- SQL queries used for data extraction and analysis.
- CSV datasets exported from the SQL analysis.
- Power BI dashboard screenshots.
- The Power BI report file, where available.

- Skills Demonstrated: SQL | Data Analysis | Data Preparation | Marketing Analytics | Customer Segmentation | Business Intelligence | Microsoft Power BI | Data Visualisation
  
## 12. Microsoft Power BI Report

A Microsoft Power BI report is included in this repository:

- **File:** [`Microsoft BI Final.pbix`](./Microsoft%20BI%20Final.pbix)
- **Download:** [`Microsoft BI Final.pbix`](./Microsoft%20BI%20Final.pbix)

The `.pbix` file contains the interactive report pages and visualisations described in this README.

### 13. Travel Business X – SQLite Database

This SQLite database contains the original dataset used to support my Travel Business X Email Marketing and Customer Analytics project.

The database was created and managed using DB Browser for SQLite and consists of three relational tables:

- **Campaigns:** Contains email campaign information, including campaign names, types, objectives and start dates.
- **Customers:** Contains customer information, including customer segments, age groups, countries and preferred travel destinations.
- **Email Events:** Records email marketing activity, including emails sent, deliveries, opens, clicks, conversions, unsubscribes and booking values.

The database was used as the foundation for my SQL analysis, allowing me to explore relationships between customer behaviour, email campaign performance, bookings and revenue.

SQL queries were used to extract, combine and analyse the data before the findings were developed into interactive dashboards using Microsoft Power BI.

**Privacy Notice:** Travel Business X is a pseudonym used to protect the identity of the original business. This project uses a constructed, illustrative dataset. All customer records and business performance figures are simulated and do not represent actual commercial results.

**File:** `Travel Business X Database.db`

**Tools:** SQLite | DB Browser for SQLite | SQL | Microsoft Power BI
