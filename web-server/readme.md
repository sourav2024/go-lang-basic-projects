# Simple Go Web Server 🌐

This is a basic web server written in **Go (Golang)** that handles three routes:

- `/` → Serves an `index.html` with a message
- `/hello` → Responds with "hello"
- `/form` → Serves `form.html` to accept user input

---

## 🧩 Project Structure


---

## 📄 Description

This project demonstrates a minimal Go web server with basic route handling and HTML file serving.

### Routes

| Route     | Functionality                  |
|-----------|--------------------------------|
| `/`       | Displays "This is index file"  |
| `/hello`  | Displays "hello"               |
| `/form`   | Loads `form.html` for input    |

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/sourav2024/go-lang-basic-projects.git

cd web-server

go build 
go run main.go
