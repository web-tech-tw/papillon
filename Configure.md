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

The port which is used to expose on Internet for `LINE Webhook Agent` visiting, default value is `80`.

- CHANNEL_ACCESS_TOKEN and CHANNEL_SECRET

Both of them are required to identity your BOT and verify the events incoming, more detail please check

https://developers.line.biz/en/docs/messaging-api/getting-started

- ROOM

ROOM is the ID of target which is fixed for transporting the messages from Matrix.

https://developers.line.biz/en/faq/#what-are-user-id-groupid-roomid

# Matrix

- HOME_SERVER

https://matrix.org/faq/#what-is-a-homeserver%3F

- USERNAME

https://matrix.org/faq/#what-is-a-mxid%3F

example:
`@supersonictw:matrix.org`

- PASSWORD



- ROOM

example:
`!yTRzUDNyviBhrMwYGG:matrix.org`
