# here-assignment-example
it is an example of implementing websocket(ws) on both server and client side

## Install
```
$ npm install --save ws express
or 
$ git clone git@github.com:wahengchang/here-assignment-example.git
```

## Unstanding ws
 `ws` is a WebSocket client and server implementation, fast, and easy to use.
#### client
`websocket client` is a browser supported object.

There are 3 basic must know fucntions:
 - `ws.onopen` : emmited when connected
 - `ws.send` : sending a send event to websocket server
 - `ws.onmessage` : event emmited when receiving message 

([Read More](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_client_applications))


## Run

Run server
```
$ npm start
``` 

Open browser
```
http://localhost:3000/
```
