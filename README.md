[README.md](https://github.com/user-attachments/files/29864899/README.md)[Uploading R# Bremba-Te'n — Web

Web de una sola página (scroll con anclas) para Artesania e Decoracion Bremba-Te'n, Bossòst (Val d'Aran).

## Estructura
```
index.html          → toda la web (nav + 5 secciones + footer)
assets/
  logo_bremba.jpg    → logo circular (nav + footer)
  tienda_entrada.jpg → foto de la entrada de la tienda (footer / quiénes somos)
  ceramica_producto.jpg
  gres_producto.jpg
```

## Secciones (anclas)
- `#inicio` — hero
- `#instagram` — carrusel (placeholder, ver siguiente apartado)
- `#productos` — cerámica vs gres
- `#quienes-somos` — historia familiar
- `#contacto` — dirección, horario, email, Instagram

## Pendiente antes de publicar

1. **Widget de Instagram**: conecta tu cuenta @brembaten en snapwidget.com o elfsight.com,
   genera el código de inserción y pégalo en `index.html` donde dice
   `AQUÍ VA EL CÓDIGO DE INSERCIÓN DEL WIDGET` (dentro de `#instagram-widget`),
   sustituyendo el `<div class="ig-fallback-grid">` de ejemplo.

2. **Datos de contacto reales**: en la sección `#contacto` hay 2 campos marcados con
   comentario `<!-- Roger: ... -->` que hay que rellenar con la dirección, horario
   y email reales de la tienda.

## Desplegar en GitHub + Netlify

```
git init
git add .
git commit -m "Web Bremba-Te'n"
git branch -M main
git remote add origin <url-de-tu-repo>
git push -u origin main
```

En Netlify: **Add new site → Import an existing project → GitHub** → selecciona el repo.
No necesita build command ni carpeta especial (deja "Publish directory" vacío o en `.`).
EADME.md…]()
