---
title: "TV, Halftime Shows and the Big Game🏈"
date: 2020-01-13
tags: [Python, Jupyter Notebook, data manipulation]
header:
  image: "/images/super_bowl.jpg"
excerpt: "Load, clean and explore Super Bowl data in the age of soaring ad costs and flashy halftime shows."
---

This is my first Data Science project after learning a thing or two about Data Manipulation. Here I load, clean and explore Super Bowl data.

Some of the questions I look at: -
- What are the most extreme game outcomes?
- How does the game affect television viewership?
- How has viewership, TV ratings and ad cost evolved over time?
- Who are the most prolific musicians in terms of halftime show performances?

The dataset used in this project was scraped and polished from Wikipedia. It is made up of three CSV files, one with [game data](https://en.wikipedia.org/wiki/List_of_Super_Bowl_champions), one with [TV data](https://en.wikipedia.org/wiki/Super_Bowl_television_ratings) and one with [halftime musician data](https://en.wikipedia.org/wiki/List_of_Super_Bowl_halftime_shows) for all 52 Super Bowls through 2018.

## Combined points and point differences distribution📊

<img src="{{ site.url }}{{ site.baseurl }}/images/superbowl_blog/combined_points.png" alt="Point distribution in Super Bowl">

The combined points distribution shows that most matches have ended with combined points between the range of 40 and 50 which is pretty average when we look at the highest value of combined points which is 75, in a match between San Francisco 49ers and San Diego Chargers. The Super Bowl in 2018 comes at second highest combined points where Tom Brady's Patriots lost to Nick Foles' Eagles with a score of 41-33 hence the combined score being 74.

But, when we look at the points difference distribution most matches have ended with a point difference range between 0 and 10 which is pretty close. The closest match was New York Giants vs Buffalo Bulls where the NY Giants won by a point!

<img src="{{ site.url }}{{ site.baseurl }}/images/superbowl_blog/point_diff.png" alt="Point difference in Super Bowl">

## Does one team's dominance lead to lost viewership?📡

You know when the point difference is very high like Seattle Seahawks crushing Denver Broncos with a point difference of 35 points (43-8), does this lead to losing viewers? Do people get bored of the match and stop watching it because its one sided and simply, domination over the other team?
Here, I created a scatter plot with a linear regression model fit using the seaborn package to find correlations between household share (average percentage of US households with a TV in use that were watching for the entire broadcast) vs. point difference.

<img src="{{ site.url }}{{ site.baseurl }}/images/superbowl_blog/linreg.png" alt="Graph explaining the above relation">

It does show a decreasing trend but there is no strong evidence that this does happen. Also, we can't be very certain of the decreasing trend as 52 datapoints are very less to determine a strong trend.

## Halftime shows and the ads📺

Nowadays, many people stick around to watch the halftime shows which is really good for the TV industry as it costs $5 million for a 30 seconds spot! But, let's look at the data...

<img src="{{ site.url }}{{ site.baseurl }}/images/superbowl_blog/subplots.png" alt="Graph showing the above relation">

The average number of US viewers started increasing before the ad costs, so yeah, maybe halftime shows were not that good, but who knows? Maybe there were network issues back then?

## Mirrors or Firework?🎼

Now, let's look at number of songs performed per halftime show appearance.

<img src="{{ site.url }}{{ site.baseurl }}/images/superbowl_blog/song_graph.png" alt="Number of songs per halftime show performance">

Given that the halftime show is just for 12 minutes, musicians normally perform 1-3 songs. But, Justin Timberlake went wild by doing 11!

<img src="{{ site.url }}{{ site.baseurl }}/images/superbowl_blog/top_songs.PNG" alt="Top 10 performers in super bowl">

## Conclusion📃

It was a great experience doing such a project. This is just the start, I intend to do even more and would love to blog about all of them! I hope you liked this blog and maybe learnt something from it ;). Would love to get a feedback from you guys and do consider subscribing to the blog if you liked the content. I'll attach the link to the code below, feel free to download it on your own machine and start exploring!

You can find the code [here](https://github.com/devanshu125/TV-Halftime-Shows-and-the-Big-Game).
