# Initial Codebook, for the movies_2023-09-14 data

Variables in **bold** are used in Breakout 1

Variable | Description
---------: | :---------------------------------------------------------------------------
`film_id`	| Film # (1-201) - alphabetical placing numbers first; sequels after originals
`film`	| Film's title
**year**	| **Film's year of release**
**length**	| **Length of film in minutes**
mpa	| MPA rating (G, PG, PG-13, R, NC-17)
**imdb_categories**	| **Up to three categories (from IMDB listing)** (and SEE BELOW!!)
star_1	| Name of first star in film
star_2	| Name of second star in film
star_3	| Name of third star in film
director	| Name of director(s) of film
**imdb_ratings**	| **# of IMDB public ratings as of 2023-09**
**imdb_stars**	| **# of stars (0-10) in IMDB public rating as of 2023-09**
imdb_pct10	| % of 10-star public ratings in IMDB as of 2023-09
imdb_link	| Link to IMDB public page for film
dr_love	| Has Dr. Love seen this film? (Yes or No)
mentions	| # of times film has been mentioned by students in 431 between 2020-2023
list_2020	| # of students who mentioned this film in the Fall 2020 version of 431
list_2021	| # of students who mentioned this film in the Fall 2021 version of 431
list_2022	| # of students who mentioned this film in the Fall 2022 version of 431
list_2023	| # of students who mentioned this film in the Fall 2023 version of 431

## More on `imdb_categories`

There are 20 different categories listed. Remember that each film could have 1, 2 or 3 categories in the `imdb_categories` variable. Across the 201 films in the `movies_2023-09-14` data, 15 have one category, 44 have two, and the remaining 142 have three.

Category | # of Films with this Category
---------: | --------:
Action | 51
Adventure | 67
Animation | 18
Biography | 11
Comedy | 72
Crime | 21
Drama | 115
Family | 18
Fantasy | 28
History | 3
Horror | 8
Music | 11
Musical | 6
Mystery | 12
Romance | 34
Sci-Fi | 25
Sport | 3
Thriller | 21
War | 4
Western | 1


[Back to breakout activity 1](breakout1.md)
