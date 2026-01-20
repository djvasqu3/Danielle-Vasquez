\# Git Practice Project Task2



This is a starter project for practicing additional Git operations in an existing repository.



\## Branch Structure



The dev branch combines the feature branches.

The feature branches worked on developing different parts of the game on their own.

The hotfix branch focuses on fixing randomInt within main.



\## Branch Descriptions



\- main: Contains the stable running version of the numbers guessing game

\- dev: An integration branch where the completed features are combined and tested

\- feature1: Allows the user to play and quit the game with user friendly messages

\- feature2: Manages end game logic

\- feature3: Develops hint system over multiple commits

\- hotfix: Fixes a bug involving the random integer used in main



\## Learning Summary



\### Differences



\- Merge: Merges branches together while keeping the branch version that was merged

\- Rebase: Cleans up branch history by showing commit history next to each other but is prone to conflicts

\- Squash: Merges multiple commits into one commit

\- Cherry-pick: Mostly used for hotfixes to use one commit in another branch



\### Observations



\- feature1 was merged with dev and then deleted

\- feature2 was merged with dev after conflicts were resolved

\- feature3 was merged with dev after squashing multiple commits into one commit



\### Use



\- Merge: Used in a real project to complete work safely while keeping branch history intact

\- Rebase: Used in a real project to clean up branches to create a more linear and readable history

\- Squash: Used in a real project to clean up commits for a better, more readable summary

\- Cherry-pick: Used in a real project to apply hotfixes without merging other work

