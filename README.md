# `What Zen`
```
                           _ooOoo_
                          o8888888o
                          88" . "88   What Zen Task Manager
                          (| -_- |)   Community Empowerment 
                          O\  =  /O
                       ____/`---'\____
                     .'  \\|     |//  `.
                    /  \\|||  :  |||//  \
                   /  _||||| -:- |||||_  \
                   |   | \\\  -  /'| |   |
                   | \_|  `\`---'//  |_/ |
                   \  .-\__ `-. -'__/-.  /
                 ___`. .'  /--.--\  `. .'___
              ."" '<  `.___\_<|>_/___.' _> \"".
             | | :  `- \`. ;`. _/; .'/ /  .' ; |
             \  \ `-.   \_\_`. _.'_/_/  -' _.' /
   ===========`-.`___`-.__\ \___  /__.-'_.'_.-'================
                           `=--=-'                    
```
## `Overview`
What Zen is a task manager app which combines the functionality of a minimalist Agile board integrated with a chat feature designed to empower its users. Now users can directly contribute in the decision making process for all the tasks in their board in real-time.

What Zen is a production of Team What Zen - 
* David Mears
* Dan Groze
* Adrien Fabre
* Sherif Shendidy
* Diptis Halder

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### `Our deployed app at` https://what-zen-app.firebaseapp.com/
## `Running the app locally`
1. Install necessary files
```
git clone https://github.com/what-zen/what-zen-app.git
cd what-zen-app
npm install
```
2. Create project at https://console.firebase.google.com/<br>
3. Navigate to Project Overview -> Project Settings<br>
4. Retrieve following project details<br>
apiKey:<br>
authDomain:<br>
databaseURL:<br>
projectId:<br>
storageBucket:<br>
messagingSenderId:<br>
5. Create a .env file in the root folder and insert mentioned values in their respective fields
REACT_APP_API_KEY=<br>
REACT_APP_AUTH_DOMAIN=<br>
REACT_APP_DATABASE_URL=<br>
REACT_APP_PROJECT_ID=<br>
REACT_APP_STORAGE_BUCKET=<br>
REACT_APP_MESSAGING_SENDER_ID=<br>

6. To run server:
```
 npm start
 ```
7. Runs the app in the development mode.<br>
8. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

# `How to run tests`
```
npm cypress:open
```
Launches the feature test runner, cypress.<br>

## `To deploy:`
```
npm run build
```
Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>

Install (and log in to) Firebase:

### firebase deploy

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
### `Wiki link` https://github.com/what-zen/what-zen-app/wiki