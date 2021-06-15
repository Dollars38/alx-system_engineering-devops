alias ls="rm*"
echo hello $USER - This is for saying hello user, where the user is the user
echo /PATH/*/action - Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
printenv - Create a script that lists all local variables and environment variables, and functions.
BETTY="Holberton" - Create a script that creates a new local variable.

Name: BETTY
Value: Holberton

export HOLBERTON="Betty" - Create a script that creates a new global variable.

Name: HOLBERTON
Value: Betty

8. echo $((TRUEKNOWLEDGE+128)\n) - Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

9. echo $(((POWER)/(DIVIDE))\n)  - Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables

10. echo $(((BREATH)**(LOVE))\n)  - Write a script that displays the result of BREATH to the power LOVE

BREATH and LOVE are environment variables
The script should display the result, followed by a new line

11. echo $(((2#(BINARY))\n) - Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line

