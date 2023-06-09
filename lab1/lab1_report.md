University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)  
Year: 2023  
Group: K34212    
Author: Demidyuk Oleg Sergeevich   
Lab: Lab1   
Date of create: 18.03.2023   
Date of finished: ...   

Цель работы: Изучить рабочую среду Cisco Packet Tracer, ознакомить- ся с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.  
Ход работы:  

ЧАСТЬ 1 

1. Была собрана схема соединения.
 
![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/1.jpg)

2. Для каждого компьютера были задани ip(192.168.1.2 - 192.168.1.8) и маски. 

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/2.jpg)

3. Далее с помощью пингов была произведена проверка, что любой компьютер одной сети передает пакеты любому другому компьютеру другой сети.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/3.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/4.jpg)

ЧАСТЬ 2 

1. Была собрана схема соединения.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/6.jpg)

2. Изменино имя маршрутизатора на CMERouter.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/5.jpg)

3. Был настроен интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/7.jpg)

4. Для автоматической настройки компьютеров и IP-телефонов в сети был настроен DHCP сервер на маршрутизаторе Cisco 2811. В
конфигурационном режиме создан пул DHCP адреса с названием VOICE.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/8.jpg)

5. Была произведена настройка CallManager Express, то есть телефонного сервиса в автоматическом режиме. 

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/9.jpg)

6. Затем был настроен интерфейс управления коммутатором (SwitchA) в сети VLAN.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/10.jpg)

7. Далее каждому телефону был присвоен номер, 54001 и 54002. Были проверены звонки между телефонами.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/11.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab1/screenshots/12.jpg)

Вывод: В ходе выполнения работы были изучена рабочая среда Cisco Packet Tracer, ознакомлены с интерфейсами основных устройств, типами кабелей, собрана топология. Изучено построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.
