# Diamond Platnumz Spotify Data Analysis Project

## Overview  
This project analyzes track and album data for **Diamond Platnumz**, a prominent Tanzanian artist, using the Spotify Web API. The goal is to uncover insights into his music catalog, such as track popularity, audio features, and album release patterns.

## Features  
- Fetch detailed track and album data for Diamond Platnumz via the Spotify API.
- Analyze audio features (e.g., danceability, energy, tempo) of his songs.
- Identify top-performing tracks based on popularity metrics.
- Visualize trends in audio features and release history.

---

## Tools & Technologies  
- **Google Colab**: Interactive  programming notebook similar to a classic jupyter notebook.  
- **Spotify Web API**: To fetch data on popular tracks, popular albums, and audio features.  
- **pandas**: For data manipulation and analysis.  
- **matplotlib** & **seaborn**: For creating visualizations.  

---

## Data Pipeline  

1. **Authentication**:  
   - Authenticate with the Spotify API using client credentials.

2. **Data Retrieval**:  
   - Fetch all albums and singles by Diamond Platnumz.  
   - Retrieve track metadata and audio features for each song.  

3. **Data Processing**:  
   - Clean the raw data and structure it into a usable format.  
   - Combine track and audio feature data for analysis.

4. **Analysis**:  
   - Explore patterns in track popularity and album releases.  
   - Analyze audio features like tempo, valence, and energy.  

5. **Visualization**:  
   - Create visualizations to showcase key findings.

---

## Project Workflow  

1. **Google Colab Setup**:  
   Open the Colab notebook directly from the repository or upload it to your Google Drive.  

2. **Spotify API Setup**:  
   - Sign up at [Spotify for Developers](https://developer.spotify.com/) and create an app to get your `CLIENT_ID` and `CLIENT_SECRET`.  
   - Add the credentials directly into the notebook when prompted or store them securely in a file and load them.  

3. **Data Extraction and Analysis**:  
   - Execute the cells sequentially to retrieve data, clean it, and perform analyses.  

4. **Visualization**:  
   - Review visual insights directly within the notebook.

---

## Project Structure  

```
├── notebooks/
│   ├── Diamond_Platnumz_Spotify_Analysis.ipynb  # Main analysis notebook for Colab

├── README.md                 # Project overview
└── requirements.txt          # Python dependencies (for local use)
```

## Example Insights  

- **Top Tracks by Popularity**:  
  Discover the top 5 most popular tracks by Diamond Platnumz.  

- **Audio Features Profile**:  
  Understand how audio features like danceability, energy, and tempo vary across his songs.  

- **Release Patterns**:  
  Visualize the timeline of album and single releases.

---

## Future Enhancements  
- Extend the analysis to compare Diamond Platnumz’s data with similar artists.  
- Implement machine learning models to predict track popularity based on audio features.  
- Incorporate fan engagement metrics like playlist inclusions or monthly listeners.

---

## Acknowledgments  
- **Spotify API**: For providing access to a comprehensive dataset.  
- The open-source community for tools and libraries.  

---

**License**: This project is licensed under the MIT License.
