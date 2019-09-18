# Class_functions_python
# Define a class which has at least two methods: getString: to get a string from console input printString: to print the string in upper case. Also please include simple test function to test the class methods.
class test() :
    def __init__(self) :
        self.a= ''
    def gets(self) :
        self.a = input('Enter the string you want to convert into upper case :')
    def puts(self) :
        return self.a.upper()
obj = test()
obj.gets()
otp=obj.puts()
print(otp)
