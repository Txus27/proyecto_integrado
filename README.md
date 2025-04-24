Descripción del trabajo
Este trabajo consiste en la instalación de Home Assistant Supervised usando Docker en Debian (Linux) para la gestión de los dispositivos de domótica, además integraré DuckDNS para tener actualizada mi IP pública y poder acceder a mi equipo desde fuera de mi casa.

Más adelante describiré qué es cada cosa detalladamente.

El objetivo es poder controlar los dispositivos domóticos en un entorno centralizado y de software libre, lo cuál nos da un extra de seguridad al estar el código fuente supervisado por la comunidad. Otra de las principales virtudes de este software es la posibilidad de gestionar los dispositivos compatibles de manera local, sin tener que depender de los servidores del fabricante o de terceros, lo cual nos dá un extra de privacidad y una mejora del rendimiento de los dispositivos al ejecutarse de manera local, además de acabar con la obsolescencia programada del dispositivo cuando las marcas le retiran el soporte. 

Para este trabajo usaré un enchufe inteligente con el firmware Tasmota, que nos permitirá controlarlo desde Home Assistant de manera local, y una cámara de seguridad Reolink E1 Zoom que podremos ver y controlar desde Home Assistant y además enviará el video a un servidor FTP que crearé en el equipo anfitrión para ese fin.
