
| Команда Linux | Призначення, короткий опис | Приклади використання  |
|-----------|-------------------------|---------------|
| `ls` | Lists the contents of the current directory. | ![1](https://github.com/Uklonsd/DevOps/assets/129956851/38b93f7d-21c1-4724-a71c-fd7971e3a5ae)|
| `ls -R` | Lists all files in the directory and subdirectories recursively. | ![2](https://github.com/Uklonsd/DevOps/assets/129956851/24357ff4-162f-46c3-98ac-942ead39a506) |
| `ls -a` | Lists all entries including hidden files starting with '.' | ![3](https://github.com/Uklonsd/DevOps/assets/129956851/02a2e33b-1dda-4f0c-bc03-a7920d4c9b80)|
| `ls -al` | Lists detailed information about all files, including hidden ones. |![4](https://github.com/Uklonsd/DevOps/assets/129956851/21f5f27c-e31c-4e06-8239-1b3e0607e154)|
| `cd` or `cd ~` | Changes the current directory to the home directory. |![5](https://github.com/Uklonsd/DevOps/assets/129956851/f350b3c8-d49d-42c9-a868-30379f330351) |
| `cd ..` | Moves one directory up in the hierarchy. |![6](https://github.com/Uklonsd/DevOps/assets/129956851/c2d8c714-7577-48bd-8969-7b6d4fbbbc98)|
| `cd /` | Changes the current directory to the root directory. |![7](https://github.com/Uklonsd/DevOps/assets/129956851/eb590373-6761-49ac-a5f0-efb9087bd841) |
| `cat > filename` | Creates a new file or overwrites an existing file and allows you to enter content. |![8](https://github.com/Uklonsd/DevOps/assets/129956851/352be2a0-8f4b-4d33-a784-84d477931a07) |
| `cat filename` | Displays the contents of a file. | ![image-20](https://github.com/Uklonsd/DevOps/assets/129956851/0d404f47-d634-4b8c-b306-b08b54141c2b)|
| `cat file1 file2 > file3` | Concatenates file1 and file2 and writes the output to file3. |![image-21](https://github.com/Uklonsd/DevOps/assets/129956851/dea7b0c6-6f7a-4eab-b7d4-b7b1b569ff55) |
| `mv file "new file path"` | Moves or renames a file to a new location. | ![image-22](https://github.com/Uklonsd/DevOps/assets/129956851/0c3043d4-7fb0-4fef-9463-d85d14fbc482)|
| `mv filename new_file_name` | Renames a file. | ![image-23](https://github.com/Uklonsd/DevOps/assets/129956851/e10e3f86-02ee-4c02-8d25-2647c442713f)|
| `sudo` | Executes a command with superuser (root) privileges. |![13](https://github.com/Uklonsd/DevOps/assets/129956851/58380124-ab2f-4ebe-ab2b-d2ed1cb39387)|
| `rm filename` | Removes (deletes) a file. | ![image-25](https://github.com/Uklonsd/DevOps/assets/129956851/b6a8e2f3-f30a-4caa-bc73-d85ceb7324fd) |
| `man` | Displays the manual page for a command. |![image-26](https://github.com/Uklonsd/DevOps/assets/129956851/09457aaf-5dfb-4619-be10-3526bc6cfd4b)|
| `history` | Displays the command history. |![16](https://github.com/Uklonsd/DevOps/assets/129956851/c2165ffb-da1a-496c-ac35-100d41bb1f6e)|
| `clear` | Clears the terminal screen. |![17](https://github.com/Uklonsd/DevOps/assets/129956851/89c9deb8-9dab-49f5-b5f0-dce9790ec507)|
| `mkdir directoryname` | Creates a new directory. | ![image-29](https://github.com/Uklonsd/DevOps/assets/129956851/176f54a1-28db-4373-9489-8e93448a0bc1)|
| `rmdir` | Removes an empty directory. |![image-30](https://github.com/Uklonsd/DevOps/assets/129956851/d40a489a-e547-4a96-bacc-28111c79a849)|
| `mv` | Moves or renames files or directories. | Rename file:![image-31](https://github.com/Uklonsd/DevOps/assets/129956851/7a2e1288-5d9a-4c6a-b6cc-ac8fcfe91ffd)
 Move file:![image-32](https://github.com/Uklonsd/DevOps/assets/129956851/506c0e44-b631-4c33-9512-4cfbda23f114) |
| `pr -x` | Formats text files for printing, '-x' sets the number of columns. | ![image-33](https://github.com/Uklonsd/DevOps/assets/129956851/7ab84a0f-93db-470d-b03f-df2c0ccae3ba)|
| `pr -h` | Adds a header to the file when printing, '-h' specifies the header. |![pr -h](https://github.com/Uklonsd/DevOps/assets/129956851/fb4e90b6-bef1-4bc2-839a-ee2ce2d93356)|
| `pr -n` | Adds line numbers to the file. | ![pr -n](https://github.com/Uklonsd/DevOps/assets/129956851/8daa6ebe-beb2-44cc-959b-6241270808f7)|
| `lp -n c` or `lpr -# c` | Sends a file to the printer, '-n' specifies the number of copies. | `lp -n 2 file.txt` - prints two copies of file.txt |
| `lp -d` or `lpr -P` | Specify the destination | `lp -d printer_name file.txt` or `lp -P printer_name file.txt` |
| `apt-get` | APT package handling utility in Debian and Ubuntu, used for installing, updating, and removing packages. |![apt](https://github.com/Uklonsd/DevOps/assets/129956851/1ec1b7b6-c0d1-42be-8b76-8ed84e4eb903)|
