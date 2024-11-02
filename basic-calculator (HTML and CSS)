#Program to make python calculator using oops

# A calculator class
class Calc():

    def get_operator():
        
        num1 = int(input("Enter first number: "))
        num2 = int(input("Enter second number: "))
        operator = input('''Enter 
                         + for addition
                         - for subtraction
                         * for multiplication
                         / for division''')
        
        if operator == '+':
            print(Calc.add(num1, num2))  
        elif operator == '-':
            print(Calc.sub(num1, num2))  
        elif operator == '*':
            print(Calc.mul(num1, num2))  
        elif operator == '/':
            print(Calc.div(num1, num2))  
        else:
            print('You have not typed a valid operator, please run the program again.')
        Calc.message()
        

    # functions to define our operators (+,-,*,/)
 
    def add(x, y):
        return x + y
        
   
    def sub(x, y):
        return x - y

   
    def mul(x, y):
       return x * y
       
   
    def div(x, y):
        return x / y
    
     # Define again() function to ask user if they want to use the calculator again
   
    def message():

        # Take input from user
        calc_again = input(''' Do you want to calculate again? 
                           Please type Y for YES or N for NO.''')

        # If user types Y, run the calculate() function
        if calc_again.upper() == 'Y':
            Calc.calculate()

        # If user types N, say good-bye to the user and end the program
        elif calc_again.upper() == 'N':
            print('See you later.')

        # If user types another key, run the function again
        else:
            Calc.message()
