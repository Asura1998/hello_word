Input = []
while True:
    x = input()
    if x :
        Input.append(x)
    else :
        break
NetValue = 0
ValueIN = dict()
for value in Input:
    if "D" in value:
        NetValue += int(value[2:5])
    else:
        NetValue -= int(value[2:5])
print(NetValue)
