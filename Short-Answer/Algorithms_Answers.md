#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)

The runtime complexity of this block of code would be `O(n^3)` (polynomial), where n is the input size. This is because the `while` loop is running on the order on `n^3` times. While the code in the loop is incrementing by a value on the order of `n^2`, the higher polynomial order of `n^3` will dominate the `n^2` for large inputs.

b)

The runtime complexity of this block of code would be `O(n log n)` (linearithmic), where n is the input size. This is because the outer `for` loop runs `n` times, for a runtime complexity of `O(n)`. Meanwhile, the value of `j` in the inner `while` loop is doubling rather than incremening, resulting in a runtime complexity of `O(log )`. For nested loops, we want to multiply the runtime complexities, so we would get a combined runtime complexity of `O(n log n)`.

c)

## Exercise II
