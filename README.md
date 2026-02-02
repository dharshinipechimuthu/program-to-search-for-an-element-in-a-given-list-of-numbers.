# program-to-search-for-an-element-in-a-given-list-of-numbers.
L=[2,58,95,999,65,32,15,1,7,45]
n=int(input("Enter the number to be searched:"))
found=0
for x in L:
    if x==n:
        print("Item found at position:",L.index(n)+1)
        found=1
if found==0:
    print("Item not found")

OUTPUT:

1.
Enter the number to be searched:5
Item not found

2.
Enter the number to be searched:1
Item found at position: 8

