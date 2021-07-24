#Калькулятор
what = input("What i should do? (+,-,/,*,**):")

a = float(input("Enter first number:"))
b = float(input("Enter second number:"))

if what =="+":
    c= a + b
    print("Output:" + str(c))
elif what =="-":
	c= a - b
	print("Output:" + str(c))
elif what == "/":
	c = a / b
	print("Output:" + str(c))
elif what =="*":
	c= a * b
	print("Output:" + str(c))
elif what == "**":
	c = a ** b
	print(Outputт:" + str(c))

else:
	print("Invalid operation selected")
print(Have a good day!")
	

