# Employee Task Tracker

A modern, responsive web application for managing employee tasks with real-time filtering and persistent storage.

## 🚀 Features

- View all employees and their assigned tasks
- Dashboard with task statistics (total, completed, in progress, pending)
- Filter tasks by status (All, Pending, In Progress, Completed)
- Add new tasks to employees
- Update task status with dropdown
- **Bonus**: LocalStorage persistence - data survives page refreshes
- Fully responsive design

## 🛠️ Tech Stack

- **Framework**: React 18 with Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **State Management**: React Hooks (useState, useEffect)
- **Data Persistence**: LocalStorage API

## 📦 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Steps

1. Clone the repository:
```bash
git clone <your-repo-url>
cd employee-task-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open your browser and navigate to:
```
http://localhost:5173
```

## 🎯 How to Use

1. **View Dashboard**: See summary statistics at the top
2. **Filter Tasks**: Click filter buttons to view tasks by status
3. **Add Task**: Click "Add Task" button, fill form, and submit
4. **Update Status**: Use dropdown next to each task to change status
5. **Data Persistence**: All changes are saved automatically to LocalStorage

## 📊 Mock Data Structure
```json
{
  "employees": [
    {
      "id": 1,
      "name": "Alice Johnson",
      "role": "Frontend Developer",
      "tasks": [
        { "id": 101, "title": "Build login page", "status": "Completed" }
      ]
    }
  ]
}
```

## 🎨 Design Decisions

- **Color Scheme**: Indigo/purple gradient for modern feel
- **Status Colors**: 
  - Green for Completed
  - Blue for In Progress
  - Yellow for Pending
- **Responsive Grid**: 1 column (mobile) → 2 columns (desktop)
- **Card Design**: Gradient headers with clean white bodies

## 🔮 Future Enhancements

- Search functionality
- Task deletion
- Employee management (add/edit/delete)
- Due dates for tasks
- Task priority levels
- Export to CSV

## 📸 Screenshots

[Add screenshots here]

## 🤝 Assumptions & Limitations

- No backend integration (frontend-only with mock data)
- Task IDs are auto-generated sequentially
- No user authentication
- LocalStorage has 5-10MB limit (sufficient for this use case)
- Works best on modern browsers with LocalStorage support

## 👨‍💻 Author

[Your Name]

## 📄 License

MIT
