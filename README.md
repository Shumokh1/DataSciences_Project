# Smarter Sustainable Tourism: Building a High-Quality Dataset for the Future of Tourism Analytics in Saudi Arabia

This repository contains a comprehensive data science project aimed at analyzing and improving tourism experiences in Saudi Arabia. The project integrates datasets, performs detailed sentiment and trend analyses, and provides a recommendation system for tourist destinations. It aligns with Saudi Arabia's Vision 2030 goals by leveraging data to promote tourism and enhance visitor satisfaction.

## Key Features

### 1. **Data Collection and Integration**
- **Sources**: Data scraped from **TripAdvisor**, **Google Maps**, and two **Kaggle** datasets:
  - [Entertainment Destinations in Saudi Arabia](https://www.kaggle.com/datasets/anas123siddiqui/entertainment-in-saudi-arabia)
  - [Cafe Shops in Riyadh](https://www.kaggle.com/datasets/riybot/riyadh-cafes)
- **Scraping and Cleaning**: Implemented preprocessing steps to normalize and integrate multiple data sources.

  
## Codebook for Relevant Variables
- **name**: Name of the destination.
- **PlaceRating**: Numerical rating given by users (1–5) to the place.
- **number_of_reviews**: Total count of reviews for each destination.
- **Reviews**: Comments given by users for the places.
- **ReviewRating**: rating with the review.
- **text_sentiment**: Sentiment classification inferred from reviews (positive, neutral, negative).
- **theme**: Categorical description of the type of destination (e.g., "Points of Interest," "Religious Sites").
- **latitude** and **longitude**: Geographical coordinates of the destination.
- **address** The full postal or descriptive address of the destination.
- **webUrl** URL to the place’s page on platforms like TripAdvisor or Google Maps, allowing users to find additional details, reviews, and directions.
- **website** The official website or a direct link associated with the destination, if available. Often used to find more detailed or official information about the attraction.
- **description**  A textual overview of the destination, summarizing its key attractions, features, and significance.

### 2. **Data Preprocessing**
- Deduplication and standardization of place names and themes.
- Translation of non-English entries to English.
- Removal of irrelevant data and unrelated entries.
- Added new features like sentiment analysis based on user reviews.

### 3. **Visualizations**
- Distribution and density plots of ratings and sentiments across themes.
- Number of positive, neutral, and negative reviews.
- Geographical distribution of attractions using scatter plots.
- Number of reviews for each theme.

### 4. **Recommendation System**
- Utilizes **TF-IDF vectorization** and **cosine similarity** to suggest similar destinations based on themes.
- Provides detailed outputs, including destination names, themes, ratings, and URLs.

### 5. **Insights and Analysis**
- Highlights key trends in visitor engagement, sentiment, and geographical clustering.
- Offers actionable insights for tourism stakeholders.

## Results
- Over 24,000 entries analyzed, offering a high-quality dataset for tourism analytics.
- Strong overall sentiment, with 78.6% of reviews categorized as positive.
- Popular clusters around major urban hubs like Riyadh, Jeddah, and Dammam.

## Limitations and Future Directions
- **Sentiment Analysis**: Ratings-based sentiment categorization could be enhanced with advanced NLP techniques.
- **Dynamic Nature**: Data reflects a snapshot and requires updates for new trends.
- **Expansion Plans**:
  - Broader data collection from rural and niche areas.
  - Integration of traveler personas for deeper insights.
  - Advanced modeling and predictive analytics.


## Acknowledgments
This project was developed using public datasets and openly accessible tools. We thank TripAdvisor, Google Maps, and the contributors of the Kaggle datasets for their valuable resources.

---

Contributors: 

Deema Hamidah

Shumokh Abdullah

Hadeel Balahmar
