# movie-recommendations
Project: Movie Recommendation App with Redux 
Project: Movie Recommendation App with Redux
Key Features:
User Authentication:

Implement user login/signup and use Redux to manage authentication and session state.
Movie List Fetching:

Fetch a list of movies from a public API (like TMDB or OMDb) and store the fetched data in Redux.
Movie Search and Filters:

Allow users to search for movies by title or filter by genre, rating, or release year.
Manage the state of search and filters with Redux selectors and actions.
Favorite Movies:

Users can mark movies as favorites, and the app should maintain a list of these favorite movies using Redux.
Add a "Favorites" section where users can view all their favorite movies.
Movie Details Page:

When a user clicks on a movie, navigate to a detailed page showing the movie's information (title, genre, cast, plot, etc.).
Use Redux to manage the state of the selected movie.
Recommendations Based on Favorites:

Provide movie recommendations based on the user's favorite movies. This can be achieved by using Redux to track favorite genres or directors and fetch related movie suggestions.
Rating Movies:

Allow users to rate movies on a scale (e.g., 1-5 stars) and store this rating data in Redux.
Display average user ratings for each movie.
Async Actions (Thunk or Saga):

Use Redux Thunk or Redux Saga to handle API calls (fetching movies, adding ratings, etc.) asynchronously.
Watchlist:

Add a "Watchlist" feature where users can add movies they want to watch later. Use Redux to manage this watchlist.
Dark Mode Toggle:

Add a dark mode/light mode toggle, and manage the theme state using Redux.
Technologies:
React (with functional components)
Redux (for managing movie data and user state)
Redux Toolkit (optional for easier state management)
React Router (for navigation between pages)
