# AlGo

Playground repository containing collection of algorithms written in Go.

## Algorithms

### Sorting

1. [Bubble](https://github.com/bartossh/AlGo/blob/main/bubblesort/bubblesort.go) - bubble sort is the simplest sorting algorithm with O(n2) time complexity
2. [Insertion](https://github.com/bartossh/AlGo/blob/main/insertionsort/insertionsort.go) - insertion sort is simple sorting algorithm with  O(n) time complexity
3. [Bucket](https://github.com/bartossh/AlGo/blob/main/bucketsort/bucketsort.go) - bucket sort uses insertion sort for sorting bucket that are in increasing order, best time complexity is O(n+k), average O(n)
4. [CocktailShaker](https://github.com/bartossh/AlGo/blob/main/cocktailshakersort/cocktailshakersort.go) - cocktail shaker sort is swings back and forth to sort data with time complexity average of 0(n2) and best 0(n)
5. [Merge](https://github.com/bartossh/AlGo/blob/main/mergesort/mergesort.go) - merge sort is a divide and conquer sort algorithm with time complexity average of O(n log n)
6. [Shell](https://github.com/bartossh/AlGo/blob/main/shellsort/shellsort.go) - shell sort algorithm will sort values that are far apart from each other rather than adjacent, worst time complexity is O(n log^2 n), worst is O(n log n)
7. [Quick](https://github.com/bartossh/AlGo/blob/main/quicksort/quicksort.go) - quick sort algorithm is a divide and conquer sort algorithm with time complexity average of O(n\log n)


### Math

1. [BabyStepGiantStep](https://github.com/bartossh/AlGo/blob/main/babystepgiantstep/babystepgiantstep.go) - small step big step algorithm solves discrete logarithm problem of a^x = b (mod n) , with respect to gcd(a, n) == 1 with time complexity of O(sqrt(n))
2. [ExtendedEuclidean](https://github.com/bartossh/AlGo/blob/main/extendedeuclidean/extendedeuclidean.go) - in arithmetic and computer programming, the extended Euclidean algorithm is an extension to the Euclidean algorithm, and computes, in addition to the greatest common divisor (gcd) of integers a and b, also the coefficients of Bézout's identity, which are integers x and y such that

### Dynamic Programming

#### Memoization

1. [Fibonacci nth element](https://github.com/bartossh/AlGo/blob/main/fibonacci/fibonacci.go) - calculates n'th fibonacci sequence element recursively storing each n'th fibonacci value in the map to only calculate it once
2. [Coin Change](https://github.com/bartossh/AlGo/blob/main/coinchange/coinchange.go) - calculates the fewest number of coins that need to make up that amount
3. [Maximum Sub Array](https://github.com/bartossh/AlGo/blob/main/maximumsubarray/maximumsubarray.go) - finds sub array with the maximum sum and returns it sum
