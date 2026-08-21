# nivra-serv

Este repo tiene un único trabajo: decirle a la app **NIVRA** dónde está el
servidor en este momento.

El servidor corre en una PC y sale a internet por un túnel, cuya dirección
cambia cada vez que se reinicia. En vez de grabar esa dirección adentro del
APK (lo que obligaría a recompilar y reinstalar la app en cada cambio), la
app lee `servidor.txt` de acá al arrancar.

`servidor.txt` se actualiza solo cuando se abre `INICIAR-APP.bat`.

**Este repo es público a propósito** y no contiene nada sensible: solo una
línea con una dirección web. El código de la app, la base de datos y las
claves están en un repo privado aparte.
