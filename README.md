# Micro CRM Leads (Project 1)

## Live Deployment
Live: https://p1-leads-2jty.onrender.com

## Run Locally

### Setup Instructions
npm install // Installs all project dependencies defined in the package.json file.
npm start // Executes the "start" script defined in package.json (e.g., node server.js).
Open http://localhost:3000/ // Instructs the user where to access the application in their browser.

## Features
- Create and list leads
- Filter by status and search by name or company
- Update status

## Windows and macOS Notes
Open VS Code terminal. The commands are the same on both platforms.

## Reflection (Required for Marking)
For this project, I developed a "Micro CRM Leads Tracker," a full-stack web application designed to manage sales prospects. The architecture consists of a Node.js and Express backend that serves static files and exposes RESTful API endpoints. On the client side, I utilized HTML, CSS, and vanilla JavaScript to create an interactive interface where users can input new leads, filter the display list, and update lead statuses dynamically without refreshing the page.
Through this process, I gained a practical understanding of the client-server model. I learned how to initialize a Node environment, structure routes to handle HTTP requests, and manage asynchronous data flow using fetch. A significant new addition to my skillset was learning to use the Render.com web service for deployment. This was a valuable learning experience, as it taught me how to take code from a local Git repository and configure it as a live, production-ready web service accessible via a public URL.
In terms of improvements, the most logical next step would be to integrate a persistent database like MongoDB. Currently, the application relies on a simple data structure that does not scale well. I would also implement user authentication (login/signup) to secure the data.

## Video Presentation
Watch the Demo Here: https://www.youtube.com/watch?v=lPsUIsF42o8

**Timestamps:**
* 0:00 Introduction and problem
* 0:36 Features and architecture
* 1:10 Live demo: add and edit item
* 2:07 Deployment and live service
* 2:08 Code highlight
* 2:49 Challenge and next steps
