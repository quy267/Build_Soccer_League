# Build_Soccer_League
Build a soccer league from player CSV file then generate letters to guardians.

## Overview
You have volunteered to be the Coordinator for your town’s youth soccer league. As part of your job you need to divide the 18 children who have signed up for the league into three even teams - Dragons, Sharks and Raptors. In years past, the teams have been unevenly matched, so this year you are doing your best to fix that. For each child, you will have the following information: Name, height (in inches), whether or not they have played soccer before, and their guardians’ names.

The project has three major parts. For each part choose from the tools we have covered in the courses so far.

Part 1: We have provided information for the 18 players in the attached file. Read the data from the file and store it in an appropriate data type so that it can be used in Part 2.

Part 2: Create logic that can iterate through all 18 players and assign them to teams such that each team has the same number of players. The number of experienced players on each team should be the same. Store each team’s players in its own new collection variable for use in Part 3. Please note: your logic should work correctly regardless of the initial ordering of the players.

Part 3: Create logic that iterates through all three teams of players and generates a personalized letter to the guardians, letting them know which team the child has been placed on and when they should attend their first team team practice. As long as you provide the necessary information (player name, guardians’ names, practice date/time), feel free to have fun with the content of the letter. The team practice dates/times are as follows:

Dragons - March 17, 1pm, Sharks - March 17, 3pm, Raptors - March 18, 1pm

When your complete code is run, it should output individual letters to file. There should be a total of 18 letters, one for each player.

Good luck!

## Project Instructions
Create appropriate variables and logic to divide players into three teams: Sharks, Dragons and Raptors. Be sure that your logic results in all teams having the same number of experienced players on each.

Write a letter for each player to a file. Use the player's name as the name of the file, in lowercase and with underscores and ending in .txt. For example, kenneth_love.txt

Be sure the text of each letter is formatted as a letter and starts with "Dear" and the guardian(s) name(s) and with the additional required information: player's name, team name, and date & time of first practice.

Name your script league_builder.py. Ensure your script doesn't execute when imported; put all of your logic and function calls inside of an if __name__ == "__main__": block.

Save to disk, a personalized letter to the Guardians of each player. Specify: the player’s name, team name, and date/time of their first team practice. There should be a total of 18 letters, one for each player.

As always, please add concise and descriptive comments to your code and be sure to name your constants, variables and keys descriptively.
