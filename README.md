# sitio-web-Grupo2

## Integrantes y Roles del Grupo:
1. Hab'il Xol - Rol 1: Editor de texto
2. Yaxchel Xol - Rol 2: Diseñador de imágenes
3. William Ramirez - Rol 3: Estilista CSS

## Tipos de páginas web

### Páginas estáticas
Son páginas que muestran el mismo contenido para todos los usuarios y no cambian a menos que se modifique el código. No utilizan bases de datos ni programación adicional, para ingresar a ellas solo se necesita el enlace y puede funcionar en cualquier servidor. Ejemplo: páginas de información corporativa.

### Páginas dinámicas
Generan contenido en tiempo real basado en interacciones del usuario o datos de una base de datos, también permiten la creación y uso de aplicaciones dentro de la misma web, manteniendose en constante actualización. Ejemplo: redes sociales como Facebook.

### Páginas interactivas
Permiten la interacción con el usuario mediante JavaScript y tecnologías modernas, estas páginas, al proporcionar contenido pertinente y personalizado, facilitan que los usuarios hallen con facilidad lo que buscan, manteniendo su interés y promoviendo una mayor fidelidad del público. Ejemplo: aplicaciones web como Google Docs, juegos en navegador.


### Uso de la etiqueta <style>
<style> es un elemento de HTML5 y permite incluir CSS dentro de un documento HTML. Definen como se ven los elemento y como se comportan visualmente.
Es obligatorio agregar la etiqueta <style> dentro de la sección <head> del documento, ara garantizar que los estilos se carguen antes de que se renderice el contenido del documento, asegurando que la página se vea como debería desde el primer momento.

### Ejemplo
  
```html
<head>
  <title>Ejemplo de etiqueta style</title>
  <style>
    body {
      background-color: #f0f0f0;
    }
    h1 {
      color: #333;
      text-align: center;
    }
    h2 {
      color: navy;
      margin-left: 20px;
    }
    p {
      color: #666;
      font-size: 18px;
      text-align: justify;
    }
</style>
</head>
