# Opencode-N8N
Integracion de OpenCode con N8N

post http://192.168.0.242:4096/session/:idSession/message

    {
  "agent": "plan",
  "model": {
    "providerID": "opencode",
    "modelID": "big-pickle"
  },
  "parts": [
    {
      "type": "text",
      "text": "puedes generar imagenes?"
    }
  ]
}

Obtener id session 
post http://192.168.0.242:4096/session
headers
key:Content-Type  value:application/json
raw
{
  "title": "Analiza la imagen y determina si hay fuego"
}
