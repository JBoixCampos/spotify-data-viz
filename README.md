# 🎧 spotify-data-viz 📊

## Unveiling Your Musical Journey Through Data Analysis

This project transforms your Spotify listening history into insightful visualizations, helping you understand your unique musical habits through R and data science techniques.

### 🎵 What You'll Discover
- Your most active listening hours
- Daily and monthly music consumption patterns
- Top artists and tracks
- Listening diversity and exploration

### 🧰 Tools Used
- R Programming Language
- Tidyverse
- ggplot2 for data visualization
- Spotify Streaming History JSON data

### 📊 Key Visualizations
- Hourly listening heatmaps
- Monthly listening trend analysis
- Artist and track popularity charts
- Listening time distribution

### 🚀 Purpose
Democratize personal data analysis by providing an accessible, reproducible method to explore your music listening habits using free, open-source tools.

### ✨ Inspiration
Born from curiosity about the stories hidden in personal streaming data, this project turns raw JSON into meaningful musical insights.

# Spotify Listening Analysis: Getting Started Guide

## 🖥️ Technical Requirements
- **R Programming Language** (Latest version recommended)
- **RStudio** (Free desktop version)
- **Required R Libraries**:
  - tidyverse
  - lubridate
  - jsonlite

## 🔍 Prerequisites
1. **Download Your Spotify Data**
   - Go to Spotify Account Settings
   - Request "Extended Streaming History"
   - Wait for Spotify to email you the JSON file
   - Save the `StreamingHistory_music_0.json` file somewhere memorable

## 💻 Installation Steps
1. **Install R and RStudio**
   - Download R from: https://cran.r-project.org/
   - Download RStudio from: https://posit.co/download/rstudio-desktop/

2. **Install Required Libraries**
   Open RStudio and run:
   ```
   install.packages(c("tidyverse", "lubridate", "jsonlite"))
   ```
## 🚀 Project Setup
  - Clone or download this GitHub repository
  - Open the .Rmd file in RStudio
  - Locate the data loading line:
  ```
  data <- jsonlite::fromJSON("path/to/StreamingHistory_music_0.json")
  ```
  - Replace "path/to/StreamingHistory_music_0.json" with the FULL path to your downloaded Spotify JSON file
    - Windows Example: "C:/Users/YourUsername/Downloads/StreamingHistory_music_0.json"
    - Mac Example: "/Users/YourUsername/Downloads/StreamingHistory_music_0.json"

## 🛠️ Troubleshooting Tips
  - Ensure file paths use forward slashes (/)
  - Double-check spelling and exact file location
  - If unsure of file path, use file.choose() to open a file selection dialog

## 📚 Learning Resources
  - R for Data Science: https://r4ds.had.co.nz/
  - ggplot2 Documentation: https://ggplot2.tidyverse.org/

## 🤝 Contributions Welcome!
Found a bug? Have an improvement? Open an issue or submit a pull request!
