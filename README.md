# Music Library Project

## Overview

The Music Library project is a web app built with React that lets users search for music using the iTunes Search API. Users can look up their favorite artists, songs, or albums. The results are displayed in a simple, responsive gallery format, and selecting an item reveals more details like the track name, artist, album, and album cover.

I developed this project as part of my journey through NCSU's Software Development Bootcamp. It started as an introduction to React Router and evolved into a TypeScript-based application. The project was initially in JavaScript but was later upgraded to TypeScript for better type safety and easier maintenance. During the build process, the TypeScript code is compiled back into JavaScript, allowing the React app to run smoothly.

## Features

- **Single Page Application (SPA)**: The app stays on one URL, dynamically updating without full page reloads.
- **Search Functionality**: Users can search for artists, songs, or albums using the iTunes Search API.
- **Gallery View**: Search results are displayed in a gallery format for easy browsing.
- **Detailed View**: Clicking on an item expands it to show more information, such as the album cover, artist, and song details.

## Technologies Used

- **React**: Frontend framework for building the user interface.
- **React Router**: For handling navigation between different views.
- **Node.js**: Server environment for running the application.
- **iTunes Search API**: Used for fetching music-related data.
- **TypeScript**: For better type safety and easier maintenance.

## Demo

[Live Demo](https://music-library-topaz.vercel.app/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/cameronotoole44/music-library
   ```

2. Cd into directory:

   ```bash
   cd RR-Music-Library
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Run the app:

   ```bash
   npm start
   ```

   **The application will be running on http://localhost:3000**

   ## Usage

   1. Enter a search term (artist, song, or album) in the search bar.
   2. Browse through the gallery of search results.
   3. Click on an item to view more details such as the album cover and song info.

   ## Future Improvements

   <ul>
   <li> Improved UI: Enhancing the design and responsiveness of the app.
   <li> Pagination: Implementing pagination for larger result sets
   <li> CSS Styling
   </ul>
