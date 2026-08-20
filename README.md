# actividad-evaluada
# El Último Checkpoint - Rediseño Estructural

**Nombres:** Javier Moreno Menéndez 
**Módulo:** Módulo 2 - Fundamentos de Arquitectura Web (HTML5)  
**Fecha:** 20 de Agosto de 2026  

---

## Justificación SEO y Accesibilidad

Mantener un orden lógico en los encabezados (de `<h1>` a `<h6>`) es crucial porque establece la jerarquía y estructura semántica de la información. Para el SEO, los motores de búsqueda como Google utilizan esta estructura para entender de qué trata la página y qué contenido es más relevante, mejorando el posicionamiento. Para la accesibilidad, los lectores de pantalla dependen de estos encabezados para permitir a los usuarios con discapacidad visual navegar de forma ordenada por las diferentes secciones del sitio web, evitando que se pierdan en el contenido.

Asimismo, el uso de un atributo `alt` descriptivo en las etiquetas `<img>` es vital por dos razones: permite que los lectores de pantalla describan verbalmente la imagen a personas con ceguera o baja visión (ej. "Link observando el vasto reino..."), garantizando una experiencia inclusiva; y sirve como texto de respaldo que se muestra en caso de que la imagen no pueda cargar debido a problemas de conexión.

---

## Reto IA: Auditoría y Validación de Código

### 1. Código Defectuoso (Intencional)
Diseñamos el siguiente fragmento simulando el trabajo de un desarrollador inexperto que no aplica semántica ni accesibilidad:

```html
<div class="cabeza">
    <h6>Formulario de Contacto</h6>
</div>
<div>
    <img src="banner-contacto.jpg">
    <br>
    Nombre: <input type="text">
    <br>
    <div class="boton">Enviar</div>
</div>