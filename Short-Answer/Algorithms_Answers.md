#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) _O(log n)_ We are growing exponentially #inside# the inner loop while counting up to a number.
judging my thought process on one like this earlier though its probably O(n) lol

b) Not O(1) for sure. Not O(n^2) because of that second while loop multiplying by 2. Im
thinking its a _O(n log n)_ because of the way is multiplying j by 2. The first 'n' because
we are iterating thorugh the first loop n times already. The second loop gets progressively smaller

c) _O(n)_ These seems like O(n) to me because the problem grows linearly with n

## Exercise II

maybe this could just be a binary search type thing?

- if f == 1, return that floor
- compare f with n // 2
- elif egg breaks at that floor, search the middle of bottom half of floors and recurse. repeating starting step 1
- elif egg doesnt break, search the middle of top half of floors and recurse. repeating starting step 1

time complexity == _O(log n)_
