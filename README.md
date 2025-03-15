# SIT323-2025-Prac2P

In order for this project to run you will need to have express.js installed in the project folder

Firstly I opened Terminal, navigating my way to where I wanted the project folder to be and titled it "task2.1p"

Ran the code "touch index.js", then "npm install express" followed by "nano index.js"

I typed out the following code:

const express = require ('express');

const app = express();

const PORT = 8080;

app.get('/', (req, res) => {
 res.send('Hello World');
}); 

app.listen(PORT, () => {
 console.log(`Server running at: http://localhost:${PORT}/`);
});

Once saved I ran "node index.js", the terminal displayed the console message "Server running at: http://localhost:8080/"

I opened Brave Browser and typed in "localhost:8080" and was greeted with the message "Hello World"

I proceeded to then do the command "ctrl+c" cancelling the node server and run "touch .gitignore" followed by "nano .gitignore"

Then input "node_modules" so that when I uploaded this project to Github it ignored the node_modules folder

After everything for the task was done I proceeded to upload to Github using the following commands

"git init"

"git add ."

"git commit -m "Uploading finished task2.1p to Github""

"git remote add origin https://github.com/velitel/sit323-2025-prac2p.git"

"git push -u origin master"

