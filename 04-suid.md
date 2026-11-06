<img width="521" height="53" alt="image" src="https://github.com/user-attachments/assets/1c41e66e-2571-4ec4-a3b1-c6ce9b71dd6c" />  

-rwsr-xr-x. - SUID.

<img width="769" height="260" alt="image" src="https://github.com/user-attachments/assets/4c878746-9c48-482e-9abb-689767a1facb" />  

euid=0 обозначает что мы root и у нас абсолютные права. Происходит это из-за SUID(система видит его и запускает программу от имени root, а не от имени пользователя).  
passwd может менять пароли так как программа запускается от имени root, но она не выдает тех же прав пользователю, по этому мы сами не можем.
 




