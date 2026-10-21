# Adivina el número

Mi primer juego de consola en Python. Adivina un número del 1 al 100 en siete intentos. El juego te dice si debes probar un número mayor o menor.

## Cómo ejecutarlo en Windows

Necesitas Python 3. No requiere librerías adicionales. Si aún no tienes Python, puedes obtenerlo en https://www.python.org/downloads/.

1. Descarga y descomprime el proyecto.
2. Abre la carpeta que contiene `main.py` en el Explorador de archivos.
3. Escribe `powershell` en la barra de direcciones y presiona Enter.
4. Ejecuta:

```powershell
python main.py
```

Si `python` no funciona, prueba `py main.py`.

Escribe un número y presiona Enter. Las entradas inválidas no gastan intentos. Al terminar, escribe `s` para jugar otra vez. Puedes escribir `salir` durante una partida o presionar Ctrl+C para cerrar.

## Cómo subirlo a GitHub manualmente

1. Inicia sesión en GitHub y crea un repositorio con el nombre `adivina-el-numero`.
2. Elige si quieres que sea público o privado y crea el repositorio vacío.
3. En la página del repositorio, busca la opción para subir archivos (`uploading an existing file` o `Add file` → `Upload files`).
4. Sube `main.py`, `README.md` y `.gitignore` desde la carpeta descomprimida. El archivo `.gitignore` puede estar oculto en el Explorador.
5. Confirma la subida con `Commit changes`.

Sube los archivos descomprimidos para poder ver el código directamente en GitHub.

## Qué puedes aprender

- `input()` y `print()`: leer respuestas y mostrar mensajes.
- `int()` y `try/except`: convertir y validar números.
- `if` y `while`: tomar decisiones y repetir instrucciones.
- Funciones: organizar el programa en partes.
- `random.randint()`: elegir un número al azar.

Para practicar, cambia `intentos = 7` por `intentos = 10` y actualiza el mensaje de bienvenida de la ronda.
