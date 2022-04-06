# snake
print('Insert num:\n')
x, y, z, t = int(input()), int(input()), int(input()), int(input())
array = [x, y, z, t]
for step in range(1, len(array)):
   key = array[step]
   s = step - 1
   while s >= 0 and key < array[s]:
       array[s + 1] = array[s]
       j = s - 1
   array[s + 1] = key
print(array)
