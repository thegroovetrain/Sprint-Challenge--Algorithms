#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n**3)
the while loop will finish in n*n*n.

b)
O(n log n)
the for loop is O(n), the while loop (i think) is O(log n).

c)
O(n)
its recursive, decrementing bunnies by 1 until it reaches 0.

## Exercise II


Assuming infinite eggs, this is easily solved as a binary search.
Drop an egg at floor n/2, and continue halving in either direction
depending on whether or not it breaks. Performance is O(log n)

i.e.

n=10
drop at floor 5
if it breaks, drop at floor 2. if not, drop at floor 7.
keep testing halfway to the previous endpoint.