
# Music Recommendation System using Python


Music Recommendation Systems operate through intricate algorithms that analyze vast amounts of data about users’ musical interactions, such as their listening history, liked tracks, skipped songs, and even explicit user preferences conveyed through ratings or feedback. These data points are instrumental in constructing comprehensive user profiles, delineating individual tastes and preferences.

In the initial phase, the system employs various data preprocessing techniques to cleanse and organize the information efficiently. Subsequently, the system uses recommendation algorithms, such as collaborative filtering, content-based filtering, and hybrid approaches, to generate music recommendations.

As users continually interact with the system, it accumulates additional data, refining and updating their profiles in real time. Consequently, the recommendations become increasingly precise and aligned with the user’s evolving musical preferences.

## Spotify API & How to build a Music Recommendation System using Spotify API?

The Spotify API is a set of rules and protocols provided by Spotify developers. It enables developers to interact with Spotify’s vast music catalogue and collect music-related data. Through the Spotify API, developers can access information such as tracks, albums, artists, playlists, user profiles, and play history, among other features, empowering them to build innovative applications and services that integrate seamlessly with the Spotify platform.

To build a Music Recommendation System using the Spotify API, we are required to collect real-time music data from Spotify. For this task, we need a Spotify developer account to get our credentials from Spotify to access their data.

## Libraries
import requests
import base64
from enum import Enum
import argparse
import warnings
warnings.simplefilter("ignore", DeprecationWarning)
warnings.resetwarnings()

import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
from datetime import datetime
from sklearn.metrics.pairwise import cosine_similarity

## Libraries Used

This project makes use of several Python libraries to perform various tasks:

- **requests**:
  - Description: Used for making HTTP requests, typically for fetching data from web services or APIs.

- **base64**:
  - Description: Provides encoding and decoding functions for working with Base64-encoded data. It's commonly used for encoding binary data into a text format.

- **enum**:
  - Description: Allows you to create enumeration classes. In this project, it's used to define the `Enum` class for specifying feature types.

- **argparse**:
  - Description: A command-line argument parsing library. It helps define and parse command-line arguments and options.

- **sklearn.preprocessing.MinMaxScaler**:
  - Description: A preprocessing technique in scikit-learn for scaling features to a specified range, typically between 0 and 1 (min-max scaling).

- **datetime**:
  - Description: A module in Python's standard library for working with date and time objects. It's used for date calculations and formatting.

- **sklearn.metrics.pairwise.cosine_similarity**:
  - Description: A function from scikit-learn's metrics module for computing the cosine similarity between vectors. In this project, it's used for similarity calculations, likely in the context of recommendation systems.



## Demo



![Alt Text](https://github.com/AnkitMandusia/Music-Recommendation-System-using-Python/blob/4ba60adebc5c927a9386c43fd117af4de57b557b/Screenshot%202023-09-14%20223413.png)

