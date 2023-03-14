1. Склонировать репозиторй в папку.

2. внутри папки создать папку frontend и backend.

3. создать файл .env и скопировать в него содержимое файла env.example.

4. зайти в папку backend, создать файл .env и скопировать в него содержимое файла env.example.

5. в корневой папки с проектом выполнить команду sudo docker-compose build

6. затем выполнить sudo docker-compose up

7. зайти в контейнер backend sudo docker exec -it courses_backend bash b выполнить команды: composer-install && php artisan migrate && php artisan db:seed
