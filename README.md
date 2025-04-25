# swapping
a=1
b=2
a,b=b,a
print(a,b)
#temp variable swapping
a=190
b=288
print("a:",a)
print("b:",b)
temp=a
a=b
b=temp
print("a:",a)
print("b:",b)
b=temp
print(a,b)
#swapping by arthematic operations(+,-)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a+b
b=a-b
a=a-b
print("after swapping:")
print("a:",a)
print("b:",b)
#swapping by arthematic operations(*,/)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print("after swapping:")
print("a:",a)
print("b:",b)
#swapping by arthematic operations(^)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print("after swapping:")
print("a:",a)
print("b:",b)
#list(1)
fruits=['apple','mango','cherry']
print(fruits)
print(fruits[1])
#list(2)
fruits=['apple','mango','cherry']
print(fruits)
print(fruits[1])
fruits[1]='banana'
print(fruits)
print(fruits[-1])
#numerical values in list
nums=[0,1,2,3,4,5]
print(len(nums))
#slicing method(1)
print(nums[3:6])
print(nums[:3])
print(nums[::2])
print(nums[::-1])
#slicing method(2)
nums=[0,1,2,3,4,5]
print(len(nums))
#slicing method
print(nums[3:6])
print(nums[:3])
print(nums[::2])
print(nums[::-1])
print(3 in nums)
#sort,rev ()
fruits=['apple','mango','cherry']
fruits.sort()
print(fruits)
fruits.reverse()
print(fruits)
#nestedlist
nestnum=[[1,2],[3,4],[5,6]]
print(nestnum[1])
print(nestnum[2][0])
print(nestnum[0][1])




