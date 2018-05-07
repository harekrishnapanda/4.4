# 4.4

n = 20
x = 15
p = 0.25
prob = (math.factorial(n)/(math.factorial(x)*math.factorial(n-x)))*(p**x) *((1-p)**(n-x))
print ("Binomial Random Variable =", prob)
