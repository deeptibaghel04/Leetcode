# Single Number III

🔗 Problem Link: https://leetcode.com/problems/single-number-iii/

---

## 🧠 Approach (HashMap)

- Use HashMap to count frequency
- Store elements appearing once
- Return them

---

## ⏱️ Complexity

- Time: O(n)
- Space: O(n)

---

## 💻 Code

```java
class Solution {
    public int[] singleNumber(int[] nums) {
        HashMap<Integer,Integer> hm=new HashMap<>();
        
        for(int i=0;i<nums.length;i++){
            hm.put(nums[i],hm.getOrDefault(nums[i],0)+1);
        }

        int i=0;
        int arr[]=new int[2];

        for(int v:hm.keySet()){
            if(hm.get(v)==1){
                arr[i]=v;
                i++;
            }
        }
        return arr;
    }
}
