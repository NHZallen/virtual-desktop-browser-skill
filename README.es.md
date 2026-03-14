# Virtual Desktop Browser (Español)

Una skill para OpenClaw/agentes que ejecuta **Chromium en modo no headless** sobre un **display virtual Xvfb (fijo 1200x720x24)** y realiza automatización tipo humano con PyAutoGUI.

## Funciones
- Iniciar/detener Xvfb + Chromium
- Clic de ratón, escritura, atajos de teclado
- Scroll, captura de pantalla, color de píxel
- Búsqueda por plantilla de imagen (OpenCV)
- Activación de ventana

## Dependencias del sistema
```bash
sudo apt-get update
sudo apt-get install -y xvfb chromium-browser \
  libnss3 libgconf-2-4 libxss1 libasound2 \
  libatk1.0-0 libatk-bridge2.0-0 libcups2 \
  libdrm2 libgbm1 libgtk-3-0 libxshmfence1 x11-utils
```

## Dependencias de Python
```bash
pip install -r requirements.txt
```

## Autor
Creador: **Allen Niu**
