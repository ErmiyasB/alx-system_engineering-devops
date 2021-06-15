echo "Hello World" - pront hello world follwed by a new line to the standard output.

1----

cat /etc/passwd - display the content of the /etc/passwd file.

cat /etc/passwd /etc/hosts - display content of 2 files

tail -10 /etc/passwd -display the last 10 lines of/etc/passwd

head -10 /etc/passwd -display the first 10 lines

head -n 3 iacta | tail -n 1 -to display the third line if the file

cat >file | echo "Helberton School"-to creates a file name exactly \*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:) containing the text holberton school ending by new line

ls -la > ls_cwd_content -writes the command in to ls_cwd_content if the file exist it overwrite it id the file ls_cwd_content does not exist it creat it

tail -n 1 iacta | cat>> iacta- duplicate last line

find . -type f -name "*.js" -delete -delte only match files and do not include directory

find . -mindepth 1 -type d |wc -l -counts the mumber of directories and sub-sirectories in the current directory

ls -t | head displays the 10 newst files in the current directory

sort | uniq -u that takes a list of words as input and prtint only words

grep root /etc/passwd display lines containing the pattern "root" from the file /etc/passwd

grep -c bin /etc/passwd - display the mumber of lines that contain the pattern "bin" in the file

cat /etc/passwd | grep -A 3 "root" -display the containing the pattern "root" and 3 lines after them in thee file /etc/passwd

grep ^[[:alpha:]] /etc/ssh/sshd_config display all lines of the file starting with a letter including letters as well

tr 'Ac' 'Ze' - replace all characters A and c from input to Z and e respectively

tr -d 'Cc' remove all letters c and C from input.

rev -reverse its input

cut -d":" --fields=1,6 /etc/passwd | sort displays all users and thir home directories  sort by users