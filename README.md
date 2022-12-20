# How did Politicalization on Youtube evolve over time?

## Short Introduction (Abstract)

## About YouNiverse

## About Radicalization Dataset

## Framing Research

## Data exploration (YouNiverse)
First we explore the dataset after reduction into the three main categories. As per the below figures, fig 1 shows the number of channels per category as can be seen from the graph, "People & Blogs" Category is the highest around 18k channels. From fig 2, we can see how subscribers count is distributed among the three categories. Since the distribution of subscribers count is heavily skewed we've used log scaled count. We can observe that "News and Politics" category has the highest median with more than 50% of the channels have more than 60k subscribers.

![channel/subscriber distribution](/assets/img/exploration_1.png)

## Data exploration (Radicalization Dataset)

![pol orient distribution](/assets/img/exploration_2.png)


## A) Did the general political interaction on Youtube increase over time?

Furthermore, we want to explore the activity of channels by category measured by video production on quarter basis. As well as views by category.

![quarterly video release](/assets/img/number_videos_uploaded.png)

As can be seen from the above graph, video production in the "News & Politics" category started to grow exponentially from 2015 and it exceeded the other two categories starting 2017.

![quarterly views](/assets/img/Interaction.png)

The above graph shows that people's interest in "News & Politics" category is growing overtime while interest in "People & Blogs" catgory started to drop beginning of 2017.

![quarterly total heat](/assets/img/heat_metric_1.png)

Surprisingly, the dislikes over total number of likes and dislikes dropped overtime. We have some theories about what this happens:

- People are accepting opposing opinions
- People are becoming so politically radicalized that they only interact/view videos that agree with their own political views

![quarterly avg interaction](/assets/img/avg_interactions.png)

As can be seen from the above graph, peoples average interactions per video is growing overtime for this category. Which means that people are having stronger opinions about the content either positive or negative (which can be a sign of redicalization)



## B) Did the political sentiment on Youtube change over time? 

![quarterly amount videos trump etc](/assets/img/trump_clinton_obama_videos.png)

![quarterly views trump etc](/assets/img/trump_clinton_obama_monthly_views.png)

Seems like trump got much more coverage & publicity from youtube compared to his opponent (hillary) and his predeccessor (obama).
His videos got more attention as well we measure that with the average views per videos.

![monthly avg views trump etc](/assets/img/avg_views_trump_etc.png)

Trump got much more coverage & publicity & attention from youtube compared to his opponent (hillary) and his predeccessor (obama). 



## C) Which political topics had the most interactions?

**(a) Growth comparison of politically categorized videos in (pre-) election period of Donald Trump**

As described before, we study and compare the growth of the view_count for the three categorical videos ("left", "right" and "center") starting in the pre-election period of 2017.

![growth_published_videos](/assets/img/growth_published_videos.png)


**(b) Heat-Metric comparison of politically categorized videos in (pre-) election period of Donald Trump**

Also as describe in before, we want to analyze also the the evolvement of the heat-metric during that period to assess the user engagement for the three different political categories. We have shown the feasibility of this metric-calculation in part 3-Q1-b, so we will apply it analoguously to this data-subset.

![Avg_heat_metric_pol_orient](/assets/img/Avg_heat_metric_pol_orient.png)

**(c) Word Cloud comparison**

![wordcloud left](/assets/img/word_cloud_left.png)

![wordcloud left](/assets/img/word_cloud_right.png)




![This is an image](/assets/img/sent_time.png)

![This is an image](/assets/img/sent.png)

![This is an image](/assets/img/sent_figures.png)
