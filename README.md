

---

# SCHOOL MANAGEMENT SYSTEM

### Developed by Hunain Sualeh

A web-based application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This project was initially created for a UMT project but will also be used for personal experience and portfolio development.

[LinkedIn](https://www.linkedin.com/in/hunain-sualeh-3087701b9)

---

## About

The School Management System streamlines school management by facilitating class organization and enhancing communication between students, teachers, and administrators.

## Features

- **User Roles:** Admin, Teacher, and Student, each with specific functionalities.
- **Admin Dashboard:** Add students, teachers, create classes/subjects, manage accounts, and system settings.
- **Attendance Tracking:** Teachers can mark attendance and generate reports.
- **Performance Assessment:** Teachers can assign marks and feedback; students can track progress.
- **Data Visualization:** Interactive charts for students to visualize academic performance.
- **Communication:** Messaging between teachers and students to promote collaboration.

---

## Technologies Used

- **Frontend:** React.js, Material UI, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

---

## Installation


1. Open two terminals.

### Terminal 1: Setting Up Backend
   ```sh
   cd backend
   npm install
   npm start
   ```
   Create a `.env` file in the backend folder with the following content:
   ```sh
   MONGO_URL = mongodb://127.0.0.1/school
   ```
   (Replace with your MongoDB Atlas URL if applicable.)

### Terminal 2: Setting Up Frontend
   ```sh
   cd frontend
   npm install
   npm start
   ```

Navigate to `localhost:3000` in your browser. The backend API will run at `localhost:5000`.

---

## Deployment

- **Server:** Render (Backend)
- **Client:** Netlify (Frontend)

---

## AI Bot Installation (Optional)

For integrating AI bot functionality:
```sh
npm install @google/generative-ai
```

--- 

