# Closer OS — Herramienta de ejecución comercial

Aplicación web para ventas consultivas, con guion y salidas dinámicas según el prospecto.

## Funciones
- Panel con métricas reales del registro de prospectos y seguimiento.
- Prospectos con fichas, estado comercial y notas.
- Guion de primera llamada: 9 etapas, preguntas, salidas condicionales, notas y recapitulación.
- Biblioteca de objeciones y respuestas consultivas.
- Entrenamiento con práctica manual de roleplays.
- Seguimientos por fecha.
- Exportación CSV y copia de seguridad / restauración JSON.

## Cómo usar
Abrí `index.html` en un navegador. Si querés, podés iniciar un servidor local:
`python3 -m http.server 8000`
y luego abrir http://localhost:8000.

## Publicar en la web
Podés subir estos archivos a GitHub y desplegarlos gratis en Vercel, Netlify o GitHub Pages como sitio estático.

## Limitaciones
Los datos se guardan localmente en el navegador usando `localStorage`. No hay cuentas, sincronización entre dispositivos, base de datos en la nube ni inteligencia artificial en tiempo real. Para un equipo comercial con varios usuarios, añadí autenticación, base de datos segura y permisos.

Exportá copias JSON con regularidad. Evitá almacenar información personal sensible sin necesidad y gestioná el consentimiento de tus prospectos.

## Despliegue en Vercel

Importá `Paly14/notengoidea` desde https://vercel.com/new e indicá la rama `main`.
La configuración `vercel.json` sirve este proyecto como sitio estático desde la raíz,
sin instalación de dependencias ni compilación. No requiere variables de entorno.

La publicación no sincroniza los datos: cada navegador conserva su propio registro.
