# OAuth_Project

## Project Description

I built this project in conjunction with the Full Stack Engineer Course with Codecademy. This was a project to help understand the implementation of OAuth2. The project was created to introduce me to the code needed to implemen OAuth2. I used Visual Studio Code to build this project. Along with Express, Passport, and JavaScript.

A challenge that I found was getting the ight syntax in order for the project to load. I managed to fix the problem, but I did find it frustrating that on letter/line can stop the program from running. From this challege I found taking breaks and understanding the problem can help. The error message needs to be understood, so that I know what the problem is and how to fix it. 

## How to Install/Run the project

In order to use the project, first you will need to fork the repository. Once you have forked the repository the project will show up in you Github repostories. Then you can clone the repository to your local repository. From there you will need to open a terminal and navigate to the files location. You will then  need to run the command npm install. This will install the dependencies that you need to run the project. Once this is complete, there are a few extra steps that need to be completed in order to use the project. These step will be set out in the bullet points below.

- Navigate back to your GitHub Homepage
- Click on your icon in the top right hand corner
- Click on settings
- Scroll down to <> Developer Settings (left hand side menu)
- Click on <> Developer Setting
- Once <> Developer Settings have loaded click on OAuth Apps
- Click New OAuth App
- Fill in the application name with OAuth Project (or a title of you choice)
- In the homepage URL type http://localhost:3000
- In authorization callback URL type http://localhost:3000/auth/github/callback
- Click register application
- Copy the Client Id (keep this private)
- Create a Client Secret and make a copy (keep this private)
- Make sure the Client Id and Client Secret is stored in a secure location. You will need them later
- Navigate to the project and open it you desired code editor. (I would recommend Visual Studio Code as that is the code editor I used to create the project)
- Navigate to the env page.
- Replace <GITHUB_CLINET_ID> and <GITHUB_CLIENT_SECRET> with you client Id and Client Secret
- Then you can load the project by running node app.js in your terminal (you may need to type http://localhost:3000 in to your browser if it doesn't load directly from the terminal)

## How to use the project?

You will need a Gityhub account username and password to access this simple project.
Please DO NOT make any changes to the project as this is an example of how to implement OAuth2.