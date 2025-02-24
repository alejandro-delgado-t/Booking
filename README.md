# EFFECTS OF FORMULA 1 ON BARCELONA’S RENTAL PRICES (ACCORDING TO BOOKING DATA)

## Abstract

This study investigates the impact of the Formula 1 Grand Prix in Barcelona on hotel rental prices using computational techniques in web scraping, text mining, and econometric modeling. Our approach involves developing an automated web scraper to extract booking data from Booking.com, capturing hotel prices, amenities, and customer ratings for both Barcelona (treatment group) and Lisbon (control group) across multiple time periods.

We preprocess textual hotel descriptions using Natural Language Processing (NLP) techniques, including tokenization, stopword removal, and stemming, to extract key amenities as control variables in our econometric models. Additionally, word cloud visualizations before and after preprocessing highlight the impact of text cleaning on feature selection.

For analysis, we implement a Difference-in-Differences (DiD) model with fixed effects regression, integrating text-derived features to refine price variation estimates. The results indicate a significant price surge during the event, particularly in lower-rated hotels. We further enhance our model by incorporating heterogeneous treatment effects, examining how pricing dynamics shift based on hotel characteristics.

Our study demonstrates the power of computational methods in economic research, showcasing the integration of web scraping, NLP, and econometrics for data-driven insights. Future improvements include applying advanced machine learning models for price prediction, sentiment analysis of hotel reviews, and expanding the dataset across multiple events for generalizability.

--
## Authors
- Viktoria Gagua
- Alex Malo
- Alejandro Delgado

--

## Methodology  

1. **Web Scraping**:  
   - Develop an automated web scraper using Python and Selenium to extract hotel data from Booking.com.  
   - Capture key attributes including price, hotel rating, and amenities.  
   - Scrape data for Barcelona (treatment group) and Lisbon (control group) across selected time periods.  

2. **Data Preprocessing**:  
   - Clean and structure the scraped data into a standardized format.  
   - Convert textual hotel descriptions into structured features using NLP techniques (tokenization, stopword removal, stemming).  
   - Generate word cloud visualizations to analyze key textual features before and after preprocessing.  

3. **Econometric Modeling**:  
   - Implement a Difference-in-Differences (DiD) model to quantify the effect of the Formula 1 event on hotel prices.  
   - Use fixed effects regression to control for unobserved hotel-specific and time-specific variations.  
   - Integrate text-derived features (e.g., amenities) as additional control variables.  

4. **Heterogeneous Treatment Effects Analysis**:  
   - Examine the impact of the event across different hotel categories (e.g., low-rated vs. high-rated hotels).  
   - Incorporate interaction terms to explore variations in price effects based on hotel characteristics.  

5. **Validation and Robustness Checks**:  
   - Conduct pre-treatment trend analysis to verify the parallel trends assumption.  
   - Assess model fit and performance using diagnostic tests.  
   - Explore alternative control cities to validate findings.  

6. **Future Enhancements**:  
   - Apply advanced machine learning models for price prediction.  
   - Perform sentiment analysis on customer reviews to enrich price determinants.  
   - Extend the study across multiple events and years to improve generalizability.

  --

  ## File Descriptions
    - booking_project: Jupyter notebook with the code.
    - NLP_Final_Project: pdf with project analysis.
    - merged_hotel_data: scrapped data.
