# PostIt
PostIt is a fully-featured social media web application, built with the MERN stack.  

Steps to run the PostIt Project

1. Clone the given repository:

    - git clone https://github.com/pasupathi-azure-devops-c2s/postil-master.git

2. Change the given directory

    - cd postil-master

3. Install the docker, node and npm

    - Refer the docker-kubectl-install.txt file and follow the steps to install the docker, npm, node, docker compose, kubectl, and az cli on ubuntu machine.

4. Install the npm models

    - npm install
    - cd client
    - npm install
    - npm install --save-dev @babel/plugin-proposal-private-property-in-object
    - npm install react-scripts@latest webpack@latest webpack-dev-server@latest



    **Note:** Using the npm install command to install the project dependencies modules.

5. Run the project

    - cd postil-master

    - docker pull mongo
    - docker run ---
    
    - npm run server
    
    - cd client
    - npm start
