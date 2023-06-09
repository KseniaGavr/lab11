# Лабораторная работа №11

### Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачать ngrok<br />
```$ ngrok config add-authtoken 2PKbzib3vbB0pJOeY3faOrNxOCL_5nFREJMsewBF1Nfgg467t``` - Добавление токена в ngrok.yml для удобной работы с сервисом<br />
```$ sudo apt-get install openssh-server``` - скачать сервер <br />
```$ sudo systemctl start ssh``` - запус<br />
```$ sudo systemctl status ssh``` - проверка<br />
новое окно консоли<br />
```$ python3 -m http.server``` - распакова модуля http.server<br />
```$ nano index.html``` - создание<br />
```$ ngrok tcp 22``` - запуск TCP туннеля<br />
![Снимок экрана от 2023-06-01 17-47-52](blob:https://web.telegram.org/c70b3d95-bc84-419c-8037-63faab734646)<br />
***ssh 6.tcp.eu.ngrok.io -p 12977***
