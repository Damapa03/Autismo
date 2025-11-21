# Instrucciones
## Estructura del proyecto
- `deployment/`: configuración de despliegue (Docker Compose, manifiestos y scripts auxiliares)
- `data/`: fuentes de datos y recursos utilizados por los procesos del proyecto, organizados según las mismas bases de conocimiento descritas en https://docs.google.com/document/d/1fUPQTlCgwdrrd3C4mi6CJIKNWoGj84CVIHkcAKq_ohs/edit?tab=t.0#heading=h.ab2u4rpyvjfn

## Cómo ejecutar Open WebUI + Ollama
- Requisitos: Docker y Docker Compose instalados; 8 GB de RAM libres recomendados para los contenedores de IA.

### Puesta en marcha
```
cd deployment
docker compose up -d
```

### Acceder a Open WebUI
- Open WebUI en http://localhost:3000

### Finalizar la sesion
- Apaga los contenedores cuando termines: `docker compose down`.
