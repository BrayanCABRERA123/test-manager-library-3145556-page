# test-manager-library-3145556-page

> **Prueba técnica · Ficha ADSO 3145556**
> Entrega: **martes 13 de octubre de 2026, a las 5:00 p. m.** (17:00, hora Colombia).

Sitio público **estático** de presentación de *Manager Library* (T-23). **No habla con la API** y no muestra datos personales de socios
(data-model §7). El spec está en [`test-manager-library-3145556-docs`](https://github.com/BrayanCABRERA123/test-manager-library-3145556-docs)
(versión del reto: `spec-laravel/`).

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | Presentación: qué hace el sistema y sus cinco categorías |
| `styles.css` | Estilos responsivos (rejilla adaptable, sin dependencias externas) |

## Cómo verlo

Abrir `index.html` en el navegador. No necesita servidor, API ni instalación.

## Evidencia (T-23)

- Se abre sin la API: no hace ninguna petición de red.
- Correcto en móvil y escritorio: la rejilla de tarjetas pasa de varias columnas a una sola en pantallas angostas.

## Convenciones

- Código, rutas, ramas y mensajes de commit/PR: **inglés** (Conventional Commits).
- Documentación y textos al usuario: **español** (constitución, artículo XI).
- Flujo de ramas: `feature/*` → `develop` → `main`, siempre mediante Pull Request.
