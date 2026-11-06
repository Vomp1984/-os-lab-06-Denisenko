<img width="380" height="152" alt="image" src="https://github.com/user-attachments/assets/fdc5350a-1d74-4260-accc-84462fb38a27" />  Права после первого изменения.  

<img width="304" height="85" alt="image" src="https://github.com/user-attachments/assets/15f4820f-6d21-4529-b0da-25daf4434e27" /> Права после второго изменения.  

<img width="335" height="100" alt="image" src="https://github.com/user-attachments/assets/158ecf34-846d-4bbb-9da8-4a2c6f1f114d" /> Права после третьего изменения.  

<img width="344" height="102" alt="image" src="https://github.com/user-attachments/assets/d8e74181-b69d-4e4e-8c3a-87d278fe7178" />  Права после третьего изменения.  

| Буквенно | Восьмерично |
| :--- | :--- |
| rw-r--r-- | 644 |
| rwxr-x--- | 750 |
| rw------- | 600 |
| r-xr-xr-x | 555 | 

X для файла позволяет исполнять только этот файл, а для директории X позволяет добраться до файла(если у нас есть разрешение x на файл но нет x к директории, мы не сможем его запустить).  

chmod -R 777 / ломает систему так как выдает абсолютные права всему что есть в системе, что ломает логику программ и является уязвимостью в безопасности.

