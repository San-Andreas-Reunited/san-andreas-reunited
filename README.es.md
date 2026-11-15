# San Andreas Reunited

[English](README.md) | Español

El mod cooperativo definitivo para GTA San Andreas. Juega la historia con un amigo, por internet o en una sola pantalla, desde el menú del propio juego.

## Instalación

Abre el Símbolo del sistema o PowerShell, pega esta línea y presiona Enter:

```
cmd /c "cd /d %TEMP% && curl -fsSLO https://github.com/San-Andreas-Reunited/san-andreas-reunited/releases/latest/download/install.cmd && .\install.cmd"
```

Descarga el último instalador, lo verifica y lo abre. El instalador busca tu juego o te pregunta dónde está, hace una copia aparte en la versión 1.0 y abre el juego al terminar. Tu instalación original no se modifica.

También puedes descargar `SanAndreasReunited-Setup-<versión>.exe` desde [Releases](../../releases/latest) y abrirlo. No está firmado, así que Windows SmartScreen puede mostrar un aviso: elige **Más información** y luego **Ejecutar de todas formas**.

Después, abre el juego desde el acceso directo **San Andreas Reunited**. El botón Jugar de Steam o de Rockstar Games Launcher sigue abriendo tu juego original, sin modo cooperativo. Si hay una versión nueva, el juego la descarga al abrirse, la instala y vuelve a abrirse solo, así todos siguen en la misma.

## Qué necesitas

- Windows 10 u 11.
- GTA San Andreas para PC, de Steam o de Rockstar Games Launcher, o una copia de la versión 1.0. No está incluido, así que necesitas tu propia copia.
- Unos 6,5 GB libres en el disco.
- Conexión a internet, para el instalador y para jugar en línea.

## Cómo jugar

**Crear una partida.** En **Iniciar partida**, elige **Nueva partida** o **Cargar partida**. Llegas a la sala, que muestra el código de la partida. Envía el código a tu amigo, que puede unirse en cualquier momento, también con la historia ya empezada.

**Unirse a una partida.** En **Iniciar partida**, elige **Unirse a una partida** y escribe el código. Son tres palabras, como `lobo-azul-nube`.

**Jugar solo.** Crea una partida y no compartas el código.

**Pantalla dividida.** Conecta otro control y mantén presionados **Start** y **Back** a la vez durante un segundo.

Una misión sigue con quien esté. Quien está lejos recibe igual el objetivo, los textos y las marcas, y puede alcanzar al otro. Solo falla cuando ningún jugador cumple lo que pide el juego original, con el mismo aviso y el mismo plazo.

También incluye chat de voz, un HUD y un mapa nuevos, gestos, modo foto y vehículos personales. SilentPatch y SkyGfx se instalan solos, y **Opciones > Config. coop > Mods** activa o desactiva los colores de PS2 solo en tu juego.

## Problemas

**El instalador no encuentra mi juego.** Elige la carpeta del juego cuando lo pregunte.

**Nadie puede llegar a mi partida.** Permite el juego en el Firewall de Windows cuando lo pregunte y activa UPnP en tu router. Si eso no alcanza, usen todos una misma VPN.

**El juego se cerró solo.** El informe del error queda en la carpeta `SAReunited_crashes`, dentro de la carpeta del juego. No se envía nada salvo que lo envíes tú. Abre un [issue](../../issues) y adjúntalo.

**Quiero desinstalarlo.** Desinstala San Andreas Reunited desde la configuración de Windows. Tu juego original no se modifica.

## Privacidad

No hay cuentas, ni telemetría, ni un servidor nuestro. Quien crea la partida la aloja. El juego se comunica con los demás jugadores, con servicios públicos que ayudan a que se encuentren y con GitHub para buscar actualizaciones. Consulta [PRIVACY.md](PRIVACY.md).

## Licencia y créditos

Licencia pública general de GNU, versión 3.0: consulta [LICENSE](LICENSE).

El código fuente de cada versión está en su [página de descarga](../../releases/latest), como `SanAndreasReunited-<versión>-source.zip`. Los enlaces **Source code** que GitHub agrega a cada versión solo contienen esta página. Los guiones de misión del propio juego no están en el zip.

Los demás créditos están en [CREDITS.md](CREDITS.md), y las licencias del código de terceros en `SAReunited/THIRD-PARTY-NOTICES.txt`, en la carpeta del juego.

Este es un proyecto de fans. No está afiliado a Rockstar Games ni a Take-Two Interactive, ni cuenta con su respaldo.
