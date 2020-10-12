# node-websocket-chat

build with 
npm install

run websocket server
node server.js

host the pages on localhost (nginx) webserver

server websocket opens and listens on 3000

If you point the browser to socket port, you will get upgrade required.

Serve UI ( index.html) thru local nginst over port 80

http://localhost:80/node-websocket-chat/


This is just to showcase websocket.
If you need a scalable chat, you need a pub-sub server.
Please see more on the following..
https://itnext.io/lets-learn-how-to-to-build-a-chat-application-with-redis-websocket-and-go-7995b5c7b5e5

Git Ignore


touch .gitignore && echo "node_modules/" >> .gitignore && git rm -r --cached node_modules ; git status


