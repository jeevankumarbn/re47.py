i = 1

while i<=20:
    if i % 2 == 0:
        i += 1
        continue
    print(i)
    i += 1
    if i>20:
        break
print(" ")
