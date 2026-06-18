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

### Lección 1: ¿Qué es el desarrollo web?
- **Descripción**: El desarrollo web es la disciplina encargada de crear y mantener sitios y aplicaciones que funcionan en Internet. A través de tecnologías como HTML, CSS y JavaScript, y mediante componentes como el frontend y el backend, permite que los usuarios accedan a información y servicios en línea. Los sitios web pueden ser estáticos o dinámicos y desempeñan un papel fundamental en ámbitos como la educación, la comunicación, el comercio y muchas otras actividades de la vida cotidiana.
- **Enlace**: [Ver la lección] (https://youtu.be/k-CRvpr58mE)
- **Consejos clave**: El desarrollo web esta confrmado por 2 componenets princiaples Frontend y Bakcend, Sitios web = Contenido (HTML) + Estilo (CSS) + JavaSript(Dinamismo) y  ¿Como funciona un sitio web en segundos con internet? https://youtu.be/rw41W8crZ_Y?si=1dTvbBUlo1u2JLXY.
- **Empieza a programar**: [Open CodePen](https://codepen.io/pen/?template=your-starter) **¡No necesitas registrarte!**

### Lección 2: Introducción a HTML (10 minutos)
- **Descripción**: Explora las etiquetas HTML básicas y crea tu primera página.
- **Enlace**: [Ver la lección](https://youtu.be/dgWzhnhYKIo)
- **Consejos clave**: Usa `<html>`, `<head>`, `<body>`, `<h1>`, `<p>`.
- **Práctica**: [Clic para programar](https://codepen.io/your-pen-id) 🚀 **¡No necesitas registrarte!**

**Código de ejemplo:**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi primera página</title>
  </head>

  <body>
    <h1>Mi primera página</h1>
    <hr>
    <br>

    <!--Oye! no te olvides que la <p> es para agregar parrafo -->
    <p>Buenas noches, <u>esta es mi <i>primera</i> página</u>, es un gusto que todos se encuentren por aquí año</p>
  </body>
</html>
```

### Lección 3: Añadir más elementos HTML (8 minutos)
- **Descripción**: Agrega listas, imágenes y enlaces para que tu página sea interactiva.
- **Enlace**: [Ver la lección](https://youtu.be/NLQQN2IEWHI)
- **Consejos clave**: Usa las etiquetas `<ul>`, `<img>`, `<a>`.
- **Práctica**: [Clic para programar](https://codepen.io/your-pen-id) **¡Comienza al instante!**

**Código de ejemplo:**

```html
<ul>
  <li>Computación</li>
  <li>Matemáticas</li>
  <li>Aritmética</li>
</ul>

<img src="https://images.unsplash.com/photo-1777026059641-53bcbd04f194?crop=entropy&cs=srgb&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3ODE3OTE0MzJ8&ixlib=rb-4.1.0&q=85" alt="Paisaje" width="300" height="100">

<h2>Aprendizaje</h2>
<p>Se aprendió listas y src images en el curso</p>
<p>Dale click a <a href="https://google.com">Google</a> para ir al buscador</p>
```


### Lección 4: Introducción a CSS 

- **Descripción**: Aprende a personalizar una página web utilizando CSS. Aplicarás colores, fuentes, espacios e imágenes para transformar una página HTML sencilla en una página visualmente atractiva.
- **Objetivo de aprendizaje**: Al finalizar la lección, podrás aplicar estilos básicos con CSS utilizando selectores, propiedades y valores.
- **Enlace**: [Ver la lección](https://youtu.be/jAgK3RY7Ggs)
- **Herramienta utilizada**: CodePen (no requiere instalación).
- **Práctica guiada**: [Abrir el CodePen utilizado en clase](https://codepen.io/editor/Lopescamos/pen/019eda53-c38f-7ee7-81eb-96475ebdd7e1)

---

#### Antes de comenzar

En esta práctica utilizaremos el HTML creado en las lecciones anteriores. En CodePen, el contenido debe ir en el panel **HTML**, los estilos en el panel **CSS**, y la vista previa mostrará los cambios automáticamente.

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

👉 **Comienza aquí:** [CodePen para practicar](https://codepen.io/Lopescamos/pen/NPddyam)

> Este CodePen incluye únicamente el HTML base para que puedas crear tu propia hoja de estilos.
> Este CodePen incluye únicamente el HTML base para que puedas crear tu propia hoja de estilos.

👉 [CodePen para practicar](https://codepen.io/Lopescamos/pen/NPddyam)

> Este enlace contiene únicamente el código HTML para que puedas crear tu propia hoja de estilos. 

### Lección 5: Crear una página web sencilla (15 minutos)

**Descripción**: Combinar HTML y CSS para crear una página de perfil personal utilizando el editor en línea CodePen.

**Enlace**: [Ver la lección](https://youtu.be/6P3AbvcYdgo)

**Consejos clave**: Aplicar estilos estructurados, centrar cajas contenedoras, realizar pruebas de sintaxis para corregir errores comunes y comprender la utilidad de los paneles de la interfaz de desarrollo.

**Proyecto Final**: [Crea tu Perfil en CodePen](https://codepen.io/pen/) ¡Guarda y comparte!

---

#### 📋 Guía de Desarrollo para la Lección 5

En esta sesión práctica de 15 minutos, los estudiantes integrarán los conceptos de maquetación y diseño para construir una tarjeta de presentación digital interactiva. 

> **Nota sobre el entorno de desarrollo**: La interfaz de CodePen presenta tres paneles principales de edición: **HTML**, **CSS** y **JS** (JavaScript). Para efectos de esta lección introductoria enfocada en fundamentos visuales, el panel de **JS** permanecerá cerrado, ya que la lógica y el comportamiento dinámico corresponden a etapas posteriores del aprendizaje. Toda la estructura y apariencia se resolverán exclusivamente con los dos primeros paneles.

---

#### 1. Código de Estructuración (Panel HTML)

Los estudiantes deben escribir el siguiente bloque de código en el panel de HTML para definir los componentes, textos, imágenes y listas que formarán parte de la página de perfil:

```html
<div class="tarjeta-perfil">
  
  <img src="[https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=150](https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=150)" alt="Foto de perfil de Ana" class="foto-perfil">
  
  <h1>¡Hola, soy Ana! 👋</h1>
  <p class="subtitulo">Estudiante de Secundaria & Futura Programadora</p>
  
  <hr>
  
  <h3>Sobre mí</h3>
  <p>Me encantan los videojuegos, dibujar y aprender a crear páginas web. ¡Bienvenido a mi espacio digital!</p>
  
  <h3>Mis Pasatiempos Favoritos</h3>
  <ul>
    <li>🎮 Jugar videojuegos de rol con amigos</li>
    <li>🎨 Dibujo digital en tableta</li>
    <li>📚 Leer novelas de ciencia ficción</li>
  </ul>
  
  <a href="#" class="boton-contacto">¡Salúdame!</a>
  
</div>
```
#### 1. Código de diseño (Panel CSS)

Los estudiantes deben escribir el siguiente bloque de código en el panel de CSS para definir los estilos de la página de perfil:
```css
/* Configuración del fondo de la pantalla completa */
body {
  background-color: #f0f4f8;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

/* Estilo de la tarjeta contenedora */
.tarjeta-perfil {
  background-color: #ffffff;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  text-align: center;
  max-width: 350px;
  width: 100%;
}

/* Diseño circular para la imagen */
.foto-perfil {
  border-radius: 50%;
  border: 4px solid #4a90e2;
  width: 120px;
  height: 120px;
  object-fit: cover;
}

/* Tipografía y espaciados */
h1 {
  color: #333333;
  font-size: 24px;
  margin: 15px 0 5px 0;
}

.subtitulo {
  color: #777777;
  font-size: 14px;
  margin: 0 0 15px 0;
}

h3 {
  color: #4a90e2;
  text-align: left;
  font-size: 16px;
  margin: 20px 0 5px 0;
}

p, ul {
  color: #555555;
  font-size: 14px;
  text-align: left;
  line-height: 1.5;
}

ul {
  padding-left: 20px;
}

/* Estilo interactivo del botón */
.boton-contacto {
  display: inline-block;
  background-color: #4a90e2;
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  border-radius: 20px;
  margin-top: 15px;
  font-weight: bold;
  transition: background-color 0.3s;
}

/* Efecto visual al pasar el cursor por encima */
.boton-contacto:hover {
  background-color: #357abd;
}
```
### Lección 6: Consejos, errores comunes y próximos pasos

* **Descripción**: En esta lección se revisa una página de perfil digital creada con HTML y CSS. El objetivo es aprender a detectar errores comunes, aplicar pequeñas mejoras al código y conocer los próximos pasos para seguir aprendiendo desarrollo web.
* **Enlace**: [Ver la lección](https://youtu.be/MENc1TAPrkw)
* **Herramienta utilizada**: CodePen.
* **CodePen de la lección**: [Abrir práctica y código final](https://codepen.io/dosullz/pen/QNxdzd)
* **Consejos clave**: Revisa que las clases coincidan entre HTML y CSS, usa correctamente el punto `.` en los selectores de clase, no olvides cerrar etiquetas, usa el atributo `alt` en imágenes y prueba la página en diferentes tamaños de pantalla.

---

#### Código base utilizado

Este código sirve como punto de partida para revisar y mejorar una página de perfil digital.

> En CodePen, colocar únicamente el contenido del `<body>` en el panel **HTML**.

```html
<div class="tarjeta-perfil">
    
  <img src="https://avatar.iran.liara.run/public/60" alt="Foto de perfil" class="foto-perfil">
    
  <h1>Hola, soy [Tu Nombre]</h1>
  <p class="subtitulo">Estudiante de Secundaria y Aprendiz Web</p>
    
  <hr>

  <h3>Mis intereses:</h3>

  <ul class="lista-intereses">
    <li>Desarrollo de videojuegos y tecnología</li>
    <li>Práctica de deportes y actividades al aire libre</li>
    <li>Lectura y diseño de páginas web</li>
  </ul>

  <a href="https://github.com" target="_blank" class="boton-enlace">Ver mi GitHub</a>

</div>
```

```css
/* Configuración del fondo general de la página */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(135deg, #74b9ff, #a29bfe);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

/* Contenedor principal en forma de tarjeta */
.tarjeta-perfil {
  background-color: #ffffff;
  border-radius: 20px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
  padding: 30px;
  max-width: 350px;
  text-align: center;
  border: 3px solid #6c5ce7;
}

/* Estilo para redondear la imagen de perfil */
.foto-perfil {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 4px solid #6c5ce7;
  background-color: #f5f5f5;
}

/* Estilos de texto */
h1 {
  color: #2d3436;
  font-size: 24px;
  margin: 15px 0 5px 0;
}

.subtitulo {
  color: #636e72;
  font-size: 14px;
  margin-bottom: 20px;
}

hr {
  border: 0;
  height: 1px;
  background-color: #dfe6e9;
  margin: 20px 0;
}

h3 {
  color: #6c5ce7;
  font-size: 16px;
  text-align: left;
}

/* Lista de intereses sin viñetas predeterminadas */
.lista-intereses {
  list-style: none;
  padding: 0;
  text-align: left;
}

.lista-intereses li {
  margin-bottom: 10px;
  font-size: 14px;
  color: #2d3436;
}

/* Botón interactivo inferior */
.boton-enlace {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #6c5ce7;
  color: white;
  text-decoration: none;
  border-radius: 25px;
  font-weight: bold;
  transition: background 0.3s ease;
}

/* Cambio de color interactivo al pasar el cursor */
.boton-enlace:hover {
  background-color: #5352ed;
}
```

---

#### Mejoras aplicadas en la lección

En esta lección se aplican mejoras pequeñas para que la página sea más clara, adaptable y fácil de revisar.

**1. Personalizar el nombre**

```html
<!-- Antes -->
<h1>Hola, soy [Tu Nombre]</h1>

<!-- Después -->
<h1>Hola, soy Camila</h1>
```

**2. Mejorar el texto alternativo de la imagen**

```html
<!-- Antes -->
<img src="https://avatar.iran.liara.run/public/60" alt="Foto de perfil" class="foto-perfil">

<!-- Después -->
<img src="https://avatar.iran.liara.run/public/60" alt="Avatar de mi perfil digital" class="foto-perfil">
```

**3. Hacer la tarjeta más adaptable**

```css
.tarjeta-perfil {
  background-color: #ffffff;
  border-radius: 20px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
  padding: 30px;
  width: 90%;
  max-width: 350px;
  text-align: center;
  border: 3px solid #6c5ce7;
}
```

**4. Cambiar `height` por `min-height`**

```css
body {
  min-height: 100vh;
}
```

**5. Mejorar el efecto del botón**

```css
.boton-enlace {
  transition: background 0.3s ease, transform 0.3s ease;
}

.boton-enlace:hover {
  background-color: #5352ed;
  transform: translateY(-3px);
}
```

---

#### Errores comunes revisados

**1. Clase diferente en HTML y CSS**

```html
<!-- HTML -->
<div class="tarjeta-perfil">
  <h1>Hola, soy Camila</h1>
</div>
```

```css
/* Incorrecto */
.tarjeta {
  background-color: white;
}

/* Correcto */
.tarjeta-perfil {
  background-color: white;
}
```

**2. Olvidar el punto en una clase CSS**

```css
/* Incorrecto */
boton-enlace {
  background-color: #6c5ce7;
}

/* Correcto */
.boton-enlace {
  background-color: #6c5ce7;
}
```

**3. No cerrar una etiqueta HTML**

```html
<!-- Incorrecto -->
<h1>Hola, soy Camila

<!-- Correcto -->
<h1>Hola, soy Camila</h1>
```

**4. Escribir mal una etiqueta**

```html
<!-- Incorrecto -->
<tilte>Mi Perfil Digital</tilte>

<!-- Correcto -->
<title>Mi Perfil Digital</title>
```

**5. Quitar el atributo `alt` de una imagen**

```html
<!-- No recomendado -->
<img src="https://avatar.iran.liara.run/public/60" class="foto-perfil">

<!-- Recomendado -->
<img src="https://avatar.iran.liara.run/public/60" alt="Avatar de mi perfil digital" class="foto-perfil">
```

---

#### Código final mejorado

> En CodePen, colocar únicamente este contenido en el panel **HTML**.

```html
<div class="tarjeta-perfil">
    
  <img 
    src="https://avatar.iran.liara.run/public/60" 
    alt="Avatar de mi perfil digital" 
    class="foto-perfil"
  >
    
  <h1>Hola, soy Camila</h1>

  <p class="subtitulo">Estudiante de Secundaria y Aprendiz Web</p>
    
  <hr>

  <h3>Mis intereses:</h3>

  <ul class="lista-intereses">
    <li>Crear páginas web personales</li>
    <li>Aprender diseño con CSS</li>
    <li>Compartir mis proyectos en GitHub</li>
  </ul>

  <a href="https://github.com" target="_blank" class="boton-enlace">
    Ver mi GitHub
  </a>

</div>
```

```css
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(135deg, #74b9ff, #a29bfe);
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  margin: 0;
}

.tarjeta-perfil {
  background-color: #ffffff;
  border-radius: 20px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
  padding: 30px;
  width: 90%;
  max-width: 350px;
  text-align: center;
  border: 3px solid #6c5ce7;
}

.foto-perfil {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 4px solid #6c5ce7;
  background-color: #f5f5f5;
}

h1 {
  color: #2d3436;
  font-size: 24px;
  margin: 15px 0 5px 0;
}

.subtitulo {
  color: #636e72;
  font-size: 14px;
  margin-bottom: 20px;
}

hr {
  border: 0;
  height: 1px;
  background-color: #dfe6e9;
  margin: 20px 0;
}

h3 {
  color: #6c5ce7;
  font-size: 16px;
  text-align: left;
}

.lista-intereses {
  list-style: none;
  padding: 0;
  text-align: left;
}

.lista-intereses li {
  margin-bottom: 10px;
  font-size: 14px;
  color: #2d3436;
}

.boton-enlace {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #6c5ce7;
  color: white;
  text-decoration: none;
  border-radius: 25px;
  font-weight: bold;
  transition: background 0.3s ease, transform 0.3s ease;
}

.boton-enlace:hover {
  background-color: #5352ed;
  transform: translateY(-3px);
}
```

---

#### Reto práctico

Personaliza la página **“Mi Perfil Digital”** aplicando las mejoras vistas en la lección.

**Instrucciones:**

1. Cambia el nombre del perfil.
2. Cambia la imagen o el avatar.
3. Modifica la lista de intereses.
4. Cambia al menos un color.
5. Prueba el efecto `hover` del botón.
6. Revisa que las clases coincidan entre HTML y CSS.
7. Verifica que la imagen tenga atributo `alt`.
8. Prueba cómo se ve la tarjeta en una pantalla pequeña.

---

#### Próximos pasos

Después de esta lección, se recomienda seguir aprendiendo:

* Más propiedades de CSS.
* Diseño responsive.
* JavaScript para agregar interactividad.
* GitHub Pages para publicar páginas web.
* Validadores online para revisar errores en HTML y CSS.
