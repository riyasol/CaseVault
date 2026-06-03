# Database Management System

## Overview

The Database Management System is a full stack web application designed to manage, analyze, and visualize crime related information. The platform enables users to search criminal records, monitor crime hotspots, view most wanted criminals, submit complaints, and stay updated with crime related news through an interactive and user friendly interface.
The project combines database management, crime analytics, geographical visualization, and modern web technologies to provide a centralized crime information system.

## Features

### Record Management

Store and manage criminal information in a structured database.
Search and retrieve criminal records efficiently.
View detailed profiles and crime related information.

### Crime Hotspot Visualization

Interactive crime maps powered by Leaflet.
Heatmap based visualization of crime dense regions.
Location based crime analysis for better insights.

### Most Wanted Section

Dedicated module for displaying most wanted criminals.
Quick access to criminal profiles and details.

### Complaint Management

Users can submit complaints through the platform.
Administrative view for complaint monitoring and management.

### Crime News Integration

Displays crime related news updates.
Automated news refresh using scheduled background jobs.

### Authentication and Security

User authentication system.
Secure API communication between frontend and backend.
Database driven access control mechanisms.

## Technology Stack

### Frontend

React.js
React Router DOM
Axios
Chart.js
React ChartJS 2
Leaflet
React Leaflet
Leaflet Heat
Leaflet Marker Cluster
React Toastify
CSS

### Backend

Node.js
Express.js
Axios
JWT Authentication
Bcrypt
Node Cron
CORS
Body Parser
Dotenv

### Database

MySQL

## System Architecture

Frontend built with React communicates with RESTful APIs developed using Express.js. The backend interacts with a MySQL database for storing and retrieving criminal records, complaints, and related information. Crime visualization is implemented using Leaflet maps and heatmap layers, while scheduled tasks automatically update crime related news.

## Database Design

The project includes a relational database schema designed to manage:

Records
Crime Details
Complaint Information
Most Wanted Data
User Information
Administrative Records
An Entity Relationship Diagram is included within the project for database design reference.

## Installation

### Clone Repository

git clone https://github.com/riyasol/CaseVault.git
cd CaseVault

### Backend Setup

cd backend
npm install
Create a .env file using the provided .env.example template and configure database credentials.
Start the backend server:
npm start

### Frontend Setup

cd frontend
npm install
npm start
The application will run locally and communicate with the backend API.

## Project Objectives

Provide a centralized criminal information management system.
Improve accessibility of crime related information.
Enable efficient criminal record searching.
Visualize crime patterns using geographical data.
Support complaint registration and monitoring.
Integrate real time crime related updates.

## Future Enhancements

Role based access control.
Advanced crime prediction and analytics.
Machine learning based crime trend analysis.
Mobile responsive enhancements.
Cloud deployment and scalability improvements.
Real time notification system.




