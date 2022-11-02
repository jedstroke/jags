# Mr. Jags
Leetcode Assessment

```javascript
// Leetcode Assessment

/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[]}
 */

var twoSum = function(nums, target) {
   
    for(i = 0; i < nums.length; i++){
       for(j = 0; (j < nums.length); j++){
           if(nums[i] + nums[j] == target && i !== j){
               console.log([i, j]);
               return [i, j];
           }   
       }
   }

};

twoSum([3,2,4], 6); // [1, 0]
twoSum([0, 3, 5, 6, 7], 3); // [1, 0]
twoSum([5, 6, 0, 3, 7], 3); // [1, 0]
twoSum([5, 6, 7, 0, 3], 3); // [1, 0]
```
