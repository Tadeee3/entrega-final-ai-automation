# Entrega Final - AI Automation

Tadeo Collado

Para la entrega final armé un flujo en n8n para Zafira Alotti, la marca de ropa con la que trabajo. El flujo toma los pedidos de guiones que cargo en Airtable, Claude escribe el guion, me llega a Slack para aprobarlo o rechazarlo y, si lo apruebo, se le manda por Gmail al editor de video.

Herramientas: n8n, Airtable, Claude, Slack y Gmail.

Probé el flujo 6 veces, incluyendo un contenido sin brief para probar la ruta de error y un rechazo en Slack para probar la reescritura con feedback.

## Archivos

- arquitectura-zafira-pipeline-ia.pdf: diagrama de arquitectura y explicación del flujo
- zafira-pipeline-ia.json: el workflow exportado de n8n
- screenshots: capturas del flujo y de las pruebas

## Base de datos

Link de Airtable en modo lectura:
https://airtable.com/app0nLPywzJQYbcnM/shrZiaEH7bTZPojSk
