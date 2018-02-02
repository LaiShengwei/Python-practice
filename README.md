# Python-practice
## iq test

	def iq_test(numbers):
    li=numbers.split(" ")
    even=odd=0
    for i in range(0,len(li)):
        if int(li[i])%2==0:
            even+=1
            k1=i
        else:
            odd+=1
            k2=i
    return k1+1 if even==1 else k2+1