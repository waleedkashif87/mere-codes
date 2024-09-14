num = int(input("enter size of pyramid: "))

count = 1
for i in range(num, 0, -1):
    for c in range(i):
        print(" ", end='')
    print('#' * count)
    count = count + 2
