```ini
[LINE]
EXPOSE_HOST = 127.0.0.1
EXPOSE_PORT = 80
CHANNEL_ACCESS_TOKEN =
CHANNEL_SECRET =
ROOM =

[Matrix]
HOME_SERVER =
USERNAME =
PASSWORD =
ROOM =
```

## LINE

`LINE Messaging API` is using [Webhook](https://en.wikipedia.org/wiki/Webhook), which is required the host of bridge exposed on Internet.

Please make sure your server can be visible external, and the port you configured(`EXPOSE_PORT`) is available.

- EXPOSE_HOST

As known as the address for exposing your LINE bridge on specific network, default value is `127.0.0.1`.

- EXPOSE_PORT

- `CHANNEL_ACCESS_TOKEN` and `CHANNEL_SECRET`

https://developers.line.biz/en/docs/messaging-api/getting-started/

- ROOM

# Matrix

- HOME_SERVER
- USERNAME
- PASSWORD
- ROOM
