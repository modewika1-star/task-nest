<div align="center">

# ✅ Task Manager

### Add tasks, organize their status, and manage your list in one place.

A vanilla JavaScript task manager with task creation, editing, deletion, status updates, filtering, and browser-based persistence.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![CSS](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=222)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

## ✨ Features

| Feature | Description |
| --- | --- |
| ➕ **Add tasks** | Create tasks with a name and description. |
| ✏️ **Edit tasks** | Update an existing task through an edit modal. |
| 🗑️ **Delete tasks** | Remove individual tasks. |
| 🔄 **Status updates** | Toggle tasks between completed and waiting. |
| 🎚️ **Filters** | View all tasks, completed tasks, or waiting tasks. |
| 🧹 **Clear all** | Remove all tasks from the current list. |
| 💾 **Local persistence** | Save task data in localStorage. |
| ⌨️ **Keyboard support** | Press Enter in the task fields to add a task. |

## 🛠️ Built with

- HTML5
- JavaScript (vanilla)
- Bootstrap 5
- Bootstrap Icons
- Browser localStorage

## ⚙️ Run locally

~~~bash
git clone https://github.com/modewika1-star/t12.git
cd t12/code
~~~

Open `index.html` in your browser. The project uses CDN links for Bootstrap and Bootstrap Icons, so an internet connection is needed for those assets.

## 🗂️ Project structure

~~~text
t12/
└── code/
    ├── index.html
    └── Js/
        ├── script1.js   # Main task manager
        └── script2.js   # Alternate people-table exercise (commented)
~~~

## 💾 Data

The task list is stored in localStorage under the `tasks` key. Changes remain in the same browser until site storage is cleared.

---

**Repository:** [modewika1-star/t12](https://github.com/modewika1-star/t12)
