# Spotify Music Analysis Project

* This repository contains a data analysis project focusing on Spotify music data. The project uses MySQL for data management and querying. Below, you will find an overview of the project, setup instructions, and insights obtained from the analysis.

# Project Overview

# Objective

* To analyze cleaned music-related data and uncover key insights regarding track performance, artist trends, and audience preferences.

# Tools Used

* MySQL: For efficient data storage, querying, and analysis.

# Data Source

* The dataset used for this project is provided in CSV format as cleaned_dataset.csv. It contains:

* Track metadata such as names, energy values, danceability scores, and liveness.

* Artist and album information.

* Streams, views, likes, and comments for tracks.

* Flags for licensed tracks and official videos.

# Project Files

* cleaned_dataset.csv: The cleaned dataset used for the analysis.

* spotify.sql: SQL script containing the schema definition and data import queries.

# Prerequisites

* MySQL Server installed locally or hosted in the cloud for executing the SQL scripts.
# Setup Instructions
# Data Import:
* open mysql - Create a Database - Right click on Tables - Table Data Import Wizard - Choose the excel file

# Queries Solved

1: The analysis conducted in this project addressed multiple queries, including:

2: Retrieving the names of all tracks that have more than 1 billion streams.

3: Listing all albums along with their respective artists.

4: Getting the total number of comments for tracks where licensed = TRUE.

5: Finding all tracks that belong to the album type single.

6: Counting the total number of tracks by each artist.

7: Calculating the average danceability of tracks in each album.

8: Identifying the top 5 tracks with the highest energy values.

9: Listing all tracks along with their views and likes where official_video = TRUE.

10: Calculating the total views of all associated tracks for each album.

11: Retrieving the track names that have been streamed on Spotify more than on YouTube.

12: Finding the top 3 most-viewed tracks for each artist using window functions.

13: Writing a query to find tracks where the liveness score is above the average.

14: Using a WITH clause to calculate the difference between the highest and lowest energy values for tracks in each album.

# Results

Highlighted Insights

Over 50 tracks exceeded 1 billion streams, with several belonging to top-charting artists.

Albums by renowned artists had the highest views and likes, especially for tracks with official videos.

Tracks from singles dominated streams for certain artists, indicating a shift towards single releases.

Energy levels were a critical factor in determining the popularity of tracks, with high-energy tracks featuring prominently in the top 5 lists.

Danceability scores varied significantly by album, suggesting that specific albums cater to different audience preferences.



