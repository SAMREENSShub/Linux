![image](https://github.com/user-attachments/assets/37849bdd-f89d-455c-938f-0caff9cef1b5)# Linux
notes on linux
# Archituture of linux

 1.  hardware -if u want to know the details or info about h/w use-- dmidecode 
  2. kernal - not only interprets the input thro shell but does many works
     it manages resources(top command), schedules tasks (cronttab -l), manages security (sc linux--- df-h,)
 3. shell -- echo $SHELL , bash shell, kshell. on top the shell the commands are excecuted, these gives input to kernel. shell acts as interpreter.
    uname -r is used to check the linux verssion
  4. utilities -- commands like ls, etc

     # file system hirechary

      / -------->  root directory or the parent directory 
     1. /root -----> home directory of ur root user ( who is ur root user- super user having all the previlage), it provides the working dir of root users.
     2. /home -----> home director is dir of normal users eg-- sam, user1,user2 etc.. even we create monitoring tool  user which will go under this home dir,
     3. /boot ------> all bootable file sit under this. eg.. grub dir **** /boot dir also has all info abt kernel
     4. /etc -------> contains all configuration related files and dir  ---eg, yum, http..etc
     5. /usr ---> has multiple dir ---
     6. 

