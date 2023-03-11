Ansible role для развертывания Lighthouse
=========

Роль предназначена для развертывания Lighthouse на операционной системе Centos 7

Requirements
------------

Требования для установки роли:

1. Операционная система Centos

Role Variables
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

License
-------

MIT

Author Information
------------------

Олег Троицкий, учебная работа, 2023
