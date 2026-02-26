
# Video Upload, Sensitivity Processing & Streaming App

## Setup Backend
cd backend
npm install
cp .env.example .env
npm start

## Setup Frontend
cd frontend
npm install
npm run dev

Backend runs on http://localhost:5000
Frontend runs on http://localhost:5173

This project is a full-stack Video Upload, Sensitivity Processing, and Streaming Application built using Node.js, Express, MongoDB, React, and Vite.

It allows users to securely upload videos with proper file validation and metadata handling.

The system performs automated sensitivity analysis and classifies videos as safe or flagged.

Real-time processing updates are provided using Socket.io for a better user experience.

Videos are streamed efficiently using HTTP Range Requests with 206 Partial Content support.

The application follows a multi-tenant architecture where users can access only their own content.

Role-Based Access Control (RBAC) is implemented with Viewer, Editor, and Admin roles.

JWT-based authentication ensures secure access to protected routes and APIs.

The frontend provides a responsive dashboard, upload interface, and integrated video player.

The project demonstrates scalable architecture, clean code structure, and secure video management practices.
