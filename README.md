# Docker-Otus
1. Создаем  **Dockerfile**  для сборки образа. Создаем файл **nginx.conf** . Берем дефолтную страницу nginx и немного изменим ее получим файл **index.html**
2. Далее все команды под суперпользователем
3. Приступаем к сборке образа nginx:alpine   ``` docker build -t nginx:alpine . ```
4.  Проверяем, что получили после сборки
5.  ![alt text](./Pictures/1.png)
6.  root@dmikhaylov-Ubuntu-22-04:~/docker/nginx-alpine# docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED             STATUS                         PORTS                               NAMES
d71af4aa7d0c   dd0c1c80d316   "nginx -g 'daemon of…"   39 minutes ago      Exited (1) 39 minutes ago                                          eloquent_albattani
c31a343fb2a3   dd0c1c80d316   "nginx -g 'daemon of…"   41 minutes ago      Exited (1) 41 minutes ago                                          lucid_vaughan
e4ee73f8e7e1   dd0c1c80d316   "."                      43 minutes ago      Created                        0.0.0.0:80->80/tcp, :::80->80/tcp   competent_vaughan


