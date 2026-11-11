# Advanced Icon & Image Resizer Suite PRO

Aplicación web 100% client-side diseñada para el procesamiento, recorte, filtrado y empaquetado de imágenes e iconos. Permite generar archivos `.ico` multi-tamaño y lotes de imágenes `.png` en formato `.zip` directamente en el navegador, sin requerir backend ni transferencia de datos a servidores externos.

## Características Principales

- **Generación binaria nativa:** Construye archivos ICO (cabeceras, directorios y datos BMP DIB/PNG) y empaquetados ZIP desde cero utilizando `ArrayBuffer` y `DataView`, sin librerías de terceros.
- **Procesamiento de imágenes en Canvas:** Implementa algoritmos de redimensionamiento progresivo, ajuste de recorte (1:1) y modo de contención (relleno transparente) mediante la API de Canvas.
- **Filtros en tiempo real:** Ajuste de brillo, contraste y aplicación de un filtro de nitidez (sharpen) mediante la manipulación directa de píxeles (`ImageData`).
- **Simulador de entornos:** Previsualización del icono generado en contextos reales (pestaña del navegador, barra de tareas de Windows, explorador de archivos).
- **Persistencia local:** Gestión del estado de la aplicación, historial de deshacer/rehacer y preferencias del usuario a través de `localStorage`.
- **Accesibilidad (a11y):** Soporte para navegación por teclado, atributos ARIA, temas claro/oscuro y respeto por las preferencias de movimiento reducido (`prefers-reduced-motion`).

## Stack Tecnológico

- **HTML5 / CSS3:** Estructura y estilos base.
- **Tailwind CSS (CDN):** Sistema de diseño basado en utilidades y temas dinámicos.
- **JavaScript (Vanilla ES6+):** Lógica de manipulación de Canvas, gestión de estado y construcción de archivos binarios.
- **Lucide (CDN):** Iconografía vectorial para la interfaz.

## Uso Local

1. Clona este repositorio:
   ```bash
   git clone https://github.com/JCalderon-Tech/icon-resizer-pro.git