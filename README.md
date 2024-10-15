# DSA-PRACTICE
def large(arr,n):
    lar=arr[0]
    for i in range(1,n):
        if lar<arr[i]:
            lar=arr[i]
    return lar

arr=[]
n=int(input("enter the no of elements"))
for i in range(0,n):
    ele=int(input())
    arr.append(ele)
print(arr)
ans=large(arr,n)
print("largest element in array is:",ans)
