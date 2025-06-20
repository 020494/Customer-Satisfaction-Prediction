# Customer Satisfaction Prediction

This project focuses on predicting customer satisfaction using a Machine Learning approach. By analyzing historical customer support data, it uncovers the key drivers of satisfaction and builds a predictive model to help businesses improve customer experiences.

# 🎯 Objectives

- Analyze customer support ticket data to understand patterns in satisfaction.
- Identify key features that influence customer sentiment.
- Build a predictive model using Random Forest Classifier.
- Apply hyperparameter tuning to improve model performance.
- Derive actionable insights to enhance support operations.

# 🔍 Project Highlights

- Performed data cleaning, outlier handling, and feature engineering.
- Visualized patterns across age, gender, issue types, support channels, and priorities.
- Built a Random Forest model with optimized hyperparameters.
- Found that issue resolution speed and ticket type/channel had stronger influence than demographics.
- Provided recommendations to boost satisfaction based on service factors.

# 📊 Key Visuals

- Age and gender distribution plots
- Ticket volume by product, type, priority, and channel
- Customer satisfaction breakdowns by demographics and support features

# 🧰 Technologies Used

- Python (pandas, matplotlib, seaborn)
- scikit-learn (Random Forest, GridSearchCV)
- Jupyter Notebook

# 📌 Dataset Overview

- Features: `customer_id`, `gender`, `age`, `ticket_channel`, `ticket_priority`, `product_purchased`, `ticket_type`, `resolution_time`, `satisfaction_level`, etc.
- Label: `satisfaction_level` (e.g., Satisfied, Neutral, Dissatisfied)

# 💡 Key Insights

- High-priority tickets get resolved faster and yield higher satisfaction.
- Channels like chat and social media tend to lead to more satisfied customers.
- Younger customers prefer digital-first support options.
- Service quality and responsiveness have a greater impact than demographic factors.

