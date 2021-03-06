# Movie Project
This is a movie database project, where it shows movies, their casts, ratings, trailers, related movies, genres, and so on.

This project uses The Movie DB API: `https://api.themoviedb.org/3`. 

# Features
- A home page that shows popular movies
- When you click one of the movies, you'll see the Single Movie page, which includes:
    - Movie poster
    - Movie title
    - Movie release date
    - Movie runtime
    - Movie description
    - An empty cast section



### Navbar
 A universal navbar (it appears on every page) to the home page that includes
buttons that go to the following pages:

- Home button, takes you to the home page
- Movies button that has a dropdown list to show different movie genres. For
  example: Action, Sci-Fi, Comedy ...etc, When you click one of them it should
  load the movies for that genre.
- Actor list page
- About page that has a description of the website
- Search box where you can type the movie or actor name and display the
related results.
- A filter dropdown to filter the displayed movies in the home page, based
on (popular, relase date, top rated, now playing and up coming) 

### Footer
 a universal footer that includes:

- Credit to you and your partner for building the website, 
- You and your partner's github link inside an icon and optionally, your social
  media links

### Styling

-  Hovering over the movie makes the mouse pointer icon seem
  clickable.

## Movies List Page

### Styling

- Using CSS and Bootstrap, display the page as a grid with 3 columns (3 movies
  in the same row)
- Responsive where it displays 2 columns for tablets and 1 column for
  phones
- Rating and genres to the movies in the home page and a description
  when you hover over one of them

## Single Movie Page Feauters:

- The main 5 actors of the movies in the credit section
- The movie language
- A related movies section which includes at least five related movies
- A trailer section that has the movie trailer from youtube
- The movie production company name and logo
- The director name 
- The movie rating and how many votes has it received

### Functionality
- Clicking an actor in the main actors should go to the single actor page.



## Actor List Page
Displays a list of actors styles in the same way as the movies list page, but
with the actor photo and the actor name. Clicking any actor should go to the
Single Actor Page. CSS should most certainly be reused here!

## Single Actor Page
This page can be reached by clicking on an actor in the actors list page or the
credits in the single movie page.

### Data Display
- The actor name
- The actor gender
- A picture of the actor
- The actor popularity
- The birthday of the actor and (if available) death day
- A biography about the actor
- A list of movies the actor participated in


