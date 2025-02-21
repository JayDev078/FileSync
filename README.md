# FileSync
 
File Management System Using Express.js
A simple backend project using Node.js, Express.js, and EJS for file management. Features include creating, reading, renaming, and listing text files stored in a local directory. Styled with Tailwind CSS for a clean UI. Perfect for beginners to learn basic file handling and backend functionality.
This is a simple backend project that demonstrates basic file management functionality using Node.js, Express.js, and EJS. It allows users to:

Create new text files with a title and description.
View the content of any file.
Edit the filename.
List all existing files in the system.
The project features a clean UI styled with Tailwind CSS and stores files in a local directory (/files).

Project Details:
Tech Stack:
Backend: Node.js, Express.js
Frontend: EJS (Embedded JavaScript) with Tailwind CSS
File Handling: Native fs module of Node.js
Features:
File Listing: Displays all files stored in the ./files directory on the home page.
File Reading: Users can click "Read More" to view the content of a file.
File Editing: Rename any existing file through the "Edit FileName" option.
File Creation: Add a new file by providing a title and description.
Routes Overview:
/ - Home page displaying a list of all files.
/files/:filename - Reads and displays the content of a specific file.
/edit/:filename - Renders a form to edit the filename.
/edit/ (POST) - Renames the file based on user input.
/create (POST) - Creates a new file with the title and description provided by the user.
