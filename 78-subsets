class Solution:
    def subsets(self, nums: List[int]) -> List[List[int]]:
        def generate(ind,subsets,ans,nums):
            if(ind==len(nums)):
                ans.append(subsets.copy())
                return
            subsets.append(nums[ind])
            generate(ind+1,subsets,ans,nums)
            subset.pop()
            generate(ind+1,subset,ans,nums)
        ind=0
        subset=[]
        ans=[]
        generate(ind,subset,ans,nums)
        return ans
