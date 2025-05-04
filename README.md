# Tweets Visualization and Analysis

## Project Overview
This project involves analyzing and visualizing Twitter sentiment data to understand public opinion and sentiment patterns across different entities. The analysis focuses on sentiment classification and entity distribution in tweets.

## Dataset
The project uses two datasets:
- `twitter_training.csv`: Training dataset containing labeled tweets
- `twitter_validation.csv`: Validation dataset for model evaluation

The datasets contain the following columns:
- `tweetID`: Unique identifier for each tweet
- `entity`: The subject/entity being discussed
- `sentiment`: Sentiment label (Positive, Negative, Neutral, Irrelevant)
- `tweet_content`: The actual text content of the tweet

## Data Preprocessing
1. **Data Loading and Merging**:
   - Combined training and validation datasets
   - Standardized column names
   - Removed duplicate entries
   - Handled missing values

2. **Data Cleaning**:
   - Removed null values
   - Dropped unnecessary columns (tweetID, tweet_content)
   - Focused on entity and sentiment analysis

## Key Findings
1. **Entity Distribution**:
   - Visualized the distribution of entities using pie charts
   - Identified most discussed entities
   - Analyzed sentiment distribution across different entities

2. **Sentiment Analysis**:
   - Examined sentiment distribution across the dataset
   - Identified patterns in sentiment expression
   - Analyzed the relationship between entities and sentiment

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib for visualization
- NumPy for numerical operations

## Project Structure
```
tweets-visualization-and-analysis/
├── data/
│   ├── twitter_training.csv
│   └── twitter_validation.csv
├── tweets-visualization-and-analysis.ipynb
└── README.md
```

## Usage
1. Install required dependencies:
   ```bash
   pip install pandas matplotlib numpy
   ```

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook tweets-visualization-and-analysis.ipynb
   ```

## Next Steps
1. Implement more advanced sentiment analysis techniques
2. Add entity-specific sentiment analysis
3. Create interactive visualizations
4. Develop predictive models for sentiment classification

## Contact
For questions or suggestions, please contact:
- Email: [ypssefmohammedahed@gmail.com]
- Phone: [01126078938]
