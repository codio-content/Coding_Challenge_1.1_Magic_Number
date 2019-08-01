## Skills required
This is a simple variable assignment challenge. Students will need to be able to:

 - Accept a number as input
 - Create variables
 - Assign values to variables
 - Output values
 
 - Concatenate strings (optional)
 - Use a delay (optional)
 
## Advice
Students should be focusing on using suitably named variables as well as accepting inputs and writing outputs. These are fundamental skills and without them they will not be able to progress.

## Solutions

This is the basic solution

    user_choice = int(input("Choose a number"))

    total = user_choice * 2
    total = total + 9
    total = total - 3
    total = total / 2

    answer = total - user_choice

    print("The final value is", round(answer))

This solution uses delays to improve the user experience

    import time

    user_choice = int(input("Choose a number"))

    print("Multiplying your number by 2")
    time.sleep(1)
    total = user_choice * 2

    print("Adding 9 to the total")
    time.sleep(1)
    total = total + 9

    print("Subtracting 3 from the total")
    time.sleep(1)
    total = total - 3

    print("Dividing the total by 2")
    time.sleep(1)
    total = total / 2

    answer = total - user_choice

    time.sleep(1)
    print("The final value is", round(answer))