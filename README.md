# Docker-Otus
1. Создаем  **Dockerfile**  для сборки образа. Создаем файл **nginx.conf** . Берем дефолтную страницу nginx и немного изменим ее получим файл **index.html**
2. Далее все команды под суперпользователем
3. Приступаем к сборке образа nginx:alpine   ``` docker build -t nginx:alpine . ```
4.  Проверяем, что получили после сборки
5.  ![alt text](./Pictures/1.png)
6.  root@dmikhaylov-Ubuntu-22-04:~/docker/nginx-alpine# docker ps -a
7.  



