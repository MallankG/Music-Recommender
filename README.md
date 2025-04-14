# Spotify Music Recommendation System

A machine learning-based music recommendation system that uses the Spotify Web API to provide personalized song recommendations based on user preferences and audio features.

## Features

- **Trending Songs Analysis**: Retrieve and analyze popular songs from Spotify playlists
- **Audio Feature Analysis**: Analyze various audio characteristics of songs including:
  - Danceability
  - Energy
  - Valence
  - Tempo
  - Acousticness
  - Instrumentalness
  - Liveness
  - Speechiness
- **Data Visualization**: Visualize music characteristics and patterns
- **Personalized Recommendations**: Generate song recommendations based on user preferences

## Prerequisites

- Python 3.x
- Spotify Developer Account
- Required Python packages:
  - spotipy
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Setup

1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Spotify API credentials:
   - Create a Spotify Developer account
   - Create a new application in the Spotify Developer Dashboard
   - Add your credentials to the environment variables or configuration file

## Usage

1. Run the Jupyter notebook `MusicRecommendation.ipynb`
2. Follow the authentication steps to connect to your Spotify account
3. Explore the analysis and recommendation features

## Project Structure

- `MusicRecommendation.ipynb`: Main notebook containing the recommendation system implementation
- `.gitignore`: Git ignore file for Python projects

## Security

- Never commit your Spotify API credentials
- Keep your access tokens and refresh tokens secure
- Use environment variables for sensitive information

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.