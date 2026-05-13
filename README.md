# STAT331 Project (LAB)
Authors: Caleb Huang and Sean Paik

## Proposal

**Learning Goals**:
- Writing functions to solve real world problems
- Efficiently visualize real world data for clear comparisons
- Users will get better in reading, joining, and analyzing multiple datasets

**Datasets**: 

Spotify Global Trends & Popularity Analysis
>*https://www.kaggle.com/datasets/algozee/spotyfy*
- Updated last month (178 by 13)
- Recent global hits on Spotify (song, artist, number of streams, genre, etc)
- Since it’s a recent dataset, it can be connected to last year’s data and be used for comparison and contrast. See if any of the 2025 popular artists/songs are still up there. 

Spotify Wrapped 2025 | Top Songs & Artists
>https://www.kaggle.com/datasets/alitaqishah/spotify-wrapped-2025-top-songs-and-artists?select=spotify_wrapped_2025_top50_artists.csv 
- 2025 most streamed Spotify artist (50 by 11)
- Used to join the datasets together to see which artists are on both lists. With the number of streams of each artist, we will be able to test users on what visualization method they think will work the best. The number of Spotify followers are listed, which can be another factor to decide their popularity.
> https://www.kaggle.com/datasets/alitaqishah/spotify-wrapped-2025-top-songs-and-artists?select=spotify_wrapped_2025_top50_songs.csv 
- 2025 most streamed Spotify songs (50 by 16)
- Used to join the datasets together to see which artists are on both lists. With the number of streams of each song, we will be able to test users on what visualization method they think will work the best. Songs marked explicit are listed, and thus could be used to practice filters.  

Spotify Global Music Dataset (2009–2025)
>https://www.kaggle.com/datasets/wardabilal/spotify-global-music-dataset-20092025
- Dataset of songs & artists from 2009 to 2025 (8,778 by 15) through Spotify API. 
- Popular artists, as well as non-popular artists, are listed on this dataset, which will be useful in practicing joining, since a lot of the artists/songs in this dataset will not show up in the other two. Track_id is provided, which is also useful in joining. 
