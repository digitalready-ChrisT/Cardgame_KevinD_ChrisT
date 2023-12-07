> The cardgame that we had developed is based off the game WAR. Basically whoever has the higher card will win. We've made the modification that the computer has a pre-set card, and we have to choose our card that we consider the highest. To play this game just pick the highest card in the hand your given which is our deviation from war and who ever is luckier will win !!
>
> Prerequisite: Python3
>
> We set up our plan to code this little console game into 4 total functionalities required for our game to run.
>
> 1. Firstly we decided to instantiate a variable called value which represents the 13 unique card in a deck and a variable called deck to represent the 4 unique suite in a deck in the Card class.
>    We than realize the deck had to be shuffled to randomize the deck and thus we deseigned a method in order to shuffle the entire deck.
>
> 2. Second we realize that we had to assign symbole to the 4 unique suites and also assign values to the Jack, Queen, King, and Ace. We created a repr function that assigns symbole of the suite to their string counterparts and also assign the approporiate values to J,Q,K,A.
>
> 3. Third we created two seperate class to represent the player and computer, which will both have 6 random cards from the deck. The player will have the option to pick the highest card and the computer will automatically pick the highest card. The winner is determind purely by luck and some skill whether the player can determine which card is their highest option.
>
> 4. Fourth we created a series of conditional to determine the winner base on their chosen card value. Than the console will output a statement that determines the winner of the war game. 
