# 📂 Terminal Commands: cd, ls, pwd and dir

This guide helps you navigate the file system using terminal commands on **Linux/macOS** and **Windows**.

---

## 🔹 What does `cd` mean?
`cd` stands for **change directory**, which means you move to another folder (directory) in the computer’s file system.

### Common `cd` Commands and Examples

| Command           | Description |
|-------------------|-------------|
| `cd` or `cd ~`    | Go to the home directory (`/home/user` on Linux/macOS or `C:\Users\YourName` on Windows) |
| `cd ..`           | Move up one level |
| `cd ../..`        | Move up two levels |
| `cd ../../..`     | Move up three levels |
| `cd <foldername>` | Move down into a specific subfolder |
| `cd folder1/folder2` | Move down multiple levels at once |
| `cd ../folder2`   | Move to another folder on the same level |

📌 **Note:** `cd` only works for directories, not files. For example, `cd file.txt` will not work.

---

## 🔹 List Files and Folders
- **Linux/macOS:**
  - `ls` → shows all visible files and folders
  - `ls -la` → also shows hidden files (starting with `.`)

- **Windows CMD:**
  - `dir` → lists all files and folders

---

## 🔹 Show Current Directory
- `pwd` (**print working directory**) → prints the full path of the current directory.

Example:
```bash
/home/user/project
```

---

## ✅ Quick Reference

| Command           | Description |
|-------------------|-------------|
| `pwd`             | Show where you are right now |
| `cd` or `cd ~`    | Go to the home directory |
| `cd ..`           | Move up one level |
| `cd ../folder2`   | Move to a folder on the same level |
| `cd ../..`        | Move up two levels |
| `cd folder1/folder2` | Move down multiple levels |
| `ls`              | List files |
| `ls -la`          | List all files, including hidden ones |
| `dir` (Windows)   | List files and folders in Windows |

---

## 📝 Exercises

**Exercise 1:** Go to the home directory  
👉 You are in `/home/user/project/python/tester`.  
**Answer:**
```bash
cd ~
```

**Exercise 2:** Move up one level  
👉 You are in `/home/user/project/python/tester`.  
**Answer:**
```bash
cd ..
```

**Exercise 3:** Move up two levels  
👉 You are in `/home/user/project/python/tester`.  
**Answer:**
```bash
cd ../..
```

**Exercise 4:** Move to a folder on the same level  
👉 You are in `/home/user/project/python/folder1` and want to go to `folder2`.  
**Answer:**
```bash
cd ../folder2
```

**Exercise 5:** Move down multiple levels  
👉 You are in `/home/user` and want to go to `project/python/tester`.  
**Answer:**
```bash
cd project/python/tester
```

**Exercise 6:** Show all files, including hidden ones  
👉 You are in the project folder.  
**Answer:**
```bash
ls -la
```

**Exercise 7:** Show the current directory  
👉 You are unsure where you are.  
**Answer:**
```bash
pwd
```

**Exercise 8:** Try to navigate into a file (theoretical)  
👉 You have a file `report.pdf`.  
**Answer:**
No, `cd` only works on folders. You will get an error.

**Exercise 9:** Windows user  
👉 You want to list files in your current folder.  
**Answer:**
```cmd
dir
```

**Exercise 10:** Combine navigation and listing  
👉 You are in your home directory and want to list contents of `project/python`.  
**Answer:**
```bash
cd project/python && ls
```
(Windows CMD: `cd project\python && dir`)

---

## 💡 Best Practice Tips
1. Always use `pwd` first to check where you are.  
2. Then use `cd` to move to the correct location.

