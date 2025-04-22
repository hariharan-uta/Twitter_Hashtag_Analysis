# Twitter Hashtag & Sentiment Analysis

This project analyzes tweets related to ChatGPT by extracting hashtags and performing sentiment analysis. It provides insights into trending hashtags and the overall sentiment of the Twitter discourse.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [How to Run](#how-to-run)
- [Dataset](#dataset)
- [Sample Output](#sample-output)

## Features

- **Hashtag Extraction** - Uses regex to extract hashtags from tweet texts.
- **Hashtag Frequency Analysis** - Counts and ranks the most used hashtags.
- **Top 5 Hashtag Visualization** - Displays the top 5 hashtags in a bar chart.
- **Sentiment Analysis** - Utilizes TextBlob to classify tweet sentiments as positive, negative, or neutral.
- **Sentiment Pie Chart** - Visualizes sentiment distribution using a pie chart.
- **CamelCase Split Utility** - Converts CamelCase text like `GoingHomeTomorrow` to `Going Home Tomorrow`.

## Tech Stack

| Tool/Library     | Purpose                        |
|------------------|--------------------------------|
| `pandas`         | Data handling and manipulation |
| `re`             | Regex-based hashtag extraction |
| `matplotlib`     | Visualization (bar/pie charts) |
| `textblob`       | Sentiment analysis             |

## How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/twitter-hashtag-analysis.git
   cd twitter-hashtag-analysis
   ```

2. **Install Requirements**
   ```bash
   pip install pandas matplotlib textblob
   ```

3. **Run the Script**
   Ensure you have the dataset at the correct path (`/content/drive/MyDrive/dataset tweet/chatGPT.csv`). Then run:
   ```bash
   python twitter_hashtag_analysis.py
   ```
   
## Dataset
- The project expects a CSV file named `chatGPT.csv` with at least the following columns:
  - `tweet`
  - `user_name`
  - `location`

Ensure the CSV is placed in the appropriate directory or update the script with your custom path.

## Sample Output

- Bar chart of top 5 hashtags
- Pie chart of sentiment distribution
  

> Built with ❤️ using Python and open-source libraries.

