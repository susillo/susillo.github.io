---
title: "Hola mundo"
description: "Primera nota del cuaderno: de qué va esto y cómo escribo aquí."
pubDate: "2026-09-21"
---

Este es mi cuaderno público. Lo uso como libreta: apunto qué estoy haciendo, qué aprendo cada día y cosas de tecnología que me llaman la atención.

Escribir aquí es muy fácil: creo un fichero `.md` en `src/content/blog/`, le pongo este pequeño encabezado arriba y ya está:

```yaml
---
title: "Título de la nota"
description: "Una línea resumen."
pubDate: "2026-09-21"
---
```

Y debajo, texto en Markdown normal y corriente: **negritas**, *cursivas*, listas, enlaces e incluso bloques de código:

```js
const hola = "mundo";
```

Cuando hago `git push`, la web se publica sola. Nada más que hacer.
