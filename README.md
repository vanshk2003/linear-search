# linear-search

Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found,
otherwise the search continues till the end of the data set.

How Linear Search Works?
Step 1: First, read the search element (Target element) in the array.
Step 2: Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.
Step 3: Match the key with arr[i].
Step 4: If the key matches, return the index. Otherwise, increment i by 1.

Complexity Analysis of Linear Search:
Time Complexity:
Best Case: In the best case, the key might be present at the first index. So the best case complexity is O(1)
Worst Case: In the worst case, the key might be present at the last index i.e., opposite to the end from which the search has started in the list. So the worst case complexity is O(N) where N is the size of the list.
Average Case: O(N)
Auxiliary Space: O(1) as except the variable to iterate through the list, no other variable is used.
