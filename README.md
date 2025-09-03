# 📝 Todos List (React Project)

A simple yet functional **React.js Todo List application** built as a learning project.  
This project demonstrates **React fundamentals** such as **components, props, state management, event handling, local storage, and React Router**.  
It also integrates **Bootstrap** for responsive design and styling.  

---

# 🔑 Important Features & Concepts Used

# ⚛️ React Fundamentals

 1- Functional Components → Each part of the app (Header, Footer, TodoItem, etc.) is broken into reusable components.

 2- Props → Data is passed between components (todos, onDelete, etc.).

 3- State Management with useState → Todos are stored in component state.

 4- useEffect Hook → Syncs todos with localStorage whenever they change.

 5- 🗑️ CRUD (Create + Delete) Operations

 6- AddTodo → Creates new todos with title + description.

 7- Delete Button → Removes individual todos from both state and localStorage.

#  💾 Local Storage Persistence

1- Todos are stored in localStorage so they remain after refresh.

2- Implements basic client-side persistence.

# 🌐 React Router

1- BrowserRouter, Routes, Route → Enables multiple pages (/ for Home, /about for About).

2- Shows how to structure a multi-page React app.

# 🎨 Bootstrap 5 Integration

1- Navbar (Header) and buttons use Bootstrap classes.

2- Ensures responsive design with minimal custom CSS.

# 🛡️ Clean Project Structure

1- Organized into src/Components folder.

2- Each feature has its own dedicated component file.

# ⚡ Performance & Extras (CRA Boilerplate)

1- reportWebVitals.js → Optional performance tracking.

2- setupTests.js & App.test.js → Testing setup included.

3- .gitignore → Ensures clean repo (ignores node_modules).

---

## 🚀 How It Works

1. On load, `App.js` checks `localStorage` for saved todos.  
2. **`AddTodo`** creates new todos, updating state + saving to `localStorage`.  
3. **`Todos`** maps todos, rendering **`TodoItem`** for each.  
4. Clicking **Delete** calls `onDelete(todo)`, updating state + removing from `localStorage`.  
5. **React Router** manages navigation between pages.  
6. **Header/Footer** remain consistent across routes.  

---

## 📦 Dependencies
- **React** – UI framework  
- **React Router DOM** – Routing/navigation  
- **Bootstrap 5** – Styling and responsive design  

---

## 📂 Project Structure

### **Root Directory**
- **`.gitignore`** → Ensures unnecessary files (like `node_modules`, logs, etc.) aren’t committed to GitHub.  
- **`package.json`** → Contains project metadata, dependencies (`react`, `react-router-dom`, `bootstrap`), and scripts (`start`, `build`, etc.).  
- **`package-lock.json`** → Auto-generated file that locks dependency versions for consistency.  

---

### **Public Folder (`/public`)**
Static assets served directly to the browser.

- **`index.html`** → The main HTML template. React mounts the app inside `<div id="root"></div>`.  
- **`favicon.ico`** → Browser tab icon.  
- **`logo192.png` / `logo512.png`** → App icons for Progressive Web App (PWA).  
- **`manifest.json`** → PWA metadata (app name, theme color, icons).  
- **`robots.txt`** → Provides crawling rules for search engine bots.  

---

### **Source Folder (`/src`)**
Where the React app logic lives.  

#### Files in `src/`
- **`index.js`** → Entry point. Renders `<App />` into `index.html`.  
- **`App.js`** → Main app component: manages state (`todos`), local storage, and routing.  
- **`App.css` / `index.css`** → Stylesheets.  
- **`logo.svg`** → Default React logo.  
- **`App.test.js`, `setupTests.js`** → Testing boilerplate.  
- **`reportWebVitals.js`** → Optional performance monitoring.  

#### Components (`/src/Components`)
- **`Header.js`** → Navbar with navigation links and optional search bar.  
- **`Footer.js`** → Footer displayed on all pages.  
- **`About.js`** → Static About page.  
- **`AddTodo.js`** → Form to add new todos.  
- **`Todos.js`** → Displays list of todos or message if empty.  
- **`TodoItem.js`** → Renders a single todo with delete functionality.  

---

# 👨‍💻 Developer  

 Muhammad Subhan – Full-Stack Developer (in progress)  

---

# 📜 License  

 This project is licensed under the Apache License 2.0 – you are free to use, modify, and distribute it under the terms of this license. See the LICENSE file for details.  

 ---
