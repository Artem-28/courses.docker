1. Склонировать репозиторй в папку.

2. внутри папки создать папку frontend и backend.

3. создать файл .env и скопировать в него содержимое файла env.example.

4. зайти в папку backend, создать файл .env и скопировать в него содержимое файла env.example.

5. зайти в папку frontend в файле Dockerfile закомментировать последнюю строку CMD ["npm", "run", "dev"].

6. в корневой папки с проектом выполнить команду sudo docker-compose build.

7. зайти в папку frontend в файле Dockerfile раскомментировать последнюю строку CMD ["npm", "run", "dev"].

8. в корневой папки с проектом выполнить команду sudo docker-compose build.

9. затем выполнить sudo docker-compose up

7. зайти в контейнер backend sudo docker exec -it courses_backend bash b выполнить команды: composer-install && php artisan migrate && php artisan db:seed
