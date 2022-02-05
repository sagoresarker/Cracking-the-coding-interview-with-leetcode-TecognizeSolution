class Solution:
    def smallerNumbersThanCurrent(self, nums: List[int]) -> List[int]:
        hashmap = {}
        
        nums_sort = sorted(nums)
        res = []
        
        for i in range(len(nums_sort)):
            if nums_sort[i] not in hashmap:
                hashmap[nums_sort[i]] = i
                
        for i in range(len(nums)):
            res.append(hashmap[nums[i]])
            
        return res
                
                
