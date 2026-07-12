# Project 4 – Linux Users & Permissions

## Objective

- Learn how Linux controls access to files through users, groups, ownership, and permissions.
- Practice viewing and changing permissions while following the Principle of Least Privilege.

---

## Environment

- Ubuntu Desktop LTS
- Oracle VirtualBox
- Bash Terminal

---

## Skills Practiced

- Identifying the current Linux user
- Viewing the current directory
- Reading Linux permission strings
- Checking file ownership
- Creating practice files
- Changing permissions with `chmod`
- Understanding ownership with `chown`
- Using `sudo` for administrative tasks
- Applying the Principle of Least Privilege

---

## Linux Commands Used

| Command | Purpose |
|---|---|
| `whoami` | Show the current logged-in user |
| `pwd` | Show the current working directory |
| `ls -l` | View file ownership and permissions |
| `ls -la` | View all files, including hidden files |
| `touch mission4.txt` | Create a practice file |
| `chmod a-w mission4.txt` | Remove write access from all users |
| `chmod u+x mission4.txt` | Add execute permission for the owner |
| `chown` | Change file ownership |
| `sudo` | Run a command with administrative privileges |

---

## Lab Activities

- Verified the current Linux user and working directory.
- Reviewed file ownership and permission information.
- Learned how permissions are divided between the owner, group, and others.
- Created a practice file for permission testing.
- Removed write access from all users.
- Added execute permission for the file owner.
- Reviewed how ownership is displayed in Linux.
- Used `sudo` to complete an administrative task.
- Reviewed why unrestricted permissions can create a security risk.

---

## Screenshots

### 01 – Verifying Current Users and Directory

![Verifying Current Users and Directory](screenshots/Project4/01 Verifying Current Users and Directory.png)

### 02 – Analyzing Linux File Ownership

![Analyzing Linux File Ownership](screenshots/Project4/02 Analyzing Linux File Ownership.png)

### 03 – Understanding Linux File Permissions

![Understanding Linux File Permissions](screenshots/Project4/03 Understanding Linux File Permissions.png)

### 04 – Creating a Practice File

![Creating a Practice File](screenshots/Project4/04 Mission4.txt.png)

### 05 – Modifying Linux File Permissions with chmod

![Modifying Linux File Permissions with chmod](screenshots/Project4/05 Modifying Linux File Permissions With chmod.png)

### 06 – Examining Linux File Ownership

![Examining Linux File Ownership](screenshots/Project4/06 Examining Linux File Ownership.png)

### 07 – Using sudo for Administrative Tasks

![Using sudo for Administrative Tasks](screenshots/Project4/7 Using sudo for Administrative Tasks.png)

---

## Lessons Learned
- I learned how to read Linux permission strings and understand what access each user group has.
- I practiced changing permissions with `chmod` and checking the results with `ls -l`.
- I learned the difference between file permissions and file ownership.
- I learned why administrative access should only be used when it is needed.
- I became more comfortable recognizing permission settings that could create a security risk.

---

## SOC Analyst Takeaways

- File permissions can help an analyst determine who is allowed to read, change, or execute a file.
- Permissions such as `rwxrwxrwx` are risky because every user has full access.
- Unexpected ownership or permission changes should be reviewed to determine who made the change and whether it was authorized.
- The Principle of Least Privilege limits access and reduces the damage caused by mistakes or compromised accounts.
  
