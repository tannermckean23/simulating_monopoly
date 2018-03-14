# simulating_monopoly
Simulating monopoly to determine the proportion that all spaces are landed on

In order to determine the proportion of spaces landed on, we simulate 1000 games. In each of these games, we have two players that each have 150 turns.

In this simulation, we assume that players will only leave jail if they roll doubles while in jail. That is they never pay to leave jail, and we do not keep track of get out of jail free cards either.

All of the cards drawn from either chance spaces or community chest spaces are hard coded. That is, each card is assigned a number, and if the player lands on one of the spaces then the card is the one that matches a random number drawn.
