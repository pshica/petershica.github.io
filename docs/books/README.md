# Biblioteca de Libros Recomendados

Esta carpeta contiene libros en formato PDF que están disponibles para descarga desde el blog.

## Estructura de Archivos

Los archivos de libros deben estar organizados de la siguiente manera:

```
docs/books/
├── README.md (este archivo)
├── estadistica-para-dummies.pdf
├── python-for-data-science.pdf
├── thinking-fast-and-slow.pdf
└── [otros-libros].pdf
```

## Cómo Agregar Nuevos Libros

1. **Subir el archivo PDF**: Coloca el archivo PDF en esta carpeta
2. **Nombrar el archivo**: Usa nombres descriptivos en minúsculas con guiones (ej: `machine-learning-basics.pdf`)
3. **Actualizar el blog**: Modifica `blog.html` para agregar el nuevo libro en la sección "Libros Recomendados"

### Ejemplo de código para agregar un libro en blog.html:

```html
<div class="book-item">
  <div class="book-cover">📚</div>
  <div class="book-info">
    <h4>Título del Libro</h4>
    <div class="book-author">Nombre del Autor</div>
    <a href="docs/books/nombre-del-archivo.pdf" class="download-btn" download>
      📥 Descargar PDF
    </a>
  </div>
</div>
```

## Consideraciones Legales

⚠️ **IMPORTANTE**: Solo incluir libros que:
- Sean de dominio público
- Tengas los derechos de distribución
- Tengas permiso explícito del autor/editorial
- Sean de tu autoría

## Tipos de Libros Recomendados

### Categorías Sugeridas:
- **Ciencia de Datos**: Python, R, estadística, machine learning
- **Matemáticas**: Cálculo, álgebra lineal, estadística
- **Filosofía**: Pensamiento crítico, epistemología
- **Desarrollo Personal**: Productividad, aprendizaje
- **Tecnología**: Programación, inteligencia artificial

## Formato Recomendado

- **Formato**: PDF
- **Tamaño máximo**: 50MB por archivo
- **Calidad**: Preferible texto seleccionable (no escaneado)
- **Idioma**: Español o inglés preferentemente

## Mantenimiento

Revisar periódicamente:
- Enlaces rotos
- Tamaño total de la carpeta
- Actualizar descripciones en el blog
- Verificar que los archivos sean accesibles

---

*Última actualización: Enero 2025*
