# Fullstack Web System

This project is a fullstack web application designed to replicate the functionality and user experience of the Zhixue platform (zhixue.com). It includes both frontend and backend components, providing features for students and teachers, including login systems, score queries, score registration, and rankings.

## Project Structure

```
fullstack-web-system
├── client
│   ├── public
│   │   └── index.html
│   ├── src
│   │   ├── assets
│   │   │   └── images
│   │   ├── components
│   │   │   ├── Animation.tsx
│   │   │   ├── Login.tsx
│   │   │   └── Navbar.tsx
│   │   ├── views
│   │   │   ├── StudentDashboard.tsx
│   │   │   └── TeacherDashboard.tsx
│   │   ├── App.tsx
│   │   └── index.tsx
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
├── server
│   ├── src
│   │   ├── controllers
│   │   │   ├── authController.ts
│   │   │   ├── scoreController.ts
│   │   │   └── rankController.ts
│   │   ├── models
│   │   │   ├── User.ts
│   │   │   └── Score.ts
│   │   ├── routes
│   │   │   ├── authRoutes.ts
│   │   │   ├── studentRoutes.ts
│   │   │   └── teacherRoutes.ts
│   │   ├── services
│   │   │   └── scoreService.ts
│   │   └── app.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
└── README.md
```

## Features

- **User Authentication**: Secure login system for both students and teachers.
- **Student Dashboard**: A dedicated view for students to check their scores and rankings.
- **Teacher Dashboard**: A dedicated view for teachers to register scores and view rankings.
- **Score Management**: Functionality for querying and registering scores.
- **Ranking System**: Displays overall rankings, class rankings, and grade rankings.
- **Animations**: Smooth transitions and animations for a better user experience.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- TypeScript

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the client directory and install dependencies:
   ```
   cd client
   npm install
   ```

3. Navigate to the server directory and install dependencies:
   ```
   cd server
   npm install
   ```

### Running the Application

- Start the server:
  ```
  cd server
  npm start
  ```

- Start the client:
  ```
  cd client
  npm start
  ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License

This project is licensed under the MIT License. See the LICENSE file for details.# web.github.io
