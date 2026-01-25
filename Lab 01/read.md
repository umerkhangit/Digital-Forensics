#LAB 01 Q&A
Q1. If we want to list all the .txt files in the current directory, what command would we use?

A1. If we wanted to list all the .txt files in the current directory, we would use " ls *.txt "

Q2. What command can we use to read the contents of the /etc/passwd file?

A2. If we want to read the contents of the file /etc/passwd, we will use cat /etc/passwd

Q3. If we wanted to search for the string Error in all files in the /var/log directory, what would our command be?

A3. If we wanted to search for the string Error in all files in the /var/log directory, we would use grep "Error" /var/log/*

Q4.What would be the commands to calculate MD5 and SHA1 hashes of the file /etc/passwd?

A4. If we want to calculate MD5 and SHA1 hashes of the file /etc/passwd, we would use " md5sum /etc/passwd " and " sha1sum /etc/passwd "

Q5. Use the file command to determine the type of the file /usr/bin/cat and explain the output in 2-3 sentences.

ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, BuildID[sha1]=8ff77e5585da488ded426fe771ceaae234703a9a, for GNU/Linux 3.2.0, stripped
Q6. What command can we use to display all printable strings of length ≥ 8 in the file /bin/bash?

A6. If we want to display all printable strings of length ≥ 8 in the file /bin/bash, we will use " strings -n 8 /bin/bash "
Q7. Given the following output of the file command, can you determine what’s wrong with this file?
A7. This file is neither an image nor a text file.
         The file output clearly shows it is an ELF 64-bit executable, which means it’s a binary program for Linux.
          So even though it’s named image.jpg, that extension is misleading the file is actually a compiled executable, not readable text, and not a real image.
Q8. If we want to look for files modified in the last 30 minutes in the/home directory, what command would we use?
A8. If we want to look for files modified in the last 30 minutes  in the /home directory, we would use find /home -type f -mmin -30.
Q9. What command can we use to display information about all active TCP connections on the system?
A9. If we want to display information about all active TCP connections on thhe systems,we will use netstat -tn command.
Q10. Given this corrupted image file, can you find a way to recover and view its contents?
A10. For viewing this file we have to change it's hex value to png hex value.
