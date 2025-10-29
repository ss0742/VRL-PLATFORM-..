VRL Platform System
This project is a Java-based server application for a Virtual Remote Learning (VRL) platform. It uses Java’s HttpServer class to handle HTTP requests and serves HTML pages for a virtual learning environment, including functionalities for login, registration, profile updates, and various classroom-related pages.

Features
Login System: Authenticate users based on hard-coded credentials.
Registration: Accepts and stores user registration data in memory.
Dynamic Profile Management: Displays user profile data and allows updates.
Static Page Serving: Serves multiple static HTML pages for VRL platform features like joining classes, video sessions, and settings.
Error Handling: Displays error messages for missing pages and incorrect HTTP methods.
Project Structure
The server uses several HttpHandler classes for different routes:

LoginHandler: Handles login authentication with hardcoded credentials.
RegistrationHandler: Handles user registration, storing user data in memory.
StudentProfileHandler: Displays and updates user profile information.
PageHandler: Generic handler for serving static HTML pages.
Setup
Prerequisites
Java JDK 11 or later
Installation
Clone the repository:
git clone https://github.com/your-username/VRLPlatformSystem.git
cd VRLPlatformSystem

