# Meeting Bingo Server

For now, this is a simple web server that relays messages between clients. When one client sends a message, the message is broadcast to all clients with an established WebSocket connection with the server.

## Start server
```
go get github.com/gorilla/websocket
go build
./meeting-bingo-backend
```

The front end connects to the WebSocket endpoint at `http://localhost:8080/ws`
