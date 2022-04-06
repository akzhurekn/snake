# snake
print('Insert num:\n')
x, y, z, t = int(input()), int(input()), int(input()), int(input())
arr = [x, y, z, t]
for step in range(1, len(arr)):
   key = arr[step]
   p = step - 1
   while p >= 0 and key < arr[p]:
       arr[p + 1] = array[p]
       p = s - 1
   arr[p + 1] = key
print(arr)
