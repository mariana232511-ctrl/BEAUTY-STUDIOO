# Beauty Studio Web — inicio para principiantes

Este paquete contiene una primera versión web basada en el prototipo de Beauty Studio.
Todavía no incluye cuentas de usuario, base de datos ni conexión a una IA real.

## Antes de comenzar
Necesitas un computador con Windows, macOS o Linux y conexión a internet para instalar las herramientas.

1. Instala Node.js LTS desde https://nodejs.org/ (elige la versión LTS).
2. Instala Visual Studio Code desde https://code.visualstudio.com/.
3. Descomprime `beauty_studio_web.zip` en una carpeta fácil de encontrar, por ejemplo Documentos.
4. Abre Visual Studio Code y elige **File > Open Folder** (Archivo > Abrir carpeta). Selecciona la carpeta `beauty_studio_web`.
5. En Visual Studio Code abre **Terminal > New Terminal** (Terminal > Nueva terminal).
6. Escribe estos comandos, uno por uno, pulsando Enter después de cada línea:

   npm install

   npm run dev

7. La terminal mostrará una dirección local, normalmente http://127.0.0.1:5173/. Mantén la terminal abierta y abre esa dirección en tu navegador.
8. Para detener el servidor, vuelve a la terminal y pulsa Ctrl+C.

## Comprobar que el proyecto se puede compilar
Cuando quieras comprobar el paquete, detén el servidor con Ctrl+C y ejecuta:

   npm run build

Si termina sin errores, se creará una carpeta `dist` con la versión preparada para publicar.

## Próximas mejoras
- Separar la web en componentes y páginas.
- Añadir más lecciones con contenido propio o autorizado.
- Guardar favoritos y progreso de forma persistente.
- Añadir registro e inicio de sesión.
- Conectar una API de IA desde un servidor seguro (nunca poner claves secretas en el código del navegador).
- Publicar la web y probarla en varios dispositivos.

## Si algo falla
- Si aparece `npm no se reconoce`, cierra y vuelve a abrir Visual Studio Code después de instalar Node.js.
- Si el puerto 5173 está ocupado, Vite te mostrará otra dirección; abre la que aparezca en la terminal.
- Copia el mensaje de error completo y pide ayuda antes de cambiar muchos archivos.
