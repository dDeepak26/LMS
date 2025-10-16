# 📚 Learning Management System (LMS)

A full-stack Learning Management System where **Instructors** can create and manage courses, and **Students** can enroll, track progress, and bookmark courses. The platform supports uploading course images and lecture videos via Cloudinary.

---

## 📂 Repositories

- **Frontend Repo:** [GitHub Link](https://github.com/dDeepak26/LMS-Frontend.git)
- **Backend Repo:** [GitHub Link](https://github.com/dDeepak26/LMS-Backend.git)

---

## 🛠 Tech Stack

### **Frontend**
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Mantine](https://mantine.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Cloudinary SDK](https://cloudinary.com/documentation/react_integration)

### **Backend**
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Cloudinary](https://cloudinary.com/)
- [Multer](https://github.com/expressjs/multer) (for file uploads)

---

## ✨ Features

### **Authentication & Authorization**
- Secure login and registration
- JWT-based authentication
- Role-based access for:
  - **Instructor**
  - **Student**

---

### **Instructor Features**
- **Course Management**: Create, update, delete courses
- **Add Lectures**: Add multiple lectures to a course (video + description)
- **Media Upload**: Upload course thumbnails and lecture videos to **Cloudinary**
- **Enrolled Students**: View list of students enrolled in each course

---

### **Student Features**
- **Course Listing**: Browse and view available courses
- **Enroll in Course**: Join any course with one click
- **Track Progress**: System tracks which lectures are completed per user
- **Bookmark Courses**: Save courses for later in a dedicated bookmarks section
- **Watch Lectures**: Access course content including video lectures
