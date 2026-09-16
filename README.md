# PetCare — Prototipo v6

Cambios principales:
- Tofi usa una puerta de entrada estricta: una especie sola nunca selecciona un artículo.
- Tofi no redirige consultas no cubiertas a artículos irrelevantes.
- Consultas con términos de problemas/diagnósticos fuera de la biblioteca (por ejemplo, sida/VHI/cáncer) devuelven únicamente el mensaje de falta de información verificada.
- No se muestran sugerencias cuando Tofi no encuentra información.
- Se eliminó la barra lateral visible de “Regla de oro”.
- Se agregó interfaz demostrativa de crear cuenta / iniciar sesión y registro opcional de mascota.
- Se agregó una caja de publicación comunitaria con moderación previa demostrativa.
- La autenticación y moderación siguen siendo de prototipo local; para producción deben ejecutarse en servidor/base de datos.

Para GitHub Pages: reemplazar `index.html` por este archivo y mantener `main` / `(root)`.
