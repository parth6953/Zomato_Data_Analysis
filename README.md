# Zomato_Data_Analysis

Executive Summary
Purpose: The primary aim of this project is to analyze sales data from Zomato in Bangalore to uncover insights that can drive business strategies, improve customer satisfaction, and enhance overall performance.
Methods:
•	Data Collection: The Zomato dataset, provided by the company, includes comprehensive details such as restaurant names, locations, ratings, votes, types, dishes liked, cuisines, and more.
•	Data Cleaning: Addressed missing values and standardized data formats to ensure consistency and accuracy.
•	Data Analysis: Employed exploratory data analysis (EDA) techniques to identify patterns and trends. Leveraged Power BI for visualization to create insightful dashboards.
Key Findings:
•	Customer Preferences: Identified the most popular dishes, top-rated restaurants, and preferred types of cuisines.
•	Ordering Patterns: Found significant preferences for online ordering over dining in.
•	Restaurant Performance: Highlighted the types of restaurants with the highest ratings and votes.
•	Impact of Online Ordering: Discovered a positive correlation between the availability of online ordering and higher restaurant ratings.
Recommendations:
•	Focus on Popular Cuisines: Enhance marketing efforts for the most demanded cuisines to attract more customers.
•	Improve Online Ordering: Invest in optimizing the online ordering system to boost customer engagement and satisfaction.
•	Encourage Reviews: Develop strategies to encourage customers to leave reviews, as higher review counts correlate with better ratings.
•	Strategic Partnerships: Form partnerships with top-rated and popular restaurants to leverage their success for promotional activities.



Introduction
In the competitive landscape of the food and beverage industry, data-driven decision-making has become a critical factor for success. Zomato, as a leading online food delivery platform, generates vast amounts of data daily from customer interactions, restaurant reviews, and order details. Analysing this data can provide valuable insights into customer preferences, market trends, and operational efficiencies.
This project, "Zomato Sales Analysis," focuses on the restaurant scene in Bangalore, a major hub for dining and food delivery services. The primary objective is to leverage the provided Zomato dataset to uncover patterns and trends that can inform strategic business decisions.
By examining key metrics such as restaurant ratings, customer engagement, popular cuisines, and the impact of online ordering, this analysis aims to offer actionable insights that can enhance customer satisfaction, drive business growth, and optimize restaurant performance.
The project is structured to provide a comprehensive overview of the data analysis process, including data collection, cleaning, and visualization. Using powerful tools like Power BI, the project transforms raw data into meaningful visualizations, making it easier to interpret and act upon the findings. Through this analysis, Zomato can better understand its customer base, improve its service offerings, and maintain its competitive edge in the market.

Project Objectives
• Analyse Customer Preferences and Ordering Patterns:
•	Investigate which dishes and cuisines are most favored by customers.
•	Determine the frequency and types of orders placed, including online orders versus dining in.
•  Identify Top-Performing Restaurants and Popular Cuisines:
•	Highlight restaurants that receive the highest ratings and most votes.
•	Explore the characteristics of these top-performing establishments, such as their types, locations, and the cuisines they offer.
•	Identify trends in popular cuisines that could inform menu development and promotions.
•  Assess the Impact of Online Ordering on Ratings:
•	Analyze how the availability of online ordering influences customer ratings and reviews.
•	Compare the performance of restaurants with and without online ordering options.
•	Investigate whether online ordering leads to higher customer satisfaction and more frequent orders.
•  Provide Strategic Recommendations for Business Improvement:
•	Based on the analysis, suggest actionable strategies to enhance customer engagement and satisfaction.
•	Recommend improvements in the online ordering system to optimize the customer experience.
•	Propose marketing strategies focusing on popular dishes and high-demand cuisines.
•	Advise on forming strategic partnerships with top-rated restaurants to boost visibility and customer trust.
Data Collection and Description
The dataset used in this project was provided by the company and sourced from Zomato. It encompasses a wide range of information related to restaurants in Bangalore, offering a comprehensive view of the food and beverage industry in the city. The dataset includes the following key columns:
•	URL: The web link to the restaurant's Zomato page.
•	Address: The physical location of the restaurant.
•	Name: The name of the restaurant.
•	Online Order: Indicates whether the restaurant offers online ordering (Yes/No).
•	Book Table: Indicates whether the restaurant provides table booking services (Yes/No).
•	Rate: The average rating of the restaurant given by customers.
•	Votes: The number of votes received by the restaurant.
•	Phone: Contact number of the restaurant.
•	Location: The specific area or neighborhood where the restaurant is situated.
•	Rest Type (Restaurant Type): The type or category of the restaurant, such as café, bar, fine dining, etc.
•	Dish Liked: Popular dishes recommended by customers.
•	Cuisines: Types of cuisines offered by the restaurant.
•	Approx Cost (for two people): The approximate cost for two people dining at the restaurant.
•	Reviews List: A list of customer reviews in text form.
•	Menu Item: The items available on the restaurant's menu.
•	Listed In (Type): The type of service or meal, such as delivery, dine-out, etc.
•	Listed In (City): The city where the restaurant is located, confirming that all data pertains to Bangalore.


