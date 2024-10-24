# SDB-12-06
Репликация и масштабирование. Часть 1 - Aleksandr Mihajlov SYS34  
  
### Задание 1

На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

*Ответить в свободной форме.*  
  
При работе в режиме "master-slave" репликация происходит в одну сторону, от master к slave.
Slave работает только начтение. Возможно использование для уменьшения нагрузки на сервер, например для информационных порталов.

При работет в режиме "master-master" репликация проиходит в обе стороны. Повышается риск допустить ошибку в бд или повредить ее.  
  
### Задание 2

Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

*Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.*  
  
<details> 
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.1.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.2.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.3.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.4.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.5.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.6.png)
![alt text](https://github.com/AleksandrMihajlov/SDB-12-06/blob/main/2.7.png)
</details>
