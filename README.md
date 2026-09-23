# La Base CanSat

Sitio web desarrollado como proyecto para presentar y documentar el proyecto **CanSat**, mostrando su objetivo, avances, comunidad y formas de contacto.

## 🌐 Sitio web

**GitHub Pages:**  
https://idel-bit.github.io/La-Base-CanSat/

---

## 📌 Sobre el proyecto

**La Base CanSat** es un sitio web creado para centralizar la información relacionada con nuestro proyecto CanSat.

El sitio presenta información sobre el proyecto, sus objetivos, avances realizados y diferentes espacios de comunicación, utilizando una estructura clara, responsive y adaptable a distintos dispositivos.

---

## 🎯 Objetivos

- Presentar el proyecto CanSat de manera clara y organizada.
- Comunicar los objetivos y características principales del proyecto.
- Documentar los avances realizados.
- Generar un espacio de comunidad e intercambio.
- Facilitar el contacto con el equipo.
- Aplicar buenas prácticas de desarrollo web y control de versiones.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- SCSS / Sass
- CSS3 (archivo generado desde SCSS)
- Bootstrap 5.3.3
- Flexbox
- CSS Grid
- `grid-template-areas`
- Media Queries
- Git
- GitHub
- GitHub Pages

---

## 📂 Estructura del proyecto

```text
La Base CanSat/
│
├── index.html
│
├── assets/
│   ├── img/
│   └── tipografy/
│
├── pages/
│   ├── base-cansat.html
│   ├── avances.html
│   ├── comunidad.html
│   └── contacto.html
│
├── scss/
│   ├── main.scss
│   ├── utilities/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _tipografia.scss
│   │   ├── _base.scss
│   │   └── _estructura.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _nav.scss
│   │   ├── _footer.scss
│   │   └── _responsive.scss
│   └── components/
│       ├── _hero.scss
│       ├── _buttons.scss
│       ├── _cards.scss
│       ├── _forms.scss
│       ├── _carousel.scss
│       ├── _accordion.scss
│       └── _bootstrap-cards.scss
└── styles/
    └── styles.css
```

---

## 🧱 Compilar estilos

El CSS que carga el sitio se genera desde `scss/main.scss`; no se edita a mano.

```bash
npm install
npm run build:css
```

Para recompilar automáticamente mientras se trabaja:

```bash
npm run watch:css
```

---

## 📄 Páginas

### Inicio
Página principal del proyecto y punto de entrada al sitio.

### Base CanSat
Presentación e información general relacionada con el proyecto.

### Avances
Espacio destinado a mostrar el desarrollo y progreso del proyecto.

### Comunidad
Sección destinada a la comunicación y participación de la comunidad.

### Contacto
Página destinada a facilitar el contacto con el equipo.

---

## 🎨 Diseño y maquetación

El diseño utiliza una identidad visual basada principalmente en tonos oscuros, azulados y detalles en celeste y dorado.

Se utilizan:

- Tipografía **Nulshock** para títulos.
- Tipografía **Montserrat** para textos y subtítulos.
- CSS Grid para la estructura principal.
- Flexbox para la distribución de diferentes componentes.
- Bootstrap para componentes y estructura responsive.
- Media Queries para adaptar el contenido a diferentes tamaños de pantalla.

El desarrollo sigue un enfoque **Mobile First**, buscando que el sitio pueda utilizarse correctamente tanto en dispositivos móviles como en tablets y computadoras.

---

## 📱 Responsive Design

El sitio cuenta con diferentes puntos de quiebre para adaptar la distribución del contenido:

- **768px**
- **1024px**
- **1440px**

La estructura se adapta progresivamente según el tamaño de pantalla, reorganizando los elementos y las áreas de la grilla cuando es necesario.

---

## 🔀 Control de versiones

El proyecto utiliza **Git** como sistema de control de versiones y **GitHub** como repositorio remoto.

Durante el desarrollo se realizaron commits significativos para registrar las diferentes etapas del proyecto y mantener un historial organizado de los cambios.

### Repositorio

El proyecto se encuentra alojado en GitHub y publicado mediante GitHub Pages.

---

## 👥 Equipo

Proyecto desarrollado en el marco del proyecto **CanSat**.

---

## 🎓 Curso

Proyecto realizado como parte del curso de **Desarrollo Web de Coderhouse**.

La página fue desarrollada progresivamente mediante diferentes pre-entregas, incorporando estructura HTML, estilos CSS, Flexbox, CSS Grid, responsive design, Bootstrap y control de versiones con Git y GitHub.
