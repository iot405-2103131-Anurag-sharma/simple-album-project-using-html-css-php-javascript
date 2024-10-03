Simple Photo Album
This project is a simple photo album web application where users can browse through images in a paginated layout. Each page displays one large main image and two smaller images, and users can navigate between pages using pagination links.

Features
Displays one main image and two smaller images per page.
Supports pagination for navigating between different sets of images.
Simple, clean layout using HTML, CSS, and PHP.
Images are loaded dynamically from the images/ folder.
Prerequisites
To run this project on your local machine, you will need:

A local web server (e.g., XAMPP, WAMP, or MAMP) with PHP support.
A browser (e.g., Chrome, Firefox) to view the application.
How to Set Up and Run the Project
Step 1: Download the Project
Option 1: Download the project files as a ZIP file and extract them.
Option 2: Clone the project from GitHub (if available):
bash
Copy code
git clone <repository-url>
Step 2: Move the Project to Your Web Server Directory
For XAMPP: Copy the project folder (photo-album/) to the htdocs directory, which is usually located in C:\xampp\htdocs\.
For WAMP: Move the folder to the www/ directory.
For MAMP: Move the folder to the htdocs/ directory, typically found in Applications/MAMP/htdocs/.
Step 3: Start Your Web Server
If you're using XAMPP, open the XAMPP Control Panel and click Start for Apache.
If you're using WAMP, click the WAMP icon in the system tray and start Apache.
Step 4: Open the Application in Your Browser
Open your browser (Chrome, Firefox, etc.).
In the address bar, type:
arduino
Copy code
http://localhost/photo-album/index.php
Press Enter, and the photo album should load.
Step 5: View and Navigate Through the Images
The main page will display one large image and two smaller images.
Use the Next and Previous buttons at the bottom to navigate between pages of images.
You can add more images by placing them in the images/ folder.
How to Add Images
Place your image files (e.g., jpg, png) into the images/ directory located in the project folder.
The images will automatically appear on the next available page in the album when you refresh the browser.
Folder Structure
graphql
Copy code
photo-album/
├── index.php          # Main page to display images with pagination
├── images/            # Directory containing all the images for the album
│   ├── image1.jpg
│   ├── image2.jpg
│   └── image3.jpg
├── style.css          # CSS file for styling the album
├── script.js          # Optional: JavaScript for additional functionality
└── README.md          # Instructions on how to set up and run the project
Notes
Ensure your images are correctly named and placed in the images/ directory.
The pagination is set to display 3 images per page: 1 large image and 2 smaller images.
For simplicity, the project is coded to automatically load all images from the images/ directory.
License
This project is open-source and can be freely used or modified
