# Express_EpicButtonGame
In this project, I want to built an Epic button Game app using Express and sockets with bellow function:

1. The app should serve only a single view, index.ejs.  
2. Any time the epic button is pushed, the count should update on every user who is connected via sockets. 
3. This should happen in real time. If a user clicks the reset button, the count should reset to 0 for every user as well!
4. This app will listen to any events that the client ask for and the events the server must listen for. 

_ starting with the coding:
1. Need to install npm init -y
2. install express
3. install ejs for the static/views folder
4. install body-parser for routes folder 
5. install socket.io for the counter function
Then :
Map out the emitters and listeners I need before you start coding. 
Use a variable on the server to keep track of how many times the button has been clicked.  
