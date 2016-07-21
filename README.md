# Zombie-Apocalypse
Do not watch too many horror movies! If you are asking why, read what happened to Lea
last week:
Lea loves horror movies and watches vast numbers of them. But last week she exaggerated
by watching a 24 hours marathon of zombie apocalypse movies. Watching all these movies
without sleeping left her dazed. After the last movie ended (there was no happy end...)
she decided to prepare for the zombie apocalypse since it must be coming if there are
that many movies about it. She rushed to the closest supermarket and began to buy huge
amounts of food.
Now, she realises that she does not know what to buy to be well-prepared. Although in
confusion, she still wants to do this right, but the weight she may carry is limited and she
fears to go to the supermarket a second time since it may be too late by then. Can you
help her once more?
#Input
The first line of the input contains an integer t. t test cases follow, each of them separated
by a blank line.
Each test case starts with a line containing two integers m and n, where m is the weight
Lea may carry in grams and n is the number of groceries available. n lines describing the
groceries follow. The i-th line contains three integers pi, li and si where pi is the number
of packets of this grocery available in the supermarket, li is the weight of a packet of this
grocery in grams and si is the amount of calories per packet.

#Output
For each test case, output one line containing "Case #i: x" where i is its number, starting
at 1, and x is a space-separated list of groceries to buy (grocery i may appear at most pi
times in this list). The sum of their weights should be at most m and the sum of their
calories should be as big as possible. If there are multiple optimal solutions, any of them
will be accepted.

#Constraints
 1 <= t <= 20 <br />
 1 <= n <= 100 <br />
 1 <= m <= 3000 <br />
 1 <= pi <= 100 for all 1 <= i <= n <br />
 1 <= li <= 100 for all 1 <= i <= n <br />
 1 <= si <= 10000 for all 1 <= i <= n <br />
 
#Sample Data
Input <br />
2 <br />
10 2 <br />
1 3 5 <br />
6 1 1 <br />
<br />
10 3 <br />
2 3 7 <br />
1 2 8 <br />
3 7 5 <br />
<br />
Output <br />
Case #1: 1 2 2 2 2 2 2 <br />
Case #2: 1 1 2 <br />
