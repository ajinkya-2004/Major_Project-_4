Objective: To build a sophisticated project management tool with user roles, task assignments, and a visual Kanban board interface.

Key Features:

User Authentication & Authorization:
User registration and login.
Project owner, team member roles with different permissions (e.g., only owner can delete project, team members can only update tasks).
Project Management:
Create, view, edit, and delete projects.
Each project has a title, description, and list of associated tasks.
Task Management (Kanban Board):
Tasks with titles, descriptions, due dates, assignees (other project members), and status (e.g., “To Do,” “In Progress,” “Done”).
Drag-and-drop interface for moving tasks between status columns on a Kanban board.
Filter tasks by assignee, status, or due date.
Team Collaboration:
Invite/remove team members to a project.
Comment section for each task.
Notifications:
Notify assignees when a task is assigned to them or its status changes.
Technologies:
Front-End: React.js (with React Beautiful Dnd or similar library for drag-and-drop functionality).
Back-End: Node.js with Express.js.
Database: PostgreSQL/MySQL (for strong relational modeling of projects, tasks, users, and their relationships).
Other: JWT for authentication, bcrypt for password hashing, potentially a charting library for basic project progress visualization (optional).
