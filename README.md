# List-Rotation-using-slicing-method
l=[2,3,4,5,6]

for i in range (3):
  l= (l[-1:] + l[:-1])
print(l)
