# Musicality & Popularity of Rock Songs from 1950 to 2020

**By Yedu Krishnan**

**Feb 15, 2024**

> “Life is what happens when you're making other plans.” - John Lennon

## Links
- **YouTube Link:** [Watch on YouTube](https://youtu.be/j3PU_fxkwss?feature=shared)
- **Notion Link:** [View on Notion](https://defiant-sunday-6a0.notion.site/Musicality-Popularity-of-Rock-songs-from-1950-to-2020-fb66240e6c174b5b890420b5dc0ce488?pvs=4)

## Overview
This project investigates the musicality and popularity of rock songs from 1950 to 2020. The analysis covers the evolution of rock music, its various subgenres, and the impact of iconic artists on the genre. The project utilizes a comprehensive dataset, exploratory data analysis, and clustering techniques to uncover trends and patterns in rock music.

## Table of Contents
- [Links](#links)
- [Overview](#overview)
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Guiding Questions](#guiding-questions)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Introduction
Originating in the United States in the late 1940s and early 1950s, rock music has evolved into a global phenomenon, captivating audiences with its infectious beats, electrifying guitar solos, and rebellious spirit. Over time, rock has branched into numerous subgenres, reflecting the social and political climates of different eras, including classic rock, punk, grunge, and alternative rock.

## Dataset
The dataset, taken from Kaggle, provides an extensive collection of the top 5484 rock songs from 1950 to 2012. It includes additional audio features from Spotify, offering insights into each song's musical attributes, such as tempo, loudness, and energy.

Link to the Kaggle dataset: [History of Rock (1950-2020)](https://www.kaggle.com/datasets/lukaszamora/history-of-rock-19502020)

## Exploratory Data Analysis
The exploratory data analysis section examines correlations between different attributes of rock songs, including length, danceability, and energy. It also investigates the popularity of artists and the usage of different musical scales in the songs. Additionally, k-means clustering is applied to identify groups of songs with similar attributes, further illuminating the structure of the dataset.

## Guiding Questions
1. How does the variation in one variable affect the behavior or pattern of another variable?
2. Which are the Top 20 Artists/Bands who are/were popular?
3. Which are the most used scales in the songs?
4. How do the attributes of loudness and energy, as well as acousticness and instrumentalness, vary across different ranks in the dataset?
5. Can k-means clustering effectively segment the dataset of rock songs into distinct groups based on their attributes?

## Conclusion
The analysis of the rock music dataset yielded valuable insights into various aspects of the genre, including correlations between attributes, artist popularity, and musical scales. K-means clustering identified distinct groupings of songs, providing a deeper understanding of rock music trends and characteristics.

## Installation
To run this project, you need to have Python installed. Install the required libraries using the following command:
```bash
pip install pandas seaborn matplotlib scikit-learn
```
## Acknowledgments
This project was inspired by various data science and music analysis resources. Special thanks to the open-source community for providing the tools and libraries used in this project.

## References
- “History of Rock (1950-2020),” *Kaggle*, Nov. 27, 2020. [Kaggle](https://www.kaggle.com/datasets/lukaszamora/history-of-rock-19502020)
- GregM, “Top 6400, Part 1/26 (songs 1-150).” [Blog](https://toprocksongs1950-2012.blogspot.com/2013/05/top-6400-part-126-songs-1-150.html)
