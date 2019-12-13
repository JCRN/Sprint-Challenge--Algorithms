#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n). This problem is linear, the number of operations will increase at a constant rate dependent on the value of n. 


b) O(n). This problem is linear, the number of operations will increase at a constant rate dependent on the value of n. 


c) O(n). This problem is linear, the returned value will always be 2(n), the number of operations will increase at a constant rate dependent on the value of n. 

## Exercise II
I would find a floor somewhere near the middle of the building and drop the first egg. If the egg breaks, then I can immediately eliminate any floor above me and will repeat the process moving downwards, otherwise I can immediately eliminate any floor below me and will repeat the process moving upwards. Either way, I am able to eliminate multiple floors with each egg drop, reducing the overall amount of egg drops. 

Since my floor selection is non-randomized the runtime complexity of this method would be O(log n).

