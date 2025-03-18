# Package and Process Management using Bash Script in Ubuntu

## **Objective**
This project helps learners understand basic **Linux package management and process handling** using **Bash scripts on Ubuntu**.

## **Prerequisites**
- A system running **Ubuntu**.
- Basic knowledge of **Linux commands**.
- Git installed.

## **Project Steps**

### **1. Clone the Repository**
```sh

git clone https://github.com/itvedant-devops-repo/Package-and-Process-Management-using-Bash-Script-in-Ubuntu.git
cd package-process-management
```

### **2. Implement Package Management Script (package_manager.sh)**

#### **The script should:**
- Check if a package is installed.
- Install it if not found.

```sh
dpkg -l | grep package_name
sudo apt-get install package_name -y
```

### **3. Implement Process Management Script (process_manager.sh)**
#### **The script should:**
- List all running processes.
- Allow the user to search for a process.
- Kill a process by entering its PID.

```sh
ps aux
ps aux | grep process_name
kill -9 process_id
```

### **4. Make Scripts Executable**

```sh
chmod +x package_manager.sh process_manager.sh

```

### **5. Test the Scripts**

- Run package_manager.sh and install/remove a package (e.g., curl).
- Run process_manager.sh and find/kill a process.
- Take screenshots of successful execution.

### **6. Submission Guidelines**
- Learners should submit a PDF on Wingz Portal containing: 
  - ✅ Screenshots of script execution.
  - ✅ Explanation of each script’s logic.
  - ✅ What did you learned?
