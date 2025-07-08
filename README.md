# ProjectHub - Project Management System

🚀 **Live Demo**: [https://projectshub11.netlify.app/](https://projectshub11.netlify.app/)

ProjectHub is a full-stack Project Management Tool built with the MERN stack (MongoDB, Express.js, React, Node.js). It offers a clean, modern interface for organizing projects, managing team tasks, viewing reports, and collaborating effectively.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### Core Functionality
- 🔐 **User Authentication** - Secure login and registration system
- 📊 **Dashboard** - Overview with project and task statistics
- ✅ **Project Management** - Add, view, and delete projects
- 📝 **Task Management** - Create, update, and track tasks
- 📅 **Calendar Integration** - Schedule and view project timelines
- 📈 **Reports & Analytics** - Visual analytics and project insights
- 👥 **Team Management** - Manage team members and assignments

### User Experience
- 🎨 **Modern UI** - Beautifully themed pages with smooth animations
- 📱 **Responsive Design** - Optimized for mobile and desktop
- ⚙️ **Settings Panel** - Theme customization and profile management
- 🌐 **Real-time Updates** - Live project and task updates

## 🛠️ Tech Stack

### Frontend
- **React.js** - Component-based UI library
- **React Router DOM** - Client-side routing
- **Axios** - HTTP client for API requests
- **Bootstrap 5** - CSS framework for responsive design
- **Custom CSS** - Additional styling and animations

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variable management
- **body-parser** - Request body parsing middleware

### Deployment
- **Frontend**: Netlify
- **Backend**: Render or Railway
- **Database**: MongoDB Atlas

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas account)
- Git

### Clone the Repository
```bash
git clone https://github.com/Shubrat111204/Ethnus-Project-Management.git
cd Ethnus-Project-Management
```

### Backend Setup
1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the backend directory:
```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/projecthub
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

4. Start the backend server:
```bash
npm start
```

### Frontend Setup
1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the frontend directory:
```env
REACT_APP_API_URL=http://localhost:5000/api
```

4. Start the frontend development server:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## 📖 Usage

### Getting Started
1. **Register**: Create a new account or use existing credentials
2. **Dashboard**: View project overview and statistics
3. **Projects**: Create new projects and manage existing ones
4. **Tasks**: Add tasks to projects and track progress
5. **Calendar**: Schedule and view project timelines
6. **Reports**: Analyze project performance and team productivity
7. **Team**: Manage team members and their roles
8. **Settings**: Customize themes and update profile information

### Key Workflows
- **Project Creation**: Navigate to Projects → Add New Project
- **Task Management**: Select a project → Add/Edit tasks
- **Team Collaboration**: Use Team section to assign tasks and manage members
- **Progress Tracking**: Monitor progress through Dashboard and Reports

## 🔗 API Endpoints

### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/auth/profile` - Get user profile

### Projects
- `GET /api/projects` - Get all projects
- `POST /api/projects` - Create new project
- `GET /api/projects/:id` - Get project by ID
- `PUT /api/projects/:id` - Update project
- `DELETE /api/projects/:id` - Delete project

### Tasks
- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create new task
- `GET /api/tasks/:id` - Get task by ID
- `PUT /api/tasks/:id` - Update task
- `DELETE /api/tasks/:id` - Delete task

## 🌐 Deployment

### Frontend (Netlify)
1. Build the frontend:
```bash
cd frontend
npm run build
```

2. Deploy to Netlify:
   - Connect your GitHub repository
   - Set build command: `npm run build`
   - Set publish directory: `build`

### Backend (Render/Railway)
1. Create a new service on Render or Railway
2. Connect your GitHub repository
3. Set environment variables
4. Deploy the backend service

### Database (MongoDB Atlas)
1. Create a MongoDB Atlas account
2. Set up a cluster
3. Get connection string
4. Update `MONGODB_URI` in environment variables

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch:
```bash
git checkout -b feature/your-feature-name
```

3. Make your changes and commit:
```bash
git commit -m "Add your feature description"
```

4. Push to the branch:
```bash
git push origin feature/your-feature-name
```

5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Shubrat** - [GitHub Profile](https://github.com/Shubrat111204)

## 🙏 Acknowledgments

- Thanks to the MERN stack community for excellent documentation
- Bootstrap team for the responsive framework
- MongoDB team for the powerful database solution

---

⭐ If you found this project helpful, please give it a star on GitHub!
