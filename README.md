Investigación sobre Etiquetas HTML Nuevas

1. details y summary
¿Para qué sirven?
details, permite crear un elemento interactivo que puede expandirse o colapsarse para mostrar información adicional.
summary, define el título visible del details, el cual puede ser clickeado para mostrar u ocultar el contenido.

¿Cómo lo apliqué en mi currículum?
Lo usé en la sección de "Experiencia Laboral" para mostrar detalles adicionales sobre los proyectos en los que he trabajado.

Ejemplo de código:
```html
<details>
    <summary>Más detalles sobre mi experiencia en SurExplora</summary>
    <p>En este proyecto, desarrollé un sistema de reservas para tours, que permite:</p>
    <ul>
        <li>Registrar usuarios con datos personales y destino seleccionado.</li>
        <li>Gestionar reservas y listar clientes registrados.</li>
        <li>Filtrar reservas según el destino turístico.</li>
    </ul>
</details>
```

2. iframe
¿Para qué sirven?
Permite incrustar contenido externo dentro de una página web, como videos de YouTube, mapas de Google, o páginas web completas.

¿Cómo lo apliqué en mi currículum?<p>
Lo utilicé en la sección "Proyectos" para mostrar un video de YouTube relacionado con mi trabajo.

Ejemplo de código:
```
<section id="proyecto">
        <h2>Proyectos</h2>
        <iframe width="560" height="315"
                src="https://www.youtube.com/embed/L3tal8ATx5o"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen>
        </iframe>

    </section>
```

3. script
¿Para qué sirve?<p>
Permite agregar código JavaScript en una página web, ya sea directamente en el documento HTML o mediante archivos externos.
Se usa para agregar interactividad y mejorar la experiencia del usuario.

¿Cómo lo apliqué en mi currículum?<p>
Lo utilicé en el footer para mostrar automáticamente el año actual en los derechos de autor.

Ejemplo de código:
```html
<footer>
    <center>
<!--  (center) para centrar -->
        <p>Creado por <strong>Maicol Enrique Hernández Zúñiga</strong></p>
        <p>📞 <a href="contacto.html" target="_blank">Contáctame</a></p>
        <p>© <script>document.write(new Date().getFullYear());</script> Todos los derechos reservados.</p>
        <!--    Este <script></script> hace que el año valla cambiando de forma automatica -->
    </center>
</footer>
```
