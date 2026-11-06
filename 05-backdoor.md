<img width="569" height="603" alt="image" src="https://github.com/user-attachments/assets/2afaaac3-e026-401e-ba3e-ee65444fe265" />  Обнаружен подозрительный SUID.  

passwd и sudo находятся в системном каталоге /usr/bin/ который защищен от записи обычными пользователями demobash находится в домашнем каталоге пользователя.  

<img width="759" height="161" alt="image" src="https://github.com/user-attachments/assets/546f6b91-8d74-49b7-b44c-263263fcf54f" />  Доказательство его опасности.  

<img width="602" height="63" alt="image" src="https://github.com/user-attachments/assets/d911c10e-0ee9-4446-a9b9-c230645ceebb" />  Удалили SUID.  

<img width="769" height="84" alt="image" src="https://github.com/user-attachments/assets/95a138a1-968c-4040-9656-803f7354f86e" />  Проверка успешности исправления.  

Задачи администратора:  

1)Проводить регулярный поиск всех файлов с SUID  

2)Сверять результаты с эталоном  

3)Использовать проверку пакетов  

4)Применять принцип наименьших привилегий  






