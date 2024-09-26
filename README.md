# 🏎️ Formula 1 Last Grand Prix Winner News Fetcher 📰

Welcome to the **Formula 1 Last Grand Prix Winner News Fetcher**! This tool allows you to search for a Formula 1 driver, retrieve details about the last Grand Prix they won, and display news articles about the location where the race was held. 

## Description

The **Formula 1 Last Grand Prix Winner News Fetcher** allows you to:
- Input a Formula 1 driver's name 🏁
- Retrieve information about the last Grand Prix they won (in the current season) 🏆
- Display the top 3 news articles about the location of the Grand Prix 🌍

## 🌐 APIs Used

1. **[Ergast F1 API](https://ergast.com/mrd/)** 🏎️:
    - **Why Chosen**: 
        - It provides detailed historical and current data on Formula 1 races, drivers, and results. We use this API to retrieve driver data and race results for the current season.
    - **Usage**:
        - Fetches the last Grand Prix win for a given driver in the current season.

2. **[TheNewsAPI](https://www.thenewsapi.com/)** 📰:
    - **Why Chosen**: 
        - Provides access to real-time news articles. We use it to search for news articles related to the location of the last Grand Prix won by the driver.
    - **Usage**:
        - Retrieves news articles about the location of the Grand Prix race based on the driver’s most recent win.

## 🛠️ Setup

### Get Your API Keys 🔑

You'll need two API keys for this project:

- **[Ergast F1 API](https://ergast.com/mrd/)**
- **[TheNewsAPI](https://www.thenewsapi.com/)**: Sign up on TheNewsAPI to get your API key.
    - **Step 1**: Go to [TheNewsAPI](https://www.thenewsapi.com/).
    - **Step 2**: Sign up for an account.
    - **Step 3**: Navigate to your dashboard and copy your API key.

- **Cloning the repository**
- git clone https://github.com/nayalafifi/data-feature.git
