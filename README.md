Amalitech Video Hosting Platform
This project is a bespoke video hosting platform, designed for exclusive branding and tailored functionality. It allows Admin to upload, view, and manage videos, and Users to signup,login , reset password with features such as user registration, OTP verification, and administrative controls.
Table of Contents
•	Features
•	Installation
•	Usage
•	Routes
•	Models
•	Environment Variables
•	Contributing
•	License

Features
•	User registration with OTP email verification
•	Admin authentication for video uploads
•	Video upload with support for multiple formats
•	Video listing and playback
•	User login and password reset

Prerequisites
•	Node.js and npm
•	MongoDB

Usage
Uploading Videos

1.	Use the credentials username: ***** and password:**** to log in.
2.	Navigate to the upload page and upload video files.

Viewing Videos
1.	Register as a user and verify your email with the OTP sent to you.
2.	Log in with your credentials.
3.	View the video at the URL provided after upload or browse available videos.

Routes
Public Routes
•	GET / - Home page
•	GET /about - About page
•	GET /signup - User signup page
•	POST /signup - Handle user signup
•	GET /verify-otp - OTP verification page
•	POST /verify-otp - Handle OTP verification
•	GET /userlogin - User login page
•	POST /userlogin - Handle user login
•	GET /reset - Password reset page

Admin Routes
•	GET /admin - Admin login page
•	POST /admin - Handle admin login
•	GET /upload - Video upload page
•	POST /upload - Handle video upload

Video Routes
•	GET /Video - Main video page
•	GET /Video/:id - View a specific video by ID

Error Handling
•	GET * - 404 page

Models
Signup
Schema for user signups with fields for email, password, and OTP.

Admin
Schema for admin credentials.

Video
Schema for storing video metadata such as title, description, and file path.
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

A DEPLOYMENT LINK
https://amalitechvideo-1.onrender.com

ER diagram
![Screenshot (11)](https://github.com/ManuelKay1/AmalitechVideo/assets/174375483/7af8a587-1fe8-4a9b-9a49-63fa13da95c5)


