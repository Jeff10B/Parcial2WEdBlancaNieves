# Parcial Práctico Segundo Corte - Maquetación Web (Clon Disney)

Este proyecto consiste en la maquetación web "pixel perfect" de una página principal de Disney (basada en el diseño de *Blanca Nieves*), desarrollado como parte del taller práctico para el segundo corte. El proyecto fue construido utilizando HTML5 y CSS3 puro, aplicando buenas prácticas de control de versiones y trabajo colaborativo (Pair Programming).

## 👥 Integrantes
* [Karen Muñoz]
* [Jefersson Beltran]

## 🛠️ Tecnologías Utilizadas
* **HTML5** (Estructura semántica)
* **CSS3** (Estilos, Flexbox, CSS Grid, Media Queries para responsive)
* **Git & GitHub** (Control de versiones y trabajo en equipo)
* **Visual Studio Code** (Editor de código)
* **Live Server** (Entorno de desarrollo local)


## 📚 Aprendizajes Obtenidos
1. **Trabajo Colaborativo (Pair Programming):** Aprendimos a sincronizar nuestro trabajo en un mismo repositorio usando Git. Entendimos la importancia de hacer `git pull` antes de empezar a trabajar para evitar conflictos y cómo subir nuestros cambios con `git push`.
2. **Dominio de CSS Grid y Flexbox:** Logramos estructurar secciones complejas (como las tarjetas de películas y las cuadrículas de 2, 3, 4 y 5 columnas) de manera responsiva y ordenada.
3. **Manejo de Rutas Relativas:** Comprendimos cómo funciona la estructura de carpetas y cómo enlazar correctamente los archivos desde el HTML, especialmente cuando los estilos están en una carpeta (`css/`) y las imágenes en otra (`img/`).
4. **Interacción con Inteligencia Artificial:** Aprendimos a usar la IA como un "tutor" para resolver errores de consola, entender comandos de Git y ajustar el código CSS para que coincidiera con las clases del HTML.

   ## Dificultades y Desafíos Encontrados
Durante el desarrollo del proyecto, nos enfrentamos a varios inconvenientes que logramos resolver satisfactoriamente:

1. **Problemas de Conexión con Git (Repositorio Remoto):** 
   * *El problema:* Al intentar descargar los cambios del compañero (`git pull`), la consola arrojaba el error `fatal: not a git repository` y `origin does not appear to be a git repository`. Además, la rama local no tenía commits iniciales.
   * *La solución:* Tuvimos que ubicarnos en la carpeta correcta y reconfigurar el repositorio remoto usando `git remote add origin <URL>`, seguido de un `git fetch` y `git pull origin main` para sincronizar las ramas correctamente.
2. **El CSS no se conectaba al HTML:**
   * *El problema:* La página se veía sin estilos. Aunque el archivo se llamaba `styles.css` y estaba en la carpeta, la ruta estaba mal escrita en el HTML. Además, el navegador guardaba el diseño en caché.
   * *La solución:* Corregimos la etiqueta `<link>` a `<link rel="stylesheet" href="css/styles.css">` y aprendimos a hacer un "Hard Refresh" (`Ctrl + F5`) para limpiar el caché del navegador.
