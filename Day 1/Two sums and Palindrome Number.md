**Question 1:Two Sums**
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

**Example 1:**

Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].
**Example 2:**

Input: nums = [3,2,4], target = 6
Output: [1,2]
**Example 3:**

Input: nums = [3,3], target = 6
Output: [0,1]
 

**Constraints:**
2 <= nums.length <= 104
-109 <= nums[i] <= 109
-109 <= target <= 109
Only one valid answer exists.


**Question 2:Palindrome Number**
Given an integer x, return true if x is a palindrome, and false otherwise.

**Example 1:**

Input: x = 121
Output: true
Explanation: 121 reads as 121 from left to right and from right to left.
**Example 2:**

Input: x = -121
Output: false
Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.
**Example 3:**

Input: x = 10
Output: false
Explanation: Reads 01 from right to left. Therefore it is not a palindrome.
 

**Constraints:**

-231 <= x <= 231 - 1
