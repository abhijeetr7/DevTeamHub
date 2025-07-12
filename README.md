# DevTeamHub

DevTeamHub - Team Management Software
DevTeamHub is a lightweight, browser-based team management application designed to help small to medium-sized teams organize tasks, track progress, communicate, and manage project goals efficiently. It features a dashboard for quick insights, a Kanban board for task management, a calendar for sprint planning, a daily standup summary, internal chat, document sharing, and project goal tracking.

Features
Dashboard: Get a quick overview of team members, tasks in progress, completed tasks, and active sprints. Includes dynamic charts for task completion trends and member productivity.

Team Members: Manage team profiles, roles, contact information, skillsets, and status.

Tasks & Kanban Board: Visualize and manage tasks through a drag-and-drop Kanban board with "To-do", "In Progress", "Review", and "Done" columns.

Calendar & Sprints: View tasks on a monthly calendar and plan sprints with weekly task breakdowns and countdowns.

Daily Standup: Submit and review daily standup summaries (what was done, what will be done, and any blockers).

Chat Simulator: A basic internal chat interface for team communication.

Document Sharing: Share important project documents with links, descriptions, and categories.

Project Goals: Define project goals, link them to specific tasks, and track their progress.

Role-Based UI: Simulate different user roles (Admin, Developer, Designer) to see how the interface adapts, showing or hiding specific functionalities.

Offline Mode Detection: Notifies the user if they are offline.

Local Storage Persistence: All data is saved locally in your browser's localStorage, ensuring your information persists across sessions.

How to Use
Open the Application: Open the index.html file in your web browser.

Navigate: Use the sidebar navigation to switch between different sections of the application (Dashboard, Team Members, Tasks, etc.).

Manage Roles: At the bottom of the sidebar, you can select your "Current Role" to see how the UI changes based on permissions (e.g., only Admins can add/edit members).

Add Data:

Team Members: Go to "Team Members" and click "Add Member" to add new team members.

Tasks: Go to "Tasks & Kanban" and click "Add Task" to create new tasks. Assign them to team members, set priority, status, and dates.

Standup: Go to "Daily Standup" to submit your daily report.

Chat: Select a user from the "Select Current Chat User" dropdown and type messages.

Documents: Go to "Documents" and click "Add Document" to share links to external resources.

Goals: Go to "Project Goals" and click "Set New Goal" to define project objectives and link relevant tasks.

Interact:

Drag and drop tasks between Kanban columns to update their status.

Click on tasks in the Calendar view to edit them.

All data is automatically saved to your browser's local storage.

Development Setup
This application is built using plain HTML, CSS, and JavaScript.

Prerequisites:

A modern web browser (Chrome, Firefox, Edge, Safari).

Running Locally:

Save the provided HTML code as index.html.

Open index.html directly in your web browser. No web server is required as all data is handled client-side via localStorage.

Technologies Used
HTML5: For the structure of the application.

CSS3: For styling and responsive design.

JavaScript (ES6+): For all interactive functionalities, data management, and dynamic rendering.

Chart.js: A popular JavaScript library for creating interactive charts (used for Dashboard visualizations).

Font Awesome: For scalable vector icons.

Data Persistence
All application data (members, tasks, standups, messages, documents, goals) is stored in your browser's localStorage. This means your data will remain even if you close and reopen the browser tab, but it is not synchronized across different browsers or devices.

Future Enhancements (Ideas)
Backend Integration: Implement a backend (e.g., Node.js, Python with Flask/Django, Firebase Firestore) for multi-user support, real-time collaboration, and persistent data storage across devices.

User Authentication: Add proper user authentication and authorization beyond simple role simulation.

Notifications: Implement in-app or browser notifications for task updates, new messages, etc.

Advanced Reporting: More detailed reports and analytics on team performance and project progress.

File Uploads: Allow direct file uploads for documents instead of just links.

Customizable Workflows: Enable users to define custom Kanban columns or task statuses.

Search and Filtering: Add search and filtering capabilities for tasks, members, and documents.

Drag-and-Drop for Calendar: Allow dragging tasks on the calendar to change dates.

Unit Testing: Implement unit tests for JavaScript functions to ensure reliability.

Feel free to explore, modify, and expand upon this application!
