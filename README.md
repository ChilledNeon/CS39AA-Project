# CS39AA-Project
1. Introduction / Background

The dataset that I am using is an Amazon Reviews dataset. What I am wanting to do with it is to make a LLM that will find what rating a user gave a product based on the review they gave. This is a text classification becuase it is taking the reviews a user wrote and it will try and classify it based on key words and try and learn the rating given. 

This first bit is showing the amount of reviews the products got. While 108,664 5 star reviews is cool, it didn't help me too much in understanding how much of them I was working with. SO by doing an average and putting the average next to the raw number, I can see what percent of the data is 5 stars or 1 star. 
![Screenshot 2023-11-09 154928](https://github.com/ChilledNeon/CS39AA-Project/assets/112008738/78fc66a4-585f-4e54-9c59-c2670119aa73)

I wanted to see what the most common word was. However the most common word was I and the. I did not care about these words, so I needed to remove these words. The way I did this was by using the pre built stopwords collection and removing them. I then ran a counter and counted up these words and found the most common word. 
![Screenshot 2023-11-09 155046](https://github.com/ChilledNeon/CS39AA-Project/assets/112008738/ee0ca462-045e-4876-becb-0e4396612bb6)
