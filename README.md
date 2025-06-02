# ✅ React Todo App

Developed a React Todo app with REST API integration. Users can add, complete, delete, and filter tasks by status. Built with TypeScript, using Bulma for styling. The project is structured with reusable components and manages state via React hooks like useState, useEffect, and useCallback.

🔗 [Live Demo](https://github.com/MariiaKapustkina/to_do_app/)

## 🎨 Design Reference
This project was implemented based on Mate Academy tasks, without a public Figma file.

## 🛠️ Technologies Used
- ⚛️ React
- 🧠 TypeScript
- 📦 Vite
- 🧪 ESLint + Prettier
- 🌐 REST API

## 🚀 Getting Started
Follow these steps to run the project locally:
1️⃣ Clone the repository:
git clone https://github.com/your-username/project-name.git
cd project-name
2️⃣ Install dependencies:
npm install
or
yarn install
3️⃣ Start the development server:
npm start
## ✨ Features
📥 Toggle Todo Status
- Toggling the checkbox sends a request to update the completed status.
- Shows a loader overlay while waiting for the response.
- Displays an error message on API failure.
✅ Toggle All Todos
- "Toggle All" checkbox updates only the todos that need changes.
- Adds .active class if all todos are completed.
✏️ Edit Todo Title
- Double-click to edit.
- Save on Enter or onBlur.
- Cancel on Esc or if the title hasn't changed.
- Delete if the new title is empty.
- Loader shown during update requests.
- Error notifications if update or delete fails.
