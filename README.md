This is the README file for the grouped anagrams program based on Leetcode's problem 49 without using non-primitive data structures packages other than ArrayList. 

Total time complexity: O(nmax(k))) = O(n^2k) with n being the length of the input list and k being the average length of the all the words. I was aiming for O(nk), but technically counting sort works only if we know the max length of all of the input strings.

A faster and more definite run time of O(n*k) can be achieved by using a hash map.
