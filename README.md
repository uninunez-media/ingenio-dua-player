# Ecosistema Multimodal Accesible

Este repositorio contiene la arquitectura de **micro-servicio frontend** para la inserción de recursos educativos accesibles en Moodle, basada en los principios del **Diseño Universal para el Aprendizaje (DUA)**.

## Componentes del Proyecto

1.  **Reproductor Universal (`index.html`):** Enrutador que carga AblePlayer (videos/señas) o visores de documentos (PDF/Moodle) mediante parámetros URL.
2.  **Generador DUA (`generador.html`):** Herramienta para docentes que automatiza la creación del código iframe para Moodle.
3.  **Orquestador de Perfiles:** Sistema de comunicación vía `postMessage` para adaptar el contenido en tiempo real según la preferencia del estudiante.

## Cómo empezar

1.  **Publicación:** Asegúrate de que GitHub Pages esté activo en este repositorio.
2.  **Uso para Docentes:** Accede a `generador.html`, configura el recurso y copia el código generado.
3.  **Integración en Moodle:** Pega el código del orquestador en el "HTML Adicional" de Moodle para habilitar el botón flotante global.

## Licencia
Distribuido bajo la **Licencia MIT**. Siéntete libre de usarlo, modificarlo y distribuirlo para mejorar la accesibilidad educativa.

---
*Desarrollado por YAIR CARDONA ACUÑA - Uninúñez - EPAI*
