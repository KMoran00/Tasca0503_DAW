# Desarrollo Web en Entorno Cliente (DWEC)

## Introducción

DWEC ha abarcado: React, testing del PI y manual de usuario.

## React: conceptos trabajados

- Estructura de un proyecto React y uso de JSX.
- Componentes funcionales reutilizables.
- Gestión del estado local con `useState`.
- Efectos secundarios con `useEffect`.

## Aplicación al PI

Componentes dinámicos en el comparador y la tienda fake.

## Testing: tipos

| Tipo | Descripción |
|------|-------------|
| Unitarias | Unidades aisladas: componente, función, hook |
| Integración | Diversas partes juntas: rutas, contextos |
| E2E | Comportamiento real del usuario completo |
| Accesibilidad | ARIA, teclado, contraste de colores |

## Pruebas NextApp — Frontend

- **Login:** error campos vacíos · llamada correcta · redirección dashboard
- **Contacto:** validación nombre/email/msg · error · envío correcto
- **Rutas:** `/` carga Home · acceso público a Noticias y Política de Privacidad
- **AuthContext** (login/logout) · **ThemeContext** (cambio de tema)

## Pruebas NextApp — Backoffice

- Rutas: `/dashboard`, `/usuaris`, `/categoria`, `/gestioContactes`
- Redirección al Login si no autenticado
- Flujo: Login → Backoffice → navegación → logout