## Part 1. Установка ОС
  <img src="./images/1.png">

- Установили Ubuntu 22.04.4 Server LTS без графического интерфейса

***

## Part 2. Создание пользователя
  <img src="./images/2.1.png">

- Добавили пользователя new_user

<img src="./images/2.2.png">

- Вывод команды cat /etc/passwd

***

## Part 3. Настройка сети ОС

<img src="./images/2.3.png">
- Установили временную зону

<img src="./images/2.4.png">
- Названия сетевых интерфейсов

<img src="./images/2.7.png">

- Получили ip адрес устройства

<img src="./images/2.6.png">
- Внешний ip-адрес шлюза (ip) и внутренний IP-адрес шлюза

<img src="./images/2.5.png">
<img src="./images/2.8.png">
- настройки ip, gw, dns

<img src="./images/3.png">
<img src="./images/3.1.png">
- пропинговали удаленные хосты 1.1.1.1 и ya.ru

***

## Part 4. Обновление ОС
  <img src="./images/3.2.png">

- Обновили системные пакеты до последней на момент выполнения задания версии


***

## Part 5. Использование команды sudo
  <img src="./images/5.1.png">

- Разрешили пользователю, созданному в Part2, выполнять команду sudo

<img src="./images/5.2.png">

<img src="./images/5.3.png">

- Вставили скрин с изменённым hostname 

***


## Part 6. Установка и настройка службы времени
  <img src="./images/2.3.png">

- служба автоматической синхронизации времени.

***

## Part 7. Установка и использование текстовых редакторов

Установили текстовые редакторы VIM, NANO, MCEDIT

- редактор vim

<img src="./images/3.3.png">
<img src="./images/3.4.png">

- редактор nano
<img src="./images/3.5.png">

***

## Part 8. Установка и базовая настройка сервиса SSHD
  <img src="./images/3.7.png">

- Установи службу SSHd.

<img src="./images/3.8.png">

<img src="./images/3.9.png">
Используя команду ps, покажи наличие процесса sshd. Для этого к команде нужно подобрать ключи.

- Вывод команды netstat -tan должен содержать  
tcp 0 0 0.0.0.0:2022 0.0.0.0:* LISTEN
<img src="./images/4.png">
***

## Part 9. Установка и использование утилит top, htop

- Установили и запустили утилиты top и htop.
  -CPU
  <img src="./images/4.1.png">
  -PID
  <img src="./images/4.2.png">
  -MEMORY
  <img src="./images/4.4.png">
  -TIME
  <img src="./images/4.4.png">

***

## Part 10. Использование утилиты fdisk
- Установили и запустили утилиты fdisk.
  <img src="./images/4.6.png">

***
## Part 11. Использование утилиты df

  <img src="./images/4.7.png">

  - Запустили команду df.

        размер раздела - 1028772

        размер занятого пространства - 308912

        размер свободного пространства - 6595188

        процент использования - 32%
  <img src="./images/4.8.png">

  - Запусти команду df -Th.



        размер раздела - 9.8G

        размер занятого пространства - 3G
        
        размер свободного пространства - 6.3G

        процент использования - 32%
***

## Part 12. Использование утилиты du

    Выведи размер папок /home, /var, /var/log
  <img src="./images/4.9.png">

  <img src="./images/5.png">

  <img src="./images/5.1.png">

  <img src="./images/5.2.png">

-  вставили скрины с выводом всех использованных команд

***

## Part 13. Установка и использование утилиты ncdu

Выведи размер папок /home, /var, /var/log
    
<img src="./images/5.1.png">

<img src="./images/5.2.png">

-  вставили скрины с выводом всех использованных команд

*** 

## Part 14. Работа с системными журналами

Выведи размер папок /home, /var, /var/log


  1. /var/log/dmesg

  <img src="./images/5.3.png">

  2. /var/log/syslog

  <img src="./images/5.4.png">

  3. /var/log/auth.log

  <img src="./images/5.5.png">
  

-  Вставили в отчёт скрин с сообщением о рестарте службы

***