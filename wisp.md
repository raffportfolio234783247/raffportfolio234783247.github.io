# Wisp

Wisp is a lightweight networking protocol to proxy TCP and UDP (and more through protocol extension) through a Websocket connection. It's specification is designed to be easy to implement and lightweight not requiring a Roundtrip per connection allowing you to immediately start sending data. This saves time on socket creation which is important for responsiveness on slow connections.