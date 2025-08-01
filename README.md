# Chatbot Conversacional Multicanal con n8n

Un chatbot moderno con interfaz tipo Claude, optimizado para móviles y conectado con n8n para respuestas de IA.

## 🚀 Características

- ✅ **Interfaz móvil optimizada** tipo Claude
- ✅ **Integración con n8n** via webhooks
- ✅ **Responsive design** para todos los dispositivos
- ✅ **Manejo inteligente del teclado** en móviles
- ✅ **Dark theme** profesional
- ✅ **Tipografía IBM Plex Mono**

## 🛠️ Tecnologías

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: n8n (workflow automation)
- **Deployment**: Vercel
- **Styling**: CSS Grid/Flexbox, Custom Properties

## 📱 Funcionalidades

### Chat Interface
- Mensajes en tiempo real
- Indicador de escritura
- Auto-scroll
- Gestión de estados

### Mobile-First
- Visual Viewport API para teclados
- Safe area insets
- Touch optimizations
- Dynamic viewport height

### n8n Integration
- Webhook communication
- Error handling
- CORS management
- Response processing

## 🔧 Configuración

### Variables de entorno
- `WEBHOOK_URL`: URL del webhook de n8n

### n8n Workflow
El webhook debe responder con:
```json
{
  "response": "Mensaje del AI",
  "message": "Alternativa",
  "content": "Otra alternativa"
}
```

## 🚀 Deployment

### Local
```bash
npx http-server -a 0.0.0.0 -p 8080
```

### Vercel
1. Conectar repositorio GitHub
2. Deploy automático
3. Configurar variables de entorno

## 📞 Canales Soportados

- 🌐 **Web** (Principal)
- 📱 **WhatsApp** (via n8n)
- 📲 **Telegram** (via n8n)
- 💬 **Otros** (extensible)

## 📄 Licencia

MIT License - Ver archivo LICENSE para más detalles.

## 👨‍💻 Autor

Desarrollado para proyecto multicanal de IA conversacional.
