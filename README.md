# Assignment 5 - Personal Portfolio & Blog Website 

## 🎯 Objective
Build a personal portfolio and blog website using Next.js. This project will help you learn dynamic routing, API integration, authentication, state management, and deployment in a fun and practical way.

---

## 🔹 Features Breakdown

### 1️⃣ Public Pages (Accessible to All Users)

#### ✅ Home Page (/)
- Display your portfolio introduction (name, bio, and profile picture).
- Showcase your skills using icons or a skill bar.
- Highlight featured projects (static or fetched from an API).
- resume download button

#### ✅ Projects Page (/projects)
- List of projects with images, descriptions, and links.
- Clicking on a project opens a detailed page (/projects/[id]).

#### ✅ Blog Page (/blog)
- Display a list of blogs (fetched from an API or JSON file).
- Clicking on a blog opens a detailed blog page (/blog/[id]).

#### ✅ Contact Page (/contact)
- Simple contact form (name, email, message).
- Save messages in local storage or a database.

---

### 2️⃣ Admin Dashboard (Only for Logged-in Users)

#### ✅ Admin Login (/admin)
- Simple email-password authentication using JWT or localStorage.
- Only admins can access the dashboard.

#### ✅ Blog Management (/admin/blogs)
- Create, edit, or delete blog posts.
- Form to add a title, content, image, and category.

#### ✅ Project Management (/admin/projects)
- CRUD operations (Create, Read, Update, Delete) for projects.
- Upload project images and descriptions.

#### ✅ Message Management (/admin/messages)
- View messages submitted from the contact form.

---

## 🔹 Technical Requirements

### ✅ Frontend
- Next.js with TypeScript.
- Use Tailwind CSS for styling or any kind of ui library or framework.
- Implement dynamic routes (/projects/[id], /blog/[id]).
- Client-side authentication using localStorage or JWT.

### ✅ Database
- MongoDB.

### ✅ Authentication & Authorization
- JWT-based authentication for admin login.
- Role-based access control (Admin/User).

### ✅ Deployment
- Deploy the website on Vercel.
- Store projects and blogs in MongoDB

---

## 🎁 Bonus Features
- Use Next.js API routes (/api/...).
- Add a dark mode toggle.
- Use Markdown for blog content.
- Implement server-side rendering (SSR) for better SEO.
- Use SSR, SSG, and metadata based on the use case.
- Add animations using Framer Motion or any other animation library.

---

## 📜 Submission Requirements
- ✅ GitHub Repository with a well-documented README.md.
- ✅ Live Deployment Link (Vercel).
- ✅ Demo Video (3-5 minutes) explaining the features.


## Deadline:
- 60 marks: February 11, 2025 11.59 PM
- 50 marks: February 12, 2025 11.59 PM
- 30 marks: After February 12

# Important Note:
Plagiarism will not be tolerated. Ensure that the code you submit is your own work. Any instances of plagiarism will result in 0 Marks.
#### Good luck with your assignment! If you have any questions, feel free to reach out for clarification.
