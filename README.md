# 📘 Dictionary Application in C

A console-based **dictionary app** developed in **C language** that allows users to insert, search, and view words with their meanings using a **Binary Search Tree (BST)** structure.

## 🚀 Features

- ✅ Add a new word and its meaning  
- 🔍 Search for a word and view its meaning  
- 📚 View all words in sorted order (in-order traversal of BST)  
- ❌ Handles duplicate entries gracefully  
- 🌳 Utilizes Binary Search Tree for efficient search and insertion  

## 🧠 How It Works

- Words are stored in a BST based on **lexicographical order**
- Duplicate entries are detected and rejected
- In-order traversal is used to display all words in sorted order

## 🛠️ Technologies Used

- **C Language**  
- **Structures (struct)** for node representation  
- **Dynamic Memory Allocation** (`malloc`)  
- **Binary Search Tree** for efficient word management  
- **Standard I/O** for user interaction

## 💻 How to Run

1. Save the code in a file, e.g., `dictionary.c`
2. Compile the program using a C compiler:
   ```bash
   gcc dictionary.c -o dictionary
