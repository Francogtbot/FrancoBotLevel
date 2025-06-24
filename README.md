# FrancoBotLevel

Este bot consulta precios de vuelos entre SCL y BCN, y si detecta tarifas menores a USD 250, te envía un mensaje por Telegram.

### Cómo funciona:
- Corre cada 5 minutos desde Render.com (usando un Cron Job)
- Usa variables de entorno para proteger el token de Telegram

### Variables necesarias:
- `TELEGRAM_TOKEN`
- `TELEGRAM_CHAT_ID`
