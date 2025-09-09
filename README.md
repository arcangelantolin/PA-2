# PA-2

For the first problem, we first initialized the 5x5 matrix with the function randn() in numpy's random class. For its parameters, we set it to 5, 5 to indicate that we want a 5x5 array. Then, we got the mean and standard deviation of the array with the functions mean() and std(), respectively. Using the formula for normalization, we got the normalized version of the array by deducting the mean of the array to itself and dividing the whole thing with its standard deviation.

For the second problem, we generate numbers ranging from 1 (inclusive) to 101 (exclusive), using the function arrange() from the numpy library. We then shape this data into a 10x10 array with the function reshape() with the parameters 10, 10. Finally, using the **2 syntax, we are able to square it. 
To find all numbers that are divisible by three, we index it with a condition stating that n%3 == 0 (where n, is an element of the matrix) by simply using the bracket notation. This returns a new ndarray. 
