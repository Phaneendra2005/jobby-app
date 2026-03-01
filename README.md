# Jobby App

A modern job search web application built using React.  
This application allows users to log in, browse job listings, apply filters, search for jobs, and view detailed job descriptions.

**Live Demo:** [https://dashing-salmiakki-48a3e1.netlify.app/]

The project demonstrates routing, protected routes, API integration, state management, and responsive UI design.

---

## 🚀 Features

- Secure login authentication
- Protected routes using JWT token
- Fetch and display job listings from API
- Filter jobs by employment type and salary range
- Search functionality
- Detailed job description page
- Loading and failure state handling
- Responsive design

---

## 🛠 Tech Stack

- React
- React Router
- JavaScript (ES6+)
- REST APIs
- CSS / Styled Components

---

## 📂 Project Structure

src/
 ├── components/
 ├── App.js
 ├── index.js
public/
package.json

---

## 🔐 Authentication Flow

- User logs in using credentials
- JWT token is stored in cookies
- Protected routes restrict unauthorized access
- Logout removes authentication token

---

## 📡 API Handling

- Fetch jobs list
- Fetch job details by ID
- Implement loading, success, and failure states
- Error handling for API failures

---

## 💻 Installation & Setup

Clone the repository:

git clone https://github.com/Phaneendra2005/jobby-app.git

Navigate into the project:

cd jobby-app

Install dependencies:

npm install

Start the development server:

npm start

---

## 📸 Screenshots

Login Page:

![Picture1](https://github.com/user-attachments/assets/67fab583-d856-4a7e-8573-b83016a03ecc)

Home Page:

![Picture1](https://github.com/user-attachments/assets/70f67bb6-7e1c-4bd4-8ceb-8d54894f9435)

Jobs Page:

![Picture3](https://github.com/user-attachments/assets/dc370b49-fcee-4447-9501-626bedd40f45)

Job Details Page:

![Picture1](https://github.com/user-attachments/assets/7fa83db1-e3d3-49e3-8ea6-c062775cc7ec)


---

## 🎯 What I Learned

- Implementing protected routes in React
- Managing application state efficiently
- Handling API request lifecycle
- Structuring scalable React applications
- Writing reusable components

---

## 📌 Future Improvements

- Add pagination for jobs
- Implement saved jobs feature
- Improve UI/UX
- Integrate real backend authentication
