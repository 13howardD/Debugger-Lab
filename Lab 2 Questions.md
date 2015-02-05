*Question 1*: ````cutoff```` if not a praameter to ````playturn```` because it is an instance variable.

*Question 2*: ````Scoresheet s = new Scoresheet```` assigns a new scoresheet to s. It then prints out the average number of turns which in this case it 0.0.

*Question 3*: You could move ````numBusts```` to the playTurn class under the line ````score=0````. 

*Question 4*: The problem is with the ````upValue```` always being 1. Line 25 in Die.jaja needs to be fixed. 

*Question 5*: I changed `````(int Math.random() * 6) + 1```` to ````(int) (Math.random * 6) + 1```` to allow  `math.random` to get a value other than 1.

*Question 6*: 10 = 5.55
			  15 = 12.625
			  20 = 8.5
			  25 = 11.333 