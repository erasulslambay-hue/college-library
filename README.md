College Library Project
Веб-проект электронной библиотеки колледжа для просмотра каталога книг и управления ресурсом.
🛠 Технологии
PHP
HTML / CSS
Docker (контейнеризация)
Git / GitHub
🐳 Docker
Для сборки и запуска проекта используется файл Dockerfile:
docker build -t college-library .
docker run -d -p 8080:80 --name library-container college-library
