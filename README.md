# The-Code-Share

### A Little about THE CODE SHARE
Code Share is a platform that provides Groups an ability to code together without being together in one place. The app has an option to work on coding challenges sourced from an NPM PACKAGE _PJS PROBLEMS_ or to work/share individual code collabratively. The app provides a built in _CODE EDITOR_ sourced from another NPM PACKAGE _CODEMIRROR_. The app will also provide a feature where USERS can find coding events based on the USER input language. USERS will also be able to create their own events. The app will provide a feature for _AUTHS_ thus enabling the USERS to post specific events connected to their profile. 

### USER STORIES ( M V P )
  *  USER should be able to create a USER NAME ( NO AUTHS )
  *  USER should be able to view the coding challenges & the events on the main page
  *  USER should be able to select a challenge followed by a render of code editor for that challenge in a specific ROOM
  *  USER should be able to SAVE the code by an option of DOWNLOAD
  *  USER should be abe to view who is in the ROOM and who is typing should show
  *  USER should be able to CREATE or SEARCH coding events based on the language they provided
  *  USER should be able to show that they are interested in attending that event and others should be able to view their interest
  
### BONUS FEATURES
  *  AUTHS - option to REGISTER and LOGIN
  *  CHAT window in the ROOMS
  
### Planned Technologies
  *  SOCKET.IO - will provide the ability fir real time updates in the code editor
  *  NPM PACKAGES:
    *  PJS PROBLEMS - will provide JS coding challenges
    *  CODEMIRROR  - will provide the code editor window
  *  3rd Party API - will provide the data for upcoming coding events
  *  SQL DataBase structure - will provide the ability to save coding events created by users. Will also serve as a REST API where we can fetch the created events and display it on the EVENTS LIST
