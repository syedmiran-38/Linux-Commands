# 🐧 LINUX TERMINAL – QUICK REVISION NOTES ( Day 2 )

Relative path is a path related to your current directory (`pwd`). It does **not** start with `/`. For example, if you are in `/Users/miran` and want to go to `/Users/miran/Desktop/linux-practices`, you can simply use `cd Desktop/linux-practices`. Special shortcuts are `..` (go up one directory) and `.` (current directory).

To create directories, you can use absolute or relative paths. For example, `mkdir /Users/miran/Desktop/folder1` creates a folder at the absolute path, while `mkdir folder2` creates a folder inside your current directory.

Copy files using `cp`. To copy a single file: `cp file1.txt ../folder2/`. To copy multiple files: `cp file1.txt file2.txt ../folder2/`. To copy entire directories recursively, use the `-r` option: `cp -r folder1 folder1_copy`.

To move files, use `mv`. For example, `mv file1.txt ../folder1/` moves the file to the `folder1` directory one level up. Note: `..` means parent directory.

To remove files, use `rm filename`. To remove directories and their contents, use `rm -r directoryname`.

To navigate directories, use `cd`. Use `cd ..` to go back (up) one directory level. Use `pwd` to print your current directory path.

---

### Quick Vim Editor Practice on Mac

- Open or create a file with `vim filename` (e.g., `vim practice.txt`).
- Vim opens in **Command Mode** by default.
- Press `i` to enter **Insert Mode** and start typing your text.
- When done typing, press `Esc` to return to **Command Mode**.
- To save and quit, type `:wq` and press `Enter`.
- To quit without saving, type `:q!` and press `Enter`.

---

### Notes

- If you get an error like `E45: 'readonly' option is set`, add `!` to force save: `:wq!`.
- Files you create will be saved in the directory from which you launched `vim`.
- Use `ls` or `ls -l` to check the file exists.
- To delete files, use `rm filename`.

---

This concludes the Day 2 Linux commands and basic vim editor practice.
