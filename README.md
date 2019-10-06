# OMP2019
Problems solved in the OMP'19.

# A - The Rise of Skywalker
#   Background
This Christmas, the saga comes to an end!! The epic fight between the dark and the light side of the Force will be decided!
The Skywalkers have prepared a new plan to conquer the universe. But this time, it will be a more peaceful plan: they will participate in the elections for the Galactic Senate, and they expect to have enough votes to be elected the new Emperor of the Universe!

#   The Problem
Each planet of the Galactic System has a certain number of votes. For example, Coruscant has 10 votes, while the moons of Endor only have 1 vote each.
Your task is to compute the minimum number of planets that are necessary to win the elections for the new Galactic Emperor, that is, to have more than half of the votes. For example, if we have 1 planet with 10 votes, and 10 planets with 1 vote each, we would need 2 planets (the planet with 10 votes, and 1 planet with 1 vote). And if we have 1 planet with 10 votes, and 9 planets with 1 vote each, we would need only 1 planet to win the elections (the planet with 10 votes).
May the Force be with you!

#   The Input
The first line of the input contains an integer N, indicating the number of test cases.
Each test case consists of two lines. The first line of each case indicates the number of planets of the Galactic System, G, between 1 and 100. Then, the second line contains G integer numbers, between 1 and 1000, indicating the number of votes of each planet.

#   The Output
For each test case, you should output the line:
Case X: M planets
where X is the number of the test case, starting from 1, and M is the minimum number of planets that are needed.



# F - More Knight Hops
#   Background
We love chess! So, let's do another problem about knights on a chessboard. But, in this case, we are interested in the total number of movements. Have you ever wondered how many knight movements can be done on a chessboard?

#   The Problem
We have a rectangular chessboard of size n x m. We represent the movements of a chess knight as edges in a graph. For example, here we have a board of size 3 x 5.
Here we have 15 nodes and 20 edges. But, in general, how many edges are there for a chessboard of size n x m?

#   The Input
The first line of the input contains an integer, t, indicating the number of test cases.
For each test case, there is a line with two numbers, n and m, separated by a space indicating the board size, where 3 ≤ n, m ≤ 15000.

#   The Output
For each test case, the output should consist of one line indicating the total number of edges of the graph corresponding to the given board size.



# G - Become a Millionaire... With Software Patents!
#   Background
The thinking heads of the country have invented a new method of making money, lots of money: software patents. You only have to patent any simple, insignificant and trivial piece of source code. Then, every time someone happens to write the patented lines, you charge him/her a 1000 euros fee.

#   The Problem
We have a set of programs, in source code. For simplicity, program instructions are denoted with capital letters: A, B, C, ..., Z. All programs end with a symbol #. We want to make as much money as possible by patenting a sequence of 3 instructions.
Your task is to find the most frequent sequence of 3 instructions in the available set of programs. Supposing we make 1000 euros for each use of our patented piece of code, how much money are we going to get from those programs?

#   The Input
The first line of the input contains an integer N, indicating the number of test cases. Each test case consists of a set of programs. The first line of each case contains an integer, M, indicating the number of programs. M lines follow, each one with a program. Each program consists of a sequence of uppercase letters, from A to Z, ending with a symbol #.

#   The Output
For each test case, you should output the line:

PATENT XXX AND WIN K EUROS!
where XXX indicates the sequence of three letters most repeated in that case (there will be, at least, a sequence of 3 letters in the existing programs). If there is more than one possibility, you have to output the alphabetically first. K is an integer number, indicating the total amount of money, in euros, we win with the patent.
