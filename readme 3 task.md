Задача  1 
https://hub.docker.com/repositories/evmen93

Задача 2

<img width="1381" height="421" alt="Задача2 " src="https://github.com/user-attachments/assets/f32cd3e3-2f6b-4610-b18a-a80fc39ec0a0" />


Задача 3

 <img width="966" height="621" alt="Задача3 ск-т 1" src="https://github.com/user-attachments/assets/5492fc85-59f2-4131-ae4c-505ea966a8de" />
 Контейнер остановился потому, что при подключении через docker attach мы выводим на консоль процессы ngnix.Когда мы жмём комбинацию клавишь Ctrl+c, мы выходим из процесса. Поэтому нужно запускать контейнер в режиме демона(фоновом). Чтобы процессы не выводилиь на консоль.

 <img width="962" height="355" alt="Задача3 ск-т 2" src="https://github.com/user-attachments/assets/fd21657a-bc24-4c18-bdb4-1e77bd469ac3" />

 

 nginx слушает порт 80. после того как мы изменили порт на 81, nginx стал слушать другой порт. А проброс портов на доккере остался прежним.
после в 11 задании мы изменили порт прослушивания nginx на 81. Пробросили порты в соотвествии с конфигурацией nginx.



Задача 4

<img width="858" height="673" alt="Задача4" src="https://github.com/user-attachments/assets/41080b6e-bdec-49f1-be92-f14b55f6856e" />



Задача 5

<img width="1048" height="439" alt="задача 5 (1)" src="https://github.com/user-attachments/assets/45f2576d-c139-403d-84d9-7c7f4896cbe7" />



Запущен файл compose.yaml, так как Docker Compose по умолчанию ищет файлы в порядке приоритета: compose.yaml compose.yml docker-compose.yaml docker-compose.yml



<img width="1231" height="644" alt="задача 5 (2)" src="https://github.com/user-attachments/assets/ff135ae5-b8cb-4ff9-891c-b46f6f352f7f" />

<img width="740" height="395" alt="задача 5 (3)" src="https://github.com/user-attachments/assets/15bf52b2-e421-4ec2-99eb-3d8da14f8171" />

<img width="1240" height="779" alt="задача 5 (4)" src="https://github.com/user-attachments/assets/0e13a8b8-3bbc-45c0-a47a-22e5d2d37f34" />

<img width="1789" height="847" alt="задача 5 (5)" src="https://github.com/user-attachments/assets/b6a4457e-03d9-42f8-a6aa-9679ee3eaadb" />

<img width="695" height="812" alt="задача 5 (6)" src="https://github.com/user-attachments/assets/5fefa355-6d26-4b5d-a67d-664fa0fb89ab" />



Я удалил compose.yml было предупреждение, о том что нужно переименовать так новая версия не использует docker-compose. Так же при запуске был WARN, который говорит нам о том, что в файле-манифесте не нужно указать версию compose.


<img width="1478" height="102" alt="задача 5 (7)" src="https://github.com/user-attachments/assets/1bc23676-b5d7-4735-8495-7e1069603afd" />



