# usePopcorn

## Overview

**usePopcorn** is a movie search and watchlist application that allows users to search for movies, view details, and add them to a "watched" list with user ratings. This app is built using React, JavaScript, and local storage, providing a smooth and responsive user experience with security and performance in mind.

## Features

- Search for movies using the [OMDb API](http://www.omdbapi.com/).
- View detailed information about each movie, including IMDb ratings, runtime, and plot.
- Add movies to a "watched" list with your own rating.
- See a summary of movies you have watched, including average ratings and runtime.
- Delete movies from your watched list.
- Responsive design with smooth transitions between movie details and the main watchlist.

## Installation

To get started with the **usePopcorn** app, follow these steps:

1. **Clone the repository:**

 
## Usage

- Use the search bar to search for movies by title.
- Click on any movie in the search results to view more details.
- Add a movie to your watched list by assigning it a personal rating.
- Access your watched list to view all movies you've rated, including their IMDb ratings and your personal score.
- Remove a movie from the watched list by clicking the delete button.

## Key Technologies

- **React**: Used to build dynamic components and manage the app’s state.
- **JavaScript (ES6)**: Core language for functionality.
- **CSS**: For styling and layout.
- **Local Storage**: Persist the list of watched movies across sessions.
- **OMDb API**: External API used to fetch movie details.

## Custom Hooks

This app uses several custom hooks for enhanced functionality:

- `useMovies`: Fetches and manages movie data from the OMDb API.
- `useLocalStorageState`: Manages the state of the "watched" list using the browser’s local storage.
- `useKey`: Adds custom keyboard event listeners for improved user experience (e.g., handling the "Enter" key in the search bar).
