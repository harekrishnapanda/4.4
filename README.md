'''
A test is conducted which is consisting of 20 MCQs (multiple choices questions) with
every MCQ having its four options out of which only one is correct. Determine the
probability that a person undertaking that test has answered exactly 5 questions wrong.
'''

# 4.4

n = 20
x = 15
p = 0.25
prob = (math.factorial(n)/(math.factorial(x)*math.factorial(n-x)))*(p**x) *((1-p)**(n-x))
print ("Binomial Random Variable =", prob)
