# Plans for Favorite Movies, Session 3

We have 201 movies in the data base. I've selected some potential predictors and outcomes from the 90 variables in the `movies_2023-10-24` data on our Shared Drive.

## What are the interesting outcomes?

Variable | Description | NA | Min, Med, Max
:-------------: | :------------------------------------------------------------------ | ---: | :---------:
`imdb_pct10` | % of 10-star public ratings in IMDB as of 2023-09 | 0 | 3.8, 15.6, 55.0
`fc_pctwins` | % of matchups won on Flickchart as of 2023-10 | 0 | 24, 52, 79
`rt_audiencescore` | Rotten Tomatoes Audience Score (% Fresh via Audience) as of 2023-10 | 0 | 28, 86, 98

and we could consider using the two outcomes we don't select to be predictors of the outcome we do choose.

## What are the predictors we'll consider?

Variable | Description | NA
:-------------: | :------------------------------------------------------------------ | ---:
`mentions` | # of times film has been mentioned by students in 431 between 2020-2023 | 0
`dr_love` | Has Dr. Love seen this film? (Yes or No) | 0
`bw_rating` | Bechdel-Wallace Test Criteria Met (0-3) | **8**
`gen_1` | Gender of star_1 (M or F) | 0
`bacon_1` | Star 1's Bacon Number (Movies only, as actor, no Soap no TV Movie) | 0
`metascore` | Metascore (0-100 scale) from critic reviews at Metacritic.com | **10**
`imdb_oscars` | # of Oscar (Academy Award) wins | **2**
`lang_1` | Primary language used in the Movie | 0
`budget` | Estimated Budget via IMDB (in $) | **19**
`box_off_mult` | World Wide Gross Revenue (as a fraction of production budget) | **20**
`ebert` | Movie Review (from Roger Ebert or other reviewer) on 0 to 4 stars scale | **25**



and indicators for the following 20 genres (1-3 per film per IMDB), no missingness in any of these...

variable | % of our movies
---------: | :----------:
drama | 57
comedy | 36
adventure | 33
action | 25
romance | 17
fantasy | 14
sci-fi | 12
crime | 10
thriller | 10
animation | 9
family | 9
mystery | 6
biography | 5
music | 5
horror | 4
musical | 3
war | 2
history | 1
sport | 1
western | <1


