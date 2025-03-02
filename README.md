# Todo List App

A clean, minimalist Todo List application built with React and Vite.


## Features

- Add new tasks to your todo list
- Mark tasks as completed with a visual indicator
- Delete tasks you no longer need
- Persistent storage using localStorage
- Clean, modern UI

## Technologies Used

- React 19
- Vite 6
- JavaScript (ES6+)
- CSS3
- Local Storage API for data persistence

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/todo-list-app.git
cd todo-list-app
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Project Structure

```
todo-list-app/
├── public/              # Static assets
├── src/
│   ├── Components/      # React components
│   │   ├── Assets/      # Component-specific assets
│   │   ├── CSS/         # Component styles
│   │   ├── Todo.jsx     # Main Todo component
│   │   └── TodoItems.jsx # Individual todo item component
│   ├── App.jsx          # Root component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
└── vite.config.js       # Vite configuration
```

## Future Improvements

- Add task categories/tags
- Implement drag-and-drop reordering
- Add due dates and reminders
- Create filter options (All, Active, Completed)
- Add dark/light theme toggle
