# ssh-server-setup


#Introduction



This project documents how to install, configure, and secure an SSH server on Ubuntu.




## Steps


1. **Install SSH server**

   

   sudo apt update && sudo apt install openssh-server -y




2. **Start and Enable SSH**


    sudo systemctl start ssh
    
    sudo systemctl enable ssh



3. **Find Your IP Address**


   ip a | grep inet



4. **Connect from Another Machine**

    
    ssh your-username@your-ip


note: use whoami to get username

5. **Security Enhancements**

   Disabled root login
   Changed the default SSH port

Author: Shakirat Abdulazeez



