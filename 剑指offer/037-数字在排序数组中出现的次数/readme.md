### 题目描述

统计一个数字在排序数组中出现的次数。


### 思路

整体用二分法，找到头和尾。

因为data中都是整数，所以可以稍微变一下，不是搜索k的两个位置，而是搜索k-0.5和k+0.5