Data Cleaning and Transformation
Data cleaning and transformation are crucial steps in the data analysis process to ensure that the dataset is accurate, consistent, and ready for analysis. The following steps were undertaken to comprehensive data cleaning and transformation processes were performed to ensure the dataset was accurate, consistent, and ready for analysis. The following steps were taken:
Handling Missing Values
Identifying and Imputing Missing Values:
•	The dataset was inspected to identify columns with missing values, particularly focusing on the Restaurant Location column, which had several missing entries.
•	To address these missing values, replaced the missing values with ‘Unknown Location’. This approach ensured the location data was complete and consistent.
Standardizing Data Formats
Standardizing Ratings:
•	The Rate column contained values in a "4.5/5" format, which were converted to numerical values such as 4.5 for easier numerical analysis.
•	Invalid ratings (e.g., "NEW" or "-") were identified and handled by replacing them with 0, ensuring that only valid numerical ratings were included in the analysis.
Transforming Categorical Data
Binary Columns Transformation:
•	The Online Order and Book Table columns were transformed into binary numerical values (Yes = 1, No = 0). This transformation allowed for easier analysis and visualization.
Addressing Duplicates
Removing Duplicate Entries:
•	Duplicate rows were identified and removed to ensure the analysis was based on unique data points. This step was crucial for maintaining the integrity and accuracy of the analysis.
Data Validation
Ensuring Consistency:
•	After performing all cleaning and transformation steps, the dataset was validated to ensure consistency and correctness. This involved cross-checking sample entries and ensuring that all transformations were correctly applied.

Exploratory Data Analysis
Exploratory Data Analysis (EDA) was performed to identify patterns, trends, and insights within the data. Key EDA techniques and visualizations included:
•	Distribution Analysis: Examining the distribution of restaurant ratings, votes, and costs to understand central tendencies and variability.
	Votes: Analyzed the distribution and central tendency of votes to assess customer engagement.
	Approx Cost: Examined the average and distribution of the approximate cost for two people to understand pricing trends.
	Restaurant Ratings: Created histograms to visualize the distribution of restaurant ratings. This helped identify if most restaurants fall within a particular rating range.
•	Correlation Analysis: Investigating the relationships between variables, such as the correlation between online ordering availability and restaurant ratings.
	 Rating vs. Votes: Plotted scatter plots to explore the relationship between restaurant ratings and votes.
	Approx Cost vs. Rating: Analyzed the correlation between the cost for two people and restaurant ratings.
•	Categorical Analysis: Analysing categorical variables like restaurant types, cuisines, and locations to identify popular categories and their performance.
	Online Order: Analyzed the frequency of restaurants offering online ordering.
	 Book Table: Examined the proportion of restaurants providing table booking services.
	 Restaurant Types: Visualized the count of different types of restaurants (e.g., cafes, bars, fine dining).
	Cuisines: Created donut charts to show the distribution of different cuisines offered by the restaurants.
•	Visualization Tools: Utilizing Power BI to create visualizations such as bar charts, donut charts, scatter plots, and word clouds to effectively communicate findings.

