# My Blog App

This is a simple blog app built with **React**, **Vite**, and **Firebase**. It allows users to add and delete blog posts, with real-time updates using Firebase Firestore.

## Features
- **Add new blog posts**: Users can add posts with a title and content.
- **Delete blog posts**: Users can delete posts they no longer want.
- **Real-time updates**: Posts are stored in Firebase Firestore and updated in real-time.

## Technologies Used
- **React**: A JavaScript library for building user interfaces.
- **Vite**: A fast build tool for modern web development.
- **Firebase**: A backend-as-a-service platform for real-time database and authentication.
- **CSS**: Basic styling for a clean and responsive UI.

## How to Run

### Prerequisites
- Node.js (v16 or higher)
- npm (comes with Node.js)
- Firebase project (for Firestore)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/my-blog-app.git 


Navigate to the project folder:

bash
Copy
cd my-blog-app
Install dependencies:

bash
Copy
npm install
Set up Firebase:

Create a Firebase project at Firebase Console.

Copy your Firebase configuration and paste it into src/firebase.js.

Start the development server:

bash
Copy
npm run dev
Open the app:

Visit http://localhost:5173 in your browser.

Folder Structure
Copy
my-blog-app/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── AddPost.jsx
│   │   └── PostList.jsx
│   ├── firebase.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
