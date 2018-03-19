*Store user id list in a file named "system_info.txt".
*Add the cpu info to the "system_info.txt" file.

$ cat /etc/passwd | awk -F: '{print $1}' >> ~/system_info.txt
$ cat /proc/cpuinfo >> ~/system_info.txt
