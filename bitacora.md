# Bitácora

Al cerrar cada sesión anota: qué hice, qué decidí y por qué, y por dónde sigo.

---

## Sesión 1 — 2026-10-08

**Hice:**

- Creé el repositorio y la estructura de carpetas.
- Descargué el dataset de Kaggle y lo cargué en el notebook.
- Creé un entorno virtual (.venv) con Python 3.12 y las librerías del proyecto.
- Guardé las dependencias en requirements.txt.

**Decisiones (y por qué):**

- Trabajar en VS Code local en vez de Colab: los archivos quedan en la carpeta del repositorio y GitHub Desktop detecta los cambios.
- Entorno propio en vez del Python de Anaconda: había un conflicto entre versiones de NumPy (pandas instalado fuera de Anaconda). El entorno aislado lo evita.
- El CSV no se sube al repositorio (.gitignore); se descarga desde Kaggle.

**Sigo con:**

- Etapa 1: conocer los datos (tipos, nulos, duplicados, valores raros).
