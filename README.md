TaskPlanr

A simple and intuitive task-management web app built using HTML, CSS, and JavaScript.
TaskPlanr helps users create, organize, and track daily tasks with an easy-to-use interface and smooth interactions.

✨ Features
✅ Add & Manage Tasks

Create new tasks instantly

Mark tasks as completed

Delete tasks with one tap

🎨 Clean & Modern UI

Minimal layout for easy focus

Styled using custom CSS (located in the Style/ folder)

Smooth transitions and hover effects

📦 Local Storage Support

Tasks are saved in your browser

Data stays even after refresh or closing the tab

⚡ Fast & Lightweight

Pure HTML, CSS, and JavaScript

No external frameworks or libraries needed

📁 Project Structure
TaskPlanr/
│── index.html           # Main webpage
│── script.js            # Task logic + interactions
│── Style/               # CSS styles & assets
│── package.json         # Node setup (optional)
│── package-lock.json
│── README.md            # Documentation
│── .gitignore
│── node_modules/        # If installed (not required for frontend)
🚀 Getting Started
1. Clone the repository
git clone https://github.com/your-username/TaskPlanr.git
cd TaskPlanr
2. Open the app

Simply open index.html in any browser.

No installation or build steps required.

🧠 How It Works

TaskPlanr uses basic DOM manipulation to create, update, and remove tasks.
JavaScript stores tasks in localStorage, so your list persists across sessions.

Key functions handled in script.js:

addTask() → adds a new task

deleteTask(id) → removes a task

toggleCompletion(id) → marks a task done/not done

saveToLocalStorage() → persists data

📌 Future Enhancements

Planned improvements:

Categories / Tags

Deadlines & reminders

Drag-and-drop sorting

Dark / Light mode

Cloud sync & multi-device support

🤝 Contributing

Pull requests are welcome!
If you’d like to improve UI, add features, or optimize the code, feel free to open an issue.
