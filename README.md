Todo List Web Interface
Este proyecto presenta una interfaz web para gestionar listas de tareas, desarrollada con tecnologías web estándar: HTML, CSS y JavaScript. A continuación, se describen los componentes fundamentales del proyecto y su funcionalidad.

[![To-Do-list.png](https://i.postimg.cc/wjBrxhDt/To-Do-list.png)](https://postimg.cc/jLGcZngK)

Estructura del Proyecto
El proyecto consta de tres archivos principales:

index.html
Descripción: Contiene la estructura básica de la interfaz web.
Funcionalidades:
Define el diseño de la página web mediante etiquetas HTML.
Incluye metadatos y recursos necesarios, como el viewport y enlaces a hojas de estilo y fuentes externas.
Agrupa contenido dentro de un contenedor principal (container) y una fila (row), además de incluir botones para interactuar con la lista de tareas.
style.css
Descripción: Archivo de estilos que define la apariencia visual de la interfaz.
Funcionalidades:
Establece el estilo general del fondo de la interfaz y su contorno rectangular.
Diseña los botones y el fondo de la pantalla para mejorar la experiencia del usuario.
index.js
Descripción: Maneja la interacción del usuario con la lista de tareas.
Funcionalidades:
Permite agregar, eliminar y marcar tareas de manera interactiva.
Utiliza el almacenamiento local del navegador para guardar el progreso de las tareas, asegurando su persistencia entre sesiones.
Implementa funciones clave como .click, saveData, y load para gestionar la lógica de la aplicación.
Funcionamiento
El proyecto utiliza HTML para definir la estructura de la página, CSS para diseñar la apariencia visual, y JavaScript para manejar la interactividad y la persistencia de datos. Los usuarios pueden interactuar con la lista de tareas a través de botones, y cualquier cambio realizado será guardado automáticamente en el almacenamiento local del navegador, lo que permite mantener el estado de las tareas incluso después de cerrar y volver a abrir el navegador.
