# Valentine's Anti-Romance Movies
🖤💔

## Goal
As a frequent movie-goer, I got a hunch that this year's Valentine's Day movies were darker than previous years. Why? Read [my article](https://tiff-xwang.github.io/valentines-movies/) to find out. I set out to find solid proof on this hunch of mine. 

## Data & Workflow
I scraped Box Office Mojo for movies released between the beginning of February and February 14th during the past 10 years, and I saved the result to [valentines_movies.xlsx](valentines_movies.xlsx). I got each movie's title, release year and date, genre, box office gross, and logline.
<br></br> 
Then, I went in there and manually picked out [romance movies](love_movies.csv), getting rid of unrelated movies that just happened to be released during Valentine's season.
<br></br>
In order to decide which movies out of all the romance movies were anti-romance, I studied the content of each movie by reading its logline and synopsis and watching the trailer. Based on my own decisions, I ended up with [a list of anti-romance movies](anti-romance.csv).
<br></br>
The analysis went on from there. Read my analysis code [here](Movies.ipynb).

## Findings
There is indeed an upshot in anti-romance movies. They advocate for singleness, discuss topics like egg freezing, or make a serial killer who only hunts after couples! The traditional kinds of romance movies, like meet-cute and heterosexual marriage, are gradually fading out of the market.