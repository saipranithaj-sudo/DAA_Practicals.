# DAA
Practical 1

SUMMARY

Sorting algorithms are essential techniques used to arrange data in a specific order, such as ascending or descending. Common sorting methods include Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each algorithm has different characteristics in terms of time complexity, memory usage, and efficiency. Simple algorithms like Bubble, Selection, and Insertion Sort are easy to understand and suitable for small datasets, while Merge Sort and Quick Sort are more efficient and preferred for large datasets.

CONCLUSION

The choice of a sorting algorithm depends on the size and nature of the data. Bubble Sort, Selection Sort, and Insertion Sort are ideal for learning basic sorting concepts and handling small datasets. Merge Sort provides stable and consistent performance with a time complexity of O(n log n), while Quick Sort is generally the fastest in practice for large datasets due to its average-case O(n log n) performance. Understanding these algorithms helps in selecting the most suitable sorting technique for different applications and improves overall program efficiency.

Practical 2

SUMMARY

Linear Search and Binary Search are two commonly used searching algorithms for finding an element in a collection of data. Linear Search checks each element one by one and works with both sorted and unsorted data, making it simple but less efficient for large datasets. Binary Search, on the other hand, works only on sorted data and repeatedly divides the search space into halves, making it much faster and more efficient for large datasets.

CONCLUSION

Both Linear Search and Binary Search are important searching techniques with different use cases. Linear Search is suitable for small or unsorted datasets due to its simplicity, while Binary Search is the better choice for large, sorted datasets because of its faster performance. Choosing the appropriate algorithm depends on the size and organization of the data.

Practical 3

SUMMARY

Max Heap Sort is a comparison-based sorting algorithm that uses a Max Heap data structure. First, the given elements are arranged into a Max Heap, where the largest element is placed at the root. The largest element is then moved to the end of the array, and the heap is rebuilt for the remaining elements. This process continues until all elements are sorted in ascending order. The algorithm has a time complexity of O(n log n) in the best, average, and worst cases.

CONCLUSION

Max Heap Sort is an efficient and reliable sorting algorithm, especially when consistent performance is required. It does not require an additional array for sorting and has a worst-case time complexity of O(n log n). Therefore, Max Heap Sort is suitable for sorting large datasets efficiently.

Practical 4

SUMMARY

The recursive and iterative methods are two different approaches to solving a problem such as finding the factorial of a number. In the recursive method, a function calls itself repeatedly until it reaches a base condition. In the iterative method, loops such as for or while are used to repeat the required operations. Both methods produce the same result, but they differ in implementation and memory usage.

CONCLUSION

Both recursive and iterative methods are useful for solving computational problems. Recursion makes the code simpler and easier to understand for problems that naturally involve repeated subproblems, but it uses additional memory for function calls. Iteration generally uses less memory and can be more efficient for simple repetitive operations. Therefore, the choice between recursion and iteration depends on the problem requirements and efficiency considerations.

Practical 7

SUMMARY

Dynamic Programming (DP) is an algorithm design technique used to solve complex problems by breaking them into smaller subproblems. The results of these subproblems are stored and reused instead of calculating them repeatedly. This reduces unnecessary computations and improves the efficiency of algorithms. Dynamic Programming mainly uses two approaches: Memoization (Top-Down) and Tabulation (Bottom-Up).

CONCLUSION

Dynamic Programming is an efficient technique for solving problems with overlapping subproblems and optimal substructure. It can significantly reduce execution time compared with simple recursive approaches. Although DP may require additional memory to store intermediate results, it provides better performance for many complex problems. Therefore, Dynamic Programming is widely used in algorithms such as Fibonacci, 0/1 Knapsack, Coin Change, and Longest Common Subsequence (LCS).

practical 6

SUMMARY

Chain Matrix Multiplication is an important Dynamic Programming problem used to find the most efficient order for multiplying a sequence of matrices. The program uses a DP table to store the minimum multiplication cost for different matrix chains. The formula

$$ dp[i][j] = \min_{i \leq k < j} \{dp[i][k] + dp[k+1][j] + p[i-1]\times p[k]\times p[j]\} $$

is used to calculate the minimum cost. The program accepts matrix dimensions from the user and also measures the execution time. Its time complexity is O(n³) and space complexity is O(n²).

CONCLUSION

The Dynamic Programming approach provides an efficient way to solve the Chain Matrix Multiplication problem by avoiding repeated calculations. It determines the optimal multiplication order with minimum scalar multiplication cost. The use of a DP table makes the solution systematic and efficient compared with checking every possible parenthesization. The execution-time measurement also helps analyze the practical performance of the algorithm.

