# Tourism Analytics and Recommendation System for Saudi Arabia

This repository contains a comprehensive data science project aimed at analyzing and improving tourism experiences in Saudi Arabia. The project integrates datasets, performs detailed sentiment and trend analyses, and provides a recommendation system for tourist destinations. It aligns with Saudi Arabia's Vision 2030 goals by leveraging data to promote tourism and enhance visitor satisfaction.

## Key Features

### 1. **Data Collection and Integration**
- **Sources**: Data from TripAdvisor, Google Maps, and two Kaggle datasets:
  - [Entertainment Destinations in Saudi Arabia](https://www.kaggle.com/datasets/anas123siddiqui/entertainment-in-saudi-arabia)
  - [Cafe Shops in Riyadh](https://www.kaggle.com/datasets/riybot/riyadh-cafes)
- **Data Includes**: Tourist destination names, ratings, reviews, locations, descriptions, and themes.
- **Scraping and Cleaning**: Implemented preprocessing steps to normalize and integrate multiple data sources.

### 2. **Data Preprocessing**
- Deduplication and standardization of place names and themes.
- Translation of non-English entries to English.
- Removal of irrelevant data and unrelated entries.
- Added new features like sentiment analysis based on user reviews.

### 3. **Visualizations**
- Distribution and density plots of ratings and sentiments across themes.
- Geographical distribution of attractions using scatter plots.
- Sentiment trends and review counts across different categories.

### 4. **Recommendation System**
- Utilizes **TF-IDF vectorization** and **cosine similarity** to suggest similar destinations based on themes and visitor preferences.
- Provides detailed outputs, including destination names, subtypes, ratings, and URLs.

### 5. **Insights and Analysis**
- Highlights key trends in visitor engagement, sentiment, and geographical clustering.
- Offers actionable insights for tourism stakeholders.

## Results
- Over 24,000 entries analyzed, offering a high-quality dataset for tourism analytics.
- Strong overall sentiment, with 78.6% of reviews categorized as positive.
- Popular clusters around major urban hubs like Riyadh, Jeddah, and Dammam.

## Limitations and Future Directions
- **Data Completeness**: Some regions and themes may be underrepresented.
- **Sentiment Analysis**: Ratings-based sentiment categorization could be enhanced with advanced NLP techniques.
- **Dynamic Nature**: Data reflects a snapshot and requires updates for new trends.
- **Expansion Plans**:
  - Broader data collection from rural and niche areas.
  - Integration of traveler personas for deeper insights.
  - Advanced modeling and predictive analytics.

## How to Use
- **Setup**: Clone the repository and install dependencies listed in `requirements.txt`.
- **Dataset**: Preprocessed datasets are available in the `data/processed/` folder.
- **Run Notebooks**: Explore analyses and visualizations in the Jupyter Notebooks.
- **Recommendation System**: Use the `recommend()` function in the model script to get destination suggestions.

## Acknowledgments
This project was developed using public datasets and openly accessible tools. We thank TripAdvisor, Google Maps, and the contributors of the Kaggle datasets for their valuable resources.

---

Contributors: 
Deema Hamidah

Shumokh Abdullah

Hadeel Balahmar
