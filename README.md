# **Smarter Housing Choices — Real Estate Market Analysis in Bahrain**

## **Project Overview**

Smarter Housing Choices is a data analytics project that examines Bahrain’s real estate market to help families make confident and informed housing decisions.
The analysis compares rental and sale properties across all five governorates — Capital, Muharraq, Northern, Central, and Southern — to uncover price trends, affordability, and housing availability.

Using data collected through web scraping, the project highlights how prices vary by area, property type, and amenities, offering clear recommendations for different family sizes and budgets.

## **Goals**

- Provide transparency in Bahrain’s housing market through data-driven insights.

- Identify the most affordable areas for families based on budget and family size.

- Compare property types (apartments, villas, land) across rental and sale markets.

- Support property seekers in making confident housing choices.

## **Audience**
- Renters: Families seeking affordable homes under 500 BHD/month.
- Buyers: Families looking to purchase properties below 150,000 BHD.

## **Dataset**

**Source:** Property Finder Bahrain

**Total Properties:** 21,558

**Rent:** 14,100 properties

**Sale:** 7,458 properties

**Governorates:** 5

**Areas:** 146 distinct locations

**Collection Date:** 29 September 2025

## **Data Collection & Preprocessing**
**Tools:**    Python, BeautifulSoup, pandas, selenium, Power BI

**Web Scraping**

- Collected property listings from Property Finder Bahrain.

- Extracted details including title, price, property type, area, bedrooms, bathrooms, and amenities.

- Saved structured data in CSV format for analysis.

**Data Cleaning**

- Standardized price formats (removed “BHD” and “/month”).

- Created unique property IDs to prevent duplication.

- Split size column into Size_sqft and Size_sqm.

- Normalized property types and governorate names.

- Converted “Inclusive/Exclusive” utilities flag into binary (1 = included, 0 = not included).

- Combined rent and sale datasets into one unified dataset for analysis.

## **Data Dictionary**

- Property_id (Integer): Unique identifier for each listing.

- Offer (Text): Type of offer — Rent or Buy.

- URL (Text): Link to the property listing.

- Property_type (Text): Property category (Apartment, Villa, Land, etc.).

- Price (Integer): Price in Bahraini Dinar (BHD).

- Include_w_e (Binary): Whether price includes water & electricity (1 = Yes, 0 = No).

- Title (Text): Property headline.

- Area (Text): Area name.

- Governorate (Text): Administrative region (Capital, Muharraq, Northern, Central, Southern).

- Beds (Integer): Number of bedrooms.

- Baths (Integer): Number of bathrooms.

- Availability_date (Date): Date of listing or availability.

- Agent_name (Text): Listing agent name.

- Agency (Text): Real estate company.

- Amenities (Float): Number of available amenities.

- Size_sqft (Integer): Size in square feet.

- Size_sqm (Integer): Size in square meters.


## **Key Findings**
**1.** **Rental Market**

  - Capital Governorate dominates Bahrain’s rental listings.
  - Northern Governorate has the highest rents; Central is the most affordable.
  - Apartments are the most common rental type.
  - Larger homes cost nearly 4× more than smaller ones.
  - Central Governorate offers the best overall value for renters.

**2.** **Sale Market**

  - Most sale listings are in Capital and Muharraq.

  - Southern Governorate has the highest property prices.

  - Apartments are the most affordable; villas and land are priced higher.

  - Price increases significantly with the number of bedrooms.

  - Central Governorate provides the best balance between cost and amenities.


## **Conclusion**
This project provides an analytical overview of Bahrain’s property market to help renters and buyers make smarter housing choices.
By combining real-time data collection with data visualization, the analysis improves market transparency and supports decision-making based on facts rather than assumptions.






