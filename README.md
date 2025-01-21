# **Expense Tracker App using MERN stack**

## **Project Description**

The Expense Tracker App is a web-based application designed to assist users in tracking and managing their daily expenses.This system is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) to create a scalable, responsive, and user-friendly application.

---

## **Objectives**

1. Simplify expense tracking for individuals and organizations.
2. Provide detailed insights into spending patterns to enable better financial management.
3. Offer a platform for users to create, update, and delete expenses and categories.
4. Generate comprehensive reports based on user-defined time periods and categories.

---

## **Features**

- **User Authentication and Authorization**:  
  Allow users to sign up and log in to their personal accounts using secure authentication mechanisms. Implement role-based access control for administrative tasks.

- **Expense and Category Management**:  
  Enable users to create, update, and delete expense entries and categories. Track expenses by date, category, and description. Support attaching receipts or other relevant documents to expense entries.

- **Dashboard and Reporting**:  
  Provide a visual dashboard displaying an overview of the user's expenses, including total expenses, expenses by category, and recent transactions.  
  Generate reports based on selected date ranges and categories, displaying pie charts and bar graphs to help users understand their spending patterns.

- **Responsive User Interface**:  
  Ensure seamless usage on both desktop and mobile devices with an optimized and intuitive interface.
  Utilize React.js for building reusable UI components and managing state effectively.

---

  ## **Technical Architecture**

### Frontend:
- **React.js**: Used for building the user interface.
- **Libraries**: Incorporated `tsparticle` for stunning background effects, and other libraries like `unique-names-generator`, `react-datepicker`, and `moment`.
- **Responsive Design**: Implemented using CSS frameworks such as **Bootstrap** and **Material-Icons**.

### Backend:
- **Node.js and Express.js**: Built a RESTful API to handle client requests and serve as the backend.
- **Authentication and Authorization**: Utilized **JSON Web Tokens (JWT)** and middleware for secure endpoint protection.

### Database:
- **MongoDB**: Used for storing user data, expense entries, and categories as a NoSQL database.
- **Mongoose ORM**: Implemented for schema definition and validation.
  

---


## Run Locally

### Clone the project
```bash
git clone https://github.com/ankit-2706/Expense-Tracker-App.git
```
### Go to the project directory
```bash
cd Expense-Tracker-App
```
### Go to the frontend directory and Install dependencies
```bash
cd frontend
```
```bash
npm install
```
### Go to the backend directory and Install dependencies
```bash
cd backend
```
```bash
npm install
```
### Start the frontend server
```bash
npm start
```
### Start the backend server
```bash
npm run dev
```

---

## Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file in the `backend` folder.

Create a `config` folder and add a `config.env` file in it, then add all environment variables there:

- **MONGO_URL**: Your MongoDB Connection String
- **PORT**: Port number

---

## Tech Stack

**Client**: React, Redux, react-bootstrap, Material Icons, tsparticles  
**Server**: Node, Express  
**Database**: MongoDB  

---

## ScreenShots

![1](https://github.com/user-attachments/assets/d5b7e3f4-3a71-4016-aa83-175cf64b4099)
![2](https://github.com/user-attachments/assets/9704c44f-fc74-4966-96b3-c7527faa8f43)





