# Sobremesa · versión publicada (prueba)

Solo contiene la app ya compilada (`index.html`) para servirla con GitHub Pages:
https://ismaelbalsellsroma-gif.github.io/sobremesa-web/

- El código fuente está en `sobremesa-app` (privado) y el servidor en `sobremesa-api` (privado).
- Se genera con `pnpm build:servidor` en `sobremesa-app` y se copia aquí `dist-servidor/index.html`.
- Los datos están en Supabase y protegidos por usuario. La clave que va dentro de la app es la pública (*publishable*).
- Rutas: `#agenda` (app, pide entrar), `#r/<local>` (widget público de reservas), `#reserva/<código>` (enlace del cliente en los emails).

Más adelante se pasará a Cloudflare Pages con dominio propio.
