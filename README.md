# Find-the-Smallest-Window-in-a-String-Containing-All-Characters-of-Another-String
Given two strings s and t, find the minimum window substring in s that contains all the characters of t in any order. If there is no such substring, return an empty string "".
Explanation:
Use a hashmap to store the frequency of characters in t.

Use a sliding window (left and right pointers) to traverse s.

Expand right until all characters in t are found.

Once valid, try shrinking the window from left to minimize it.

Keep track of the smallest valid window.

Time Complexity: O(n) (each character is processed at most twice).
Space Complexity: O(1) (only storing characters from t).
