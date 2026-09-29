# — Linux CLI, File Management & Permissions

## Module 2: Linux, Networking & Cloud Infrastructure

### Objective

The objective of Day 6 was to gain practical knowledge of Linux command-line operations, file and directory management, and Linux file permissions.

---

#Introduction to Linux

Linux is an open-source operating system widely used for servers, cloud infrastructure, networking, DevOps, and application hosting.

During this practical session, I used Ubuntu running through Windows Subsystem for Linux (WSL) to practice basic Linux administration commands.

---

##Linux Command Line Interface (CLI)

The Linux CLI allows administrators and developers to interact with the operating system using commands instead of a graphical user interface.

### Basic Commands

| Command | Purpose |
|---|---|
| `pwd` | Displays the current working directory |
| `ls` | Lists files and directories |
| `cd` | Changes the current directory |
| `mkdir` | Creates a directory |
| `touch` | Creates an empty file |
| `cat` | Displays the contents of a file |
| `nano` | Opens a terminal text editor |

### Examples

```bash
pwd
ls
cd ~/module2
mkdir linux-practice
touch notes.txt
cat notes.txt
nano notes.txt

###Linux File Permissions

Linux uses permissions to control access to files and directories.

The three basic permissions are:

Permission	Symbol	Meaning
Read	r	= Allows reading the file
Write	w	= Allows modifying the file
Execute	x	= Allows executing a file

Linux permissions apply to three categories:

Owner — the user who owns the file
Group — users belonging to the file's group
Others — all other users

For example:

-rw-r--r--

can be interpreted as:

Owner  → rw-
Group  → r--
Others → r--

The owner can read and write, while the group and others can only read.

Numeric Permission Values

Linux also represents permissions using numbers.

Permission	Value
Read (r)	4
Write (w)	2
Execute (x)	1

The values can be combined.

For example:

7 = 4 + 2 + 1 = rwx
6 = 4 + 2     = rw-
5 = 4 + 1     = r-x
4 = 4         = r--
7. Using chmod

The chmod command is used to modify file permissions.

Example: 600
chmod 600 test.txt

This gives:

Owner  → rw-
Group  → ---
Others → ---

Only the owner can read and write the file.

Example: 644
chmod 644 test.txt

This gives:

Owner  → rw-
Group  → r--
Others → r--
Example: 755
chmod 755 test.txt

This gives:

Owner  → rwx
Group  → r-x
Others → r-x

Making a Script Executable

I also learned that execute permission is required to run a script directly.

For example:

chmod +x hello.sh

After adding execute permission, the script can be executed using:

./hello.sh
9. Viewing Permissions

The following command can be used to view file permissions:

ls -l

Example:

-rw-r--r-- 1 user user 150 notes.txt

The first section represents the file type and permissions.

10. Changing File Ownership

Linux provides the chown command for changing file ownership.

Example:

sudo chown username file.txt

#The command changes the owner of the specified file.
#Practical Commands Learned
pwd
ls
ls -l
cd
cd ..
mkdir
touch
nano
cat
cp
mv
rm
rmdir
chmod
chown
