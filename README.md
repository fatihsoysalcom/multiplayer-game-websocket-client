# Multiplayer Game WebSocket Client

This example demonstrates a basic HTML/JavaScript client for a multiplayer game using WebSockets. It simulates a game area where multiple players can move around. The client connects to a WebSocket server, sends player movement commands, and receives real-time position updates for all players, showcasing the core communication mechanism for interactive multiplayer experiences.

## Language

`html`

## How to Run

1. Save the code as `index.html`.
2. You need a simple WebSocket server running on `ws://localhost:8765`. A minimal Python server using the `websockets` library can be set up (e.g., `pip install websockets` then run a `server.py` script).
3. Open `index.html` in your web browser. Open multiple tabs/windows to simulate multiple players interacting.

## Original Article

This example accompanies the Turkish article: [Limn Motoru ve WebSockets ile Çok Oyunculu Oyun Geliştirme: Kapsamlı Bir Rehber](https://fatihsoysal.com/blog/limn-motoru-ve-websockets-ile-cok-oyunculu-oyun-gelistirme-kapsamli-bir-rehber/).

## License

MIT — see [LICENSE](LICENSE).
