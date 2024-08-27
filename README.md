# StudySphere - E-learning Platform
  
- StudySphere is an e-learning platform designed to provide a seamless  and interactive learning experience for students, making education more accessible and engaging. It also serves as a platform for instructors to showcase their expertise and connect with learners across the globe.

## Table of Contents 

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)


## Features

- **Authentication and Authorization**: Secure user authentication and authorization using JWT (JSON Web Tokens).
- **Interactive Learning**: Engaging content and interactive features for students.
- **Instructor Platform**: Tools and features for instructors to create and manage courses.
- **Technologies Used**: MongoDB, Express, React, Node.js, TailwindCSS.

## Technologies Used

- **Backend**: Node.js, Express, MongoDB
- **Frontend**: React, TailwindCSS
- **Authentication**: JWT (JSON Web Tokens)

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14.x or later)
- MongoDB (v4.x or later)

### Steps

1. **Clone the repository:**

   ```js
   git clone https://github.com/yourusername/StudySphere.git
   cd StudySphere
   ```

2. **Backend Setup:**

- Navigate to the backend directory:
  ```js
  cd backend
  ```
- Install the dependencies:

  ```js
  npm install
  ```

- Create a .env file and add your environment variables:

env
```js
MAIL_HOST = 
MAIL_USER = 
MAIL_PASS = 

REACT_APP_BASE_URL =

JWT_SECRET = 
FOLDER_NAME = 

RAZORPAY_KEY = 
RAZORPAY_SECRET = 

CLOUD_NAME = 
API_KEY = 
API_SECRET = 

MONGODB_URL = 
PORT = 4000
```

# Frontend Setup:

- Navigate to the frontend directory:

```js
cd ../frontend
```

-  Install the dependencies:
```js
npm install
```

-  Start the frontend development server:
```js
bash
npm start
```
# Usage

### For Students
- Sign Up/Login: Create an account or log in using your credentials.
- Browse Courses: Explore the available courses.
- Enroll and Learn: Enroll in courses and start learning with interactive content.
### For Instructors
- Sign Up/Login: Create an instructor account or log in.
- Create Courses: Use the platform tools to create and manage courses.
- Engage with Students: Interact with students through course content and discussions.



