# CS39AA-Project
1. Introduction / Background

The dataset that I am using is an Amazon Reviews dataset. What I am wanting to do with it is to make a LLM that will find what rating a user gave a product based on the review they gave. This is a text classification becuase it is taking the reviews a user wrote and it will try and classify it based on key words and try and learn the rating given. 

This first bit is showing the amount of reviews the products got. While 108,664 5 star reviews is cool, it didn't help me too much in understanding how much of them I was working with. SO by doing an average and putting the average next to the raw number, I can see what percent of the data is 5 stars or 1 star. If you do a bit of math, the percentages add up to 1.01%. This is because of the rounding I did to the percentages. After that I wanted to see what is the overall rating it was in my dataset. As my comment says, this average rating is not fully accurate because the ratings are not all for the same product
![Screenshot 2023-11-09 154928](https://github.com/ChilledNeon/CS39AA-Project/assets/112008738/78fc66a4-585f-4e54-9c59-c2670119aa73)

It might be a wonder what the most common word counts are for the given review. After fiddiling around I got an answer. After spliting the reviewText cell up into its individual words, I them counted those words. I them printed out the findings. On average a user is likely to use 20-30 words in there review. Whats not shown is that there are people that used 1,000+ words in their reviews. They weren't common enough for me to care, with only a handful out off 200,000 people doing it, which is why those data points are not shown
![Screenshot 2023-11-12 100410](https://github.com/ChilledNeon/CS39AA-Project/assets/112008738/27b24edd-2ab4-49e0-a6bd-79698d45a6ba)

I wanted to see what the most common word was. However the most common word was I and the. I did not care about these words, so I needed to remove these words. The way I did this was by using the pre built stopwords collection and removing them. I then ran a counter and counted up these words and found the most common word. 
![Screenshot 2023-11-09 155046](https://github.com/ChilledNeon/CS39AA-Project/assets/112008738/ee0ca462-045e-4876-becb-0e4396612bb6)
