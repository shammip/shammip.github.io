## Week 2: Arrays and Strings 

### Status Update

What did you do last week?
* Created a GitHub Pages website
* Wrote a project proposal 
* Completed LeetCode - Introduction: wrote notes
* Wrote a weekly update

What do you plan to do this week?
* Complete LeetCode - Arrays and Strings: write notes, complete practice problems, take quiz 
* Write a weekly update
* Relearn HTML & update my website

Are there any impediments in your way?
* I hope there is enough time for me to complete the current chapter and relearn HTML this week.

Reflection on the process you used last week, how can you make the process work better?
* Last week, I completed this course’s work prior to starting my other course’s work. This method helped me to focus on each course with much depth - I believe that I will continue to practice this method.
* Writing notes while reading the chapter on Introduction really helped me to understand the Big O and Recursion concepts better - I can try to read the material first and then write notes based on what I remember so that I can reflect on which concepts I understand and which ones I need to work on. 

### Leetcode Course Notes

**Array and Strings:** 
* dynamic array/list in Python are mutable but strings are immutable 

**Two Pointers:** 
* Two Pointer Strategy #1: one iterable array
  1. one pointer is at index 0 and another pointer is at index length - 1
  2. run a while loop until the pointers are the same index 
  3. for each iteration, move each pointer towards one another (both move, one moves or another moves)
  * time complexity = O(n)
  * space complexity = O(1)
* Two Pointer Strategy #2: two iterable arrays
  1. one pointer is at index 0 of one array and another pointer is at index 0 of second array
  2. run a while loop until one pointer reaches the end of the array 
  3. for each iteration, move each pointer to end (both move, one moves or another moves)
  4. if one pointer has gone over an array but another pointer has not, then it should go over it now 
  * time complexity = O(n+m) or O(n)
  * space complexity = O(1)
  
**Sliding Window:** 
* subarray/window: contiguous section of an array 
* Sliding Window Strategy #1: 
  1. left and right pointer are at index 0 and subarray/window is the first element 
  2. move right pointer to the right 
  3. if subarray becomes invalid, move left pointer to the right
  * size of window = right + left - 1
  * time complexity = O(n)
* Number of Subarrays
* Fixed Window Size

**Prefix Sum:** 
prefix array: prefix[i] is sum of all elements, including i 

**More Common Patterns:** 

**Quiz:** 4/5 = 80%
