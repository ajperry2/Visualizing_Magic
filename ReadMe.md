# Visualizing Magic

#### Introduction

My data is a publicly available dataset given at this [link](https://mtgtop8.com/), this gives information on the top decks at a country level tournament in London. I joined this data with a larger one at this [MTGjson](https://mtgjson.com/) which gives all of the information on every card in the card game. With these two combined I was able to analyze the components of the decks at the top level of play in Magic the Gathering.

The purpose of this analysis is simple. When people start playing Magic the Gathering, if they are playing this format of play, they are told very simple rules they should follow when constructing a deck. I am investigating whether these best practices in deck building are best even at the top level of play. These rules include choose cards which are low cost (require a low amount of mana to summon), stick to a small number of colors in your deck, and buy cards which are cheap but also good.

#### Summary of the Data

When someone first starts playing the modern format of Magic the Gathering, of the question of how to choose cards for a deck comes up. Often the advice is having a lot of low mana creatures, stick to one or two colors and if you buy a card, there are cheap good ones that will help you more. All of this advice is good as it counters natural impulses in a new player that hurt them badly at first.

I am investigating whether this is something that works well for beginners but should be abandoned once you know more about the game or if it is solid advice at all levels of play. I gathered data on the cards used in a modern tournament, looked at the patterns in their cards that relate to these tips, and this is what I found.

## Have Low Mana creatures
![The distribution of Mana required to play cards in the tournament](histogram.png)

It would seem that this rule is followed, but probably not as much as a new player listening to this advice would. It seems that as you learn more about the game, you should use your knowledge to choose slightly more powerful cards and a few super costly creatures. 


## Choose One or Two Colors
![Colors by Position](grouped.png)


Again, it seems that the competitors generally listen to the rule with some exceptions. Notice any patterns in the decks have more than two colors? It seems that as people get more experienced, they tend to include some cards from ‘auxiliary’ colors. Most often these support cards tend to be from the color blue. I can say the reason for this is blue cards tend to have ‘counter spells’ which are necessary in competitive matches. 


## Don’t Buy Expensive Cards
![Cost of Cards against Position](cost.png)

It would seem that these competitive players to not listen to this advice at all! The cards in their decks are very expensive with the most expensive card costing 150 dollars! 

# Conclusion:
These patterns can help someone that is becoming intermediate by explaining how to deviate from the advice they have been living by so far. If you are becoming intermediate, you may want to spend a little money on your deck but also don’t hesitate to throw a couple blue cards in to make your deck more reactive. Finally, if there is a card that is three or four mana that will really help your deck, throw it in. But only have one or two ‘big cards’ which cost more than five mana.

I hope that this advice will help people who are looking for advice on how to take their Magic deck to the next level.
