# LAB - Class 16

## Project: First AWS Beanstalk

### Author: Reece Renninger

### Problem Domain  

Deploy a simple Node.js server to EC2, using Elastic Beanstalk

    Choose a server you’ve built previously
        Option 1: A simple API or Web Server
        Option 2: A socket.io event Hub
        The server should not require a database
        Check in your server to GitHub

Task 1:

    Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
    Manually deploy your application to this environment by uploading a .zip file

Task 2:

    Using the same server, create a new environment using Elastic Beanstalk from your terminal
    Manually deploy your application to this environment by using eb deploy


### Links and Resources

- [GitHub Actions ci/cd](https://github.com/ReeceRenninger/cloud-server/actions) 
- [back-end server url](http://lab16-2ndtry-env.eba-jrbxppkx.us-east-2.elasticbeanstalk.com/) 
- [PR request to main](https://github.com/ReeceRenninger/cloud-server/pull/1)

### Collaborators

- Ryan G helped with permissions issues.
- Ike and I built out our labs side by side

### Processes

For this lab I decided to follow along for the demo code to try and get my setup mostly completed, however I made some fatal errors.  During my GUI deployment, my account was somehow logged in at their east coast region but I created applications with a west coast region attached.  This was my first major bug, after adjusting that I realized that my permissions were not working for my user/role so I had to modify those with a different access requirement than the lab.  After that we all realized as a class that if you had created the CLI application first it would have automatically generated all the required roles with permissions for creating the GUI.  Overall, it felt like a large debug day but we got there.

#### `.env` requirements (where applicable)

for now I have none and do not require one


#### How to initialize/run your application (where applicable)

- e.g. `npm start`

#### How to use your library (where applicable)

#### Features / Routes

- Feature One: Details of feature
- GET : `/hello` - specific route to hit

#### Tests


#### UML

Link to an image of the UML for your application and response to events