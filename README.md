# Fundamentos de Desarrollo Web
## Resumen del Curso
Este curso de 1 hora introduce a estudiantes de secundaria a la creación de sitios web sencillos con HTML y CSS. **¡No
requiere descargas!** Solo abre tu navegador web.
**Duración total**: ~60 minutos
**Público objetivo**: Estudiantes de 12 a 17 años sin experiencia en programación.

**Prerrequisitos**: Ninguno 

**Herramientas necesarias**: **¡Solo tu navegador web!** (Chrome, Firefox, Safari, Edge)

**📂 Repositorio de código fuente**: [https://github.com/upc-pre-202610-1asi0730-12258-Scripters/webdev-course-scripters.git](https://github.com/upc-pre-202610-1asi0730-12258-Scripters/webdev-course-scripters.git)

## Secuencia de lección

### Lección 1: ¿Qué es el desarrollo web? (5 minutos)
- **Descripción**: El desarrollo web es la disciplina encargada de crear y mantener sitios y aplicaciones que funcionan en Internet. A través de tecnologías como HTML, CSS y JavaScript, y mediante componentes como el frontend y el backend, permite que los usuarios accedan a información y servicios en línea. Los sitios web pueden ser estáticos o dinámicos y desempeñan un papel fundamental en ámbitos como la educación, la comunicación, el comercio y muchas otras actividades de la vida cotidiana.
- **Enlace**: [Ver la lección] (https://youtu.be/4GTIaaS01jM)
- **Consejos clave**: El desarrollo web esta confrmado por 2 componenets princiaples Frontend y Bakcend, Sitios web = Contenido (HTML) + Estilo (CSS) + JavaSript(Dinamismo) y  ¿Como funciona un sitio web en segundos con internet? https://youtu.be/rw41W8crZ_Y?si=1dTvbBUlo1u2JLXY.
- **Empieza a programar**: [Open CodePen](https://codepen.io/pen/?template=your-starter) **¡No necesitas registrarte!**


### Lección 4: Introducción a CSS (12 minutos)

- **Descripción**: Aprende a personalizar una página web utilizando CSS. Aplicarás colores, fuentes, espacios e imágenes para transformar una página HTML sencilla en una página visualmente atractiva.
- **Objetivo de aprendizaje**: Al finalizar la lección, podrás aplicar estilos básicos con CSS utilizando selectores, propiedades y valores.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link4)
- **Herramienta utilizada**: CodePen (no requiere instalación).
- **Práctica guiada**: [Abrir el CodePen utilizado en clase]([https://codepen.io/your-lesson4-demo](https://codepen.io/editor/Lopescamos/pen/019eda53-c38f-7ee7-81eb-96475ebdd7e1))

---

#### Antes de comenzar

En esta práctica utilizaremos el HTML creado en las lecciones anteriores. En CodePen:

- El contenido debe ir en el panel **HTML**.
- Los estilos deben escribirse en el panel **CSS**.
- La vista previa mostrará los cambios automáticamente.

---

#### Recordatorio: estructura de una regla CSS

```css
selector {
  propiedad: valor;
}
```

Ejemplo:

```css
h1 {
  color: #2563eb;
}
```

| Parte | Ejemplo |
|---|---|
| Selector | `h1` |
| Propiedad | `color` |
| Valor | `#2563eb` |

---

#### Código HTML utilizado

Copia este código en el panel **HTML** de CodePen:

```html
<div class="perfil">
  <img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43b?auto=format&fit=crop&w=300&q=80" alt="Foto de perfil">
  <h1>Alex García</h1>
  <h2>Estudiante de secundaria</h2>
  <p>
    Me gusta la tecnología, los videojuegos y aprender desarrollo web.
  </p>
  <ul>
    <li>Programación</li>
    <li>Diseño digital</li>
    <li>Videojuegos</li>
  </ul>
  <a href="#">Visita mi perfil</a>
</div>
```

---

#### Código CSS explicado en la lección

Escribe el siguiente código en el panel **CSS** de CodePen.

**1. Cambiar el color del título**

```css
h1 {
  color: #2563eb;
}
```

**2. Cambiar el fondo y la fuente de la página**

```css
body {
  background-color: #eaf4ff;
  font-family: Arial, sans-serif;
}
```

**3. Organizar el contenido principal**

```css
.perfil {
  width: 350px;
  margin: 40px auto;
  padding: 20px;
  background-color: white;
  border-radius: 15px;
  text-align: center;
}
```

**4. Personalizar subtítulos y párrafos**

```css
h2 {
  color: #1f2937;
}

p {
  color: #4b5563;
}
```

**5. Mejorar la imagen de perfil**

```css
img {
  width: 150px;
  border-radius: 50%;
}
```

**6. Dar estilo a la lista**

```css
ul {
  list-style-position: inside;
  padding: 0;
}

li {
  margin: 8px 0;
}
```

**7. Personalizar el enlace**

```css
a {
  display: inline-block;
  margin-top: 15px;
  color: #7c3aed;
  text-decoration: none;
  font-weight: bold;
}

a:hover {
  text-decoration: underline;
}
```

---

#### Código CSS completo

```css
body {
  background-color: #eaf4ff;
  font-family: Arial, sans-serif;
}

.perfil {
  width: 350px;
  margin: 40px auto;
  padding: 20px;
  background-color: white;
  border-radius: 15px;
  text-align: center;
}

h1 {
  color: #2563eb;
}

h2 {
  color: #1f2937;
}

p {
  color: #4b5563;
}

img {
  width: 150px;
  border-radius: 50%;
}

ul {
  list-style-position: inside;
  padding: 0;
}

li {
  margin: 8px 0;
}

a {
  display: inline-block;
  margin-top: 15px;
  color: #7c3aed;
  text-decoration: none;
  font-weight: bold;
}

a:hover {
  text-decoration: underline;
}
```

---

#### Reto práctico

Personaliza la página creada en clase aplicando los conceptos aprendidos sobre CSS.

**Instrucciones:**

1. Cambia el color del título principal.
2. Modifica el color de fondo de la página.
3. Prueba una fuente diferente para todo el contenido.
4. Personaliza el enlace cambiando su color.
5. Agrega al menos una mejora adicional, como redondear la imagen o centrar el contenido.

> **Consejo:** Experimenta con diferentes colores y estilos. No existe una única respuesta correcta.

👉 **Comienza aquí:** [CodePen para practicar](https://codepen.io/your-lesson4-practice)

> Este CodePen incluye únicamente el HTML base para que puedas crear tu propia hoja de estilos.

👉 [CodePen para practicar](https://codepen.io/Lopescamos/pen/NPddyam)

> Este enlace contiene únicamente el código HTML para que puedas crear tu propia hoja de estilos. 
