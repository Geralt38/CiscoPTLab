1) Скриншот построенной топологии.


![img](https://i.imgur.com/Xry8QbG.png)

2) Какой протокол использует утилита tracert? На каком уровне модели OSI? Скриншот, подтверждающий Вашу точку зрения.

Протокол ICMP на сетевом уровне модели OSI.
Event List после исполнения команды tracert:
![img](https://i.imgur.com/H4sjZVn.png)

3) Анализ использования утилиты nslookup. На каком протоколе работает, на каком уровне модели OSI? Анализ результатов выполнения команды (что пытались сделать, что получили, почему). Скриншот. 

Протокол DNS на прикладном уровне модели OSI.
При попытке использования команды nslookup мы получаем в ответе "DNS request timed out.", так как в нашей сети нет узла, заявленного как DNS-сервер. (PC посылает DNS-пакет на хаб, который рассылает DNS-пакеты всем узлам сети, но те не отвечают на эти пакеты, так как они не DNS-сервера)

Результат работы команды nslookup:

![img](https://i.imgur.com/evnlOS2.png)

EventList после исполнения команды nslookup:

![img](https://i.imgur.com/fM1J5vW.png)

