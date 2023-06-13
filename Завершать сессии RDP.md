#### Параметры таймаутов RDP сессий находятся в разделе GPO Computer Configuration ####
Конфигурация компьютера -> Политики -> Административные шаблоны -> Компоненты Windows -> Службы удаленных рабочих столов -> Узел сеансов удаленных рабочих столов -> Ограничение сеансов по времени). Доступны следующие политики таймаутов:

- Задать ограничение по времени для отключенных сеансов;

- Задать ограничение времени для активных, но бездействующих сеансов служб удаленных рабочих столов) – политика позволяет завершить простаивающие RDP сессии, в которых отсутствует ввод со стороны пользователя (движение мышкой, ввод символов с клавиатуры);
- Задать ограничение по времени для активных сеансов служб удаленных рабочих столов) – максимальный срок для любой (даже активной) RDP сессии пользователя, после которого она переводится в состояние disconnected;
- Завершать сеанс при достижении ограничения по времени) – через какое время нужно завершать RDS сессию (logoff) вместо перевода ее в disconnected;
- Задать предел для выхода из сеансов RemoteApp).

![](https://private-user-images.githubusercontent.com/132609167/245430205-cea9b83d-2841-4a07-8b9f-d16975fc498a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJrZXkiOiJrZXkxIiwiZXhwIjoxNjg2NjQ5MjMyLCJuYmYiOjE2ODY2NDg5MzIsInBhdGgiOiIvMTMyNjA5MTY3LzI0NTQzMDIwNS1jZWE5YjgzZC0yODQxLTRhMDctOGI5Zi1kMTY5NzVmYzQ5OGEucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQUlXTkpZQVg0Q1NWRUg1M0ElMkYyMDIzMDYxMyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyMzA2MTNUMDkzNTMyWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NjVmZDJjZTc0NTc4NDI3NTI3YTI1ZTczYzdjYzk2ZjJjM2ZjMGRiYmE2OWI4ZjVlZGQzNzA4ZTZkZjhkNzU4YiZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.F4wNcEscHNJnvAzIfwDzNyvIQkpd2bqo67gXTL01ZXQ
