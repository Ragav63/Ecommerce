# Ecommerce
Using Springboot, MySql for Backend and Angular for front-end technology implemented this project.

#Backend
Check whether Springboot and MySql is present in the machine.
If not install it.
The file for Backend is given. For Front-end the link is given as follows,
Things need to modify to run the backend in Springboot.
Ecommerce-Backend 

#MYSQL
// src/main/resources // application.properties
The port will be- 8290 --/if need a different port means need to change it accordingly.

spring.datasource.password = root  ---//its the password of mysql. From systems it may vary can give your mysql workbench password accordingly.

spring.datasource.driver-class-name = com.mysql.cj.jdbc.Driver  ---///its the database platform that have worked on the driver class name is mention here.
In any case user are using different platform then user need to change it accordingly.

Run the backend application check whether the server is running sucessfully or not.

**#Front-end
For Front-end go on through the link below user can download it in users own Google Drive.
https://drive.google.com/drive/folders/1viWI4a9qjkc_Cfo80qPk3uql8FlpaSgF?usp=drive_link
Go on through the Link**

After download check on through like node_modules, spec.ts, .ts files are present in.

Then check whehter the corresponding features are present the cmds are given below.
node -v   --// for checking whether node is present in your system or not.    --///you have to run this cmd in cmp prompt or powershell.
If not installed then need to install from the official website --- https://nodejs.org/en/

Then inside the front-end tools want to process go to terminal and check whether angular is installed or not using the cmd
ng --version or ng -v  --// is the command for checking the version or checking whether angular is present in the workspace.
If not installed then need to install using cmd --// npm install -g @angular/cli

After all the process to run the ecommerce angular application give the cmd ---// ng serve -o (it will lead to response browser that already opened or present).
Before running front-end application ---- angular  check whether backend is running.


That's it if in case any queries pin it.
