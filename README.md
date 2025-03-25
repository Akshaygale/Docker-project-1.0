# 🚀 Docker Project 1.0  

## 📌 Purpose  
This project demonstrates **how to host a React application using Docker and Docker Compose**, ensuring a seamless and reproducible deployment process.  

## 🛠️ Technologies Used  
- **Docker**: To containerize the application  
- **Docker Compose**: To manage multi-container setup  
- **Git & GitHub**: For version control and collaboration  

---

## 🐳 Docker Setup  
This project includes **two Dockerfiles**:  
1️⃣ **Frontend (`frontend/Dockerfile`)** → Runs the React app on **port 3000**  
2️⃣ **Backend (`backend/Dockerfile`)** → Runs the API service on **port 5000**  

---

# 🚀 Steps to Create the React App and Backend  

### 1️⃣ **Create the Project Structure**  
Set up the **frontend** and **backend** directories for the application.  

### 2️⃣ **Create the React App (Frontend)**  
- Initialize a React app inside the **frontend** directory.  
- Configure the necessary dependencies.  

### 3️⃣ **Create Dockerfile for Frontend**  
- Write a **Dockerfile** to containerize the React app.  
- Expose **port 3000** for frontend access.  

### 4️⃣ **Initialize a Node.js Project (Backend)**  
- Navigate to the `backend` directory and initialize a Node.js project using the following command:  

      npm init -y


5️⃣ ***Install Express***

    npm install express cors

6️⃣ Create server.js (Backend Code)
Create a file server.js inside the backend folder and add the script:

7️⃣ Create Dockerfile for Backend
Inside the backend folder, create a Dockerfile:

🐳 

8️⃣ Create docker-compose file
Now, in the root directory (docker-project/), create a docker compose file to run both services:


  🚀 **Running the Application**
  
*Start Both Services*

Since the Docker Compose file is named file.yaml, use the following command to build and run the application:

    docker-compose -f file.yaml up -d --build

***Access the Application***

Open http://localhost:3000/ to view the React app.

The backend API is running at http://localhost:5000/.

Stop the Containers
To stop the containers, run:

      docker-compose down

**📝 NOTE
📌 All required files and scripts are uploaded in the same repository.**
