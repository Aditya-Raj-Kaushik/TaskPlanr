# TaskPlanr

A simple and intuitive **task-management web app** built using **HTML, CSS, and JavaScript**.  
TaskPlanr helps users **create, organize, and track daily tasks** with an easy-to-use interface and smooth interactions.

---

# ✨ Features

## ✅ Add & Manage Tasks

- Create new tasks instantly  
- Mark tasks as completed  
- Delete tasks with one click  

## 🎨 Clean & Modern UI

- Minimal layout for better focus  
- Styled using custom CSS (located in the **Style/** folder)  
- Smooth transitions and hover effects  

## 📦 Local Storage Support

- Tasks are saved in your browser  
- Data persists even after refresh or closing the tab  

## ⚡ Fast & Lightweight

- Built with **pure HTML, CSS, and JavaScript**  
- No external frameworks or libraries required  

---

# 📁 Project Structure

```
TaskPlanr/
│
├── index.html           # Main webpage
├── script.js            # Task logic and interactions
├── Style/               # CSS styles and assets
├── package.json         # Node setup (optional)
├── package-lock.json
├── README.md            # Project documentation
├── .gitignore
└── node_modules/        # If installed (not required for frontend)
```

---

# 🚀 Getting Started

## 1. Clone the Repository

```
git clone https://github.com/your-username/TaskPlanr.git
```

## 2. Navigate to the Project Folder

```
cd TaskPlanr
```

## 3. Open the Application

Simply open **index.html** in any web browser.

No installation or build steps are required.

---

# 🧠 How It Works

TaskPlanr uses **JavaScript DOM manipulation** to create, update, and remove tasks dynamically.

Tasks are stored using **localStorage**, ensuring your task list persists across sessions.

### Key Functions (script.js)

```
addTask() → Adds a new task

deleteTask(id) → Removes a task

toggleCompletion(id) → Marks a task as completed / not completed

saveToLocalStorage() → Stores tasks in the browser
```

---

# 📌 Future Enhancements

Planned improvements include:

- Categories / Tags for tasks  
- Deadlines & reminders  
- Drag-and-drop task sorting  
- Dark / Light mode  
- Cloud sync and multi-device support  

---

# 🤝 Contributing

Pull requests are welcome!

If you would like to:

- Improve the UI
- Add new features
- Optimize the code

Feel free to **fork the repository and open a pull request**.

---

# 📜 License

This project is **open-source** and available under the **MIT License**.
