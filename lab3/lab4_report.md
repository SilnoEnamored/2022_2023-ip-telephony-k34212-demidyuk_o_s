University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [IP-telephony](https://github.com/itmo-ict-faculty/ip-telephony)  
Year: 2023  
Group: K34212    
Author: Demidyuk Oleg Sergeevich   
Lab: Lab4   
Date of create: 25.03.2023   
Date of finished: ...   

Цель работы: Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т.
Ход работы:

ЧАСТЬ 1 

1. Была собрана схема соединения. Изменино название роутеров и свичей на RouterA, RouterB, SwitchA, SwitchB.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/1.jpg)

2. Была создана конфигурация интерфейса fa0/0 на маршрутизаторе RouterA и RouterB.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/2.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/3.jpg)

3. Также создана конфигурация интерфейса s0/1/0 на маршрутизаторах Cisco 2811.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/4.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/5.jpg)

4. Для автоматической настройки компьютеров и IP-телефонов в сети был настроен DHCP сервер на маршрутизаторе Cisco 2811. В
конфигурационном режиме создан пул DHCP.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/6.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/7.jpg)

5. Далее была произведена настройка динамической маршрутизации на основе протокола RIP второй версии для передачи информации между маршрутизаторами в сети.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/8.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/9.jpg)

6. Затем была настроен CallManager Express.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/10.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/11.jpg)

7. Назначены диапозоны портов на свитчах. 

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/12.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/13.jpg)

8. Далее каждому телефону был присвоен номер, на маршрутизаторе RouterA: 1101,1102,1103 и на RouterB: 1201,1202,1203. Была произведена дополнительная конфигурация, были созданы логические "телефонные" линии. 

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/14.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/15.jpg)

9. Были проверены звонки между соседними и удаленными телефонами.

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/16.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/17.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/18.jpg)

![Image text](https://github.com/SilnoEnamored/2022_2023-ip-telephony-k34212-demidyuk_o_s/raw/main/lab3/screenshots/19.jpg)

Вывод: В ходе работы была построена и изучена сеть IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т.
