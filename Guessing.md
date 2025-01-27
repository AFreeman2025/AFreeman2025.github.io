```mermaid
flowchart TD
id[This is Guess Gizmo]
Start([Start]) --> newLines["`Generate a random number with range 1 to 100`"] -->
NODE_STRING["`If player is incorrect shows _Incorrect_`"] --> 
COMMA["`If player input is higher than the randomly selected number show _Too High_`"] --> End([End])
newLines["`If player input is lower than the randomly selected number show _Too Low_`"] -->
NODE_STRING["`If player input is the number randomly generated show _Correct_`"] -->
End([End])
```
Step 1: It generates a random number from 1 to 100.
Step 2: Waits for player input.
Step 3: It tells the player if they are "Too High", "Too Low", or "Correct" depending on their input.
Step 4: The game ends.
