# n8n-workflows-utiles

![stack: n8n](https://img.shields.io/badge/stack--n8n-0d9488?style=flat-square) ![stack: JSON](https://img.shields.io/badge/stack--JSON-0d9488?style=flat-square) ![stack: Automatizacion](https://img.shields.io/badge/stack--Automatizacion-0d9488?style=flat-square)
![IA: asistido](https://img.shields.io/badge/IA--asistido-6366f1?style=flat-square)

Coleccion de flujos n8n listos para importar: webhook con clasificacion por reglas y cron con HTTP.

> **Transparencia sobre IA:** este proyecto se desarrollo con asistencia de inteligencia artificial (generacion de codigo, revision y documentacion). El codigo fue leido, ejecutado y probado manualmente antes de publicarse. No declara clientes, metricas ni resultados que no puedan verificarse.

## Problema que resuelve

Automatizar tareas repetitivas (clasificar mensajes, enviar resumenes) sin escribir un servicio propio.

## Solucion implementada

Dos flujos n8n importables: un webhook que clasifica por reglas y responde JSON, y un cron que envia un resumen por HTTP.

### Funcionalidades principales

- Webhook con clasificacion por reglas
- Trigger programado (cron)
- Nodo HTTP configurable
- Flujos exportados en JSON

## Stack

- n8n
- JSON
- Automatizacion

## Estructura

```
workflows/webhook-clasificar-mensaje.json  # webhook + code + respond
workflows/bitacora-a-http.json              # cron + code + httpRequest
```

## Puesta en marcha

```bash
# En n8n: Workflows -> Import from File -> elegir el JSON
```

## Complejidad del proyecto

**Nivel: Intermedio** — Integracion de nodos y expresiones; el despliegue requiere una instancia de n8n.

El nivel describe la complejidad tecnica del proyecto, no el grado de dominio de quien lo escribio.

## Despliegue

Automatizaciones para n8n; necesitan una instancia del servidor n8n.  
El codigo fuente si esta disponible en este repositorio.

## Autor

**Luis Felipe Zuniga Leon** — Desarrollador de software asistido por IA

- GitHub: <https://github.com/Luisf2020>
- Correo: developerluis2@gmail.com
- WhatsApp: +504 3237 0056

---

_Proyecto de portafolio. El desarrollo se apoyo en herramientas de IA bajo revision tecnica humana._
