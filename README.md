# Кейсы </> Системный администратор
`Чечель Степан. Вот, что я умею`


### Лабораторная работа 1

1.	Создать виртуальную машину Linux.
2.	Установить службу FTP.
3.	Установить службу HTTP.
4.	Добавить в систему два накопителя.
5.	Настроить RAID (зеркало) на этих накопителях.
6.	Проверить правильность работы сервера. Должны быть доступны:


[Ссылка на файл .docx с содержимым](https://github.com/stepan-ch/allwork/blob/main/img/ssh_ft_raid.docx)

---

### Лабораторная работа 2

1. Создать две виртуальную машину Linux
2. Сконфигурировать на них сеть
3. Запустить сервисы и настроить firewall
4. Имплементировать скрипт локального резервного копирования
5. автоматизировать его запуск

[Ссылка на файл .docx с содержимым](https://github.com/stepan-ch/allwork/blob/main/img/d.docx)

---


### Docker
На примере установка контейнера nginx.
Просмотр информации к данному контейнеру, например какой установлен порт и что в данном контейне внутри.
Информация о контейнере, сколько потребялет ресурсов и т.д. Так же просмотр live log'a на примере nginx. И конфигурация самогу контейнера, например изменить .conf файл внутри контейнера nginx. Проброс портов в контейнер nginx, на примере два web сервера с nginx с портом 80 и 8080.

[Ссылка на файл .docx с содержимым](https://github.com/stepan-ch/allwork/blob/main/img/docker.docx)

---


### Установка MySQL + создание базы данных + backup базы данных и восстановление

--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/my1.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/my2.jpg)

---


### Реализация отказоустойчивости. Репликация MySQL, MASTER-SLAVE
--


![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/r1.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/r2.jpg)

---


### Лабораторная работа 3 
- Конфигурация vlan (виртуальная локальная сеть). Логическое деление коммутатора на несколько не сообщающихся между собой сетей.

--


![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/v1.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/v2.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/v3.jpg)


---


### Лабораторная работа 4 
- Настройка топологии сети NAT/DHCP/DNS в программе Cisco Packet Tracer.

--


![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/nat_dhcp_dns.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/nat_dhcp_dns2.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/nat_dhcp_dns3.jpg)


---

### Демонтрация практической работы установка программы Joomla на локальный сервер, посредством подключения через сетевой протокол прикладного уровня SSH, чтобы производить удаленное управление операционной системой Linux и его конфигурирование.
- Виртуальная машина ubuntu 22.04 live server.
- MySQL Ver. 8.0.32
- PHP 8.0.28
- Nginx nginx/1.18.0
- Joomla 4.3.0
- Fail2ban защиты от брут-форс атак.


![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/j1.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/j2.jpg)

---


### Демонстрация работы Ansible c автоматизацией playbook

--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/a1.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/a2.jpg)

---

### Базовая установка и настройки файлового хранилища SAMBA сервер


--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/s1.jpg)

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/s2.jpg)

---

### Развернутая виртуальная машина Ubuntu 22.04. Установка и настройка PostgreSQL + nginx + zabbix-server + zabbixagent.

--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/z1.jpg)

---


### Установка и конфигурация MySQL Cluster на основе PERCONA XtraDB. На примере 3 локальных сервера, установленно PERCONA XtraDB в объеднином в кластер и на каждый севрер установлен keepalived. Если один из серверов выходит из строя, то виртуальный адрес(плавающий IP) переходит на другой сервер, таким образом продолжают работать другие сервера.

--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/p1.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/p2.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/p3.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/p4.jpg)

---


### Отказоустойчивость при помощи балансировочной нагрузки в связке keepalived и HAproxy. 1-я и 2-я нода.

--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/k1.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/k2.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/k3.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/k4.jpg)

---


### Разведка pentest на сетевую досупность. И, пример утилиты arpspoof, навязывания ложного марширута. Схема полуперехвата, в рамках локальной сети.

--

![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/nm1.jpg)
![Image alt](https://github.com/stepan-ch/allwork/blob/main/img/nm2.jpg)

---
