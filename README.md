Запуск blackbox_exporter
========

Данный репозиторий является ролью Ansible 
========================

*   В данно роли есть 2 сценария развертывания develop и production

    * Как работает develop сценарий:
        * Запуск blackbox_exporter с публикацией всех портов на адресе хостовой машины
    * Как работает production сценарий:
        * Запуск blackbox_exporter с публикацией всех портов на loopback интерфейсе хостовой машины
    * Контейнеры работают в виртуальной docker сети.