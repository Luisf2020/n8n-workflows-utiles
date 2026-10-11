# n8n-workflows-utiles

Coleccion de flujos n8n listos para importar: webhook con clasificacion por reglas y cron con HTTP.

> Proyecto de portafolio de Luis Felipe Zuniga Leon. Desarrollado con asistencia de IA
> (generacion de codigo, revision y documentacion); el codigo fue revisado y probado manualmente.
> No declara clientes, metricas ni resultados no verificables.

## Stack

- n8n
- JSON
- Automatizacion

## Como ejecutar

```bash
# En n8n: Workflows -> Import from File -> elegir el JSON
```

## Estructura

```
workflows/webhook-clasificar-mensaje.json  # webhook + code + respond
workflows/bitacora-a-http.json              # cron + code + httpRequest
```

## Que incluye

- **webhook-clasificar-mensaje**: recibe `{ mensaje }`, clasifica por reglas y responde JSON (sin servicios externos).
- **bitacora-a-http**: se dispara por cron y envia un resumen a un endpoint configurable.

## Importante

Los flujos vienen **inactivos** y apuntan a `example.com`; ajusta URL y credenciales antes de activarlos.

## Estado

Muestra tecnica de portafolio. Sin datos de produccion.
