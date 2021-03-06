Introduction to Computer Engineering Programming Project {Most Negative Subarray Sum}

The goal of this project is to implement the most negative sum subarray problem in MIPS. The most negative subarray sum takes as input an array of integers and produces as output the most negative sum of any contiguous subarray in the original array. 

For example: The input can be the array {2, 5, -6, 2, 3, -1, -5, 6}. An example of a subarray is {5,-6,2} but {2,3,-5} is not a subarray. We seek to find the most negative sum of elements in any subarray of the given array. In this example, the highlighted subarray has the most negative sum, which is -7. (You can verify this for yourself by trying other subarrays; this value will be the most negative possible). 

We solve this problem using divide-and-conquer. A divide-and-conquer algorithm works by recursively breaking down a problem into two or more sub-problems of the same or related type, until these become simple enough to be solved directly. 

In this project, we will develop a program to take as input an array, use a divide-and-conquer (function MaxNegSubArraySum defined below) to calculate the most negative sum of any subarray of the array, and print the most negative sum and its starting and ending positions in the array on the console and exit.
