#Dodgeball v2
##Core Features:
- "High Society" style auctions
- Building balanced teams
- Scrambling for limited ball tokens to attack and defend
- Collecting victories and placing them in the "trophy case" for persistent effects

##Setup:
- Starting decks
- Shuffle Main Deck
- Place dodgeball token in the middle of play area, where everyone can reach.
	- For a game of 4 players, there should be 10 tokens.
	- For a game of 3 players, there should be 8 tokens.
	- For a game of 2 players, there should be 7 tokens.
	- At any point, if there are zero tokens unclaimed, everyone must immediately return all of their tokens, they are no longer claimed by anyone.
- Shuffle each individual stack of victory cards, and then remove
	- 3 from each stack (4 players)
		- 2 in test
	- 5 from each stack (2-3 players)
- On their first turn, each player gets 5 cards from their deck.

##Goal:
- Score the most victory points via victory cards, players on your team, or tactics
- The game ends when either of the last two victory stacks is depleted.

##On Your Turn:
###Determine your team's power.
In the four stats any given player has (Aim, Strength, Speed, Dodge) have a numerical value.

- Add all your players' Aim, and that is your team's Aim.
- Add all your players' Strength, that is your team's Strength.
- Do the same for all of your stats, and determine which of the four is the lowest. This value is your team's power.
- Your team's power is never treated as less than two. If your power is 0, 1, or 2, treat it as functionally 2. Your team power fuels so much of the game, you are at a severe disadvantage if you let it remain this low.

Now that you can know your team's power, you can proceed with your turn.

###Main Turn Structure
The majority of these are able to be done at any point
- **First:** Draw according to power
	- If your team's power is 3, you can draw a total of 3 (any combination of cards and dodgeball tokens).
	- If your team's power is low, your power is treated as 2 (you will always be able to draw cards on your turn).
- *at any point:* Play any amount of player cards into your core team:
	- Team can only have three players at any given time.
	- You are always able to move a player from your team to your discard pile. This makes room for a new player on your team of three.
- *at any point, but only once per turn:* Recruit new cards
	You may choose between buying a victory card, or flipping over cards from the main deck, and choosing one of those cards to auction.
	- If you choose to start an auction on a victory card, you must pay it's cost in dodgeball tokens. To participate in this auction, you will have to also play a dodgeball token. The cost on the card is what it costs to start the auction, to participate in an auction that is started by someone else, you only need to pay one token.

	- If you would rather auction a card from the main deck, turn over the top few cards. The number of cards you turn over is equal to whatever your team's power is. If you have any recruit bonus, you can add that to your power for this purpose.
	- You can then choose one of these cards to begin an auction.
- *at any point:* Use a tactic
	- By default, you may play one tactic card per turn.
	- If you have additional tactics (for example from a card saying +1 tactics) you may play more than one tactic card on a turn.
- *at any point:* Attack
	- If, you have an attack action available to you, you may attack a player from another team.
- *at any point:* Bench
	- If, you have a bench action available to you, you may use it to permanently remove a card from your deck.
		- You can remove a card from your hand or your team.
		- If the card you are removing is a victory card, it gets placed face up in it's own stack. This stack will not be shuffled back into your deck.
			- In many cases, the visible victory card (the one of top, most recently removed) gives an ongoing benefit during every turn, until it is covered by another victory card.
		- If the card you are removing is not a victory card, it goes to the bench, a stack of cards that will not be shuffled back into your deck, you cannot recover a card after it has been benched, but victory points on the card *will* count towards your score at the end of the game.
- **Last:** Discard down to power level

##Attacking:
**Attack** - The attacker may spend dodgeball tokens equal to the highest stat of an enemy card (plus any possible defense bonus).
**Defending from attack** - The defender may discard cards and/or dodgeball tokens to boost their defense. one for one.
If the defender is not able to overcome the attack, they receive one of the tokens the attacker has spent, and discards the card being atacked.

##Auctions:
During an auction, play progresses clockwise around the table, with each player taking one of the following actions:
- Placing an amount of cards in front of you, with a total value exceeding the current highest bid
	- Value is determined by adding their up their number(s) on upper left of card(s)
	- This total value is now the highest bid
- Passing, which makes you unable to participate in, or win, this particular auction.
Once there is a high bid that makes it all the way around to the original bidder without being increased by other players, that player has one the auction and gets to put their won card, and all the cards "spent" bidding for it in their discard pile.
Those that have not won the auction can return any cards they may have played back into their hands.
>Possible rule to test out: If you did not win an auction you started, you may start another auction at -1 recruit strength (never less than 2)
