# Landing — Psicología (consulta online)

Landing page estática de una sola página para un psicólogo con consultas en remoto. Textos e imágenes son placeholders (Lorem Ipsum).

Ver: abre `index.html` en el navegador (`open index.html`). No requiere build ni dependencias.

## Dominio personalizado en GitHub Pages

El repositorio está preparado para usar `javiergarciapsicologo.com` mediante el archivo `CNAME`.

En GoDaddy, configura estos registros DNS:

- `A` para `@` → `185.199.108.153`
- `A` para `@` → `185.199.109.153`
- `A` para `@` → `185.199.110.153`
- `A` para `@` → `185.199.111.153`
- `CNAME` para `www` → `juliojgarciaperez.github.io`

Elimina cualquier registro `A`, `AAAA` o redirección incompatible que ya exista para `@` o `www`. Después, en GitHub, entra en **Settings → Pages**, selecciona la rama y carpeta desde la que se publica y escribe `javiergarciapsicologo.com` en **Custom domain**. Activa **Enforce HTTPS** cuando GitHub lo permita.

Los cambios DNS pueden tardar desde unos minutos hasta 24–48 horas en propagarse.
