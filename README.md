# Hotel-Booking-Cancellations
Predictive Analysis for Hotel Booking Cancellations  and Guest Behavior

Abstract
This project analyzes hotel booking demand data to identify key factors influencing guest bookings and predict cancellations, leveraging data analysis and machine learning for optimized booking management. The dataset includes attributes such as booking lead time, hotel type, market segment, booking cancellations, and total stay duration.
Through extensive Exploratory Data Analysis (EDA), we identified patterns such as the dominance of small group bookings and the relatively limited impact of lead time on guest numbers. Feature engineering was employed to enhance the dataset, creating new variables such as total stay duration and lead time categories based on hotel type and stay duration. The insights gained from this project can help hotel managers optimize operations, manage inventory, and adjust pricing strategies based on demand fluctuations.
________________________________________
Problem Statement
The objective of this project is to conduct an Exploratory Data Analysis (EDA) on the Hotel Booking Demand dataset and build a model to predict whether a booking will be canceled. By leveraging customer demographics, booking details, and seasonal patterns, this analysis will provide insights into key trends and behaviors, enabling hotels to anticipate cancellations more effectively.
Accurate predictions will allow hotels to implement strategies such as overbooking, targeted marketing for at-risk customers, or dynamic pricing to mitigate cancellation impacts. The insights gained from this project can contribute to broader applications in customer behavior analytics and operational optimization, making it a valuable tool for improving hotel management strategies.
Key Questions Addressed:
•	What factors contribute to booking cancellations?
•	Can we accurately predict whether a hotel booking will be canceled using available data?
•	How do seasonal trends and customer preferences influence hotel booking demand?
________________________________________
Dataset
The dataset used in this project contains the following key attributes:
•	Booking Lead Time: Number of days between booking and arrival date
•	Hotel Type: City hotel or resort hotel
•	Market Segment: Source of the booking (e.g., online, corporate, direct walk-in)
•	Total Stay Duration: Sum of nights spent at the hotel
•	Cancellation Status: Whether the booking was canceled
•	Customer Demographics: Includes variables such as country of origin
•	Seasonal Factors: Month and year of booking
________________________________________
Methodology
1.	Data Cleaning & Preprocessing:
o	Handling missing values
o	Encoding categorical variables
o	Feature engineering (e.g., creating new features based on existing ones)
2.	Exploratory Data Analysis (EDA):
o	Identifying trends in cancellations, lead times, and seasonal variations
o	Visualizing customer booking behaviors
3.	Feature Selection & Model Building:
o	Applying machine learning models such as Logistic Regression, Random Forest, and Gradient Boosting
o	Fine-tuning hyperparameters for optimal performance
4.	Evaluation & Interpretation:
o	Assessing model performance using accuracy, precision, recall, and F1-score
o	Extracting actionable insights for hotel management
________________________________________
Key Findings
•	Small group bookings dominate hotel reservations.
•	Lead time has a moderate influence on booking volume.
•	Specific customer segments are more likely to cancel bookings.
•	Seasonal trends play a significant role in demand fluctuations.
________________________________________
Technologies Used
•	Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
•	Jupyter Notebook for analysis
•	Machine Learning models (Logistic Regression, Random Forest, Gradient Boosting)
Results and Insights
•	The best-performing model achieved an accuracy of 86% on the test dataset.
•	Feature importance analysis revealed that lead time, special requests, and previous cancellations were the most influential factors in predicting cancellations.
•	The Online Travel Agents (OTA) segment shows the highest booking and cancellation rates, indicating a potential area for targeted improvements.
________________________________________
Conclusion
Best Model: Random Forest emerged as the best model with the highest accuracy (86%) and F1-score (0.79) for predicting cancellations. It effectively captured complex patterns in the data, making it the most suitable model for our problem statement.
This analysis provided valuable insights into hotel booking cancellations:
•	Lead time, special requests, and previous cancellations were identified as major contributors to booking cancellations.
•	Predicting cancellations: Random Forest was the most effective model, allowing hotels to anticipate cancellations and adjust pricing, marketing, and operations accordingly.
•	City Hotels are the preferred choice, receiving 79,330 bookings compared to 40,060 for Resort Hotels. Most bookings originate from European countries, particularly Portugal, highlighting a strong domestic market.
•	Seasonal trends: City Hotel bookings exhibit noticeable fluctuations, whereas Resort Hotels maintain relatively stable occupancy throughout the year.
•	Booking behavior: Most reservations are for 1 to 2 guests, with most bookings made within 0-90 days prior to check-in.
•	Guest composition: Adults and children primarily drive booking numbers, with Bed & Breakfast being the most popular meal option.
•	Cancellations: More common with longer lead times, though room mismatches do not significantly impact cancellations.
These findings will enable hotel management to refine marketing strategies, optimize booking processes, and implement measures to improve customer satisfaction while reducing cancellation rates.
________________________________________
Future Work
•	Incorporating deep learning techniques for improved accuracy.
•	Using real-time booking data for dynamic prediction updates.
•	Expanding the dataset to include external factors such as weather and local events.


