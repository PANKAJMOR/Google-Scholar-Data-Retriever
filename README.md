🚀 Google Scholar Data Extraction Web App

📌 Overview
A web-based application designed to extract, manage, and download scholarly data from Google Scholar. This tool allows users to create profiles, automate searches, and store results in MongoDB for easy retrieval. It features a secure authentication system and an intuitive web interface built with Flask.

✨ Features
✅ User authentication (register, login, logout)
✅ Google Scholar data extraction and processing
✅ Profile-based query management
✅ Secure storage with MongoDB
✅ Download extracted data in Excel format
✅ Flask web interface for seamless interaction

🛠️ Technology Stack
🔹 Flask – Backend web framework
🔹 Flask-Login – User authentication
🔹 MongoDB – NoSQL database for data storage
🔹 Scholarly – Google Scholar data extraction library
🔹 Pandas – Data handling and transformation
🔹 OpenCV – Image preprocessing (if required in future updates)
🔹 Gunicorn – Production-ready web server

📂 Project Structure
📁 app.py → Flask web application entry point
📁 forms.py → User authentication and profile management
📁 generate_10.py → Extracts 10 Google Scholar results
📁 generate_all.py → Extracts all available Google Scholar results
📁 main_logic.py → Core logic for data extraction and processing
📁 models.py → Database schema using MongoEngine
📁 routes.py → Flask routes for user interaction
📁 requirements.txt → Project dependencies
📁 runtime.txt → Python version specification

🚀 Workflow
1️⃣ User registers and logs in
2️⃣ Creates a profile with a specific search query
3️⃣ Extracts scholarly data using the Google Scholar API
4️⃣ Saves extracted results in MongoDB for later access
5️⃣ Downloads structured data as an Excel file

🏗️ Future Enhancements
🔹 Optimize data extraction for improved efficiency
🔹 Enhance UI/UX for a more user-friendly experience
🔹 Implement real-time notifications for data updates
🔹 Extend support for additional research platforms
🔹 Deploy as a cloud-hosted service

🤝 Contributors
🚀 Your Name (@yourgithubhandle)

