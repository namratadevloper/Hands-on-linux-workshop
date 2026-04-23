# 🐧 Linux Shell Scripting Basics

This project introduces **Linux Shell Scripting** in a beginner-friendly way.  

The goal is to help beginners understand:
- What scripting is  
- How shell scripting works  
- How to create and run scripts  
- How to automate real-world tasks  

---

## 🛠️ Step-by-Step Implementation

### 🔹 Step 1: Create File
```bash
vim script.sh
````

---

### 🔹 Step 2: Write Script

```bash
#!/bin/bash
echo "My first script"
```

---

### 🔹 Step 3: Give Permission

```bash
chmod +x script.sh
```

👉 Makes file executable

---

### 🔹 Step 4: Run Script

```bash
./script.sh
```

---

## 🎬 Example 1: Loop (Fun Example)

### 🎯 Problem

Print character names one by one.

### Characters:

* Raju
* Shyam
* Baburao

---

### 💻 Solution

```bash
#!/bin/bash

for name in Raju Shyam Baburao
do
  echo "Character: $name"
done
```

---

### 🧠 Theory

* `for loop` repeats task
* Each name is printed automatically

---

## ⚙️ Example 2: Automation Script (Real Use)

### 🎯 Problem

Can we automate daily system tasks?
👉 Yes ✅

---

### 💻 Solution

```bash
#!/bin/bash

echo "Starting system task..."

echo "Updating system..."
sudo apt update

echo "Creating folder..."
mkdir demo_folder

echo "Listing files..."
ls

echo "Task Completed!"
```

---

### 🧠 Theory

* Multiple commands in one file
* Runs automatically
* Saves time

---

## 🧪 Practice Questions

---

### 🔥 Question 1 (Basic Loop)

👉 Task:
Print numbers from 1 to 10

👉 Output:

```
1
2
3
...
10
```

---

### 🔥 Question 2 (File Automation)

👉 Task:

* Create a folder
* Go inside it
* Create 3 files
* List them

---

### 🔥 Question 3 (Real-World Task - Slightly Hard)

👉 Task:

* Create a folder called `project`
* Inside it create 5 files
* Display:
  👉 **"Setup completed successfully"**

👉 Hint:
Use loop + commands

---

## 🎯 Learning Outcome

After completing this project, students will:

* Understand scripting basics
* Know how to create and run scripts
* Automate simple Linux tasks
* Gain confidence in using terminal

---

## 🚀 Real-World Use

Shell scripting is used in:

* DevOps
* System administration
* Automation
* Deployment scripts

---

## 🛠 Future Enhancements

* Add variables
* Add if-else conditions
* Add advanced automation scripts
* Build mini projects

---

## 📜 Conclusion

👉 **Scripting is where Linux becomes powerful**

Because:

* You stop typing commands manually
* You start automating tasks

---

⭐ If you like this project, give it a star!

````
