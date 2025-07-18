# 📝 Redux Todo List

A simple and modern Todo List application built using **React** and **Redux Toolkit**. It demonstrates how to manage global state using Redux and perform CRUD operations on todo items.

## 🚀 Features

- Add new todo items
- Update existing todos
- Delete todos
- Keyboard support (Enter to update)
- Auto-focus on input when updating
- Global state management using Redux Toolkit
- Clean, responsive UI using Tailwind CSS

## 🛠️ Tech Stack

- React
- Redux Toolkit
- Tailwind CSS
- Vite

## 📂 Folder Structure

src/
├── app/
│ └── store.js # Redux store configuration
├── components/
│ └── AddTodo.jsx # Input form for adding todos
│ └── Todos.jsx # Renders and manages todo list
├── features/
│ └── todo/
│ └── todoSlice.js # Redux slice for todo logic
└── main.jsx # React root


## 🚧 Installation and Running Locally

```bash
# Clone the repository
git clone https://github.com/your-username/redux-todo-list.git
cd redux-todo-list

# Install dependencies
npm install

# Start the development server
npm run dev

#Open your browser and navigate to http://localhost:5173

✨ Learnings

    How to use createSlice from Redux Toolkit

    Immutability in reducers

    useSelector and useDispatch hooks

    Managing form inputs and focus with useRef

📌 Future Improvements

    Persist todos in localStorage

    Add due dates or priorities

    Mark todos as completed

    Add filters (All, Completed, Incomplete)

📄 License

This project is open-source and free to use.

✍🏻Author
Himanshu Singh