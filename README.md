# airbnb-ratings-discovery

Which metrics influence Airbnb’s guest reviews? 

[Airbnb Analytics Project Overivew & Findings] (https://docs.google.com/presentation/d/1eSemTVEjqQycnH_mSbbX3vGekGQFGTVFvG3zooCCyIc/edit?usp=sharing) 

### Goal
We are hoping to utilize the LA Airbnb Listings dataset in order to test the impact of certain metrics (such as price, location, host profile, amenities) on an Airbnb’s overall ratings. 

### Research Questions
- Is there a correlation between the neighborhood and ratings?
- Is there a correlation between price and ratings?
- What are the most common types of rooms seen in LA?
- Discover neighborhood clusters on a map to find out popular neighborhoods.
- Does the number of total listings a host has affect their communication scores?
- How does the review score of an airbnb relate to the host’s identity being verified?

### How do research questions affect our project goal?

We aim to analyze Airbnb’s data to discover how different factors influence ratings - whether it is a host’s rating or a rating of their listing. Our research questions will be used to find correlations of ratings with price and the location of a neighborhood. Based on this, we also want to investigate the most popular areas where Airbnb’s are located around the city of Los Angeles. Our questions analyze how the price of a listing would change with location of the listing around Los Angeles as well as observe how ratings of a listing change with the price of a listing. Next, we wish to find out the most common types of rooms in LA and possibly find trends in room prices and room type. We are also interested in learning more about the hosts of these Airbnb’s, and therefore wish to investigate how a host’s identity being verified relates to their score. Finally, we wish to investigate whether the total number of listings a host has affects their communication scores with their customers.

### Business Implications

Airbnb is one of the world’s most valuable vacation listing services and with that comes a very large user base. To select the best listing, customers of Airbnb primarily look at reviews of listings, hosts and prices to determine a good fit for a new vacation stay. Analyzing these metrics help Airbnb decide how to prioritize their listings and showcase top hosts and top priced listings. The potential business implications that we can apply with our insights would involve helping Airbnb and their customers better understand hosts, listings, and how ratings are finally decided based on these different criteria/attributes. 

[Why reviews matter | Reviews build trust in the community and help drive your business.](https://www.airbnb.com/resources/hosting-homes/a/why-reviews-matter-41)

### Preliminary Analysis of DataSet
Key Columns (and data types): 
- Id
    - Data Type: Numerical 
    - Value Example: ‘16228948’ 
- host_is_superhost
    - Data Type: Boolean
    - Value Example: ‘t’
- host_total_listings_count	
    - Data Type: Numerical 
    - Value Example: ‘1’
- host_identity_verified	
    - Data Type: Boolean
    - Value Example: ‘t’
- neighbourhood_cleansed	
    - Data Type: Text
    - Value Example: ‘Acton’
- Latitude
    - Data Type: Numerical 
    - Value Example: ‘34.0288991695155’
- Longitude	
    - Data Type: Numerical
    - Value Example: ‘t’
- property_type	
    - Data Type: Text
    - Value Example: ‘Apartment’
- room_type	
    - Data Type: Text 
    - Value Example: ‘Entire home/apt’ 
- amenities	
    - Data Type: String List 
    - Value Example: ‘{Internet,"Wireless Internet",Kitchen,"Free parking on premises",Washer,Dryer,"Smoke detector",Essentials,Shampoo}’
- Price
    - Data Type: Numerical 
    - Value Example: ‘30’
- availability_365	
    - Data Type: Numerical 
    - Value Example: ‘306’
- number_of_reviews	
    - Data Type: Numerical
    - Value Example: ‘12’
- review_scores_communication	
    - Data Type:
    - Value Example: ‘t’
- review_scores_location	
    - Data Type: Numerical
    - Value Example: ‘10’
- review_scores_value	
    - Data Type: Numerical 
    - Value Example: ‘10’ 
- cancellation_policy	
    - Data Type: Text
    - Value Example: ‘Strict’
- Reviews_per_month
    - Data Type: Numerical
    - Value Example: ‘1.91’
