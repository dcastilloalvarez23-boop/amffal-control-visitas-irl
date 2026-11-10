# Implementación AMFFAL

- Frontend: GitHub Pages (estático).
- Backend: Supabase, proyecto `nlpgpshwtlpjmrrnekvh`.
- Instalaciones: Casa Matriz, Patio Inca, Planta San Pedro.
- Categorías: Visita, Contratista, Proveedor, Otro.
- Administrador: usuario autorizado mediante Supabase Auth.

## Pendientes antes de operar

1. Configurar Cloudflare Turnstile (site key pública y secret en Edge Function).
2. Conectar formulario público con validación y firma a la Edge Function.
3. Validar correspondencia exacta del documento IRL con el original aprobado.
4. Probar autenticación, permisos, registros, autorizaciones y salidas.
5. Revisar advertencia de Chrome y credenciales usadas en el sitio anterior.
6. Habilitar GitHub Pages y probar la URL HTTPS antes de generar QR.

Nunca almacenar datos personales de visitantes en GitHub.
