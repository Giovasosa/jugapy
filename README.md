# JugáPY

Prototipo de una red social para alquilar canchas, organizar torneos y conocer gente para jugar. Trabajo práctico de la materia, hecho por Giovanni Sosa, Carlos Sánchez y Tiago López.

Es una sola página HTML sin dependencias. Abrí `index.html` en el navegador o entrá a la versión publicada con GitHub Pages.

## Qué se puede probar

- Buscar canchas por deporte y zona
- Reservar una franja horaria (las ocupadas aparecen bloqueadas) y pagar la seña, con pago simulado
- Inscribirse en un torneo y ver fixture y posiciones
- Seguir jugadores, unirse a partidos abiertos y chatear
- Ver las reservas en el perfil

Los datos son de ejemplo y no se guardan al recargar la página.

## Pruebas

`tests/test_prototipo.py` recorre el prototipo con Playwright y comprueba los 17 casos de prueba del informe (validación de acceso, reserva, bloqueo de franjas, torneos, comunidad, chat, cancelación y diseño a 360 px). También guarda las capturas de pantalla en `tests/capturas/`.

```
pip install playwright
playwright install chromium
python tests/test_prototipo.py
```
