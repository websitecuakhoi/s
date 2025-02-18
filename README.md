# Build Complete Canva Project

## 📌 Overview
This project is designed to empower users with a seamless and intuitive platform for creating and managing digital content. Inspired by Canva, it aims to bridge the gap between simplicity and functionality, allowing both casual users and professionals to design with ease. The ultimate goal is to provide an accessible, efficient, and visually engaging tool that enhances creativity and productivity.

## 🚀 Technologies Used
- **Frontend:** React.js, Functional Components, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Middleware for protected routes, User Register/Login
- **Cloud Storage:** Cloudinary for image uploads

## 🔥 Features
- **User Authentication**: Register and Login functionality with protected routes.
- **Design Tools**:
  - Move, Resize, Rotate elements
  - Add Text with opacity, padding, and font weight options
  - Image upload and manipulation
- **Data Storage**: Store user-generated content in MongoDB.
- **Responsive UI**: Built with Tailwind CSS for a modern and sleek user experience.

## 📂 Project Structure
```
project-folder/
│── controllers/       	   # Business logic
│── middleware/           # Middleware for authentication
│── models/               # Database models (MongoDB)
│── routes/               # API Routes
│── server.js             # Main entry point''
│── package.json          # Dependencies and scripts
│── .env                  # Environment variables
│── .gitignore            # Ignore unnecessary files
│
│── frontend/             # Frontend
│   ├── src/
│   │   ├── components/  # Functional components
│   │   ├── pages/       # Page views
│   │   ├── hooks/       # Custom hooks
│   │   ├── context/     # Global state management
│   │   ├── assets/      # Images, icons
│   │   └── App.js       # Main React App
```

## 🛠 Installation & Setup
### 1. Clone the repository
```sh
git clone https://github.com/yourusername/canva-project.git
cd canva-project
```
### 2. Install dependencies
#### Backend Setup
```sh
cd backend
npm install
```
#### Frontend Setup
```sh
cd frontend
npm install
```
### 3. Set up environment variables
Create a `.env` file in both `backend/` and `frontend/` directories and configure necessary variables such as database URI, Cloudinary API keys, etc.

### 4. Start the application
#### Run Backend Server
```sh
cd backend
npm start
```
#### Run Frontend
```sh
cd frontend
npm start
```
The application will be accessible at `http://localhost:3000`

## 📌 Contributing
Feel free to fork this repository and submit pull requests with improvements and new features.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---
### 🌟 Happy Coding! 🚀
