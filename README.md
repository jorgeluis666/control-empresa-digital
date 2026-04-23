# Control Empresa Digital

Test interactivo de diagnóstico "¿Qué tanto control tienes sobre tu empresa en digital?" para **Lima Retail**.

Web estática de un solo archivo (`index.html`) con CSS y JS inline. Sin dependencias ni build.

## Estructura

- `index.html` — app completa (UI + lógica del test + resultados).

## Cómo probar localmente

Abre `index.html` directamente en el navegador, o sirve la carpeta con cualquier server estático:

```bash
# opción 1: doble clic a index.html
# opción 2:
npx serve .
```

## Qué evalúa

7 preguntas con ramificación sobre:

1. Acceso a hosting
2. Control del dominio
3. Meta Business Manager
4. Google Ads / Analytics
5. Continuidad ante pérdida de proveedor
6. Respaldo de administradores
7. Documentación de accesos

Entrega un puntaje porcentual y un diagnóstico en 4 niveles (control alto / parcial / riesgo alto / peligro crítico) con CTA a WhatsApp.

## Despliegue

Al ser un archivo estático, se puede servir desde cualquier host: GitHub Pages, Netlify, Vercel, o embeberlo como iframe dentro de WordPress/Divi.
