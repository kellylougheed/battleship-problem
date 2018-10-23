# 2-2: Battleship

Write a program that creates a 5x5 2D array. Place two battleships (three columns long) randomly in the array using the pseudo-random number generator from the [Skittles problem](https://docs.cs50.net/2016/ap/problems/skittles/skittles.html).

You'll want to generate the location of the first ship in a random row, starting in one of the first three columns (at index 0, 1, or 2). You'll generate the location of the second ship of the same way except you'll make sure the ships don't overlap (i.e. they are not in the same row). Each ship should span three columns.

Then you will prompt the user to guess the ships' locations. Continuously prompt the user to guess a row index and a column index, and congratulate them for hitting a ship if they do so. Otherwise, tell them to guess again.

**Extra Credit (+3 pts)**: Keep track of whether the user has found all of both ships. When they find all of both ships, stop prompting them to guess locations and congratulate them!
