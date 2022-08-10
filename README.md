# Rules
- Each player has a deck (no size limit)
-  Each player starts the game by choosing 5 cards from their deck
- A game board has 9 spaces. Each space can hold 1 card each. (1 card will not be played)
- Each card has a top, bottom, left and right value
	- The top, bottom, left and right values are between 1-10
- When a card is played, it will look at all the adjacent spaces and evaluate whether or not it's values are greater than or less than the cards occupyting those spaces
	- If the balues are greater than the cards it beats then it will be "captures"
	- Every captured card increases the score by 1 point for the player
