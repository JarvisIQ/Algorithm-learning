第一题      

两数之和：

    给定一个整数数组 nums 和一个目标值 target，请你在该数组中找出和为目标值的那 两个 整数，并返回他们的数组下标。
    你可以假设每种输入只会对应一个答案。但是，你不能重复利用这个数组中同样的元素。     
    
    示例：
        给定nums[] = {2,7,11,15},target=9
        因为nums[0]+nums[1]=2+7=9,所以返回{0，1}

    
    题目来源：力扣（LeetCode）
    链接：https://leetcode-cn.com/problems/two-sum
    
    
    
    解法一：
    遍历数组，将每个元素与其后的各个元素之和与target相比较，如果符合条件，则返回相应下标
    代码详见twoSumOne.java
    
