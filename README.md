# Startup
CS 260 Internet startup

[Class Notes](notes.md)

- To-do: 
 - Fix responsiveness bug with narrow windows on chat page
 - re-style login page

## CSS Deliverable
- Simon CSS deployed
- CSS added to main pages header, footer, main and Navigation elements
- Leaderboard styled for readability, general navbar and footer style added
- Bootstrap implemented with most elements
- Custom CSS used to give the vhat bubbles on the chat page their shape
- Style Responsive to window resizing
- Styling applied to application element mock-ups

## HTML Deliverable
Changes:
 - framework of pages created representing the final functionality of the app, including home, play, friends, chat, login, leaderboard, and account info pages
   - Including the tags Body, Nav, Main, Header, and Footer on each page
 - Links to each page from the home page via the nav bar (account info page is behind the login page - it will accept anything as a username and password right now)
 - Standin text and images for the eventual project features, including a picture and settings inputs to stand in for the game, input fields for options to join or watch another game, login placeholders, mimic chat structure, and more
 - Login page includes a placeholder login form, and submitting it takes you to the account page, including placeholder displays for account info including user name, rank, friends summary, and highscore.
 - Database placeholder on the leaderboard page
 - Websocket placeholder on the chat page
 - 3rd party service placeholder on the login page (SSO option) and in account creation functionality not currently visible (GetOTP call for email verification)

## Specifications

### Pitch

Imagine a roguelike game that you can cooperate on with your friends! So you can play like a wizard, your friend can hold the knives, and you have to find the exit for the maze-like dungeon! It would adjust the difficulty and size of the dungeon maze depending on how many players were in the game when the level was generated, so you can play in the same game alone and with friends, and it would support an integrated chat so you could collaborate real-time.

### Specifics

End goal:
Rougelike game is the main functionality, with fully randomly generated dungeons that can change size depending on how many players are present.

Chat functionality is the secondary main functionality, with cooperative play and observation the third stage and then enhancements of gameplay the  final stage of development.

Each user will have an account to save preferences for gameplay and to enable chat features and friend requests. There may be an option to link to existing platforms at some point, like signing in with Google, Facebook, or even Apple's gamecenter, depending on how far this project gets.

#### HTML
Basic Structure and content. Pages for Login, Chat, Play, Friends, Account, etc. Possible reduction with use of React.

#### CSS
Adaptive styling that looks goood and interesting on a variety of different screen sizes. Smooth and modern appearance and design.

#### React
Will provide Login, game settings, and game play elements in a streamlined flow. Will help chat experience to be seamless and integrated with other code areas.

#### Web Service
Authentication - Use of the third party GetOTP service to verify emails and phone numbers used on the website. Potential integration with SSO providers, including Apple, Google, and Facebook. Chat featuress potentially added this way. 

#### Authentication
Users will have individual logins and basic profile information associated with them. 

#### Database Data
The database will store highscores for individual players, as well as characters the players have created and users' chat history.

#### WebSocket data
Data from the server rendered on the user's screen will include realtime chat data, scoring data, friends' statistics and scores, how many players are playing with you or watching you play, and so forth.

#### Concept Art/Wireframes
![Main Page (not logged in)](/Startup/ConceptArt/MainPageLoggedOut.png)
![Friends Page](/Startup/ConceptArt/FriendsPage.png)
![Profile Page](/Startup/ConceptArt/ProfilePage.png)
