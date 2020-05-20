---
title: "How to make a best-selling video game🎮"
date: 2020-05-10
tags: [Python, Video-Games, Data Analysis, Statistics]
header:
  image: "/images/videogame_blog/blog_cover.jpg"
excerpt: "Exploring video games sales data to find the best combination of genre,
platform and publisher to make a best-selling video game."
---

Today, I will explore the video games sales [data](https://www.kaggle.com/gregorut/videogamesales) and look at how to make a best-selling video game based on exploratory data analysis. I will divide this into four sections, the first three will be country specific, like North America, Europe and Japan and in the fourth section I will look at the global scenario. We will look at three main things to determine what would a best selling game look like -

1. Genre
2. Publisher
3. Platform

Let's start with North America.

## North America💵
To decide which genre to choose for our video game, let's look at the top 5 highest selling video game genres in North America.

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/NA_genre.PNG" alt="Video game genre graph">

Clearly, the Action genre dominates the market in North America, followed by Sports. The next question you would ask is about the publisher. Who is the best video game publisher in North America? Any guesses?

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/NA_pub.PNG" alt="Video game publisher graph">

Nintendo it is! Dominating the market since a long time, followed by Electronic Arts. Sorry to all those FIFA fans who thought Electronic Arts would dominate the market in North America :) Last but not the least, which platform is the best for your video game in North America?

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/NA_plat.PNG" alt="Video game platform graph">

It's Xbox-360! Wow! So, here you have it, the best combination of genre, publisher and platform to make a best-selling video game in North America is -

> Action + Nintendo + Xbox-360

## Europe💶
Let's look at how things would change if you want to make a best-selling video game in Europe, starting with genre.

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/EU_genre.PNG" alt="Video game genre graph">

Pretty similar to North America, only difference is at the third position. In Europe it's Racing genre whereas in North America it's Platform genre. This is because of the Formula-1 and the whole racing culture in Europe. Let's look at the publishers now. Any guesses?

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/EU_pub.PNG" alt="Video game publisher graph">

It's the same, again! Nintendo dominates Europe as well! Now comes the third and final criteria, Platform, will Xbox-360 be the best platform in Europe as well? Let's find out!

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/EU_plat.PNG" alt="Video game platform graph">

Nope, Xbox-360 is on the third position. PlayStation-3 tops the chart but not clearly dominating because of PlayStation-2! It's a close call. So, the best combination for Europe would be -

> Action + Nintendo + PlayStation-3

## Japan💴
Here comes the plot twist! Japan's gaming community is one of the best in the world and it will clearly show in the analysis that how different they are, from the rest of the world.

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/JP_genre.PNG" alt="Video game genre graph">

Role-Playing genre dominates the market by a huge margin! I think this is due to the Anime and Manga culture in Japan. Anyways, moving on to publishers, will Nintendo still dominate the market?

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/JP_pub.PNG" alt="Video game publisher graph">

Yes, it does! But there are three new names here. Namco Bandai Games who is famous for games like Pac-Man, Konami, known for Pro Evolution Soccer and Capcom who is known for amazing games like Resident Evil 3 and Street Fighter V. Let's look at which platform would be the best for releasing a game in Japan.

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/JP_plat.PNG" alt="Video game platform graph">

This is completely different from what we have seen so far. Nintendo DS dominates the market followed PlayStation-1. But it's Japan, so anything can happen! So, the best combination for Japan is -

> Role-Playing + Nintendo + Nintendo DS

## Global🌏
Now, it's time to look at global data and see what is the best combination to make a highest selling video game.

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/global_genre.PNG" alt="Video game genre graph">

It's Action again! Due to the fact that this genre dominates the market in North America and Europe which is a very big portion of the gaming community around the world. Let's look at publishers now. Will it be Nintendo again?!

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/global_pub.PNG" alt="Video game publisher graph">

Of course! Its clear domination everywhere! Finally, let's look at platforms to gain more insights.

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/global_plat.PNG" alt="Video game platform graph">

It's PlayStation-2! PlayStation-3, Xbox-360 and Wii are very close and its a tough call to choose between those three, but for now, PlayStation-2 clearly dominates. So, the best combination to make a best-selling video game globally is -

> Action + Nintendo + PlayStation-2

## Conclusion🎲
Fun fact, in this dataset, there is no game with this combination in the top 10!

<img src="{{ site.url }}{{ site.baseurl }}/images/videogame_blog/top10.PNG" alt="Top 10 video games">

But, Nintendo still dominates, as you can see all of the games in top 10 are published by Nintendo. So, choose your combination wisely! Even though the combination I mentioned is not there in the top 10, total global sales wise, it is the best combination.

You might have noticed that these figures are old and the ranking has changed, I know. The dataset I'm using was last updated 4 years ago and I just wanted to explore this dataset and give you insights regarding these combinations which would still work with a slight tweak or sometimes even as it is! Still there are many people who own a PlayStation or a PlayStation-2 and you never know, this combination could be the combination for the next best-selling video game!
