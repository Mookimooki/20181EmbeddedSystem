* List up the all user ids in an ascending order

cat /etc/passwd | awk -F: '{print $1}'

* Check the hardware information
 * Core #:
	# cat /proc/cpuinfo | grep -c processor
 * Memory Size:
	# awk '{print $2}' /proc/meminfo | head -1
 * Bit architecture:
	# uname -m
