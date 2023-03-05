The key idea to solve this problem is to understand that rainwater can only be trapped if there exists a block of greater height, both on the left and the right side than the current block. Then rainwater can be trapped on top of the block.

So, it can be easily inferred that the amount of water a block can hold is equal to the minimum of the maximum height present on both the left and right half minus the height of the current block.

i.e.

Vol_of_A[i] = min(right_max, left_max) – A[i]
