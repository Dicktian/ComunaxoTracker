COMUNAXO TRACKER



Versión: 1.7

Compatibilidad: World of Warcraft 3.3.5a (Wrath of the Lich King)

Autor: Comunaxo ([https://github.com/Dicktian](https://github.com/Dicktian))



============================================================

1\. ¿QUÉ ES COMUNAXO TRACKER?

============================================================



ComunaxoTracker es un addon de gestión y seguimiento de personajes que reúne en una sola interfaz información de los personajes de una cuenta de World of Warcraft 3.3.5a.



Permite consultar los recursos, profesiones, emblemas, estadísticas PvP, bloqueos de bandas y notas registrados. Resulta útil para administrar varios personajes sin tener que iniciar sesión con cada uno para consultar su última información guardada.



Los datos de un personaje desconectado reflejan su último registro: no se actualizan en tiempo real.



============================================================

2\. ¿QUÉ INFORMACIÓN REGISTRA?

============================================================



\- PERSONAJES: nombre, clase, nivel, hermandad y datos de equipo. Identifica las clases mediante colores y permite reorganizar las filas.



\- ORO Y OFICIOS: dinero desglosado en oro, plata y cobre; premios de cocina y fichas de joyería de Dalaran.



\- PROFESIONES: profesiones principales y secundarias, niveles de habilidad y equitación, con colores según los rangos.



\- EMBLEMAS: Escarcha, Triunfo, Conquista, Valor y Heroísmo.



\- PVP: puntos de honor, puntos de arena y muertes honorables.



\- BANDAS: bloqueos registrados de Ciudadela de la Corona de Hielo (ICC), Cámara de Archavon (VoA), Sagrario Rubí (RS), Prueba del Cruzado (ToC) y Prueba del Gran Cruzado (ToGC), según los datos disponibles del cliente, en modalidades aplicables de 10 y 25 jugadores.



\- NOTAS: Una pizarra con guardado automático y límite de 1.200 unidades de texto por pizarra.



\- DKP GLOBAL: campo editable para mantener un valor de DKP compartido entre los personajes registrados en la misma cuenta.



============================================================

3\. ¿CÓMO ES SU INTERFAZ?

============================================================



La ventana utiliza una estética minimalista en tonos grises, con información organizada en tablas y pestañas. Los personajes pueden ordenarse manualmente arrastrando sus filas.



Incluye acceso desde un botón del minimapa y una guía integrada de funciones y comandos.



============================================================

4\. INSTALACIÓN

============================================================



1\. Cierra World of Warcraft.

2\. Extrae el archivo .zip del addon.

3\. Copia la carpeta «ComunaxoTracker» dentro de:



World of Warcraft/Interface/AddOns/



4\. Comprueba que el archivo principal esté en:



Interface/AddOns/ComunaxoTracker/ComunaxoTracker.toc

Interface/AddOns/ComunaxoTracker/ComunaxoTracker.lua



5\. Inicia World of Warcraft 3.3.5a y activa el addon en la pantalla de selección de personajes si es necesario.

6\. Entra con cada personaje que quieras registrar para actualizar sus datos.



Si el addon no aparece en la lista, comprueba que no haya una carpeta «ComunaxoTracker» duplicada dentro de otra del mismo nombre.



============================================================

5\. COMANDOS

============================================================



/ct             Abre o cierra la ventana principal.

/chartracker    Abre o cierra la ventana principal.

/ctsave         Actualiza los datos del personaje conectado.

/emblems        Abre o cierra la ventana principal.

/ctdebug        Muestra información de diagnóstico.

/ctguild        Comprueba la información de hermandad.



También puedes abrir el addon mediante su botón del minimapa.



============================================================

6\. FUNCIONAMIENTO TÉCNICO Y GUARDADO

============================================================



El addon está diseñado para la interfaz 30300 de World of Warcraft 3.3.5a y utiliza el archivo ComunaxoTracker.lua para su funcionamiento.



Guarda información localmente mediante las variables persistentes de WoW:



\- ComunaxoTrackerDB

\- EmblemTrackerDB



Los datos se conservan en los archivos SavedVariables de la carpeta WTF del juego. No se sincronizan automáticamente entre diferentes cuentas u ordenadores ni se envían a un servicio externo.



IMPORTANTE: no elimines las SavedVariables si deseas conservar los registros. La opción de reinicio total puede borrar personajes guardados, orden de filas, notas y DKP de esa cuenta.



============================================================

7\. LIMITACIONES Y COMPATIBILIDAD

============================================================



\- Diseñado para WoW 3.3.5a (Wrath of the Lich King), interfaz 30300.

\- Los datos de personajes desconectados pueden estar desactualizados hasta volver a entrar con ellos.

\- Los bloqueos de bandas dependen de la información que proporciona el cliente del juego.

\- Los datos de distintas cuentas no se combinan automáticamente.

\- El funcionamiento puede variar en servidores privados con modificaciones propias.

\- Es un proyecto independiente y no oficial de Blizzard Entertainment.



============================================================

8\. PREGUNTAS FRECUENTES

============================================================



¿Puedo consultar personajes sin conectarme con ellos?

Sí, siempre que hayan sido registrados previamente. Verás su última información guardada.



¿Se actualizan todos los personajes en tiempo real?

No. Debes entrar con cada personaje para renovar sus datos.



¿Puedo organizar manualmente los personajes?

Sí. La interfaz permite cambiar el orden de las filas.



¿El dinero se muestra como una única cantidad de oro?

No. Se presenta desglosado en oro, plata y cobre.



¿Puedo utilizarlo en varias cuentas?

Sí, pero los registros de cada cuenta se guardan por separado y no se sincronizan automáticamente.



¿Tiene botón de minimapa?

Sí. También puedes abrirlo mediante /ct o /chartracker.



¿Cómo conservo los datos al actualizar?

Sustituye los archivos del addon en Interface/AddOns sin borrar los archivos SavedVariables correspondientes en WTF.



============================================================

9\. INFORMACIÓN DEL PROYECTO

============================================================



Nombre: ComunaxoTracker

Versión: 1.7

Autor: Comunaxo ([https://github.com/Dicktian](https://github.com/Dicktian))

Juego: World of Warcraft: Wrath of the Lich King

Interfaz: 30300

Idioma: Español

Archivos principales: ComunaxoTracker.toc y ComunaxoTracker.lua

Variables guardadas: ComunaxoTrackerDB y EmblemTrackerDB



© Comunaxo



