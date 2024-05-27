# URL-Shortner


**Project Overview:**
This project is a URL shortener web application that allows users to shorten long URLs, track the number of clicks on each shortened URL, and manage their URLs through a user-friendly interface. The application includes user authentication and detailed analytics features.

**Technology Stack:**

Frontend: HTML5, CSS3, JavaScript
Backend: Node.js, Express.js
Templating Engine: EJS
Authentication: JWT (JSON Web Tokens)
Hosting: AWS Elastic Beanstalk


**Key Features:**

**URL Shortening:**

Users can input a long URL and receive a shortened version.
The shortened URL redirects to the original long URL when accessed.

**User Authentication:**

Users can create a new account and log in.
Authentication is managed using JWT, ensuring secure user sessions.

**Analytics Dashboard:**

Logged-in users can view analytics for their shortened URLs.
Analytics include the number of URLs created and the number of clicks each URL has received.

**User Interface:**

Clean and intuitive interface for easy URL management and viewing analytics.
Responsive design ensuring usability across different devices.

**Technical Details:**

HTML5 & CSS3: Used to create and style the web pages.
JavaScript: Adds interactivity to the frontend.
Node.js & Express.js: Handles the backend server logic, routing, and API endpoints.
EJS (Embedded JavaScript Templating): Renders dynamic content on the server side.
JWT (JSON Web Tokens): Manages user authentication and session security.
AWS Elastic Beanstalk: Provides a scalable and reliable hosting environment for deploying the application.
Project Workflow:

**User Registration & Login:**

Users register with an email and password.
Users log in using their credentials, receiving a JWT for session management.

**URL Shortening**:

Logged-in users enter a long URL in the input field.
The backend generates a unique short URL and saves the mapping in the database.
The short URL is displayed to the user.

**Analytics Tracking:**

Each click on a short URL is tracked and logged.
Users can view the total number of URLs they have created and the click count for each URL in their dashboard.

**Hosting and Deployment:**

The application is deployed on AWS Elastic Beanstalk, ensuring high availability and scalability.
AWS Elastic Beanstalk manages the deployment, from capacity provisioning, load balancing, and auto-scaling to application health monitoring.


This project demonstrates my skills in full-stack web development, user authentication, and real-time analytics, leveraging modern web technologies and cloud services.
