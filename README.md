# rello
Building AI course project

## Summary

The project consist on a Crypto Price Prediction Tool, created as an strategy game where a digital player tries to find out the best factors and conditions to take into consideration so that he can predict the future prices.

The demand defines the price, which fluctuates in time according to many factors, but the pure data is there, so the challenge is to discover the weather signs that can predict either the rain or the sunshine of a concrete token value.

## Background

I’ve been dealing with crypto for a few years now. I bought a couple of books (Andreas M. Antonopoulos, Gavin Wood, Mastering Ethereum & Mastering Blockchain) to understand blockchain, the amazing technology beneath, and Ethereum, for the magic of smart contracts. In fact, I’m also learning Solidity as a hobby, and I’ve dealt with many ways of getting crypto in many places.

Besides the evident use of crypto, the thing is that investing on it is very risky at the minimum due to the relative volatility of prices, but after swimming in that brave sea, one can easily perceive that there seem to be patterns followed by those that somehow track the market movements, triggering thousands or millions of individuals after them.

If you have a look at the trades when they are going up or down, there is a lot of data that can be analyzed, not only for a concrete token during whatever period of time, but for many of them all together. Of course there are environmental factors that affect prices unexpectedly (like Elon’s tweets), but the point here is to try to predict with the best accuracy what’s going to happen at a concrete moment in future time, by discovering those “weather signs”, those behaviors hidden in that immense amount of data.

Discovering those facts to follow is the challenge, to find correlation, to discover best “weights” here or there. My guess is that this should be done by a Reinforcement learning approach, choosing this or that data. After all, we can simulate trades, and react based on the real market results.

Right now, I am not thinking of trade concepts like stop-loss, but this and others would be nice to have if this goes ahead well.

Another maybe relevant source of data to take into consideration would be gathering the trades of the “Big players” as a shortcut, which BTW first have to be identified, we’ll see.

I am perfectly aware that this thing I am thinking of may not be possible at all, or better said, I may not be able to find a solution at all, but, that’s the challenge that motivates me a lot to dive deep in AI.

## How is it used?

If there is a solution with a respectable % of accuracy, besides using it for myself of course, I would think of it as another rate factor to take into account, perhaps with premium features to be sold by subscription, like ChatGPT. But since I have no idea yet of what the pre-conditions are to obtain good results, I can’t reasonably think of how it would be used.

## Data sources and AI methods

Trades are widely available, but also are the concrete blockchains where the tokens “live”, where the movements of the accounts can be somehow crawled, there are millions of accounts, but not so many moving the greatest percentage of the volume.

Other factors to explore may be considered, like activity in certain social networks, but this is yet to be evaluated. 

The ideal situation is the one where as usual we easily gather a huge amount of real live data with inputs and results, where we can discover patterns based upon which the market tends to move.

As an initial implementation approach I see Reinforcement Learning AI techniques, where we could even see the issue as a kind of strategy game. This path seems to be very promising in the community (i.e. https://www.amii.ca/latest-from-amii/future-ai-reinforcement-learning-and-heres-why/#:~:text=Supportive%20AI%20requires%20two%20things,next%20big%20thing%20in%20AI.), and also, regarding the data availability there seems to be no problem at all.

The programming language to use will be Python, but of course we’ll adapt to the circumstances.

This would a very high level picture of the system:
![rello](/Screenshot 2023-04-01 at 14.25.01.png)

## Challenges

The most important ones would be:
* How to discover what to look at.
* Confirm RL as a correct approach.
* How to manage the apparently huge amount of data to analyze, from either technical or financial perspectives. 

For the first point, a lot of study on the matter will be necessary, this is not a new challenge and surely there will be tons of docs, but on the other hand, crypto is “new” and AI has evolved dramatically in the last years, so, there is hope for new ways of presenting the problem and so the solutions.
RL is what is on my mind, but this may not be the proper path, however, the journey to find it out will be amazingly fruitful.

If in order to find a solution, we guess that it is mandatory to manage a huge amount of information, so there may exist a financial problem, we’ll see, in any case, I hope the work done to reach to that conclusion would be enough to attract possible investors, or we can work at scale, I don’t know.

## What next?

Very briefly:
* Study deeply the RL AI techniques
* Study deeply the possible factors involved in the challenge.
* How and from where to gather the data
* Design the game model, by little steps, testing from the beginning in an agile way, by producing SW frequently.

## Acknowledgments
At this stage just a Great thank you! to the creators of the Building AI course
