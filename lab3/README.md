University: ITMO University  
Faculty: FTMI  
Course: Облачные платформы как основа технологического предпринимательства  
Year: 2026/2027  
Group: U4225  
Author: Солдатов Егор Олегович  
Lab: Lab3  
Date of create: 06.10.2026  
Date of finished: 06.10.2026  

## 1. Создание бакета  
<img width="1920" height="921" alt="image" src="https://github.com/user-attachments/assets/1bc7edc2-0e08-47fc-bad9-04323d38a848" />  
<img width="1920" height="915" alt="image" src="https://github.com/user-attachments/assets/fed042d6-f3ac-42d0-9453-c9636e100ddc" />  

## 2. Загрузка файлов  
<img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/e514456c-29db-46c9-9f05-29c91cae629b" />  

## 3. Создание папки и перемещение в неё файлов
<img width="1920" height="910" alt="image" src="https://github.com/user-attachments/assets/354d7ff5-0bc3-4e1f-b9b7-15e2ad828f39" />  

## 4. Управление доступом  
<img width="1920" height="918" alt="image" src="https://github.com/user-attachments/assets/27daf4f3-11bd-45af-85e1-fe4be9185a96" />  
<img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/6506391d-23f9-4c31-93ef-5829c254f995" />  
<img width="1920" height="969" alt="image" src="https://github.com/user-attachments/assets/b0854af9-d77f-4a49-9396-321b647d3c53" />
<img width="1920" height="976" alt="image" src="https://github.com/user-attachments/assets/643047ae-9fc8-4a95-a3f5-100808b16b6e" />
<img width="1920" height="973" alt="image" src="https://github.com/user-attachments/assets/f353d56c-3473-4d94-8da0-b0bfcb910988" />
<img width="1920" height="971" alt="image" src="https://github.com/user-attachments/assets/b53f96eb-f0f6-4f43-a1d5-468ebd06f7e1" />

**Public URL для файлов в бакете:**  
[monke.png](https://storage.googleapis.com/esoldatov-lab3-bucket-2026/pictures/monke.jpg), [lzhenauki.jpg](https://storage.googleapis.com/esoldatov-lab3-bucket-2026/pictures/lzhenauki.jpg), [Lego Goblin.png](https://storage.googleapis.com/esoldatov-lab3-bucket-2026/pictures/Lego%20Goblin.png), [traditional values.png](https://storage.googleapis.com/esoldatov-lab3-bucket-2026/pictures/traditional%20values.png)

## Выводы
1. Изучены различия между типами хранилищ. Cloud Storage представляет собой объектное хранилище, которое идеально подходит для хранения неструктурированных данных (изображений, видео, резервных копий), обеспечивая высокую доступность и масштабируемость.
2. Понятие "папки" в объектном хранилище является условным (это префикс в имени объекта), что отличает его от классических файловых систем, но удобно для восприятия пользователем.
3. На практике отработан механизм безопасного предоставления публичного доступа: вместо отключения защиты всего бакета, используется выдача роли Storage Object Viewer для allUsers с последующим точечным открытием доступа к конкретным объектам. Это соответствует требованиям информационной безопасности.

