Запуск сервера

В консоли:

npm init -y
npm install express socket.io
node server.js


Ты увидишь:

Сервер запущен на порту 3000

Подключаем ngrok

В другой вкладке консоли:

ngrok http 3000


ngrok покажет тебе примерно такое:

Forwarding  https://1234abcd.ngrok.io -> http://localhost:3000

https://1234abcd.ngrok.io - ваш публичный адрес.
 
 # zvonok
