# Домашнее задание к занятию «Кеширование Redis/memcached» - Жаринов Павел

---

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*
Ответ.
Высокая нагрузка на сервер:
-длительный ответ при запросах в БД.
-скачки обращений к определенным данным.
-большой расход ресурсов сервера при работе с данными.

---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*
![image](image/1.png)

---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*
![image](image/2.png)

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*
![image](image/3.png)


