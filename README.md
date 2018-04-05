
fibanaci=[]

pre_Value = 0
value = 1
newValue = 0
counter = 0

while counter < 100:

   fibanaci.append(pre_Value)
   newValue = pre_Value + value
   pre_Value = value
   value = newValue
   counter += 1

print(fibanaci[5])
