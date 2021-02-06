--- 
layout: post
title: Brief notes about the Sliding Windows Algorithm
author: Xinyue Xiang
---

# Introduction

The sliding window algorithm can be used to solve the problem of the sub-string of the array/string. 
In another word, it is an advanced double pointers framework to solve some leetcode questions.
It can convert the nested loop problem into a single loop problem and reduce the time complexity.

(Noted:Sub-string questions can look at the Python function find.)

# Types of the problem

In general, any problem where the author is asking for any of the following return values can use a sliding window:
Minimum value, Maximum value, Longest value, Shortest value, K-sized value... etc

Furthermore, a question that uses a list or data type that must be iterated over in sequence is a great candidate for a sliding window. 

Some common data structures one will be using a sliding window on are strings, arrays, and even linked lists.

# Algorithm Logic

The idea of sliding window algorithm is this:

1) We use the left and right pointer technique in the double pointer in the string S, initialize left = right = 0, and call the index closed interval [left, right] a "window".

2) We first continue to increase the right pointer to expand the window [left, right], until the string in the window meets the requirements (including all characters in T).

3) At this time, we stop adding right, and continue to increase the left pointer to shrink the window [left, right] until the string in the window no longer meets the requirements (not including all the characters in T). At the same time, every time left is added, we have to update the results of a round.

4) Repeat steps 2 and 3 until right reaches the end of the string S.


Pseudocode

```python 3

left = 0, right = 0;

while (right < s.size()) {

    window.add(s[right]);
    
    right+=1;
    
    while (valid) {
    
        window.remove(s[left]);
        
        left+=1;
    }
}
```

Time Complexity: O(N)

# Example questions

[3.Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters)

[567.Permutation in String](https://leetcode.com/problems/permutation-in-string)



# References
https://github.com/labuladong/fucking-algorithm
https://www.geeksforgeeks.org/window-sliding-technique/
https://levelup.gitconnected.com/an-introduction-to-sliding-window-algorithms-5533c4fe1cc7
https://www.zhihu.com/question/314669016



# Quote

Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.
