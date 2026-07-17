# Vigía Limarí PRO — El Tiempo en Ovalle

Panel del tiempo para Ovalle (Región de Coquimbo) con ensamble Monte Carlo
alimentado en vivo por los modelos globales ECMWF, GFS (NOAA) e ICON (DWD),
más humedad, presión, viento, nubosidad, UV, visibilidad, sol/luna y calidad
del aire (AQI) vía Open-Meteo. Incluye línea de tiempo reproducible, gráficos
interactivos con hover, tarjetas de día expandibles y mini-mapa de la zona.

Es un sitio 100% estático: un solo `index.html` sin dependencias de build.

## Desplegar en Render
1. Sube esta carpeta a un repositorio de GitHub.
2. En https://dashboard.render.com → **New +** → **Static Site**.
3. Conecta el repositorio.
4. Build Command: (déjalo vacío) · Publish Directory: `.`
5. **Create Static Site**. Render entrega una URL pública (https://…onrender.com).

El `render.yaml` incluido permite además usar **New + → Blueprint** para que
Render lea la configuración automáticamente.
