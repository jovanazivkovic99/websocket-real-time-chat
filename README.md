# WebSocket Chat Aplikacija

WebSocket chat aplikacija implementirana koristeći Spring Boot i WebSocket protokol. Ova aplikacija omogućava korisnicima da se povežu na chat, šalju poruke u realnom vremenu i vide obaveštenja kada se neko pridruzi ili napusti chat.

## Konfiguracija WebSocket-a

WebSocket konfiguracija omogućava povezivanje na endpoint `/ws` i koristi STOMP protokol za komunikaciju. Poruke se šalju na destinaciju `/app/chat.sendMessage` za slanje poruka i `/app/chat.addUser` za dodavanje novih korisnika. Sve poruke se distribuiraju preko `/topic/public`.

## Napravljen front u html radi testiranja: 

![image](https://github.com/jovanazivkovic99/websocket-real-time-chat/assets/116586798/d5b19023-0108-4bbf-86c7-028def088d24)
