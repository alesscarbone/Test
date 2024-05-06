# Test
Test 
# This is my first code for ISYS 320
# A temperature Converter
# The program allows the user to do three temperature conversions
# It converts from Celsius to Fahrenheit

for tempCoversion in range (3):
    inC_str = input("Please, enter your temperature in Celsius: ") #Takes the user's input as a string
    temp_Celcius = float(inC_str) # Converts the string into a float to make calculations
    temp_F= 1.8* temp_Celcius + 32 # Celcius to Fahrenheit formula variable
    print(" The temperature in Fahrenheit is", temp_F, "degrees") # Prints the result

print("Thank you for using Temp_Converter!")
