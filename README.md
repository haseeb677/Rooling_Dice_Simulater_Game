# Rooling_Dice_Simulater_Game_usng the Random Module In python.
**Overview**
The Dice Simulator is an interactive program designed to simulate the rolling of dice. It allows users to customize their experience by specifying the number of dice to roll and the number of sides on each die. The program validates user input, provides the results of each roll, and calculates the total sum of all dice rolled. Users can choose to roll again or exit the game.

**Features**
Customizable Dice Rolling:

**Number of Dice:** Users can specify how many dice they want to roll.
**Number of Sides:** Users can specify how many sides each die has, allowing for simulation of various types of dice (e.g., six-sided, twenty-sided).
****Roll Results:

**Individual Rolls:** The program displays the result of each individual die roll.
**Total Sum:** The program calculates and displays the total sum of all dice rolled.
**Input Validation:**

Ensures the number of dice and the number of sides are valid positive integers.
Prompts the user to re-enter valid values if invalid input is detected.
**Replay Option:**

After displaying the roll results, the program asks the user if they want to roll again.
Users can choose to continue rolling or exit the program by responding with 'y' or 'n'.
How It Works
Initialization:

The program begins by greeting the user and entering a loop to facilitate multiple rolls.
**User Input:**

The user is prompted to enter the number of dice they wish to roll.
The user is then prompted to enter the number of sides on each die.
Input validation ensures that both inputs are positive integers, with appropriate error messages and re-prompts for invalid entries.
****Dice Rolling:**

The program creates a Dice object with the specified number of sides.
The dice are rolled, and the results are stored in a list.
The individual results and the total sum are displayed to the user.
Replay Prompt:

The user is asked if they want to roll again.
If the user inputs 'y', the loop repeats, allowing for another roll with new specifications.
If the user inputs 'n', the program exits, thanking the user for playing.
