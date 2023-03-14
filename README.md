Склонировать репозиторй в папку,
внутри папки создать папку frontend и backend,
создать файл .env и скопировать в него содержимое файла env.example.
зайти в папку backend, создать файл .env и скопировать в него содержимое файла env.example.
в корневой папки с проектом выполнить команду sudo docker-compose build
затем выполнить sudo docker-compose up
зайти в контейнер backend sudo docker exec -it courses_backend bash b выполнить команды: composer-install && php artisan migrate && php artisan db:seed
