To change "the apt-get repository" from kr.archive.ubuntu.com to ftp.daumkakao.net,
I had to modify the file "/etc/apt/sources.list"
added "deb-src http://ftp.daumkakao.net precise main restricted"

Finally, command "sudo apt-get update", "sudo apt-get upgrade" in terminal.
