# 0x02. Shell, I/O Redirections and filters

Description of each script in this directory:

- `0-hello_world`: prints "Hello, World" followed by a new line.
- `1-confused_smiley`: displays a confused smiley `"(Ôo)'`.
- `2-hellofile`: displays the content of `/etc/passwd`.
- `3-twofiles`: displays the content of `/etc/passwd` and `/etc/hosts`.
- `4-lastlines`: displays the last 10 lines of `/etc/passwd`.
- `5-firstlines`: displays the first 10 lines of `/etc/passwd`.
- `6-third_line`: displays the third line of the file `iacta`.
- `7-file`: creates a specially named file containing the text "Best School".
- `8-cwd_state`: writes the result of `ls -la` into the file `ls_cwd_content`.
- `9-duplicate_last_line`: duplicates the last line of the file `iacta`.
- `10-no_more_js`: deletes all regular `.js` files in the current directory and subdirectories.
- `11-directories`: counts the number of directories and subdirectories in the current directory.
- `12-newest_files`: displays the 10 newest files in the current directory, one per line, newest first.
- `13-unique`: prints words from stdin that appear exactly once, sorted.
- `14-findthatword`: displays lines containing "root" in `/etc/passwd`.
- `15-countthatword`: displays the number of lines containing "bin" in `/etc/passwd`.
- `16-whatsnext`: displays lines containing "root" and the 3 lines after them in `/etc/passwd`.
- `17-hidethisword`: displays lines in `/etc/passwd` that do not contain "bin".
- `18-letteronly`: displays lines of `/etc/ssh/sshd_config` starting with a letter.
- `19-AZ`: replaces characters `A` and `c` with `Z` and `e` respectively from stdin.
- `20-hiago`: removes all letters `c` and `C` from stdin.
- `21-reverse`: reverses its input.
- `22-users_and_homes`: displays all users and their home directories, sorted by user, based on `/etc/passwd`.
- `23-empty_casks`: finds all empty files and directories, printing only their names.
- `24-gifs`: lists all `.gif` files recursively, names without extensions, sorted case-insensitively.
- `25-acrostic`: decodes an acrostic using the first letter of each line.
- `26-the_biggest_fan`: parses TSV web server logs and displays the top 11 hosts by number of requests.
