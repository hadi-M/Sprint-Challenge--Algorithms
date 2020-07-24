#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)
Because the length of the loop is n^3
You can actually change the while into 3 for loops, each with O(n) complecity

b) O(nlog(n))
The outer loop's complexity is O(n), and the inner one's is log(n, 2)


c) O(n)
Each function is O(1), but when it gets run n times, the complexity will be O(n)

## Exercise II
I'll use binary search: O(log(n))

So for every egg we drop, we get to find out something about all of the higher or lower floors,
I will use binary search.
Let's say your building has 1,000,000 floors, I will start from the middle and decide where to go.
If the egg breaks, move to 250,000, and if not, move to 750,000, so on so forth.
