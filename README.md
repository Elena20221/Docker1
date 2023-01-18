## Домашнее задание 1 к лекции "Docker"
### 1. Для создания контейнера выполнить команду 
      docker build -t new_nginx 

### 2. Для запуска контейнера выполнить команду
      docker run -d -p 8888:80 --name=new_nginx new_nginx

### 3.Проверка:

      curl localhost:8888
* http://localhost:8888