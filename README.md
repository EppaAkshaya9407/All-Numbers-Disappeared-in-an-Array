# All-Numbers-Disappeared-in-an-Array
nums=list(map(int,input("Enter the array elements:").split()))
s=set(nums)
ans=[]
n=len(nums)
for i in range(1,n+1):
    if i not in s:
        ans.append(i)
print("Missing numbers:",ans)
