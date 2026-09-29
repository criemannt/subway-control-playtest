# SUBWAY CONTROL playtest

Get the playtest and Host/Join instructions from [the Sites playtest page](https://subway-control-playtest.riemann-c.chatgpt.site).

The 0.2.0 release provides a native Apple silicon Mac game download (macOS 14+).
Windows packaging and separate-device internet validation are still pending.

Each player downloads the same build. Use Host Multiplayer and Join Multiplayer with the host IP:port;
for different networks, connect the computers through Tailscale device sharing first. UDP port: 7777.
The game's lesson teaches Q/W/E, Space, and 1/2/3. Both players can ready for a rematch after results.

Two independently rendered packaged processes passed the connected lesson, a full match,
and rematch on one Mac through its network address with 80 ms simulated outgoing latency.
Both dispatched all 13 trains in both rounds and agreed on authoritative results.
This does not verify physical devices or an internet-reachable host.
