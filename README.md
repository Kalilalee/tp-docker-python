# TP: Docker con Python (Flask)

## 🚀 Objetivo
- Reforzar el manejo del control de versiones con Git y plataformas remotas (GitHub, GitLab o Bitbucket).
- Comprender el ciclo de vida completo de un contenedor en Docker.
- Integrar una aplicación simple dentro de un entorno contenerizado reproducible.
- Documentar el proceso técnico y los comandos empleados en un archivo README.md profesional.

## 🧱 Tecnologías usadas
- Git / GitHub
- Docker
- Python 3.10
- Flask

## 🧩 Pasos del proyecto
1. Clonar el repositorio
2. Construir la imagen:
   ```bash
   docker build -t docker-py .
3. Ejecutar el contenedor:
   ```bash
   docker run -d -p 5000:5000 docker-py
4. Visitar en el navegador:
   ```bash
   http://localhost:5000
