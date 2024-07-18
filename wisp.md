# Wisp

Wisp is a lightweight networking protocol to proxy TCP and UDP (and more) through a Websocket connection. It's spec is designed to be easy to implement and lightweight not requiring a Roundtrip per connection allowing you to immediately start sending data. This saves time on socket creation which is important for responsiveness on slow connections.