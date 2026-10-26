# Aguará Guazú Country · páginas del sistema

Sitio publicado con GitHub Pages: https://aguaraguazu-country.github.io/app/

| Carpeta | Qué es | Estado |
|---|---|---|
| `ficha/` | Ficha de actualización de datos para propietarios | En prueba con la comisión (guarda en Supabase) |
| `propietarios/` | PWA para propietarios | Pendiente |
| `guardia/` | PWA para portería (patentes y lotes) | Pendiente |
| `comision/` | Panel de la comisión: plano con lotes cargados, fichas y revisión | En prueba (requiere usuario) |

Las páginas no contienen datos personales: los datos viven en Supabase (proyecto `aguara-gestion`) y se leen según el rol de quien inicia sesión.
No subir a este repositorio archivos con datos de propietarios: el repositorio es público.

La clave `sb_publishable_…` que aparece en las páginas es pública por diseño: solo permite lo que habilitan las reglas RLS de la base. La clave secreta nunca va en este repositorio.
