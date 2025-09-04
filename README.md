# Task Management Dashboard

A modern, fully-featured task management dashboard built with React, TypeScript, and Tailwind CSS. This application provides a comprehensive solution for managing tasks, projects, and team collaboration with a beautiful, responsive interface.

## 🚀 Features

- **Dashboard Overview**: Real-time statistics and recent activity
- **Task Management**: Create, edit, and organize tasks with priority levels
- **Project Organization**: Color-coded projects with progress tracking
- **Team Management**: Assign tasks to team members and track performance
- **Calendar View**: Timeline view of upcoming deadlines and overdue tasks
- **Analytics**: Detailed insights into team productivity and project progress
- **Advanced Filtering**: Search and filter tasks by status, priority, and assignee
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Linting**: ESLint with TypeScript support

## 📦 Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd task-management-dashboard
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🏗️ Project Structure

```
src/
├── components/
│   ├── ui/                 # Reusable UI components
│   │   ├── Sidebar.tsx
│   │   ├── Header.tsx
│   │   ├── TaskCard.tsx
│   │   ├── ProjectCard.tsx
│   │   ├── StatCard.tsx
│   │   └── Modal.tsx
│   ├── forms/              # Form components
│   │   └── TaskForm.tsx
│   └── views/              # Page/view components
│       ├── Dashboard.tsx
│       ├── TasksView.tsx
│       ├── ProjectsView.tsx
│       ├── TeamView.tsx
│       ├── CalendarView.tsx
│       ├── AnalyticsView.tsx
│       └── SettingsView.tsx
├── hooks/                  # Custom React hooks
│   ├── useTasks.ts
│   └── useProjects.ts
├── data/                   # Mock data and constants
│   └── mockData.ts
├── types/                  # TypeScript type definitions
│   └── index.ts
├── App.tsx                 # Main application component
├── main.tsx               # Application entry point
└── index.css              # Global styles
```

## 🎨 Design System

### Colors
- **Primary**: Indigo (#6366F1)
- **Secondary**: Purple (#8B5CF6)
- **Accent**: Emerald (#10B981)
- **Success**: Green (#10B981)
- **Warning**: Yellow (#F59E0B)
- **Error**: Red (#EF4444)

### Typography
- **Font Family**: Inter (system font fallback)
- **Headings**: 120% line height
- **Body Text**: 150% line height
- **Font Weights**: 400 (normal), 500 (medium), 600 (semibold), 700 (bold)

### Spacing
- Consistent 8px spacing system
- Component padding: 16px, 24px, 32px
- Grid gaps: 16px, 24px, 32px

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px
- **Large Desktop**: > 1280px

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎯 Key Components

### Dashboard
- Overview statistics with visual indicators
- Recent tasks and project progress
- Quick access to all major features

### Task Management
- Kanban-style board with drag-and-drop (visual only)
- Priority levels (High, Medium, Low)
- Status tracking (To Do, In Progress, Completed)
- Due date management with overdue indicators

### Project Organization
- Color-coded project cards
- Progress tracking with visual progress bars
- Team member assignment
- Deadline management

### Team Management
- Team member profiles with avatars
- Role-based organization
- Activity status indicators
- Performance metrics

## 🎨 UI/UX Features

- **Smooth Animations**: Hover states and transitions
- **Visual Feedback**: Loading states and success indicators
- **Accessibility**: Keyboard navigation and screen reader support
- **Modern Design**: Clean, minimalist interface with subtle shadows
- **Micro-interactions**: Button hover effects and state changes

## 📊 Mock Data

The application includes comprehensive mock data for demonstration:
- 6 sample tasks with various statuses and priorities
- 4 sample projects with different progress levels
- 4 team members with roles and activity status
- Dashboard statistics and analytics data

## 🔮 Future Enhancements

- Real-time collaboration features
- File attachments for tasks
- Time tracking and reporting
- Integration with external tools (Slack, GitHub, etc.)
- Advanced project templates
- Custom dashboard widgets
- Dark mode support
- Offline functionality

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Design inspiration from modern task management tools
- Icons provided by [Lucide React](https://lucide.dev/)
- Stock photos from [Pexels](https://www.pexels.com/)
- Built with [Vite](https://vitejs.dev/) and [React](https://reactjs.org/)

---

**Note**: This is a demo application with mock data. For production use, integrate with a real backend service and database.
