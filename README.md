# CodeResQ: User Guide

Welcome to **CodeResQ** — your smart coding assistant for detecting vulnerabilities, analyzing code complexity, and refactoring Python, TypeScript, and JavaScript code, all within Visual Studio Code!

---

## 🧑‍💻 What is CodeResQ?

**CodeResQ** helps you write better code by:

- **Finding Vulnerabilities:** Instantly highlights potential security issues in your code.
- **Analyzing Complexity:** Quickly checks how complex your code is, making it easier to maintain.
- **Refactoring Code:** Automatically improves your code for readability and performance, while preserving the original as comments.

---

## 🚀 Getting Started

### 1. Installation

- Open **Visual Studio Code**.
- Go to the **Extensions** panel (`Ctrl+Shift+X`).
- Search for **"CodeResQ"**.
- Click **Install**.

### 2. Activation

CodeResQ activates automatically when you open a Python, TypeScript, or JavaScript file.

---

## 🏃 How to Run the Project (Development)

If you want to run or develop CodeResQ locally:

1. **Clone the repository** (if you haven't already):
   ```sh
   git clone <your-repo-url>
   cd CodeResQ
   ```

2. **Install frontend dependencies**:
   ```sh
   npm install
   ```

3. **Compile the extension**:
   ```sh
   npm run compile
   ```

4. **Open in VS Code**:
   ```sh
   code .
   ```

5. **Launch the extension in a new Extension Development Host**:
   - Press `F5` in VS Code, or
   - Run:
     ```sh
     code --extensionDevelopmentPath=.
     ```

6. **Run the backend server**:
   ```sh
   cd backend
   pip install -r requirements.txt
   python app.py
   ```

---

## 🎯 Features

### 🔍 Analyze Selection

- Highlight any code (Python, TypeScript, or JavaScript).
- Click **"Analyze Selection"** at the top.
- See security vulnerabilities highlighted and explained.

### 📈 Check Complexity

- Select a function or code section.
- Click **"Check Complexity"**.
- Instantly get a summary of code maintainability.

### 🛠️ Refactor Code

- Select code to improve.
- Click **"Refactor Selection"**.
- See optimized code above, with the original safely commented below.

---

## 💡 Tips

- Use **"Analyze Selection"** regularly to keep your code secure.
- Check complexity often for maintainable code.
- Refactor confidently — your original code is always preserved as comments.

---

Happy Coding with CodeResQ!
