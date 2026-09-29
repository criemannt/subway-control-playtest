# SUBWAY CONTROL playtest

Open the [Sites browser lobby](https://subway-control-playtest.riemann-c.chatgpt.site/play/).
**The streaming host is offline while the owner's Windows PC is being configured.**

The planned browser flow uses a six-character room code and two separate Unreal streams.
Testers will use a desktop browser on macOS or Windows without installing the game or a VPN.
Windows packaging, the internet relay, actual browser input, and a separate-network match/rematch are still pending.

The [0.2.0 release](https://github.com/criemannt/subway-control-playtest/releases/tag/v0.2.0) remains an optional native Apple silicon Mac download (macOS 14+).
It includes Q/W/E selection, the handwritten driver note, and the persistent grid power meter.
For a native LAN session, both players use the same Mac build; Host Multiplayer and Join Multiplayer use the host's LAN IP and UDP port 7777.

Two rendered packaged processes completed lessons, full matches, and rematches on one Mac with 80 ms simulated outgoing latency.
Two separate WebRTC protocol clients also received live video and isolated input from two Unreal processes on that Mac.
These local checks do not verify actual browsers, separate physical devices, or an internet-reachable host.
