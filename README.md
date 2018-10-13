# Music Recommendations Based on Lyrics Similarity

## Latent Sematic Analysis

Latent Semantic Analysis (LSA) is a method for finding latent similarities between documents treated as a bag of words by using a low rank approximation. It is used for document classification, clustering and retrieval. 

By calculating the similarity between lyrics, we built a music recommender system with **SVD** technique.

The dataset we used can be found in [here](https://www.kaggle.com/mousehead/songlyrics).



## Example: Give me songs similar to *Rolling In The Deep*

Given the song *Rolling In The Deep*, we can retrieve the top five similar songs.

It's quite impressive that all five songs recommended are somehow telling about the hurtful feelings of breaking up, just like Adele's song does.

 The recommended songs and their lyrics are shown below. Feel free to compare them by your own:

```
========== Current Song ========== 

< Rolling In The Deep - Adele >
----------------------------------------
There's a fire starting in my heart  
Reaching a fever pitch and it's bringing me out the dark  
Finally I can see you crystal clear  
Go 'head and sell me out and I'll lay your ship bare  
See how I leave with every piece of you  
Don't underestimate the things that I will do  
There's a fire starting in my heart  
Reaching a fever pitch and its bringing me out the dark  
  
The scars of your lov
...

========== Top 5 Recommended ========== 

001 < I'm Not Gonna Miss You - Glen Campbell >
----------------------------------------
I'm still here, but yet I'm gone  
I don't play guitar or sing my songs  
They never defined who I am  
The man that loves you 'til the end  
  
You're the last person I will love  
You're the last face I will recall  
And best of all, I'm not gonna miss you  
Not gonna miss you  
  
I'm never gonna hold you like I did  
Or say, "I love you" to the kids  
You're never gonna see it in my eyes  
It'
...

002 < Cherizar - Gino Vannelli >
----------------------------------------
I'm gonna wait till the sun comes out and  
I'm gonna wait till you come and shout it  
Cherizar  
Cherizar no matter where you are  
Cherizar you'll always be my star  
Cherizar no matter what you are  
Cherizar I'll always be your darlin'  
I'm gonna wait till the sun comes out  
I'm gonna wait till you come and shout it  
We're gonna kiss till the moon is drunk and  
We're gonna love till noon 
...

003 < No One's Gonna Love You - Christina Perri >
----------------------------------------
(Originally by Band of Horses)  
  
It's looking like a limb torn off  
Or altogether just taken apart  
We're reeling through an endless fall  
We are the ever-living ghost of what once was  
  
But no one is ever gonna love you more than I do  
No one's gonna love you more than I do  
  
And anything to make you smile  
It's a better side of you to admire  
But they should never take so long  
J
...

004 < About A Quarter To Nine - Dean Martin >
----------------------------------------
The stars are gonna twinkle and shine  
This evening about a quarter to nine  
My loving arms are gonna tenderly twine twee twee twine  
Around you around a quarter to nine  
I know I won't be late 'cause at half past eight  
I'm gonna hurry there  
I'll be waiting where the lane begins  
Waiting for you on needles and pins  
And then the world is gonna be mine oh all mine  
This evening about a q
...

005 < Just To Satisfy You - Glen Campbell >
----------------------------------------
Someone's gonna get hurt before you're through  
Someone's gonna pay for the things you do  
How many hearts will break  
How many will it take  
Just to satisfy you  
Just to satisfy-why you  
  
Another love, another fool, to play your game  
Another love, another fool, they're a-all the same  
  
Someone's gonna get hurt before you're through  
Now don't be surprised if that someone is you  
Yo
...
```