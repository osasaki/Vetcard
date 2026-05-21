# 🐾 Patitas VIP — Sistema de Fidelización

Sistema de tarjetas de fidelización digital para veterinaria.  
5 visitas = 1 premio. Sin app, sin costo mensual.

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Página de inicio |
| `cliente-firebase.html` | Tarjeta del cliente (con QR) |
| `staff-firebase.html` | Panel del staff |
| `vercel.json` | Configuración de Vercel |

## Stack

- HTML + JS puro (sin frameworks)
- Firebase Firestore (base de datos en tiempo real)
- Vercel (hosting gratuito)

## URL del cliente

```
https://tu-proyecto.vercel.app/cliente-firebase.html?id=C001
```

## Configuración

Reemplazá el `firebaseConfig` en `cliente-firebase.html` y `staff-firebase.html` con tus credenciales de Firebase.
