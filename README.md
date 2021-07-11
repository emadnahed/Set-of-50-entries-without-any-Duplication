# Set-of-50-entries-without-any-Duplication
This code is having a set built for preventing duplicates.





Entries = {"null",}
count = 0
while (count < 5):
    x = input("Enter the Name")
    for i in Entries:
      if x != i:
        print("valid Set")
      else:
        print('No Duplicates Allowed in Set')
        
        
    set1.add(x)
    print(Entries)
    count+=1
    print(count)
    
if count > 5:
    print("The loop has finally ended")
    Entries.discard('null')
    print(Entries)
