# 📌 Project Overview

The Restaurant Recommendation System leverages the large Yelp dataset to recommend restaurants based on user preferences, reviews, and business attributes. With the increasing demand for dining experiences, this system analyzes user evaluations and offers personalized suggestions to help users make informed dining choices. It also provides insights for restaurant owners to improve their businesses.

This system uses Big Data technologies to process large amounts of data from Yelp’s open dataset and builds a recommendation model based on user evaluations, business hours, food quality, service, and more.

## 📋 Features

- **User-centric Recommendations**: Recommend restaurants based on user preferences (e.g., food quality, service).
- **Data Analysis**: Analyze user reviews to extract useful information about what attracts customers.
- **Scalable & Efficient**: Built with Big Data technologies to handle large datasets efficiently.
- **Restaurant Insights**: Provide business owners with insights into their restaurant’s strengths and areas for improvement.
- **Advanced Algorithms**: Uses collaborative filtering and content-based filtering techniques for personalized recommendations.

## 🗃️ Dataset Description

The project utilizes Yelp’s Open Dataset, which includes:

- 4.7 million user reviews
- 150,000 business profiles
- 200,000 images
- 1.2 million business attributes, including:
    - Business hours
    - Parking availability
    - Reservation options
    - Customer ratings and more
- 1 million user tips from 1.1 million users

This dataset provides a comprehensive sample to implement restaurant recommendations using user-generated content and business attributes.

## 🛠️ Technologies Used

- **Big Data Frameworks**: Apache Hadoop, Spark for large-scale data processing.
- **Distributed Storage**: HBase, Cassandra for storing large datasets.
- **Data Processing**: MapReduce, Spark SQL for data analysis and transformation.
- **Recommendation Algorithms**: Collaborative Filtering, Content-Based Filtering.
- **Web Frameworks**: Flask or Django for the backend API.
- **Frontend**: React.js for a user-friendly interface.
- **Data Visualization**: Tableau, D3.js for generating visual insights.

## 🏗️ Architecture

- **Data Collection**: The system extracts data from the Yelp dataset and processes it using Spark.
- **Recommendation Engine**: The engine analyzes reviews and business data to build the user's mental model and recommend restaurants.
- **Backend API**: A Flask/Django-based API serves the recommendations to the frontend.
- **Frontend**: A React.js web application displays recommendations and restaurant details.

## 📱 Usage

- **Step 1**: Users input their preferences (e.g., preferred cuisine, rating, location).
- **Step 2**: The backend processes the input and retrieves recommendations from the dataset.
- **Step 3**: The frontend displays a list of restaurant recommendations based on the user's inputs.
- **Step 4**: Users can explore restaurant details, including reviews, location, and available amenities.

## 🎯 Project Goals

- **Scalable Recommendation System**: Build a recommendation system capable of handling large datasets.
- **User Personalization**: Provide recommendations based on individual user preferences.
- **Business Insights**: Help restaurant owners improve by understanding the aspects customers care about most (e.g., food, service).
- **Real-Time Performance**: Ensure quick recommendation generation even with massive data.

## ⚡ Challenges

1. **Handling Large Datasets**: The Yelp dataset is large, requiring efficient distributed processing.
2. **Recommendation Accuracy**: Building an effective recommendation algorithm that balances food quality, service, and user preferences.
3. **Scalability**: The system must scale efficiently with increasing amounts of user data and restaurant details.
4. **Real-time Processing**: Ensuring quick recommendation generation even with massive data.

## 📸 Work Samples

### 🔹 Screenshot 1: Ratings for Restaurants
![Login Page](https://github.com/kiran98118/Yelp-Recommendation-System/blob/5f03e0b697e64ae211c3f8321cf0660bf00583d4/Images/Screen%20Shot%202025-03-02%20at%204.50.51%20PM.png?raw=true)

### 🔹 Screenshot 2: State vs avg Rating
![Login Page](https://github.com/kiran98118/Yelp-Recommendation-System/blob/e903bc0a44037077872763bb1697b5fe7a5c8e30/Images/Screen%20Shot%202025-03-02%20at%205.10.55%20PM.png?raw=true)


### 🔹 Screenshot 3: Avg word count for each star rating
![Login Page](https://github.com/kiran98118/Yelp-Recommendation-System/blob/897de75eacdf11daaec70ca8a5608525368b4b6e/Images/Screen%20Shot%202025-03-02%20at%205.10.55%20PM.png?raw=true)


