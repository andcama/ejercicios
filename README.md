# Advent of Code 2023 - Day 1: Trebuchet?!

## The Problem

Part 1

Reads the input file line by line.
Extracts numeric characters from each line.
Combines the first and last extracted digits to form a calibration value.
Calculates the sum of all calibration values.
Part 2

Reads the input file line by line.
Iterates through each character in the line.
Checks if the character is a digit or the beginning of a spelled-out number.
Finds the first and last digit (either numeric or spelled out) in the line.
Combines the first and last digits to form a calibration value.
Calculates the sum of all calibration values.


# Advent of Code 2023 - Day 2: Cube Conundrum

## The Problem

Part 1
Read the input file: The code reads the input from a file named input.txt.
Process each game: For each game in the input:
Extract the game ID and cube information.
Iterate through each revealed set of cubes.
Compare the number of cubes revealed for each color with the predefined maximum (provided in the problem).
If any color has a revealed number exceeding the maximum, skip to the next game.
If all checks pass, add the game ID to the sum.
Print the result: The final sum of possible game IDs is printed.
Part 2
Read the input file: The code reads the input from a file named input.txt.
Process each game: For each game in the input:
Extract the game ID and cube information.
Initialize a dictionary max to store the maximum number of cubes seen for each color.
Iterate through each revealed set of cubes.
Update the maximum count for each color if the revealed number is higher.
Calculate power: Multiply the maximum number of cubes for each color to find the power of the minimum set.
Add to the sum: Add the power to the running total.
Print the result: The final sum of powers for all games is printed.






