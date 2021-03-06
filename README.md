<h1>Amazon-Text-Classification</h1>

A team project comprising:
Eram Khan,
Jeet Sanghvi,
Pooja Jaganade and
Prabhnoor Kahlon

<h2>Introduction</h2>
The introduction of anonymity has led to increase in number of reviews but on the other hand the quality of reviews has gone down on the interent forums. Different websites have tried different methods for extracting more useful comments. Amazon came up with their own helpfulness rating system.

<h2>Problem:</h2>
But still poor quality comments seem to be at the top of their review forms.The reason for the failure is that the part of the algorithm that determines the order of reviews relies on how recently the review was posted.

For example the following review was at the top of an app called “Friday Night at Freddies 4”

“I love this game so much but at first I though it was lame but when I go in the game I can't beat the first night because cause I put it to full volume and I can't here the breathing bonnie strike at 4 am Chica at 5 and plus it not lame it's better than fnaf and fnaf 2 plus get this game when u buy fnaf”

This comment, despite being at the top of the forum, is difficult to understand, a run on sentence, and full of spelling errors. The offending review was the most recent, but it’s helpfulness score was far less than previous reviews. This illustrates the difficult balance that must be struck between showing the highest rated reviews, and showing the newest reviews, to be rated by the community.

<h2>Solution:</h2>
Use machine learning techniques to design a system that “pre-rates” new reviews on their “helpfulness” before they are given a position at the top of the forum. The proposed system will use a set of Amazon review data to train itself to predict a helpfulness classification (helpful, or not helpful) for new input data.

<h2>Agenda</h2>
Data Preparation
Exploratory Analysis
Data Cleaning
Feature Engineering
Model Training and Selection