Key Findings
The analysis of the Zomato dataset revealed several critical insights through detailed data analysis and visualization. Here are the key findings from the project:
1. Customer Preferences
•	Popular Cuisines: North Indian, Chinese, and Fast Food emerged as the most popular cuisines among customers, indicating a strong preference for these food types.
•	Top Dishes: Dishes like Biryani, Paneer Butter Masala, and Pizza were frequently mentioned in positive reviews, highlighting their popularity.
•	Preferred Restaurant Types: Casual Dining and Quick Bites were the most common types of restaurants, indicating that customers prefer relaxed dining experiences.
2. Ordering Patterns
•	Online Ordering Preference: A significant number of restaurants offer online ordering services. Restaurants with online ordering available generally received higher customer ratings, indicating a strong customer preference for this convenience.
•	Table Booking: The availability of table booking services also correlated with higher customer ratings, suggesting that customers value the ability to reserve tables in advance.
3. Restaurant Performance
•	High-Rated Restaurants: Fine Dining and Casual Dining restaurants tend to have higher average ratings compared to Quick Bites and Cafes. This suggests that a more formal dining experience is appreciated by customers.
•	Votes and Ratings: Restaurants with a higher number of votes tend to have higher ratings, indicating that customer engagement and feedback positively impact perceived restaurant quality.
4. Impact of Online Ordering
•	Correlation with Ratings: There is a positive correlation between the availability of online ordering and higher restaurant ratings. Restaurants offering online ordering received more favorable reviews, possibly due to the convenience and accessibility provided to customers.
•	Customer Engagement: Online ordering also appears to boost customer engagement, as evidenced by the higher number of votes for restaurants with this service.
5. Geographical Insights
•	Restaurant Density: Certain areas in Bangalore, such as Koramangala and Indiranagar, have a high density of restaurants, indicating these are popular dining destinations.
•	High-Rated Areas: Areas with a high concentration of restaurants also tend to have higher average ratings, suggesting that competition may drive better service and quality.
6. Cost Analysis
•	Approximate Cost: The average cost for two people varies significantly across different types of restaurants. Fine Dining and Casual Dining restaurants generally have higher costs compared to Quick Bites and Cafes.
•	Cost vs. Ratings: Higher cost does not necessarily correlate with higher ratings, indicating that customers value the overall dining experience and food quality over just the cost.
7. Customer Reviews
•	Sentiment Analysis: Positive reviews often mention aspects like food quality, service, and ambiance, while negative reviews frequently highlight issues like delayed service and food quality inconsistencies.
•	Review Frequency: Restaurants with a higher frequency of reviews tend to maintain a higher average rating, showing that consistent customer feedback is vital for maintaining quality.
Recommendations
•	Focus on Popular Cuisines: Restaurants should consider enhancing their menu offerings around the most demanded cuisines, such as North Indian and Chinese, to attract more customers.
•	Enhance Online Ordering: Investing in optimizing the online ordering system can significantly boost customer engagement and satisfaction. Ensuring a seamless online ordering experience is crucial.
•	Promote Table Booking: Encouraging customers to book tables in advance can improve customer satisfaction and potentially increase restaurant ratings.
•	Encourage Reviews: Developing strategies to encourage customers to leave reviews can help restaurants gather valuable feedback and improve their ratings. More reviews can also enhance the restaurant's visibility and credibility.
•	Geographical Focus: Targeting high-density and high-rated areas like Koramangala and Indiranagar for new restaurant openings or promotional activities can leverage the existing popularity of these locations.
•	Monitor Costs: Restaurants should balance their pricing strategies to ensure they offer value for money while maintaining high service and food quality standards.

Visualizations
The data was visualized using Power BI to create insightful and interactive dashboards. Key visualizations included:
•	Donut Charts: Displaying the distribution of online orders and table bookings.
•	Bar Charts: Illustrating the approximate cost for two people across different types of restaurants.
•	Funnel Charts: Highlighting the relationship between menu items and restaurant ratings.
•	Word Clouds: Showcasing the popularity of different types of restaurants.
•	Scatter Plots: Demonstrating the correlation between restaurant ratings and votes. These visualizations effectively communicated the findings and helped in identifying patterns and trends in the data.

Conclusion
The Zomato sales analysis provided valuable insights into the restaurant landscape in Bangalore. By leveraging the comprehensive dataset, the analysis uncovered key trends in customer preferences, restaurant performance, and the impact of online ordering. The findings suggest that enhancing online ordering services, focusing on popular cuisines, and encouraging customer reviews can significantly improve restaurant ratings and customer satisfaction. The visualizations created in Power BI offered a clear and actionable view of the data, facilitating data-driven decision-making for strategic business improvements. This analysis underscores the importance of utilizing data analytics to drive business growth and optimize customer experiences in the competitive food and beverage industry.

