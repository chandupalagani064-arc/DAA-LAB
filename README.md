PRACTICAL 1

SUMMARY::     Sorting algorithms are essential techniques used to arrange data in ascending or 
               descending order, making searching and data processing more efficient. Each sorting 
               algorithm has its own strengths and weaknesses depending on the size and nature of the dataset.

CONCLUSION::  Each sorting algorithm has its own advantages. Bubble, Selection, and Insertion Sort are best for 
               small datasets and learning purposes, while Merge Sort and Quick Sort are better for large datasets 
               because they are faster and more efficient. The best algorithm depends on the size and type of data being sorted.

PRACTICAL 2

SUMMARY::      Linear Search::  Checks each element one by one until the target is found or the list ends. 
               It works on both sorted and unsorted data but is slower for large datasets
              Binary Search :: Repeatedly divides a sorted array into halves to find the target element. 
               It is much faster than Linear Search for large sorted datasets

CONCLUSION::   Linear Search is simple and suitable for small or unsorted datasets. 
               Binary Search is more efficient for large datasets but requires the data to be sorted before searching


PRACTICAL 3

SUMMARY::      Max Heap Sort is an efficient comparison-based sorting algorithm that builds a max heap and repeatedly places 
              the largest element at the end of the array. It has a time complexity of O(n log n) and sorts the data in place.

CONCLUSION::   Max Heap Sort provides reliable and consistent performance with O(n log n) time complexity in all cases. 
               It is memory-efficient and suitable for large datasets, though it is generally less efficient than 
               Quick Sort in practice due to higher constant factors.           

PRACTICAL 4

SUMMARY::     Both iterative and recursive methods calculate factorial in O(n) time. 
              Iterative uses a loop, while recursive uses function calls

CONCLUSION:: The iterative method uses less memory (O(1)), while the recursive method uses O(n) memory. 
             Therefore, iterative is generally more efficient.


PRACTICAL 7

 SUMMARY::   This program uses Dynamic Programming to find the minimum number of coins needed to make a given amount.
             It stores the minimum coin count for every amount in a DP table.
             
 CONCLUSION:: The algorithm efficiently calculates the minimum coins required. 
              Its time complexity is O(amount × number of coins) and space complexity is O(amount).


  
PRACTICAL 5 

 SUMMARY :: The 0/1 Knapsack problem uses Dynamic Programming to select items with maximum value without exceeding the given capacity.


 CONCLUSION :: The algorithm gives the optimal solution with O(n × W) time complexity and O(n × W) space complexity.


 PRACTICAL 6 

  SUMMARY:: Matrix Chain Multiplication using Dynamic Programming finds the optimal order of multiplying matrices with the minimum . 
             number of scalar multiplications .It stores solutions to smaller subproblems and uses them to solve larger ones efficiently

 CONCLUSION:: Dynamic Programming makes matrix chain multiplication more efficient by avoiding repeated calculations. The algorithm has O(n³)
               time complexity and O(n²) space complexity.
