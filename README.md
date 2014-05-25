## PART 1: SORTING THE LIST OF ALL MOVIES    (15 POINTS)

Enhance RP in the following way:

On the list of all movies page, the column headings for ‘Movie Title’ and ‘Release Date’ for a movie should be clickable links. Clicking one of them should cause the list to be reloaded but sorted in ascending order on that column. For example, clicking the ‘release date’ column heading should redisplay the list of movies with the earliest-released movies first; clicking the ‘title’ field should list the movies alphabetically by title. (For movies whose names begin with non-letters, the sort order should match the behavior of String#<=>.)

## PART 2: FILTER THE LIST OF MOVIES    (15 POINTS)

Enhance RottenPotatoes as follows. At the top of the All Movies listing, add some checkboxes that allow the user to filter the list to show only movies with certain MPAA ratings

## PART 3: REMEMBER THE SORTING AND FILTERING SETTINGS    (70 POINTS)

OK, so the user can now click on the “Movie Title” or “Release Date” headings and see movies sorted by those columns, and can additionally use the checkboxes to restrict the listing to movies with certain ratings only. And we have preserved RESTfulness, because the URI itself always contains the parameters that will control sorting and filtering.

The last step is to remember these settings. That is, if the user has selected any combination of column sorting and restrict-by-rating constraints, and then the user clicks to see the details of one of the movies (for example), when she clicks the Back to Movie List on the detail page, the movie listing should “remember” the user’s sorting and filtering settings from before.

[Heroku Deployment](http://hqixdlpt.herokuapp.com/movies)
