# Let's hack Mario!
This is forked from https://github.com/reruns/mario, who did all the hard work of actually emulating Mario in Javascript.  I've made some minor modifications to make it easier to tweak the code and play with the values.

# Setup
- Click the Green "Code" button at the top right, select "Download ZIP".
- Drag the downloaded .zip into your Documents folder and extract it.
- *OPTIONAL:* Install [Visual Studio Code](https://code.visualstudio.com/).  This will get you a nice code editor that'll make things easier for you.  If you're on a Chromebook, you probably can't do this.

# Run the game
Double click on `index.html` in your `mario` folder you extracted earlier.  A browser tab will pop up, and you'll be playing Mario in your web browser!

# Hack it
- *OPTIONAL:* If you installed Visual Studio Code, start it up, click `File->Open Folder...`, then select the `mario` folder.
- Open js/constants.js.  Change the values of the variables in there, then refresh the Mario page in your browser.  Mario will start at the beginning of the level, with new characteristics depending on what you changed.

# I just see a blue square! What do I do?
This means you typed something wrong.  Open up the console to see what the error is (Press Shift + Ctrl + J in Chrome).  If you don't know how to open the console, Google "Developer console for [your browser]" to find instructions to open it.  Remember, real programmers Google *everything*.  
  The error will show up in red.  If you don't know what the mistake you made was, Google the error!  Go look at the file you edited last.
  
# How does the game work?
If you're looking to actually start understanding what the game is doing, start with js/game.js.  That's the file that initializes the game and starts the game loop.  Good luck!
  
  
