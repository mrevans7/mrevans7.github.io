---
layout: post
title: Project 3 Reflection
---

My vignette can be found [here](https://github.com/mrevans7/ST558_Project3). 

Prior to this project, I had not done a lot of work with R Shiny. I was initially intimidated by the idea of using Shiny, as the code always looks a little extra complex. However, following this project, I plan to do a lot more work with Shiny. I really enjoyed being able to instantly get results of a model after modifying different elements, which is something that is harder to do outside of Shiny. In the future, I think this will be extremely helpful for evaluating the effectiveness of different models. Additionally, I see a lot of applications that I can use R Shiny for my work with 321 Coffee to track key metrics.

The most difficult part of this project was figuring out how to create a prediction for a user's inputted values. For one, it took a lot of code to generate input for all 20 variables. Then, I had to figure out how to combine the needed values into a data frame that could be used for prediction. I found that the best way to do this was to write static code first before trying to apply it to Shiny. This was a strategy I used for almost all parts of the project, and I found it particularly helpful when I was just starting to get the hang of Shiny in the beginning.

If I had to do this project again, I would attempt to find ways to increase the efficiency of my code in order to use a larger portion of the initial data. The data originally had over 250,000 observations, but when I tried to run models on this data, they took a very long time to run. Doing this project again, I'd look into the possibility of applying parallel computing to use a larger portion of the data (I ended up using just over 6,000 of the observations.

With that being said, my biggest takeaway from this project was using critical thinking skills to troubleshoot issues. One example of this was the issue I just discussed with the large data. I considered moving to a different set of data, but I really like the data I had, so I instead found a way to use what I had. There were many other times where my app was not working how I wanted it to and had to use critical thinking skills in order to troubleshoot.

