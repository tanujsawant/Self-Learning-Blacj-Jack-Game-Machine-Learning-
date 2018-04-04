# Self Learning Blacj Jack Game(Machine Learning)
BlackJack game:
#Objective:

The objective is to make the sum of your card values as close to 21, without going over. If we make 21 exactly, we have blackjack, which can't be beat. If we go over 21, we 'bust' and we lose the round.

#The rules of blackjack are as follows:

1.It is a single player game. 2.The game has no gambling system. 3.Here we use only a single deck of cards. 4.The player and the dealer receive two cards from a shuffled deck. 5.After the first two cards are dealt the player is asked if they would like another card (called 'hitting'), or if they are happy with the cards they have already (called 'staying'). The player is allowed to stop hitting at any point. 6.The number cards (2 through 10) are worth the number displayed, face cards are worth 10, and an Ace can be worth either 1 or 11. 7.Once our hand is finished, the dealer tries to do the same. The dealer must keep hitting until they get to 17. If they get above 17 without busting, they can stay.

#Results:
1)If the player has blackjack, they win, unless the dealer also has blackjack, in which case the game is a tie. 
2)If the dealer busts and the player doesn't, the player wins. 
3)If the player busts, the dealer wins. 
4)If the player and the dealer both don't bust, whoever is closest to 21 wins


Usually a Balck Jack game is create which is player vs computer but we are creating Computer(AI) vs Computer(AI)

Self Learning
The main decision which is need to be taken while playing a black jack game is to decide weather to take a hit or stand!! This decision totally depends on taking into consideration the players total and the dealers total!! We have not hardcoded any strategies for the self playing black jack game!! IF we had included any strategies the black jack game would have played more accurately .. But the motivative behind this project was to make the model (machine learn) on historical data!!!
We have not used the pythons built in reinforcement learning function as we wanted to make the model work on only historical data which was tough but we were able to implement it!!
