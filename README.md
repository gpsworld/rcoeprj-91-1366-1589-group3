# AI based learning management system

> **Abstract** : Project aim is build a LMS(Learning Management System) in which we 
can assign assignment , experiment, lecture and lab video, we will store 
result of the students attendence,skills, experience, their projects, 
internship, jobs and all the neccesary requirement. we will build a such 
system using student all the data autimatically create portfolio for each 
student.that portfolio we can send to recuruiter or we can onboard 
recuireter on our platform.

### Project Members
1. GATE PRATHAMESH SANJYOT  [ Team Leader ] 
2. YEWALE VAIBHAV SANTOSH 
3. MOURYA SHIVAM ASHOK 
4. PARAKH KHUSHI ANIL 

### Project Guides
1. PROF. VIJAY SHANKER  [ Primary Guide ] 

### Deployment Steps
#### 🛠 Backend Setup

```bash
cd backend
npm install
cp .env.example .env
# Update MongoDB URI and JWT_SECRET in .env
npm start
```

#### 💻 Frontend Setup

```bash
cd frontend
npm install
cp .env.example .env
# Ensure VITE_API_URL matches your backend
npm run dev
```

---

### 🔑 .env File (Backend)

```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/lms
JWT_SECRET=your_secret_key_here
NODE_ENV=development
CORS_ORIGIN=http://localhost:5173
```

---


### Subject Details
- Class : BE (AI&DS) Div A - 2024-2025
- Subject : Major Project-2 (A) (MP 2 (A) (R19))
- Project Type : Major Project

### Platform, Libraries and Frameworks used
1. [NodeJS](https://nodejs.org)
2. [ExpressJS](https://expressjs.org)
3. [TypeScript.JS]([https://expressjs.org](https://www.typescriptlang.org/))


