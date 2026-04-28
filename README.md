# RematesPaisa — Mobile

Aplicación móvil del sistema de comercio electrónico RematesPaisa, construida con React Native. Permite a los usuarios explorar productos, gestionar pedidos y recibir notificaciones en tiempo real desde sus dispositivos móviles.

## Requisitos Previos

- **Node.js** (v18 o superior)
- **Git**
- **Expo CLI** instalado globalmente:
```bash
  npm install -g expo-cli
```
- La app **Expo Go** instalada en tu celular (Android o iOS)
- El **backend corriendo** en `http://localhost:3000`

---

## Instalación y Ejecución

1. Clona el repositorio:
```bash
   git clone https://github.com/equiposeis84/mobile.git
   cd mobile
```

2. Instala las dependencias:
```bash
   npm install
```

3. Configura las variables de entorno. Duplica `.env.example` y renómbralo `.env`, luego actualiza:
   - `API_URL` — URL del backend (por defecto `http://localhost:3000`)

4. Inicia el servidor de Expo:
```bash
   npx expo start
```

5. Escanea el código QR con la app **Expo Go** desde tu celular.

---

## Importante

Asegúrate de tener el backend corriendo antes de iniciar la app. Tu celular y tu PC deben estar conectados a la **misma red WiFi**.

Puedes seguir las instrucciones en el [repositorio del backend](https://github.com/equiposeis84/backend).

---

## 🔗 Repositorios relacionados

- [Backend](https://github.com/equiposeis84/backend)
- [Frontend](https://github.com/equiposeis84/frontend)
