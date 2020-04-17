#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n*logn)


c) O(n)

## Exercise II

========|             Assuming we drop 1 egg from each floor, regardless of total height n:
   n    |             then I would iterate through the number of floors, starting at floor 1, counting 
  n-1   |             broken eggs as the difference between height n and a number one less than
  n-2   |             the floor being tested (floor f), then appending each result to a list than started empty.
  n-3   |             Once the list is filled with a value for broken eggs for each possible choice of drop-floor f,
  n-4   |             I would check the minimum value in the list, then find the index of that value, 
  n-5   |             and return the index value plus 1 as floor f.
  n-6   |        
  n-7   |             Time complexity O(n), unless using list.index() or list.min() is higher complexity.
  n-8   |             But I think they are likely each O(n) and O(3n) reduces to O(n).
  n-9   |
  n-10  |    
  n-11  | f 
  n-12  | ^  broken = n - (f - 1)
  n-13  | ^
  n-14  | ^
  n-15  | ^
  n-16  | ^
  n-17  | ^
  n-18  | = 1
TTTTTTTTTTTTTTTTTTTTTTTTTTTTTTT

