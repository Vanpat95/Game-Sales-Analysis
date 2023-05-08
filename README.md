# Game-Sales-Analysis

Overview

I have been a huge video game fan for a long time, infact the first game I ever played was Duck Hunt and Super Mario Bros. on the Nintendo Entertainment System. I have also been a PlayStation fan since the original PlayStation was released.

The question that I had on my mind was what company sold the most amount of software and hardware.
My original guess was that Nintendo had the most sales as I remember the Wii being incredibly popular and dominating in sales at the time.
In order to answer this question I went to Kaggle to find video game sales data and I utilized Python and Pandas to transform the data, then I used Matplotlib to create visuals that were more appealing than a table.

___

Process

First, I loaded the global software sales data and created a filter to only display titles that have sold at least 15 million units globally.
Next, I used Matplotlib to create a pie chart to show the top 3 game publishers.

![top3publishers](https://user-images.githubusercontent.com/108643565/235567507-d9d5e3bf-40ea-41c4-b9bb-0f1ccebd75fc.png)

What I discovered was that Nintendo was way ahead of its competition in sales with over 82% of global software sales.

Next, I loaded the hardware sales data and I removed the PC since I would not consider the PC to be a video game console in this case as it is not primarly used for playing video games.
Then I used Matplotlib to create a pie chart to visualize the data and what I found was very interesting.

![global_hardware_sales](https://user-images.githubusercontent.com/108643565/235568153-5281dac8-12df-480c-a2ef-496a7ba09f98.png)

____

Conclusion

My original hypothesis was that Nintendo lead the world in software and hardware sales, but the data proved me wrong.
What I discovered through my analysis was that while Nintendo domianted software sales, Sony was actually in the lead for hardware sales. 
