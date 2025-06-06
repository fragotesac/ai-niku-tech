# 🧠 Ollama + Open WebUI - Docker Compose Setup

Este proyecto configura un entorno local para ejecutar modelos de lenguaje con **Ollama** y una interfaz gráfica amigable usando **Open WebUI**.

---

## 📦 Servicios Incluidos

### 1. **Ollama**
- Servidor de modelos LLM local.
- Expone la API en el puerto `11434`.
- Soporte para GPU NVIDIA (comentado por defecto).
- Persistencia de modelos en `./models` y datos en volumen Docker.

### 2. **Open WebUI**
- Interfaz web para interactuar con modelos LLM usando la API de Ollama.
- Accesible en [http://localhost:3000](http://localhost:3000).
- Sin autenticación por defecto (`WEBUI_AUTH=False`).

---

## 🚀 Cómo Iniciar

```bash
docker compose up -d
```

Esto iniciará todos los servicios en segundo plano. Usa docker compose logs -f para ver los logs.


