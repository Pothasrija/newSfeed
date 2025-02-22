# 📰 NewsFeed

## 📌 Project Overview
NewsFeed is a real-time news aggregation platform that fetches and displays news from various sources. Built using **React.js, Node.js, Express.js, and MongoDB**, it ensures a seamless and responsive user experience with **Redux state management**.

## 🚀 Features
- **Latest News Updates** from multiple sources
- **User Authentication** (Login & Signup)
- **Responsive UI** for all devices
- **State Management** using Redux
- **Optimized Performance**

## 📂 Project Structure
```
📦 newsFeed
 ┣ 📂 client        # React Frontend
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 components
 ┃ ┃ ┣ 📂 redux     # Redux state management
 ┃ ┃ ┣ 📜 App.js
 ┃ ┃ ┣ 📜 index.js
 ┃ ┣ 📜 package.json
 ┣ 📂 server        # Node.js Backend
 ┃ ┣ 📂 routes
 ┃ ┣ 📂 models
 ┃ ┣ 📂 controllers
 ┃ ┣ 📜 server.js
 ┃ ┣ 📜 package.json
 ┣ 📜 README.md
```

## 🛠️ Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **State Management:** Redux Toolkit  
- **Version Control:** Git & GitHub  

## 🚀 How to Run the Project

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/Pothasrija/newsFeed.git
cd newsFeed
```

### 🔹 Step 2: Install Dependencies
#### 📌 For Backend:
```bash
cd server
npm install
```
#### 📌 For Frontend:
```bash
cd client
npm install
```

### 🔹 Step 3: Configure Environment Variables
Create a **.env** file inside the `server` folder with the following content:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## 🔐 Test Credentials
Use these test credentials to log in:
```json
{
  "email": "testuser@example.com",
  "password": "SecurePassword123"
}
```

### 🔹 Step 4: Run the Project
#### 🚀 Start Backend Server
```bash
cd server
npm start
```
#### 🚀 Start Frontend
```bash
cd client
npm start
```
Now open **http://localhost:3000** in your browser. 🎉  

## 🛡️ Contributing  
Contributions are welcome! Follow these steps:
1. **Fork the repository**  
2. **Create a new branch** (`git checkout -b feature-branch`)  
3. **Commit your changes** (`git commit -m "Added a new feature"`)  
4. **Push to GitHub** (`git push origin feature-branch`)  
5. **Create a Pull Request**  

## 📜 License
This project is **open-source** and available under the MIT License.


