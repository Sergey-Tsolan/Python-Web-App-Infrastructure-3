# Python Web App Infrastructure with source code. Load-balancer.


Разработка инфраструктуры на основе docker и docker-compose для веб-приложения на python.

Цель состояла в том, чтобы развернуть веб-приложение с базой данных Postgres и Redis и nginx как
обратный прокси/балансировщик нагрузки.

Целевое веб-приложение для развертывания и исходный код брал здесь https://realpython.com/flask-by-example-part-1-project-setup/.

Я докеризировал веб-приложение на Python и собрал docker-compose инфраструктуру, связывающую воедино все компоненты.
