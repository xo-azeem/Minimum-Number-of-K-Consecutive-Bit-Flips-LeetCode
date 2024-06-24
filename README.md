# Minimum Number of K Consecutive Bit Flips

LeetCode Q # 995.

You are given a binary array nums and an integer k.

A k-bit flip is choosing a subarray of length k from nums and simultaneously changing every 0 in the subarray to 1, and every 1 in the subarray to 0.

Return the minimum number of k-bit flips required so that there is no 0 in the array. If it is not possible, return -1.

A subarray is a contiguous part of an array.

Example 1:

>Input: nums = [0,1,0], k = 1</br>
>Output: 2</br>
>Explanation: Flip nums[0], then flip nums[2].

Example 2:

>Input: nums = [1,1,0], k = 2</br>
>Output: -1</br>
>Explanation: No matter how we flip subarrays of size 2, we cannot make the array become [1,1,1].

Example 3:

>Input: nums = [0,0,0,1,0,1,1,0], k = 3</br>
>Output: 3</br>
>Explanation: </br>
>Flip nums[0],nums[1],nums[2]: nums becomes [1,1,1,1,0,1,1,0]</br>
>Flip nums[4],nums[5],nums[6]: nums becomes [1,1,1,1,1,0,0,0]</br>
>Flip nums[5],nums[6],nums[7]: nums becomes [1,1,1,1,1,1,1,1]

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Minimum-Number-of-K-Consecutive-Bit-Flips-LeetCode/assets/171427226/1f4852d9-4e99-4886-908b-9781c7ce5d15)

  Time complexity: O(n).</br>Space complexity: O(n).
</div>
