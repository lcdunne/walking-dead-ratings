# Analysis of The Walking Dead - Views & Ratings

![logo.png](C:\Users\L\Root\projects\walking-dead-ratings\img\logo.png)

This is a basic exploration into the performance of the main TV show of The Walking Dead. Wikipedia has a [list of episodes]([List of The Walking Dead episodes - Wikipedia](https://en.wikipedia.org/wiki/List_of_The_Walking_Dead_episodes) with useful information about each episode, but I also wanted an indication of how each episode was received by the viewers, so I scraped this from IMDb.

I wanted to see which seasons and episodes were the most popular, and since we also have the data on who wrote each episode, I was curious to see which of the (many) writers wrote the best episodes.

The highest ranked seasons were seasons 1, 3, and 5, with Season 5 having the highest viewer count overall:

<img src="https://github.com/lcdunne/walking-dead-ratings/raw/main/img/views_and_ratings_by_season.png" alt="" width="620">

The top 5 episodes were #1, #23, #43, #52, and #76, with #23 standing out as it was unlikely to be confounded by "first/last episode" effects, unlike the other four. According to Wikipedia, episode #23 could be the best of all 177:

<img src="https://github.com/lcdunne/walking-dead-ratings/raw/main/img/views_and_ratings_heatmap.png" alt="" width="620">

A writer score was calculated for each writer according to their mean and standard deviation of their episode ratings. Each writer's mean rating was converted to a percentile rank, $p_r(\bar{x})$, as was each writer's standard deviation, $p_r(\bar{s})$. The writer score was simply the arithmetic mean of these rankings.

The top 5 writers from the series, with the highest writer score, were Robert Kirkman, Seth Hoffman, Glen Mazzara, Jim Barnes, and Evan Reilly. None of the 5 writers with the highest episode counts were in the top 5 scoring writers, but Scott Gimple was ranked #4 if between-episode variability is not considered. Interestingly, Sang Kyu Kim - the writer of episode #23 - did not write any other episode of The Walking Dead, so they were not included in the best writer analysis due to having only a single episode.

<img src="https://github.com/lcdunne/walking-dead-ratings/raw/main/img/best_writer.png" alt="" width="620">

As the initial creator of the original comic book series (along with Tony Moore), it seems fair that Robert Kirkman's episodes scored the highest.
