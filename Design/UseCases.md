# Actors
1. Users - Interested in an easy way to amplify their football game watching experience.
2. Matt/Abeed - Looking for software in a good enough state to be able to sell to shareholders and acquire funding with.

# Use Cases
## UC1 - New User watching live game
**Actors:** New user or football fans wanting to elevate their watching experience.
- New user joining the app for the first time to watch a game and enhance his viewing experience.

**Explanation:**
- This use case is about the steps a new user takes to join the app, access a live game, and start making predictions. It is very important because it enables users to experience the core functionality of the app immediately upon signing up.

**Steps/Flow**
1. Agree to terms/NDA
2. Create a username, password, and email in database
3. Accept email verification
4. Enter the menu and select the game currently being played

**Business Requirment:**
- BR1 - Provides the core real time football prediction experience.

## UC2 - Returning User watching an old game
**Actors:** Returning user
- A user who has previously used the app and wants to practice their prediction skills in legends mode.

**Explanation:**
- This use case is about the steps a returning user takes to play a legends game. Playing a legends game will allow users to practice and hone their skills to be able to earn points and rewards in a live game. 

**Steps/Flow**
1. Log into account using email/username and password
2. Select game located under the legends mode tab
3. Make predictions based on plays occuring in the game

**Business Requirment:**
- BR1 - Accessing past games to make predictions is still about the users interaction with making predictions and the experience the user gets.

## UC3 - User playing in a group
**Actors:** 
- **User** - A user who wants to join a group to watch games and compete with friends
- **Group Admin** - A user who creates a group and manages its settings.

**Explanation:**
- This use case shows how users can join a group and be able to play with friends while also competing against each other. Users can create a group or join a group to watch the game together, answer predictions, and compete within the group or with other groups. This keeps users engaged while also having a friendly competition.

**Steps/Flow:**
1. Log into account
2. Select group mode
3. If the user is the first member of the group:
    - Set up a new group
    - Send group code to other people 
4. Else
    - Enter a code in group mode to join group
5. Group admin selects the game to be watched
6. All group members watch along the selected game
7. Group members compete in a group leaderboard as well as a global group leaderboard

**Business Requirement:**
- BR2 - This supports a gamified experience through group competition and leaderboards, which enhances the fun aspect and keeps users on the app.
