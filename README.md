# Taller 3 Git

Proyecto base para practicar conceptos esenciales de Git y control de versiones mientras se trabaja con una página web estática muy sencilla.

## Características
- Página HTML mínima (`test.html`) que muestra un encabezado de bienvenida.
- Hoja de estilos (`hole.css`) lista para personalizar colores y tipografías.
- Archivo JavaScript (`index.js`) donde puedes experimentar con variables y lógica básica del lado del cliente.

## Requisitos
- Navegador web moderno (Chrome, Firefox, Edge, Safari).
- Opcional: cualquier servidor HTTP estático si prefieres evitar la ruta `file://`.

## Cómo ejecutar
1. Clona o descarga este repositorio en tu máquina.
2. Abre `test.html` directamente en el navegador o, si utilizas Node.js, levanta un servidor rápido:
   ```bash
   npx serve .
   ```
3. Actualiza la página después de cada cambio para ver los resultados.

## Estructura del proyecto
```text
taller3git/
├── test.html    # Entrada principal de la página
├── hole.css     # Estilos base para el sitio
└── index.js     # Espacio para la lógica JavaScript
```

## Próximos pasos sugeridos
- Conectar `hole.css` y `index.js` a `test.html` para aplicar estilos y lógica.
- Añadir más secciones y contenido al HTML (por ejemplo, una sección de servicios o contacto).
- Definir clases CSS específicas y aplicar una paleta de colores personalizada.
- Implementar interacciones básicas en JavaScript (mensajes dinámicos, validaciones, etc.).

## Buenas prácticas con Git
- Realiza commits frecuentes con mensajes claros que expliquen el “por qué” del cambio.
- Usa ramas para desarrollar nuevas funcionalidades sin afectar la rama principal.
- Sincroniza (`git pull`) antes de empezar a trabajar y revisa los cambios antes de hacer `push`.

---

¿Ideas o mejoras? ¡Abre un issue o envía un pull request!
