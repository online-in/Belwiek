Belwiek - A Modern Blogging Platform
Belwiek is a clean, modern, and fully-functional blogging platform designed for creators to share their thoughts, stories, and ideas. It's built with Vanilla JavaScript and leverages a Firebase backend for real-time data and authentication.

Live Demo: belwiek.vercel.app
<img width="2846" height="1523" alt="image" src="https://github.com/user-attachments/assets/8399cb36-e5e7-46ee-abd0-fdebc8424462" />


About The Project
This project is a complete, multi-page web application that provides a seamless experience for both readers and writers. Users can create an account, publish articles with a rich-text editor, manage their posts, and customize their public profile. The frontend is designed to be fast and responsive, using Tailwind CSS for styling.

Key Features
Full User Authentication: Secure sign-up, sign-in, and sign-out functionality.

CRUD for Posts: Users can Create, Read, Update, and Delete their own blog posts.

Custom User Profiles: Each user gets a profile page displaying their name, bio, cover image, and a list of their articles.

Profile Customization: Users can update their display name, description, profile picture, and cover image URLs.

Rich Text Editor: A Quill.js editor is integrated for an intuitive writing experience, including image uploads directly to Firebase Storage.

Dynamic Blog Page: A central page displays all posts, featuring a dynamic layout and a modal for quick reading.

Search & Filter: Readers can easily find articles by searching for keywords or filtering by category.

Static Pages: Includes a homepage, a blog directory, and an "About Me" page for the founder.

Contact Form: A functional contact form on the "About Me" page (powered by Formspree).

Tech Stack
Frontend:

HTML5

Tailwind CSS

Vanilla JavaScript (ES6+)

Backend & Database:

Firebase Authentication: For user management.

Firestore Database: As the real-time NoSQL database for posts and user data.

Firebase Storage: For hosting user-uploaded images in blog posts.

Deployment:

Vercel: For continuous integration and deployment from GitHub.

Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
You need a code editor (like VS Code with the Live Server extension) and a web browser.

Installation & Setup
Clone the repository:

Bash

git clone https://github.com/your-username/belwiek.git
Navigate to the project directory:

Bash

cd belwiek
Set up Firebase:

Go to the Firebase Console and create a new project.

In your project, create a new Web App.

Firebase will give you a firebaseConfig object. Copy this object.

In the project code, go through each HTML file (index.html, auth.html, blog.html, profile.html, creat.html, aboutme.html) and replace the existing firebaseConfig variable with the one from your Firebase project. This is essential for the app to work.

In the Firebase Console, go to Firestore Database and create a database.

Go to Authentication -> Sign-in method and enable "Email/Password".

Go to Storage and create a storage bucket.

Run the project:

Right-click on index.html and choose "Open with Live Server" from your code editor.

File Structure
The project uses a simple, flat structure for easy navigation.

/
├── index.html          # Main landing page
├── auth.html           # Sign-in and Registration page
├── blog.html           # Page to view all articles with search/filter
├── profile.html        # User profile and account management page
├── creat.html          # Form to create or edit a blog post
├── aboutme.html        # Page about the founder
└── bharath-profile.jpg # Profile image used on the aboutme page
Author
Bharath Kumar Gorle - Founder of Belwiek

Based in Bhimavaram, Andhra Pradesh.

A software engineer focused on building user-friendly web applications.
