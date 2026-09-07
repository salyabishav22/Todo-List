# 📝 Modern To-Do List Application

A fully-featured, responsive task management web application built with vanilla HTML5, CSS3, and JavaScript (ES6+). No backend or database required—just open the HTML file in your browser!

![Responsive Design](https://img.shields.io/badge/responsive-yes-brightgreen)
![Dark Mode](https://img.shields.io/badge/dark%20mode-supported-blue)
![localStorage](https://img.shields.io/badge/localStorage-enabled-success)
![License](https://img.shields.io/badge/license-MIT-orange)

---

## ✨ Features

### Core Functionality
- ✅ **Add Tasks** - Create new tasks with a simple input
- ✅ **Edit Tasks** - Modify task text at any time
- ✅ **Delete Tasks** - Remove tasks with confirmation
- ✅ **Mark Complete** - Check off completed tasks with visual feedback
- ✅ **Task Priority** - Set Low, Medium, or High priority for each task
- ✅ **Due Dates** - Assign due dates to tasks with date picker
- ✅ **Overdue Detection** - Automatic overdue status for past due dates

### Organization & Filtering
- 🔍 **Search Bar** - Search tasks by text in real-time
- 📊 **Filters** - View tasks by status:
  - All tasks
  - Active (incomplete) tasks
  - Completed tasks
- 📈 **Statistics** - Display total and completed task counts

### User Experience
- 💾 **LocalStorage** - Tasks persist after page refresh
- 🌙 **Dark Mode** - Toggle between light and dark themes
- 📱 **Mobile Friendly** - Fully responsive design for all screen sizes
- ✨ **Smooth Animations** - Polished transitions and interactions
- 🎨 **Modern UI** - Clean, professional interface with visual feedback
- 🗑️ **Clear Completed** - Bulk delete all completed tasks
- 🔔 **Toast Notifications** - User feedback for all actions

### Developer-Friendly
- 📝 **Clean Code** - Well-commented, organized JavaScript
- ♿ **Accessible** - Keyboard navigation and ARIA labels
- ⚡ **Lightweight** - No dependencies, fast loading
- 🐛 **Error Handling** - Comprehensive validation and error messages

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and form elements
- **CSS3** - Flexbox, CSS Grid, custom properties, animations
- **JavaScript ES6+** - Modern ES6 features (classes, arrow functions, destructuring)
- **LocalStorage API** - Client-side data persistence
- **Web APIs** - Date, JSON, DOM manipulation

---

## 📦 Project Structure

```
todo-list/
├── index.html          # HTML structure and layout
├── style.css           # Styling, animations, themes
├── script.js           # Application logic and state management
├── README.md           # Project documentation
└── .gitignore          # Git ignore rules
```

---

## 🚀 How to Run

### Option 1: Local File (Simplest)
1. **Download or Clone** this repository
2. **Open `index.html`** directly in your web browser
3. That's it! The app is ready to use.

### Option 2: Using Python (if you have Python installed)
```bash
cd todo-list
python3 -m http.server 8000
# Then open http://localhost:8000 in your browser
```

### Option 3: Using Node.js HTTP Server
```bash
cd todo-list
npx http-server
# Then open http://localhost:8080 in your browser
```

---

## 📚 Usage Guide

### Adding a Task
1. Type your task in the input field
2. Select a priority level (Low, Medium, High)
3. Optionally set a due date
4. Click the "Add" button or press Enter

### Managing Tasks
- **Complete Task** - Click the checkbox next to the task
- **Edit Task** - Click the "Edit" button and modify the text
- **Delete Task** - Click "Delete" and confirm in the modal
- **Clear Completed** - Remove all completed tasks at once

### Filtering & Searching
- Use filter buttons to view: All, Active, or Completed tasks
- Use the search bar to find tasks by keyword
- Combine filters and search for precise results

### Theme Toggle
- Click the moon/sun icon (top right) to switch between light and dark modes
- Your theme preference is saved automatically

---

## 💾 Data Persistence

All tasks are automatically saved to your browser's **localStorage**:
- Tasks persist across browser sessions
- Each browser/device has its own task list
- Clear browser storage to reset the app
- No account or server needed

---

## 🎨 Color Scheme

### Light Mode
- Background: White
- Text: Dark Gray
- Accent: Blue
- Priority Colors: Green (Low), Orange (Medium), Red (High)

### Dark Mode
- Background: Dark Gray
- Text: White
- Accent: Light Blue
- Priority Colors: Same as light mode

---

## 📱 Responsive Breakpoints

- **Desktop** (1200px+): Full layout with all features
- **Tablet** (768px - 1199px): Optimized grid layout
- **Mobile** (480px - 767px): Single column, adjusted spacing
- **Small Mobile** (below 480px): Minimal layout, touch-friendly buttons

---

## ♿ Accessibility Features

- Keyboard navigation support
- Focus indicators on interactive elements
- ARIA labels for screen readers
- High contrast text
- Semantic HTML structure
- Reduced motion preferences respected

---

## 🎯 Future Improvements

Potential features for future versions:

- 📅 **Calendar View** - Display tasks in a calendar format
- 👥 **Task Sharing** - Share task lists via URL
- 🏷️ **Tags/Categories** - Organize tasks by category
- 🔄 **Recurring Tasks** - Set tasks to repeat daily/weekly
- 📱 **Progressive Web App** - Install as an app on mobile
- 🔐 **Data Export** - Export tasks as JSON or CSV
- 🌍 **Multiple Languages** - Internationalization support
- 📊 **Analytics** - Task completion statistics and charts
- 🎯 **Subtasks** - Break tasks into smaller steps
- ⏱️ **Pomodoro Timer** - Built-in time tracking
- 💬 **Comments** - Add notes to tasks
- 🔗 **Links** - Attach URLs to tasks

---

## 🐛 Known Limitations

- Tasks are stored locally (per browser)
- No cloud synchronization
- No user accounts
- No task attachments
- Mobile clipboard sharing not implemented

---

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

### Development Tips
1. Follow the existing code style
2. Add comments for complex logic
3. Test on multiple devices
4. Update documentation with changes
5. Keep dependencies at zero

---

## 📄 License

This project is licensed under the **MIT License** - feel free to use it for personal or commercial projects.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 📞 Support & Issues

If you encounter any issues or have suggestions:

1. Check the browser console for errors (F12)
2. Verify localStorage is enabled in your browser
3. Try clearing browser cache
4. Test in a different browser
5. Open an issue on GitHub with details

---

## 🎉 Getting Started Checklist

- [x] HTML structure with semantic tags
- [x] Responsive CSS with mobile-first approach
- [x] Modern JavaScript with classes
- [x] LocalStorage integration
- [x] Dark/Light theme support
- [x] Search and filter functionality
- [x] Task priority system
- [x] Due date management
- [x] Confirmation dialogs
- [x] Toast notifications
- [x] Smooth animations
- [x] Accessibility features
- [x] Error handling
- [x] Cross-browser compatibility
- [x] Comprehensive documentation

---

## 🌟 Star History

If you like this project, please give it a star! ⭐

---

## 💻 Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Latest 2 versions |
| Firefox | ✅ Latest 2 versions |
| Safari  | ✅ Latest 2 versions |
| Edge    | ✅ Latest 2 versions |
| Opera   | ✅ Latest 2 versions |

---

**Happy task managing! 🚀**

*Last updated: 2024*
*Made with ❤️ by developers, for developers*
