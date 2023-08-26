# Shell_Linux
ls: List files and directories.
cd: Change directory.
pwd: Print working directory.
mkdir: Create a new directory.
touch: Create an empty file.
cp: Copy files or directories.
mv: Move or rename files or directories.
rm: Remove files or directories.
chmod: Change file permissions.
chown: Change file ownership.
ln: Create symbolic or hard links.
# WILDCAEDS
ls *.txt: Lists all files with a ".txt" extension in the current directory.
ls file?.txt: Lists files like "file1.txt", "file2.txt", but not "file10.txt".
ls [aeiou]*: Lists files starting with any vowel.
ls [0-9]*: Lists files starting with a digit.
ls [!0-9]*: Lists files not starting with a digit.

# Examples
cat - Concatenate and Display File Content:

bash
Copy code
cat filename.txt
This command will display the entire content of the filename.txt file in the terminal.

more - View File Content Page by Page:

bash
Copy code
more longfile.txt
This command will display the content of the longfile.txt file page by page. Press the spacebar to see the next page, and press q to quit.

less - View File Content with Backward Navigation:

bash
Copy code
less bigfile.log
This command will open the bigfile.log file in a viewer that allows you to navigate both forward and backward. Use arrow keys or page up/down to navigate, and press q to quit.

head - Display the Beginning Lines of a File:

bash
Copy code
head -n 10 myfile.txt
This command will display the first 10 lines of the myfile.txt file. You can adjust the number after -n to specify a different number of lines.

tail - Display the Last Lines of a File:

bash
Copy code
tail -n 20 access.log
This command will display the last 20 lines of the access.log file. You can adjust the number after -n as needed.

nano - Text Editor for Creating or Editing Files:

bash
Copy code
nano newfile.txt
This command will open the newfile.txt in the nano text editor. You can then create or edit the content of the file.

vim or vi - Powerful Text Editor:

bash
Copy code
vim document.md
This command will open the document.md file in the vim text editor. Vim is a powerful text editor with various modes and commands for editing and navigating text.

# hard links and soft links
# copy directory
cp -r dir1 dir2 

