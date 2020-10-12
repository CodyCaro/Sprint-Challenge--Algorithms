#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) because there is only one loop and the amount of times it runs is
determined by what n is

b) O(n^2) because there are two loops

c) O(n) because it relies on amount of bunnies

## Exercise II

n story building
n eggs

egg breaks if thrown off floor f or higher
not broken off floor less than f

I would start at floor 2 since floor one is the first index and if an egg broke at floor one then all floors would be bad to drop an egg off of.

After dropping off floor 2 if the egg did not break I would then go to the floor that is double the current floor I am on so in this case floor 4.

I would keep repeating this and once I got to a floor where the egg broke I would then go down to the floor that is in the middle of the current floor and previous floor.

so say we get to floor 16 and it breaks, the previous floor would have been 8 so I would go to floor 11 and drop an egg. If it broke there I would then again go to the middle floor between 11 and 8 since we knew that 8 was a safe spot.

If at floor 11 the egg did not break I would then go to the middle floor between 11 and 16 and just repeat the above process.
