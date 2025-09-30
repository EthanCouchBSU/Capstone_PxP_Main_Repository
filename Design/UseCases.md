# Actors
1. Users - Interested in an easy way to amplify their football game watching expierence.
2. Game Master - Needs to create interesting calls, and set appropriate windows for each play made, relys on low latency and concise functionality.
3. Matt/Abeed - Looking for software in a good enough state to be able to sell to shareholders and acquire funding with.
# Use Cases

## USC1 - New User watching live game
New user joining the app for the first time to watch a game

1. Sign NDA
2. Create a username, password, and email in database
3. Accept email verification
4. Enter the menu and select the game currently being played

## USC2 - Returning User watching an old game
Returning user watching a game

- Log into account using email/username and password
- select game located under the legacy mode tab

## USC3 - User playing in a group
User joining and playing in a group

- Log into account
- select group mode
- IF first memeber of the group, set up a new group to get a code to give out to other members
- Else, Enter code in group mode to join said group
- Group admin selects the game to be watched, all other group members watch along
- -group members compete in seperate group leaderboard, as well as world leaderboard



## USC4 - Game Master
Game Matser setting up a game

- Log into account with game master privileges
- create and name new game
- connect to the games stream
- as plays happen, choose the right answer and time window for each play, and then select the game the play will be verified under
