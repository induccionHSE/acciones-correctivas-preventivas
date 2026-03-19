# Sistema de Acciones Correctivas y Preventivas
 
Sistema digital para el control integral del ciclo de mejora continua: registro, seguimiento, alertas automáticas y cierre de acciones correctivas, preventivas y de mejora (ACPM), desarrollado en Google Apps Script.
 
> **v1.0 — Producción**
 
---
 
## Funcionalidades
 
| Módulo | Descripción |
|---|---|
| **Registro de acciones** | Captura por Google Forms con nivel de riesgo RAM, fecha límite calculada y estado inicial automático |
| **Seguimiento con bitácora** | Registro de avances y evidencias por acción con historial completo |
| **Alertas automáticas** | Notificación diaria por correo de acciones vencidas o próximas a vencer |
| **Análisis de causalidad** | Campo condicional según tipo y nivel de la acción |
| **Cierre con evidencia** | Registro fotográfico y documental en Google Drive por cada acción |
 
---
 
## Stack
 
- **Frontend:** Google Forms
- **Backend:** Google Apps Script (`enviarAccionMejora`, `emitirAlertasAccionesMejora`)
- **Triggers:** onFormSubmit + ejecución diaria automática
- **Base de datos:** Google Sheets (estructura desde fila 15)
- **Almacenamiento:** Google Drive
- **Notificaciones:** Gmail
 
---
 
## Contexto normativo
 
- **ISO 9001:2015** — Cláusula 10.2 No conformidad y acción correctiva
- **ISO 45001:2018** — Cláusula 10.2
- **ISO 14001:2015** — Cláusula 10.2
- **Decreto 1072 de 2015** — Acciones correctivas y preventivas del SG-SST
 
---
 
## Autor
 
**Holman Moreno** — HSEQ Coordinator · Petroleum Engineer
📧 hmoreno@pbi.com.co
🔗 [github.com/induccionhse](https://github.com/induccionhse)
 
