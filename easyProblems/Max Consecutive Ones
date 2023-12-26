class Solution {
  int findMaxConsecutiveOnes(List<int> nums) {
      int counter=0,max=0;
      for(int i=0;i<nums.length;i++)
      {
          if(nums[i]==1)
          counter++;
          else {
              if(counter>max)max=counter;
              counter=0;
          }
      }
      if(counter>max)max=counter;
      return max;
    
  }
}
