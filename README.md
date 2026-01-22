<div align="center">

# 📝 Node.js Todo Application

**A sleek, full-featured CRUD Todo application built with Node.js, Express.js, and Bootstrap**

[![Node.js](https://img.shields.io/badge/Node.js-18.x+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Express](https://img.shields.io/badge/Express.js-5.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Usage](#-usage) • [API Endpoints](#-api-endpoints) • [Tech Stack](#-tech-stack)

</div>

## 🌟 Features

- ✅ **Full CRUD Operations** - Create, Read, Update, and Delete todos
- 🎨 **Responsive UI** - Built with Bootstrap 5 for mobile-friendly design
- ⚡ **Real-time Updates** - Instant feedback with server-side rendering
- 🔧 **Simple & Clean** - Minimal dependencies, easy to understand and extend
- 🌐 **Web-based Interface** - Accessible through any modern browser

## 🎬 Demo

<div align="center">

https://github.com/user-attachments/assets/demo.gif

*Manage your todos with ease - Add, Edit, and Delete tasks in real-time*

</div>

## 🚀 Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18.x or higher)
- npm or yarn package manager

### Quick Setup

```bash
# Clone the repository
git clone <repository-url>
cd Node-PR-02-ToDo

# Install dependencies
npm install

# Start the application
npm start
```

The application will be available at: `http://localhost:7777`

## 💡 Usage

1. **Add a Todo**
   - Enter your task in the input field
   - Click "Submit" to add it to your list

2. **Edit a Todo**
   - Click the "Edit" button next to any todo
   - Modify the content in the edit form
   - Click "Update User" to save changes

3. **Delete a Todo**
   - Click the "Delete" button next to any todo
   - The task will be removed immediately

## 🛠️ API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/` | Display all todos |
| `POST` | `/create` | Create a new todo |
| `GET` | `/edit/usr/:id` | Show edit form for specific todo |
| `POST` | `/update?id=:id` | Update existing todo |
| `GET` | `/delete/usr/:id` | Delete a todo |

## 🏗️ Tech Stack

- **Backend**: [Node.js](https://nodejs.org/) + [Express.js](https://expressjs.com/)
- **Template Engine**: [EJS](https://ejs.co/)
- **Frontend Framework**: [Bootstrap 5](https://getbootstrap.com/)
- **Data Storage**: In-memory array (users)

## 📁 Project Structure

```
Node-PR-02-ToDo/
├── index.js          # Main application file
├── package.json      # Project dependencies
├── views/
│   ├── index.ejs     # Main todo list page
│   └── edit.ejs      # Edit todo page
└── README.md         # This file
```

## 🔧 Development

### Available Scripts

```bash
# Start development server
npm start

# Run with nodemon for auto-reload (install nodemon first)
nodemon index.js
```

### Environment Variables

Create a `.env` file to customize the port:

```env
PORT=7777
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Pratham**

Feel free to reach out if you have any questions or suggestions!

---

<div align="center">

**Made with ❤️ using Node.js and Express**

[⬆ Back to Top](#-nodejs-todo-application)

</div>
