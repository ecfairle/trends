# Reddit AI Keyword Trend Analysis

A Python notebook that analyzes keyword trends in AI discussions across Reddit over time.

## Purpose

This tool tracks how AI-related discussions evolve by comparing keyword frequency from 6 months ago versus recent months across major AI subreddits. It helps identify emerging topics, declining themes, and shifts in community focus.

## How It Works

1. **Data Collection**: Retrieves public posts and comments from AI-focused subreddits
2. **Time Comparison**: Splits data into two periods (6-3 months ago vs recent 3 months)
3. **Keyword Extraction**: Uses TF-IDF to identify significant terms and phrases
4. **Trend Analysis**: Compares keyword usage between periods to show growth/decline
5. **Visualization**: Creates charts and word clouds showing trend patterns

## Subreddits Analyzed

- r/MachineLearning
- r/artificial
- r/singularity
- r/ChatGPT
- r/OpenAI
- r/LocalLLaMA
- r/ArtificialIntelligence
- r/deeplearning
- r/compsci
- r/MachineLearningNews

## API Usage

- **Platform**: Reddit API (free tier)
- **Requests**: ~30-50 total per analysis
- **Rate Limit**: Well within 1000/day free limit
- **Access**: Public posts only, no private data
- **Purpose**: Academic research and trend analysis

## Setup

1. Create Reddit app at https://www.reddit.com/prefs/apps
2. Add credentials to notebook
3. Install required packages: `pip install praw pandas matplotlib seaborn wordcloud nltk scikit-learn`
4. Run notebook

## Output

- Keyword trend charts showing growing/declining terms
- Word clouds for visual comparison
- Statistical analysis of discussion themes
- CSV export of results

## Data Handling

- Only processes public Reddit content
- No personal data collection
- Focuses on text content analysis
- Results aggregated and anonymized

---

*This tool is for personal research and educational purposes to understand AI discourse trends.*
