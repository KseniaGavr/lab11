# Лабораторная работа №11

### Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачиваю ngrok<br />
```$ ngrok config add-authtoken 2PKbzib3vbB0pJOeY3faOrNxOCL_5nFREJMsewBF1Nfgg467t``` - Добавляю свой токен в ngrok.yml для удобной работы с сервисом<br />
```$ sudo apt-get install openssh-server``` - скачиваю сервер <br />
```$ sudo systemctl start ssh``` - запускаю<br />
```$ sudo systemctl status ssh``` - проверяю<br />
новое окно консоли<br />
```$ python3 -m http.server``` - распакова модуля http.server<br />
```$ nano index.html``` - создаю<br />
```$ ngrok tcp 22``` - запускаю TCP туннель<br />
![Снимок экрана от 2023-06-01 17-47-52](file:///home/ksenia/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BA%D0%B8%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-06-02%2017-55-17.png)<br />
***ssh 6.tcp.eu.ngrok.io -p 12977***
