## ✅ **Section 1: Linux Fundamentals – Assignments**

---

### **📝 Assignment 1: Linux Explorer**
**Goal**: Create a script (`explorer.sh`) that:
- Prints your current user, hostname, and present working directory.
- Displays the Linux distro and version.
- Lists all available shells from `/etc/shells`.

🔧 **Concepts Used**: `whoami`, `hostname`, `pwd`, `cat`, `uname`, file reading.

---

### **📁 Assignment 2: File System Tree Mapper**
**Goal**: Write a script (`tree_mapper.sh`) that:
- Accepts a directory path from user.
- Recursively lists all files and directories in that path.
- Counts:
  - Total files
  - Total directories

🧠 **Bonus**: Print top 5 largest files in that directory.

🔧 **Concepts Used**: `find`, `wc`, `du`, `sort`, `head`.

---

### **📂 Assignment 3: Home Organizer**
**Goal**: Create a script (`home_organizer.sh`) that:
- Creates the following directories inside your home:
  - `~/Downloads`, `~/Documents`, `~/Projects`, `~/Scripts`
- Moves:
  - `.txt` files to `Documents`
  - `.sh` files to `Scripts`
  - `.zip` or `.tar` to `Downloads`

🔧 **Concepts Used**: `mv`, `mkdir`, conditionals, wildcards.

---

### **🔐 Assignment 4: Permission Setter**
**Goal**: Write a script (`perm_setter.sh`) that:
- Takes a file name as argument.
- Sets:
  - Read-only for all `.txt` files
  - Execute permission for `.sh` files
- Displays final permissions using `ls -l`

🧠 **Bonus**: Prompt user before changing each permission.

🔧 **Concepts Used**: `chmod`, `read`, `ls`, conditionals.

---

### **🔍 Assignment 5: Ownership Verifier**
**Goal**: Script (`owner_check.sh`) should:
- Loop over files in a directory
- Show:
  - Owner and group
  - Whether the user has write access
- Allow changing owner (if run as root)

🔧 **Concepts Used**: `ls -l`, `chown`, `stat`, conditionals.

---

### **⚙️ Assignment 6: Process Watcher**
**Goal**: Script (`process_watcher.sh`) that:
- Accepts a process name as input
- Checks if it's running (`ps aux | grep`)
- Displays:
  - PID
  - Memory usage
  - Start time
- Option to kill the process

🔧 **Concepts Used**: `ps`, `grep`, `awk`, `kill`.

---

### **🧰 Assignment 7: Service Status Dashboard**
**Goal**: Script (`service_checker.sh`) that:
- Checks status of services like `ssh`, `cron`, `docker`, etc.
- Displays status using `systemctl`
- Suggests restart if inactive

🧠 **Bonus**: Color-code output (green = active, red = inactive)

🔧 **Concepts Used**: `systemctl`, loops, conditionals.

---

### **📦 Assignment 8: File Backup Utility**
**Goal**: Script (`backup_util.sh`) to:
- Take directory as argument
- Create compressed backup with timestamp in filename
- Save backups in `~/Backups/`

🔧 **Concepts Used**: `tar`, `gzip`, `date`, `mkdir`, `basename`.

---

### Optional: 🎮 **Fun Mini Challenge**
**Assignment**: Create a game-like script (`guess_os.sh`)
- Prompts user to guess the Linux distribution name
- Gives hints like: “It’s based on Debian”, “Popular for servers”, etc.

---
