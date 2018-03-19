First I had to install "openssh-server"
To change the port of SSH, I needed to modify the file "/etc/ssh/sshd_config"
And the annotaion should be removed.
#Port 22 -> #Port 10022

Finally, I had to restart the "SSH server" using this command "service ssh restart" 
