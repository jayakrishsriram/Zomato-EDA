This is collection of restaurants listed on Zomato in Bengaluru City. This dataset is present in [kaggle](https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset). 
This dataset have 17 column. These column with their use is mentioned below.
1. `url` - This data contains the URL of that reataurant.
2. `address` - This contains the complete address of the restaurants.
3. `name` - Contains the name of the restaurant.
4. `online_order` - This give the information whether they accepts online orders.
5. `book_table` - This tells that whether booking tables is possible or not.
6. `rate` -  Gives the detail about the rating of the restaurant.
7. `votes` - Tells about number of people who gave rating fot the hotel
8. `phone` - Gives the phone number of the restaurant.
9. `location` - Gives the area of the restauant.
10. `rest_type` - Gives the restaurant type.
11. `dish_linked` - Lists the most liked Dish by more people.
12. `cuisines` - Cuisines served by restaurant.
13. `approx_cost(for two people)` - Approximate Cost for Two people. 
14. `reviews_list` - Reviews of each person 
15. `menu_item` - Gives the menu list
16. `listed_in(type)` - Gives the category of the restaurants.
17. `listed_in(city)` - Name of the City(like area that it comes under)
 
These are the 17 columns with its detail. There are some columns that are not necessary for the analysis. Those columns are removed

# Plans for this analysis:
1. Type of food most people like.
2. Review based on each restaurants using review_list column.(using ai api for documenting.)
3. Ratings based on each restaurants with its range.
4. Number of votes vs rating.
5. Number of hotels in each location
6. Type of hotel that is common in each location.
7. mapping location and listed_in(city)
# Achieved analysis:
1. Removed unwanted data
2. Replace mean value for some data
3. Replacing minimum with others to make it ready for visualization.

