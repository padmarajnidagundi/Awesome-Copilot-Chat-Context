# Awesome-Copilot-Chat-Context
Awesome Copilot Chat Context — Awesome Copilot Chat Context 2025 Guide

# 🧠 GitHub Copilot 2025 — Chat Contexts Guide

Boost your productivity by providing **precise context** to GitHub Copilot Chat. This guide lists all available context types that developers and test engineers can use to supercharge AI assistance inside VS Code.

Each context type uses a `#` tag in the prompt to **explicitly include relevant code, data, or output** in your query.

---

## 📂 Project & File Structure Contexts

### `#Files`
Include specific files from your workspace.  
**Example:**  
`#Files Can you explain what authService.js is doing?`

---

### `#Folders`
Include all files within a specific folder.  
**Example:**  
`#Folders Summarize the logic in the utils/ folder.`

---

### `#Codebase`
Let Copilot search your full codebase to answer intelligently.  
**Example:**  
`#Codebase How is the access token generated in this app?`

---

## 🔍 Symbol & Code Selection Contexts

### `#Symbols` or `#sym`
Add a specific function, class, or variable symbol.  
**Example:**  
`#Symbols Refactor the validateUserInput function.`  
`#sym Improve the processOrder method's error handling.`

---

### `#Editor or terminal selection` or `#selection`
Include highlighted code or terminal output.  
**Example:**  
`#selection What does this selected code block do?`

---

### `#usage`
Show how a symbol or component is used throughout the codebase.  
**Example:**  
`#usage How is UserService used in the project?`

---

## 💻 Terminal & Runtime Contexts

### `#Terminal command output`
Include the output from your last terminal command.  
**Example:**  
`#Terminal command output Why did npm install fail?`

---

### `#terminalLastCommands`
Include history of recent terminal commands.  
**Example:**  
`#terminalLastCommands Why did my last few Git commands fail?`

---

## 🚨 Debugging & Test Contexts

### `#Problems`
Include a specific issue from the Problems panel (like ESLint/TypeScript).  
**Example:**  
`#Problems How can I fix this TS error in App.tsx?`

---

### `#Test failures` or `#testFailure`
Include details from failed test cases.  
**Example:**  
`#testFailure What’s causing the LoginForm test to fail?`

---

### `#findTestFiles`
Include all test files in a specific scope or directory.  
**Example:**  
`#findTestFiles Identify flaky tests in the checkout module.`

---

## 🌐 External Data & APIs

### `#fetch`
Include external HTTP request results (like API responses).  
**Example:**  
`#fetch Review the JSON structure from this API call.`

---

### `#searchResults`
Use results from a file, symbol, or global text search.  
**Example:**  
`#searchResults Which function handles user login?`

---

### `#vscodeAPI`
Include relevant parts of the VS Code API (for extension devs).  
**Example:**  
`#vscodeAPI How do I use window.showQuickPick properly?`

---

## ✅ Best Practices

- Use **multiple context tags** to give Copilot deeper insight.
- Combine `#Files`, `#Symbols`, and `#Test failures` for full bug investigations.
- Use `#usage` and `#searchResults` for deep refactoring and traceability.
- Tag output (`#Terminal command output`) right after running a command.

---

## 🚀 Example Prompt with Multiple Contexts

```txt
#Files #Symbols #Test failures 
Why is the login test failing in `auth.test.js`, and how can I fix the validateCredentials function?


## License

MIT License - feel free to use in your projects

## Contact

- Author: Padmaraj Nidagundi
- Email: padmaraj.nidagundi@gmail.com
- LinkedIn: https://www.linkedin.com/in/padmarajn/
- GitHub: https://github.com/padmarajnidagundi/Awesome-Copilot-Chat-Context/

