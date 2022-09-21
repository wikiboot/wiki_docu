**Introducción**

---

Vamos a ver algunas **etiquetas** que aparecieron con la **versión de HTML5** que hacen referencia a secciones dentro de una aplicación web. Mencionar que gracias a esta aparición han surgido estructuras semánticas más correctas **mejorando** varios aspecto de nuestras aplicaciones como:

- Como **representa** el **navegador** nuestro **contenido**.
- Gestión del **posicionamiento** o **SEO**.
- **Accesibilidad** para personas con capacidades especiales, como la ceguera, que necesitan navegar en nuestra aplicacin.

**header**

---

<**header**> es el elemento superior de nuestra página web, habitualmente contiene el logo de la compañía y el título de la página web.

```html
<header class="page-header">
  <h1>Cute Puppies Express!</h1>
</header>
```

[wiki_docu/HTML5/Code/content-sections/header at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/header)

**nav**

---

<**nav**> contiene la navegación de la página web.

```html
<nav class="crumbs">
  <ol>
    <li class="crumb"><a href="#">Bikes</a></li>
    <li class="crumb"><a href="#">BMX</a></li>
    <li class="crumb">Jump Bike 3000</li>
  </ol>
</nav>
```

[wiki_docu/HTML5/Code/content-sections/nav at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/nav)

**h**

---

Podemos encontrar 6 etiquetas para realizar encabezados: desde **<h1>** hasta **<h6>** Lo cual nos permite establecer niveles de importancia dentro de los títulos, siendo **<h1>** el más importante, **<h2>** el siguiente, y así sucesivamente disminuyendo importancia hasta llegar a **<h6>.**

```html
<h1>Beetles</h1>
<h2>External morphology</h2>
<h3>Head</h3>
<h4>Mouthparts</h4>
<h3>Thorax</h3>
<h4>Prothorax</h4>
<h4>Pterothorax</h4>
```

[wiki_docu/HTML5/Code/content-sections/h at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/h)

**Section**

---

<**section**> representa una división de un contenido.

```html
<section>
  <h2>Introduction</h2>
  <p>
    This document provides a guide to help with the important task of choosing
    the correct Apple.
  </p>
</section>

<section>
  <h2>Criteria</h2>
  <p>
    There are many different criteria to be considered when choosing an Apple —
    size, color, firmness, sweetness, tartness...
  </p>
</section>
```

[wiki_docu/HTML5/Code/content-sections/section at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/section)

**article**

---

<**article**> es una unidad de contenido (por ejemplo: en un blog sería un post).

```html
<article class="forecast">
  <h1>Weather forecast for Seattle</h1>
  <article class="day-forecast">
    <h2>03 March 2018</h2>
    <p>Rain.</p>
  </article>
  <article class="day-forecast">
    <h2>04 March 2018</h2>
    <p>Periods of rain.</p>
  </article>
  <article class="day-forecast">
    <h2>05 March 2018</h2>
    <p>Heavy rain.</p>
  </article>
</article>
```

[wiki_docu/HTML5/Code/content-sections/article at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/article)

**aside**

---

<**aside**> debe contener elementos que aportan información complementaria.

```html
<aside>
  <p>The Rough-skinned Newt defends itself with a deadly neurotoxin.</p>
</aside>
```

[wiki_docu/HTML5/Code/content-sections/aside at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/aside)

**footer**

---

<**footer**> es el elemento inferior de la página web y suele contener enlaces y el copyright.

```html
<footer>
  <p>© 2018 Gandalf</p>
</footer>
```

[wiki_docu/HTML5/Code/content-sections/footer at main · wikiboot/wiki_docu](https://github.com/wikiboot/wiki_docu/tree/main/HTML5/Code/content-sections/footer)
