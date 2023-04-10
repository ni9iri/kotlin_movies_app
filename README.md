# Trending Movies App

## Overview

The Exchange Rate Calculator App is a simple Android application that allows users to convert currencies from Euro to Czech Koruna (CZK) based on the latest exchange rates obtained from an external API.

The Trending Movies App is mobile application designed to display a list of popular movies that are currently trending. The app allows users to browse through a collection of movies and view details about each movie.

## Screenshots
![image](https://user-images.githubusercontent.com/89902380/230962198-f47589a4-5d58-496b-bb1c-090513b46b8f.png)

![image](https://user-images.githubusercontent.com/89902380/230962279-24d7ffd3-eb0c-4096-b6c0-e0dd4206fde5.png)

## Installation and Configuration

To install and run the app, follow these steps:

1. Clone the project from the Github repository.
2. Open the project in Android Studio.
3. Get your API key from https://www.themoviedb.org
4. In the MovieFetchApi.kt file, add your new API key to the variable "API_KEY"
5. Run the app on an emulator or physical device.


## Usage

The Trending Movies mobile app is a great way to stay up-to-date with the latest movie trends and discover new movies to watch. To use the app, simply open it on your Android device and browse through the list of trending movies that are currently popular. You can scroll through the list to see each movie's title, release date, and poster image.

If you want to learn more about a particular movie, simply tap on its poster image to view more details. This will take you to a new screen where you can see additional information about the movie, such as its synopsis, cast, and crew.


## Dependencies

The app uses the following dependencies:


Retrofit: For making network requests to the external API.
Gson: For parsing JSON responses from the API.
ViewModel and LiveData: For managing the UI state and data in a lifecycle-aware manner.
Coil : a library used for image loading 
Viewmodel : To manage UI-related data in a cycle aware way

## API Used

The app uses the https://www.themoviedb.org/ to fetch the trending movies.
