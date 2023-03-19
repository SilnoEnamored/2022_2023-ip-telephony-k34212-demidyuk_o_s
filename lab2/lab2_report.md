University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)  
Year: 2023  
Group: K34212    
Author: Demidyuk Oleg Sergeevich   
Lab: Lab2   
Date of create: 19.03.2023   
Date of finished: ...   

Цель работы: Иизучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.
Ход работы:

ЧАСТЬ 1 

1. Была собрана схема соединения. Изменино название маршрутизатора на CMERouter.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/1.jpg)

2. Отключен синтаксис ввода слов от DNS серверов.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/2.jpg)

3. Также были задны пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/3.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/4.jpg)

4. Далее был сконфигурирован интерфейс fa0/0.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/5.jpg)

5. Для автоматической настройки компьютеров и IP-телефонов в сети был настроен DHCP сервер на маршрутизаторе Cisco 2811. В
конфигурационном режиме создан пул DHCP адреса с названием VOICE.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/6.jpg)

6. Затем был настроен CallManager Express, то есть телефонный сервис в автоматическом режиме.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/7.jpg)

7. Далее был настроен интерфейс управления коммутатором (SwitchA) в сети VLAN через назначение диапазона портов.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/8.jpg)

8. Далее каждому телефону был присвоен номер, 54001,54002 и 54003. Были проверены звонки между телефонами.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/9.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/10.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/11.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/12.jpg)

ЧАСТЬ 2 

1. Была собрана схема соединения.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/13.jpg)

2. Были созданы vlan и присвоены им наименования.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/14.jpg)

3. Настроена vlan99.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/15.jpg)

4. Задан маршрут по умолчанию.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/16.jpg)

5. Затем был настроен интерфейс управления коммутатором в сети VLAN через назначение диапазона портов.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/17.jpg)

6. Включен интерфейс FastEthernet0/0.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/18.jpg)

7. Далее были созданы логические подынтерфейсы для VLAN 10, VLAN 20, VLAN 99.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/19.jpg)

8. Были исключен из пула адрес интерфейса маршрутизатора и DNS-сервера.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/20.jpg)

9. Также был был настроен DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/21.jpg)

10. Была проведена настройка телефонного сервиса в автоматическом режиме.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/22.jpg)

11. Затем были присвоены номера для всех Ip-телефонов в сети.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/26.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/23.jpg)

12. Были проверены звонки между телефонами.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/24.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab2/screenshots/25.jpg)

Вывод: В ходе выполнения работы было изучено построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.
