# Pelicula
Demo movie viewer

## Icons
All icons are from https://heroicons.com/

## TODO
- Render the main view
 - Has header splash image
   - Hide title content when scrolling
  - Create Search bar
    - Wire up the searchbar to the api
    - Debounce searches
    - Add a query param search
    - has black background when scrolling
- Render results in a grid pattern
    - Display results in a grid
    - Implement an infinite scroll
    - figure out pagination
        - this might need to fetch multiple results (sigh)
- Have a way to save movie to a playlist
  - Store movies in local storage (no way to persist)
  - On Desktop: this should be a sidepanel view 
    - Saving automatically updates sidepanel
  - On Mobile: this should take up the whole screen
- Have a way to view the playlist
- Include a footer that says "My favorite color is {your favorite color}"
- Ensure the view is responsive
- Add a No search results page
- Add a page for errors
- Build bundle and deploy to github

## Done
- Color Scheme
    - Black
    - White
    - Red

- Render the main view
  - Has header splash image
    - Background is faded
  - Create Search bar
    - Searchbar spans the background
