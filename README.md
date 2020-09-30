# chatapp
Real-time Chat Application using React, NodeJs, socket.io, express

# Prerequisites :
Latest version of Nodejs installed, if not  get the latest version [here]https://nodejs.org/en/download/

# Follow the below steps to depoly the project on your local machine

1. Clone the current repository or download the zip file of this project.
2. Open the terminal and Create a react app inside the 'client' directory with the command ' npm install '.
3. Then, change the directory to 'server' and run ' npm install '.
4. Go to the 'client' directory and start the react-app with the command 'npm start'.
5. Now,change the directory to 'server' and start the express server by running the command 'npm start'.

These steps enables you to run the project on your localhost.


# Steps included to deploy the project to a cloud (ex: AWS)

1. Connect to your  instance as ec2-user using SSH.
2. Install node version manager (nvm) by typing the following at the command line:
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
3. Activate nvm by typing the following at the command line:
    . ~/.nvm/nvm.sh
4. Use nvm to install the latest version of Node.js by typing the following at the command line:
    nvm install node
5. Test that Node.js is installed and running correctly by typing the following at the command line:
    node -v
    This must display the version of your nodejs installed
6. Clone the current repository or download the zip file of this project.
7. Open the terminal and Create a react app inside the 'client' directory with the command ' npm install '.
8. Then, change the directory to 'server' and run ' npm install '.
9. Go to the 'client' directory and start the react-app with the command 'npm start'.
10. Now,change the directory to 'server' and start the express server by running the command 'npm start'.

# Note:
    Replace ENDPOINT path with your instance IP address (like: ENDPOINT = "http://<yourIP>:5000" in the file "client/src/components/Chat/Chat.js"  
