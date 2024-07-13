Go to MongoDB website, log in to your account (create a new account if you don't have one), create a free database/cluster in a new project in your account and assign it a username & password (without '@').<br>
Download the source code from github and open the top-most project folder (containing frontend & backend folder & README.md file) in Visual Studio Code.<br>
Change the <username> & <password> in /backend/config.js to your database username & password.<br>
Open your terminal and enter the following commands sequentially (without colons): 'cd backend', 'npm i node', 'npm run dev'.<br>
If the backend terminal gives access error, then go to your database/cluster in your account project and allow access to your device IP.<br>
If Node.js requests permission, then grant it by pressing 'allow' button.<br>
Open a new terminal window using '+' at the top of the terminal and enter the following commands sequentially (without colons): 'cd frontend', 'npm i node', 'npm run dev'.<br>
Once the commands are run in the terminal in frontend folder, a localhost link (https://localhost:xyz, xyz - port address) will appear in the terminal, which should be opened in the browser.<br>
