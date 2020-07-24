#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This algorithm has a linear runtime complexity with O(n). because the number of loop runs directly porportional to the input.


b) This algorithm has a lineararithmic runtime complexity with O(n log n), because the first for loop runs directly porportional to the input O(n), and the while loop after will run through half the input Log(n) 


c) This algorithm has a linear runtime complexity with O(n). because the function will run through all the input aka bunnies until it reaches zero. 

## Exercise II
 We use a binary search so we don't go  through every floor insted we divide and conquer. Binary search will also minimize dropped and broken eggs.

Start by finding the middpoint and separating floors into a lower and higher list. Check if egg breaks at the middpoint floor. If it does eliminate upper level floors and then repeat floor separation and midpoint check on the lower floors list. If the egg didn't break then repeat floor separation and middpoint check on the higher floors. Continue middpoint checks until the list is indivisible then return that floor.

This algorithm has a logarithmic time complexity with O(log n) because it doesn't run through all the values but also still somewhat relies on number of floors.

