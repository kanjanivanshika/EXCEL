## Digital Marketing Performance Dashboard**


## Project Objective

The primary objective of this project is to develop an interactive Digital Marketing Performance Dashboard that centralizes, visualizes, and analyses cross channel marketing data (Paid Ads, SEO, and Email) into a single source of truth. This tool enables marketing teams and decision makers to track key performance indictors, monitor real-time advertising spend, and evaluate campaign efficiency (ROAS and CPA) without manual reporting. Ultimately, the dashboard eliminates data silos, helping stakeholders quickly spot underperforming campaigns, allocate budgets dynamically, and optimize user journeys to maximize digital marketing return on investment.


## Dataset Description

This Dataset consists of a multi-channel structured data log capturing the daily performance of various digital marketing campaigns across an annual or monthly timeline. It combines data from advertising platforms (Google Ads, Meta Ads), web analytics tools (Google Analytics4), and customer relationship management (CRM) systems. The dataset is structured at a granular daily campaign level, where each row represents the performance of a specific marketing campaign on a single day. It includes metadata to classify campaigns by platform and target audience, performance metrics to measure user engagement and attention, and financial metrics to compute financial viability and customer acquisition success.

### Key Columns & Data Fields

| NO. | Column Name             | Description                                                      |
| --: | ------------------------| ---------------------------------------------------------------- |
|   1 | **Date**                | The specific calendar day the metrics were recorded.             |
|   2 | **Campaign_ID**         | Unique identification code for each individual marketing.         |
|   3 | **Campaign_Name**       | Name of campaign (e.g: "Black_Friday_2026","Brand Awareness")    |
|   4 | **Marketing_Channel**   | The digital medium used (eg:Paid Search, Paid Social, Email, SEO. |
|   5 | **Platform**            | The specific network hosting the ad eg:(GoogleAds, Meta,Linkedin.)|
|   6 | **Target_Audience**     | Demographic or behavior segment targeted eg:"Lookalike_Existing_Buyers" |
|   7 | **Ad_Spend**            | The exact budget spent on that platform for the day (in currency format) |
|   8 | **Impressions**         | Total  number of times the digital ad or content was displayed to users. |
|   9 | **Clicks**              | Number of times users interacted with and clicked on the ad link.        |
|  10 | **Sessions**            | Total number of visits initiated on the company website via that specific campaign. |
|  11 | **Bounce Rate**         | Percentage of website visitors who left the site after viewing onle one page.       |
|  12 | **Leads_Generated**     | Number of users who completed a sign-up, form-fill or registration.                 |
|  13 | **Conversions_Sales**   | Total number of completed financial purchases driven by the campaign.               |
|  14 | **Revenue Generated**   | Total income earned directly from the conversion sales (in currency format).        |
