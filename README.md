******TO SET UP AND RUN THE PROJECT******
1. **Extract** the ZIP file.  
2. **Install Prerequisites** → [Node.js](https://nodejs.org) and [MongoDB](https://www.mongodb.com/try/download/community).  
3. **Backend Setup:**  
   - Open **cmd/terminal**, go to `backend` folder → `cd path-to-extracted-folder/backend`  
   - Run `npm install` → Start MongoDB (`mongod`) → Start server (`npm start`).  
4. **Frontend Setup:**  
   - Open **new terminal**, go to `frontend` folder → `cd path-to-extracted-folder/frontend`  
   - Run `npm install` → Start React app (`npm start`).  
5. **Open Browser** → Go to `http://localhost:3000/` and use the app! 




**ASSUMPTIONS MADE DURING DEVELOPMENT**
1. **Database** → MongoDB is assumed to be running locally (`mongodb://localhost:27017/taskmanager`).  
2. **Frontend-Backend Communication** → Backend runs on `http://localhost:5000/`, and frontend on `http://localhost:3000/`.  
3. **Task Ownership** → Users can only modify or delete their own tasks.  




**TECHNOLOGIES AND LIBRARIES USED**
- **Frontend (React.js)** → Axios, React DOM, React Scripts  
- **Backend (Node.js)** → Express.js, Cors, Dotenv  
- **Database (MongoDB)** → Mongoose  
  




**CHALLENGES FACED AND HOW THEY WERE ADDRESSED**
1. **Frontend-Backend Communication** → Solved using **CORS**.  
2. **Database Management** → Solved using **Mongoose**.  


