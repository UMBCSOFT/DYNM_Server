# DYNM_Server
<i>Do You Know Me?</i> is an online multiplayer party game for a group of friends. Everyone in the game is given the same question. Then, everyone receives the answers from the other players, and they are tasked with trying to figure out who wrote each answer. It's a game that answers the question... <i>Do You Know Me?</i>

This is the back-end server for the game. It is written in ExpressJS and uses WebSockets to facilitate gameplay.


# Running
1. Run `npm install` to get all the node module dependencies
2. Run `node index.js` to start the server
3. Go to `http://localhost:1337` on your browser to interact with the application using the test html page

# Configuring WebStorm
1. From the "Welcome to WebStorm page" select `Get from VSC`
2. Copy the git url `https://github.com/UMBCSOFT/DYNM_Server.git` into the URL slot
3. Click clone and login with github
4. Select the project to open it

Now we need to setup the run configuration
1. In the top right click Add Configuration
2. On the top left there will be a plus symbol. Click that.
3. In the drop down select `Node.js`
4. Be sure to include `src/index.js` in the `Node parameters` slot and optionally rename the configuration to whatever you want
5. Change the working directory to `\DYNM_Server`, so for example I cloned into `C:\school project\` so my working directory is `C:\school project\DYNM_Server`
5. Click apply

Now the project can be run by pressing Shift+f10 or by clicking the play button in the top right (or the bug next to it for attaching a debugger)

Once the app is running navigate to `http://localhost:1337/`. You can click the link in the run output box
