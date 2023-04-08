This is the README file for the grouped anagrams program based on Leetcode's problem 49 without using non-primitive data structures packages other than ArrayList. 

Total time complexity: O(n*max(k))) = O(n^2*k) with n being the length of the input list and k being the average length of the all the words.
A cleaner implementation can be achieved using mergesort but yields worse run time. 

A faster run time of O(n*k) can be achieved by using a hash map.
