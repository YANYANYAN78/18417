# 18417
水仙花


打印出所有的"水仙花数"，所谓"水仙花数"是指一个三位数，其各位数字立方和等于该数本身。例如：153是一个"水仙花数"，因为153=1的三次方＋5的三次方＋3的三次方。


Python3.x 取整为 //，而不是 /，



l=[]
for x in range(100,1000):
    a=x//100
    b=x%100//10
    c=x%10
    if x==a**3+b**3+c**3:
        l.append(x)
        
        
print(l)
