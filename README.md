# Title

   Front-end Assignment

## Objective

    Create a web panel consisting of four different pages and a global search in the Navbar.

    Home Page / Popular Movie Page
    Top Rated Page
    Upcoming Movie Page
    Single Movie Detail Page
    Searched Movie Page (UI will be same as Home Page)

## Tech Stack

    List the primary technologies.
    HTML,
    CSS,
    React.js

## Completion Instructions

### Functionality

#### Must Have

   * Upload the project on Codesandbox (https://codesandbox.io/) and submit it using the code sandbox link. * * This is mandatory, without this, the submission will not be accepted.
   * The project must be responsive with decent CSS.
   * It is not necessary that the colors should match the images above. Use your imagination and try tomake    it as you like.
   * Pagination is required.
   * Make sure the components are reusable wherever possible.

### Submission Instructions

#### Must Have

   Please submit the Project in the below link: https://forms.ccbp.in/project-submission

### APIs
   * Generate your own api key by visiting https://www.themoviedb.org/settings/api 
   ## Get all movies:
   https://api.themoviedb.org/3/movie/popular?api_key=${Api_key}&language=en-US&page=1

   ## From API Get movie detail
   https://api.themoviedb.org/3/movie/${movie_id}?api_key=${Api_key}&language=en-US 

   ## Get movie cast detail 
   https://api.themoviedb.org/3/movie/${movie_id}/credits?api_key=${Api_key}&language=en-US 

   ## Get upcoming movies 
   https://api.themoviedb.org/3/movie/upcoming?api_key=${Api_key}&language=en-US&page=1 

   ## Get top-rated movies 
   https://api.themoviedb.org/3/movie/top_rated?api_key=${Api_key}&language=en-US&page=1 

   ## Get search result 
   https://api.themoviedb.org/3/search/movie?api\_key=${Api\_key}&language=en-US&query=${movie\_name}&page=1
    
### Third-party packages

    Third-party packages
    * react-router-dom

In the project directory, you can run:

### `npm start`
