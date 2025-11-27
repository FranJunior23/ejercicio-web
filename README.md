# La Lista de Lectura

Aplicación web para gestionar una lista personal de lectura, permitiendo añadir libros, marcar los que ya has leído y llevar un registro de progreso.

---

## Funcionalidades

-  Añadir libros a la lista
-  Marcar el libro actual como leído
-  Avance automático al siguiente libro pendiente
-  Contador dinámico de progreso (leídos / totales)
-  Guarda la fecha de finalización de lectura
-  UI intuitiva y moderna

---

## Tecnologías utilizadas

| Tecnología | Finalidad |
|-----------|----------|
| HTML5 | Estructura de contenido |
| CSS3 | Estilos y diseño visual |
| JavaScript ES6 | Lógica, clases y DOM |

---

## Arquitectura del proyecto
Proyecto Lista de Lectura
│
├── src
│ ├── index.html
│ ├── style.css
│ └── app.js
│
├── tests
│ └── app.test.js ← (pruebas unitarias con Jest)
│
└── .gitignore
├── docs
│ ├── api.md
│ ├── arquitectura.md
│ └── guia-instalacion.md
│ └── herramientas-documentacion.md
├── .github
│ └── workflows
|    └── ci.yml


---
### Conexión con dominio de IONOS
En IONOS accedemos al apartado de DNS de nuestro dominio, añadimos un CNAME que apunte a franjjl05.github.io.(en mi caso)
Y tiene que quedarnos igual que lo que hemos puesto en el deploy.
Lo pegamos en el apartado de custom domain y listo.

Una vez todo correcto y el workflow okey podremos acceder a nuestra página.

### Como acceder a la visualizacion de la página desplegada en IONOS
Con este primer enlace accedemos a la página
http://despliegueexamen.frandaw.com

Con este otro accedemos a la documentación generada automáticamente
http://despliegueexamen.frandaw.com/docs/