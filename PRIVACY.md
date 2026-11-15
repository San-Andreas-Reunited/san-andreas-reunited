# Privacy

San Andreas Reunited has no accounts, no telemetry and no server of its own, and it does not send crash reports to anyone.

[Leer en español](#privacidad)

## What stays on your computer

When the game crashes, it writes a log (`.log`), a memory dump (`.dmp`) and a record of its last moments (`.box`) to the `SAReunited_crashes` folder inside the game folder. Nothing is uploaded. If you want help with a crash, you can share those files yourself. A memory dump holds whatever the game had in memory, so share it only with people you trust.

The original project can upload anonymous crash reports to its developers. San Andreas Reunited does not have that upload.

## What the game connects to

While you play:

- **The other players in your game.** They can see your IP address, your name in the game and what you write in the chat or say by voice.
- **The public BitTorrent DHT**, so that players can find each other from a code. The first contact is with router.bittorrent.com, router.utorrent.com, dht.transmissionbt.com and dht.libtorrent.org. The nodes see your IP address and a number shared by many games. The code itself never leaves your computer.
- **Public STUN servers** (stun.l.google.com, stun1.l.google.com, stun.cloudflare.com and global.stun.twilio.com), to learn the address your connection has on the internet. They see your IP address.
- **Your router**, through UPnP, to open the game's port.
- **GitHub**, to look for a new version when the game opens and to download it. GitHub sees your IP address.

During the setup:

- **GitHub**, to download the patches that take your copy to version 1.0 (Jetpack Downgrader), SilentPatch and SkyGfx from their authors' pages. GitHub sees your IP address.

Only if you use them:

- **Songs from YouTube.** yt-dlp and Deno are downloaded from GitHub the first time, and the songs come from YouTube, which sees your IP address.
- **Discord.** If the Discord app is open on your computer, the game tells it what you are doing in the game and how many players are in your game, and Discord shows that on your profile. The code of your game is not sent.

---

# Privacidad

San Andreas Reunited no tiene cuentas, ni telemetría, ni un servidor propio, y no envía informes de errores a nadie.

## Lo que queda en tu computadora

Cuando el juego se cierra por un error, escribe un registro (`.log`), un volcado de memoria (`.dmp`) y una grabación de sus últimos momentos (`.box`) en la carpeta `SAReunited_crashes`, dentro de la carpeta del juego. No se sube nada. Si necesitas ayuda con un error, puedes compartir esos archivos tú mismo. Un volcado de memoria contiene lo que el juego tenía en memoria, así que compártelo solo con personas de confianza.

El proyecto original puede subir informes de errores anónimos a sus desarrolladores. San Andreas Reunited no incluye esa función.

## Con qué se conecta el juego

Mientras juegas:

- **Los demás jugadores de tu partida.** Pueden ver tu dirección IP, tu nombre en el juego y lo que escribes en el chat o dices por voz.
- **La DHT pública de BitTorrent**, para que los jugadores se encuentren a partir de un código. El primer contacto es con router.bittorrent.com, router.utorrent.com, dht.transmissionbt.com y dht.libtorrent.org. Los nodos ven tu dirección IP y un número que comparten muchas partidas. El código nunca sale de tu computadora.
- **Servidores STUN públicos** (stun.l.google.com, stun1.l.google.com, stun.cloudflare.com y global.stun.twilio.com), para conocer la dirección que tiene tu conexión en internet. Ven tu dirección IP.
- **Tu router**, por UPnP, para abrir el puerto del juego.
- **GitHub**, para buscar una versión nueva cuando se abre el juego y para descargarla. GitHub ve tu dirección IP.

Durante la instalación:

- **GitHub**, para descargar de las páginas de sus autores los parches que cambian tu copia a la versión 1.0 (Jetpack Downgrader), SilentPatch y SkyGfx. GitHub ve tu dirección IP.

Solo si los usas:

- **Canciones de YouTube.** yt-dlp y Deno se descargan de GitHub la primera vez, y las canciones vienen de YouTube, que ve tu dirección IP.
- **Discord.** Si la aplicación de Discord está abierta en tu computadora, el juego le indica lo que estás haciendo en el juego y cuántos jugadores hay en tu partida, y Discord lo muestra en tu perfil. El código de tu partida no se envía.
