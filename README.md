# Food-Demand-Forecasting
Problem Statement
The data set is related to a meal delivery company which operates in multiple cities. They have various fulfilment centers in these cities for dispatching meal orders to their customers.
The dataset consists of historical data of demand for a product-center combination for weeks 1 to 145.
With the given data and information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations, so that these fulfilment centers stock the necessary raw materials accordingly.

Business Benefits
The replenishment of raw materials is done only on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance.
Therefore predicting the Demand helps in reducing the wastage of raw materials which would result in the reduced cost of operation. Increased customer satisfaction by timely fulfilling their expectations and requirements.

Data Dictionary
The dataset consists of three individual datasheets, the first dataset contains the historical demand data for all centers, the second dataset contains the information of each fulfillment center and the third dataset contains the meal information.

Weekly Demand data (train.csv):
Contains the historical demand data for all centers. The Train dataset consists of 9 variables and records of 423727 unique orders. test.csv contains all the following features except the target variable. The Test dataset consists of 8 variables and records of 32573 unique orders.

Variable	Definition
id	Unique ID
week	Week No
center_id	Unique ID for fulfillment center
meal_id	Unique ID for Meal
checkout_price	Final price including discount, taxes & delivery charges
base_price	Base price of the meal
emailer_for_promotion	Emailer sent for promotion of meal
homepage_featured	Meal featured at homepage
num_orders	(Target) Orders CountThe data set is related to a meal delivery company which operates in multiple cities. They have various fulfilment centers in these cities for dispatching meal orders to their customers. The dataset consists of historical data of demand for a product-center combination for weeks 1 to 145. With the given data and information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations, so that these fulfilment centers stock the necessary raw materials accordingly.
Business Benefits
The replenishment of raw materials is done only on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance.
Therefore predicting the Demand helps in reducing the wastage of raw materials which would result in the reduced cost of operation. Increased customer satisfaction by timely fulfilling their expectations and requirements.

Data Dictionary
The dataset consists of three individual datasheets, the first dataset contains the historical demand data for all centers, the second dataset contains the information of each fulfillment center and the third dataset contains the meal information.

Weekly Demand data (train.csv):
Contains the historical demand data for all centers. The Train dataset consists of 9 variables and records of 423727 unique orders. test.csv contains all the following features except the target variable. The Test dataset consists of 8 variables and records of 32573 unique orders.

Variable Definition
id Unique ID
week Week No
center_id Unique ID for fulfillment center
meal_id Unique ID for Meal
checkout_price Final price including discount, taxes & delivery charges
base_price Base price of the meal
emailer_for_promotion Emailer sent for promotion of meal
homepage_featured Meal featured at homepage
num_orders (Target) Orders Count

fulfilment_center_info.csv:
Contains information for each fulfilment center. The dataset consists of 5 variables and records of 77 unique fulfillment centers.

Variable Definition
center_id Unique ID for fulfillment center
city_code Unique code for city
region_code Unique code for region
center_type Anonymized center type
op_area Area of operation (in km^2)

meal_info.csv:
Contains information for each meal being served

Variable Definition
meal_id Unique ID for the meal
category Type of meal (beverages/snacks/soups….)
cuisine Meal cuisine (Indian/Italian/…)
