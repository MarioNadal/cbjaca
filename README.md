# 🏀 Driveline — De la Pista al Dato

> Aplicación web de gestión para clubes de baloncesto. Desarrollada a partir de la app interna del **CB Jaca** (Jaca, Huesca, Aragón).

---

## ¿Qué es Driveline?

Driveline es una **PWA (Progressive Web App)** — funciona sin instalación, directamente desde el navegador, y puede añadirse a la pantalla de inicio como una app nativa.

Permite a entrenadores y coordinadores de clubes de baloncesto:

- ✅ Pasar lista de asistencia por equipo y fecha
- 📊 Ver estadísticas de asistencia por jugador (% de presencia, rachas de ausencias, riesgo FEB)
- 📋 Consultar el historial de entrenamientos
- 📤 Compartir resúmenes por WhatsApp (versión padres / versión interna)
- ⭐ Valorar entrenamientos individuales y colectivos
- 📷 Adjuntar foto por sesión
- 📅 Configurar horarios semanales por equipo

---

## Estructura del proyecto

```
driveline/
├── index.html              ← App completa (single-file PWA)
├── README.md
└── assets/
    └── logos/
        ├── logo-icon.svg   ← Icono cuadrado (512×512) — aro de perfil
        └── logo-full.svg   ← Logo horizontal con texto DRIVELINE
```

---

## Logos — v1.0

| Archivo | Descripción | Tamaño |
|---|---|---|
| `logo-icon.svg` | Icono con tablero y aro lateral, balón con trayectoria | 512×512 |
| `logo-full.svg` | Logo completo con texto DRIVE**LINE** + tagline | 880×240 |

**Paleta:**
- Naranja principal: `#F06318`
- Naranja oscuro: `#B83808`
- Texto blanco: `#FFFFFF`
- Acento aro: `#FFD070` → `#FF9520`

---

## Uso

1. Abre `index.html` en cualquier navegador moderno
2. O despliégalo en cualquier hosting estático (GitHub Pages, Netlify, Vercel...)
3. En móvil: "Añadir a pantalla de inicio" para instalar como PWA

No requiere servidor, base de datos ni dependencias externas. Todos los datos se guardan en `localStorage` del dispositivo.

---

## Versiones

| Versión | Fecha | Descripción |
|---|---|---|
| v0.9 | Mar 2026 | App interna CB Jaca — gestión de asistencia |
| v1.0 | Abr 2026 | Rebrand a Driveline, logos SVG v1, mejoras UI |

---

## Autor

**Mario Nadal Ara**  
Fundador y Desarrollador — Driveline  
CB Jaca · Jaca, Huesca, Aragón

---

*Driveline — De la Pista al Dato*
