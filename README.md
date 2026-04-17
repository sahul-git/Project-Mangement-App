# Project Management Application

A modern, full-featured project management web application built with React, designed to help teams collaborate efficiently on projects and tasks.

## 🚀 Features

- **Dashboard**: Overview of projects, tasks, and recent activity
- **Project Management**: Create, edit, and track projects with progress monitoring
- **Task Management**: Assign tasks, set priorities, track status, and manage deadlines
- **Team Collaboration**: Invite team members, manage roles, and workspace organization
- **Analytics**: Project analytics and performance insights
- **Calendar View**: Visual timeline of project milestones and deadlines
- **Real-time Updates**: Live notifications and activity feeds
- **Dark Mode**: Modern UI with dark/light theme support

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with hooks and concurrent features
- **Vite** - Fast build tool and development server
- **Redux Toolkit** - State management
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **Recharts** - Data visualization components
- **React Hot Toast** - Toast notifications
- **Date-fns** - Date utility library

### Backend/Database
- **Prisma** - Database ORM and schema management
- **PostgreSQL** - Primary database

### Development Tools
- **ESLint** - Code linting
- **Vite Plugin React** - React integration for Vite

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- PostgreSQL database

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/project-management.git
   cd project-management
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   DATABASE_URL="postgresql://username:password@localhost:5432/project_management"
   DIRECT_URL="postgresql://username:password@localhost:5432/project_management"
   ```

4. **Set up the database**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**

   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📖 Usage

### Development
```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
npm run lint     # Run ESLint
```

### Key Features Usage

- **Creating Projects**: Click "New Project" on the dashboard to create a new project
- **Managing Tasks**: Navigate to project details to add, edit, and track tasks
- **Team Management**: Use the Team page to invite and manage team members
- **Analytics**: View project progress and team performance in the analytics section

## 🏗️ Project Structure

```
src/
├── app/
│   └── store.js              # Redux store configuration
├── assets/
│   └── schema.prisma         # Database schema
├── components/               # Reusable UI components
│   ├── CreateProjectDialog.jsx
│   ├── ProjectCard.jsx
│   ├── StatsGrid.jsx
│   └── ...
├── features/                 # Redux slices
│   ├── themeSlice.js
│   └── workspaceSlice.js
├── pages/                    # Main application pages
│   ├── Dashboard.jsx
│   ├── Projects.jsx
│   ├── Team.jsx
│   └── ...
├── App.jsx                   # Main app component
├── main.jsx                  # Application entry point
└── index.css                 # Global styles
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- Built with modern React ecosystem
- UI inspired by contemporary design systems
- Icons provided by Lucide React
- Charts powered by Recharts

---

**Note**: This is a frontend application. You'll need to set up a backend API server to handle data persistence and real-time features.</content>
<parameter name="filePath">c:\Users\sahul\Downloads\project-management-main\project-management-main\README.md
