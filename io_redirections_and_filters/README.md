# 0x02. Shell, I/O Redirections and Filters

## Description
This project introduces shell input/output redirections and filters in Bash.  
You will learn how to use commands such as `echo`, `cat`, `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, and how to redirect output with `>`, `>>`, and `|`.

## Project Structure
Each file is a script that performs a specific task:

- **0-hello_world** → prints "Hello, World"
- **1-confused_smiley** → displays a confused smiley `"(Ôo)'`
- **2-hellofile** → displays the content of `/etc/passwd`
- **3-twofiles** → displays the content of `/etc/passwd` and `/etc/hosts`
- **4-lastlines** → displays the last 10 lines of `/etc/passwd`
- **5-firstlines** → displays the first 10 lines of `/etc/passwd`
- **6-third_line** → displays the third line of the file `iacta`
- **7-file** → creates a file with a tricky name and writes "Best School" inside
- **8-cwd_state** → writes the result of `ls -la` into the file `ls_cwd_content`
- **9-duplicate_last_line** → duplicates the last line of the file `iacta`
- **10-no_more_js** → deletes all `.js` files in the current and subdirectories
- **11-directories** → counts the number of directories and subdirectories
- **12-newest_files** → displays the 10 newest files in the current directory
- **13-unique** → takes a list of words and prints only words that appear once
- **14-findthatword** → displays lines containing the word “root” in `/etc/passwd`
- **15-countthatword** → displays the number of lines containing “bin” in `/etc/passwd`
- **16-whatsnext** → displays lines containing “root” and 3 lines after them
- **17-hidethisword** → displays all lines that do **not** contain “bin”
- **18-letteronly** → displays all lines starting with a letter
- **19-AZ** → replaces all `A` with `Z` and all `c` with `e`
- **20-hiago** → removes all letters `c` and `C`
- **21-reverse** → reverses input
- **22-users_and_homes** → displays users and their home directories from `/etc/passwd`

## How to Use
```bash
chmod +x <script_name>
./<script_name>

