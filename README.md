# Disaster Management System (DMS) - Full Stack Project

This repository contains the complete source code for a comprehensive Disaster Management System. The project is a full-stack MERN application featuring a public-facing, futuristic client website for citizens and a secure, feature-rich admin panel for content and issue management.

## Key Features

### 1. Public Client Website (Aegis Protocol)
- **Futuristic & Immersive UI:** Built with advanced HTML, CSS, and JavaScript, featuring a 3D interactive globe, "glassmorphism" effects, and dynamic animations.
- **Live Alerts Feed:** Displays real-time awareness campaigns and safety information managed by administrators.
- **Shelter & Contact Directory:** Provides the public with access to a list of registered emergency shelters and important contacts.
- **Disaster Intelligence Section:** An in-depth, tabbed interface with detailed information, images, and safety protocols for various disaster types.
- **Public Issue Reporting:** A secure form for citizens to report civic or safety-related issues directly to the admin panel's Issue Tracker.

### 2. Secure Admin Panel
- **Role-Based Authentication:** A secure login system with 'super' and 'admin' roles to manage access levels.
- **Dynamic Dashboard:** An at-a-glance overview of all system statistics, including the number of active alerts, shelters, volunteers, and more.
- **Full Content Management (CRUD):**
    - Manage Awareness Campaigns
    - Manage Emergency Shelters
    - Manage Volunteers
    - Manage Resources
    - Manage Emergency Contacts
    - Manage Admin Accounts (with super admin privileges)
- **Live Issue Tracker:** View, manage, and update the status of issues reported by the public in real-time.

## Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend (Admin Panel):** React
- **Frontend (Client Website):** HTML5, CSS3, JavaScript (with Three.js for 3D globe)
- **Database:** MongoDB (with Mongoose)
- **Key Libraries:** bcrypt (for password hashing), JWT (for authentication), Express-Fileupload (for image handling)

---

## Setup and Installation

To run this project, please follow the steps below.

### Prerequisites
- Node.js and npm installed on your machine.
- A MongoDB Atlas account (or a local MongoDB instance).
    - *Note: Ensure you update the MongoDB connection string in `server/index.js` with your own.*

### How to Run the Application

1.  **Extract the Files:**
    - Unzip the provided `.rar` file. This will give you three main folders: `server`, `admin-panel`, and `client-website`.

2.  **Start the Backend Server:**
    - Open a new terminal or command prompt.
    - Navigate to the `server` directory: `cd path/to/your/project/server`
    - Run the server: `node index`
    - The server will start on **`http://localhost:4000`**. Leave this terminal running.

3.  **Start the Admin Panel:**
    - Open a **second, new** terminal.
    - Navigate to the `admin-panel` directory: `cd path/to/your/project/admin-panel`
    - Run the admin panel: `npm start`
    - The admin panel will open in your browser on **`http://localhost:3000`**.

4.  **Start the Public Client Website:**
    - Open a **third, new** terminal.
    - Navigate to the `client-website` directory: `cd path/to/your/project/client-website`
    - Run the client-side server (if you set up the Express wrapper): `npm start`
    - The public website will open in your browser on **`http://localhost:3001`**.

You should now have all three parts of the application running simultaneously.****

# Linked In post :- https://www.linkedin.com/posts/anjanghosh963_mernstack-webdevelopment-internship-activity-7374041950619881472-PsR4?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEiknjEB-QGuqv48T6vBmVagL9pwU-i1eAU

# Reference Screenshots:-
<img width="1920" height="1033" alt="{B2AE4CA6-F9B1-49F7-BB1E-59178BED944D}" src="https://github.com/user-attachments/assets/16d6b48e-70a9-48f0-a3e1-33a3111e1b73" />

<img width="1920" height="1030" alt="{3577BDEB-8462-422F-A5F3-2BC02F9E6A98}" src="https://github.com/user-attachments/assets/9207bdd8-4064-430b-a8f3-02d8447736d8" />

<img width="1920" height="1032" alt="{80F5139C-2BD8-4593-A3E8-9CFDB595158E}" src="https://github.com/user-attachments/assets/083a9f41-da40-47ff-85df-34741ca34671" />

<img width="1920" height="1026" alt="image" src="https://github.com/user-attachments/assets/664acd98-5752-4b98-97a9-c99192aaf0f5" />
