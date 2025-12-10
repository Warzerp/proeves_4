# Frontend - Smart Health

Esta carpeta contiene todos los archivos relacionados con el frontend del proyecto Smart Health.

## 📁 Estructura

```
frontend/
├── public/          # Archivos HTML públicos
│   ├── index.html   # Aplicación principal de chat médico
│   └── test.html    # Página de prueba de WebSocket
├── static/          # Archivos estáticos (CSS, JS, imágenes)
│   ├── css/
│   │   ├── chat.css # Estilos para la aplicación de chat
│   │   └── test.css # Estilos para la página de prueba
│   └── js/
│       ├── chat.js  # Lógica JavaScript para el chat
│       └── test.js   # Lógica JavaScript para pruebas
├── docs/            # Documentación del frontend
│   └── websocket.md # Documentación del protocolo WebSocket
└── scripts/         # Scripts de utilidad y pruebas
    ├── setup_websocket.bat  # Script de configuración y inicio del servidor
    └── test_websocket.py    # Script de prueba del WebSocket
```

## 🚀 Uso

### Aplicación Principal

Abre `public/index.html` en tu navegador para acceder a la aplicación de chat médico.

### Pruebas

- **HTML**: Abre `public/test.html` en tu navegador para probar el WebSocket
- **Python**: Ejecuta `python scripts/test_websocket.py` desde la raíz del proyecto

### Configuración del Servidor

Ejecuta `scripts/setup_websocket.bat` para configurar y iniciar el servidor backend.

## 📝 Notas

- Los archivos HTML están diseñados para conectarse al backend en `http://localhost:8000` o `http://localhost:8088`
- Asegúrate de que el servidor backend esté corriendo antes de usar el frontend
- Para producción, actualiza las URLs en los archivos HTML según corresponda

