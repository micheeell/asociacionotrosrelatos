# asociacionotrosrelatos

Web page for public association _Otros Relatos_

## First steps

1. Creating website in `docs/` folder
2. Downloading files to the `root` directory
3. Using links:
    + [cdmon](https://admin.cdmon.com/en/access) for DNS
    + [2019 tutorial](https://richpauloo.github.io/2019-11-17-Linking-a-Custom-Domain-to-Github-Pages/) by Rich Pauloo
    + [github manual](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
    + [SEO techniques](https://www.socialmediatoday.com/news/8-of-the-most-important-html-tags-for-seo/574987/)

## Backlog

1. use otros-relatos.github.io to point to asociacionotrosrelatos.com.ar
2. Optimize Search engine structure
3. Use responsive template from [templatemo](https://templatemo.com/)
4. Test iframe embedding for twitter & instagram
5. favicon
6. Share on twitter/whatsapp
```html
<meta property="og:title" content="Asociaci&oacuten Civil Otros Relatos" />
<meta property="og:url" content="https://asociacionotrosrelatos.com.ar/" />
<meta property="og:image" content="https://asociacionotrosrelatos.com.ar/img/share-preview.jpg" />
<meta property="og:description" content="Otros Relatos es una Asociación Civil de prevenci&oacute;n de la violencia, conformado por un equipo multidisciplinario de profesionales con perspectiva de género."/> 
```
7. Check [responsive guide](https://www.browserstack.com/guide/how-to-create-responsive-website) for reference
```html
<style>
img {
  max-width: 100%;
}
</style>

<picture>
<source type="image/webp" srcset="https://asociacionotrosrelatos.com.ar/img/image-100.webp 1x, https://asociacionotrosrelatos.com.ar/img/image-200.webp 2x">
<source type="image/png" srcset="https://asociacionotrosrelatos.com.ar/img/image-100.png 1x, https://asociacionotrosrelatos.com.ar/img/image-200.png 2x">
<img alt="Otros Relatos" src="https://asociacionotrosrelatos.com.ar/img/image-200.png" loading="lazy" width="100" height="100">
</picture>
```
8. Test SEO with chrome extension [seoquake](https://chrome.google.com/webstore/detail/seoquake/akdgnmcogleenhbclghghlkkdndkjdjc?hl=es)
