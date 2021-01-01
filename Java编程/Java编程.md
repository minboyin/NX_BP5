# Java编程

```java
/* 2021.01.01 第一个Java程序
	1、Python影响很大：使用 ： 而非 {  }
	2、不习惯使用 ；和 （）
	3、创建新的 new int[]{left,right}
*/
class Solution {
    public int[] twoSum(int[] nums, int target) {
        int left=0
        int right=nums.length()-1
        while(left<right):
            if nums[left]+nums[right]==target:
                return [left,right]
            else:
                left+=1
                right-=1
        return null
    }
}

```

