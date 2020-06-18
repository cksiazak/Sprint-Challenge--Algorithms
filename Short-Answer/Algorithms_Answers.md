#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) As the while loop is dependent on the size of n, this would be O(n)

b) The for loop will run through the size of n (O(n)), but the while loop will run through half, so it's O(n log n)

c) The function will run n times to return the sum of the number of bunny ears for n bunnies. O(n)

## Exercise II

Something similar to a binary search tree except when it returns false (egg didn't break), it then jumps up by 1 level till it reaches the highest point the egg didn't break

1. Find the middle floor of the building and drop the egg from there. If it breaks, ignore all the above floors and proceed to the half of the bottom floors, till it finds False, the egg didn't break.

2. once that is found, set the max_floor (temp value) to be that one level and jump up to the next floor.

3. For each floor the new egg is dropped from, set the temp value to that floor till finally, the egg breaks.

4. return that temp value, which should be the floor below the one where it broke
