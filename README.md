# Desafío 1: Sistema de Mensajería - Flexbox 💬

Este proyecto corresponde al primer desafío del **Módulo 2** del bootcamp de **Desarrollo Front-End**. El objetivo principal fue poner en práctica el dominio de **CSS Flexbox** para crear una interfaz de usuario simulando un sistema de mensajería moderno.

## 🎯 Objetivos del Desafío
* **Maquetación con Flexbox:** Utilizar propiedades de flexbox para la alineación, distribución y ordenamiento de elementos.
* **Estructura Semántica:** Implementar etiquetas HTML5 adecuadas para mejorar la accesibilidad y el SEO.
* **Diseño UI:** Recrear una interfaz de chat con una barra lateral de contactos y un área de visualización principal.


## 🛠️ Tecnologías Utilizadas
* **HTML5:** Marcado semántico para la estructura del sitio.
* **CSS3 (Flexbox):** Motor principal para el diseño y posicionamiento del layout.
* **FontAwesome:** Integración de iconos para mejorar la experiencia visual.
* **Google Fonts:** Uso de la familia tipográfica *Open Sans*.

## 🌟 Características Técnicas
* **Layout Bilateral:** Se utilizó `display: flex` en el cuerpo del documento para separar la barra lateral (`aside`) del contenido principal (`main`).
* **Barra Lateral de Contactos:** Implementación de contenedores flexibles para alinear avatares, nombres de usuario y marcas de tiempo de los mensajes.
* **Componentes Flexibles:** - El área de usuario y los chats individuales utilizan `justify-content: space-between` para separar la información del contacto de los iconos y la hora.
    - El botón de acción principal y la sección de bienvenida centralizan sus elementos mediante `align-items: center` y `justify-content: center`.
* **Efectos de Interacción:** Los elementos de chat incluyen transiciones de color al pasar el cursor para mejorar la retroalimentación al usuario.

## 📂 Estructura del Proyecto
```
.
├── index.html          # Estructura HTML del sistema de mensajería
├── assets/
│   ├── css/
│   │   └── styles.css  # Estilos CSS basados en Flexbox
│   └── img/            # Recursos visuales (imágenes)
```
