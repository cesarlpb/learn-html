# Ejercicios HTML: nivel Intermedio

---

### **1. Formulario de contacto**
Crea una página con un título `Formulario de Contacto`. Debe contener un formulario con los siguientes campos:
- Nombre (input de texto)
- Email (input de email)
- Asunto (input de texto)
- Mensaje (textarea)
- Botón de envío

**Requisitos:**
- Usa `label` para cada campo.
- Asegúrate de que los campos de email y mensaje sean obligatorios.

---

### **2. Embebiendo videos de YouTube**
Crea una página titulada `Videos en HTML5` que incluya:
- Un `h1` con el texto "Videos incrustados"
- Un video embebido desde YouTube utilizando la etiqueta `<iframe>`.
- Un video alojado localmente usando la etiqueta `<video>` con controles.

---

### **3. Tabla avanzada con celdas combinadas**
Crea una tabla titulada `Horarios de Clases` con encabezados, combinando celdas con `colspan` y `rowspan`.

| Hora  | Lunes   | Martes  | Miércoles | Jueves  | Viernes  |
|-------|--------|--------|----------|--------|--------|
| 08:00 | Mate   | Lengua  | Mate      | Lengua  | Física |
| 09:00 | Química |  -     | Química  | Historia |  -   |

**Requisitos:**
- Usa `<thead>` y `<tbody>` en la tabla.
- Usa `colspan` para fusionar celdas vacías.

---

### **4. Menú de navegación con enlaces internos**
Crea una página titulada `Menú de navegación` que contenga un menú con enlaces internos a diferentes secciones de la misma página:

- Inicio
- Sobre Nosotros
- Servicios
- Contacto

Cada sección debe estar separada por un `h2` y un párrafo con información ficticia.

**Requisito:**  
- Usa `id` en cada sección y enlaces con `href="#id"` para desplazarse a la sección correspondiente.

---

### **5. Galería de imágenes con enlaces**
Crea una galería de imágenes titulada `Mi Galería`. Debe contener al menos **cuatro imágenes**, cada una dentro de un enlace `<a>` que redirige a la imagen en tamaño completo.

**Requisitos:**
- Usa la etiqueta `<figure>` y `<figcaption>` para darle descripción a cada imagen.

---

### **6. Página con contenido semántico**
Crea una página con estructura semántica utilizando etiquetas de HTML5:

```html
<header> → Contendrá el título de la web
<nav> → Incluirá enlaces a otras secciones
<main> → Incluirá el contenido principal con artículos
<aside> → Contendrá enlaces a noticias relacionadas
<footer> → Mostrará información de contacto
```

---

### **7. Formulario de registro con validaciones**
Crea un formulario de registro con los siguientes campos:
- Usuario (mínimo 5 caracteres)
- Email (debe contener `@`)
- Contraseña (mínimo 8 caracteres, debe contener un número)
- Fecha de nacimiento (input type `date`)
- Género (input tipo radio)
- Aceptar términos (input tipo checkbox)
- Botón de registro

**Requisitos:**
- Usa atributos como `minlength`, `pattern` y `required` para validaciones.
- Estiliza el formulario con CSS básico.

---

### **8. Página con audio y subtítulos**
Crea una página titulada `Audio en HTML5`. Debe contener:
- Un encabezado `h1`
- Un archivo de audio embebido con controles
- Un botón para reproducir y pausar el audio con JavaScript
- Un subtítulo en `<track>` con formato `.vtt`

---

### **9. Página con iframe y Google Maps**
Crea una página titulada `Ubicación`. Debe incluir:
- Un `iframe` con la ubicación de tu ciudad usando Google Maps.
- Un `iframe` que cargue otra página de tu elección.

---

### **10. Blog con estructura de artículos**
Crea una página titulada `Mi Blog`. Debe incluir al menos **tres artículos**, cada uno con:
- Un título `<h2>`
- Un subtítulo `<h3>`
- Un párrafo `<p>`
- Una imagen ilustrativa
- Un botón de "Leer más" con un enlace `#` como placeholder

---
