Ansible role для развертывания Lighthouse
=========

Роль предназначена для развертывания Lighthouse на операционной системе Centos 7

Требования
------------

Требования для установки роли:

1. Операционная система Centos

Переменные роли
--------------

Переменные для данной роли не определены

Зависимости
------------

Нет

Примеры Playbook
----------------

Пример использования роли в Playbook

 - name: Install LightHouse
   hosts: lighthouse
   roles: lighthouse-role
   tags: lighthouse      

Лицензия
-------

MIT

Информация об авторе
------------------

Олег Троицкий, учебная работа, 2023
