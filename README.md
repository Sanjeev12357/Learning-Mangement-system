Sure, here's an improved README file for your Learning Management System (LMS) project:

# Study Notion 

## Overview

Study Notion  is a web-based Learning Management System (LMS) built using the MERN (MongoDB, Express.js, React, Node.js) stack. It provides a feature-rich environment for users to explore courses, manage profiles, and engage in learning activities. The project incorporates various functionalities, including user authentication, OTP generation, course catalog, instructor dashboards, and more.

## Screenshots

### Home Page
![Home Page](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/c03a2dc6-7cb5-46c3-9eb8-4bfa9e17ff42)

### Login/Sign Up Page
![Login/Sign Up Page](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/e7a28c1a-f4e0-474a-8800-b2b60d431384)

### OTP Generation Page
![OTP Generation Page](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/e49304f2-794b-4013-97a7-92871f75c60a)

### Profile Dashboard
![Profile Dashboard](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/6325d239-854e-4317-8192-63f247136f85)

### Course Catalog Page
![Course Catalog Page](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/4af619a2-5aeb-438f-8c5a-412b26764f78)

### Course Page
![Course Page](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/7eeefc95-0144-492a-a65b-e18a93e04c2d)

### Contact Us Page
![Contact Us Page](https://github.com/Sanjeev12357/Study-Notion-Clone/assets/124911392/16000fdd-faec-498b-9acb-6f1966e07053)

## Tech Stack

- React.js
- Node.js
- MongoDB
- Express.js

## Features

- OTP generation through Nodemailer for sign-up authentication.
- Categories of courses stored in the backend for administrators to manage.
- Three profiles (Student, Instructor, Admin) with unique interfaces.
- Razorpay integration for purchasing courses.
- Course rating and feedback section available only after purchasing the course.
- Contact Us form built using React Hook Forms and Node Mailer.

## Usage

1. Clone the repository.

```bash
git clone https://github.com/Sanjeev12357/Study-Notion-Clone.git
cd Study-Notion-Clone
```

2. Install dependencies.

```bash
cd client
npm install

cd ../server
npm install
```

3. Set up the environment variables. Create a `.env` file in the `server` directory and configure the following:

```env
PORT=your_server_port
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
MAILER_EMAIL=your_mailer_email
MAILER_PASSWORD=your_mailer_password
```

4. Run the application.

```bash
cd client
npm start

cd ../server
npm start
```

Visit `http://localhost:3000` to access the application.

Feel free to customize this README further based on your project's specific details and requirements.
