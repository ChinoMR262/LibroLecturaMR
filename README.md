
*   **`README.md`:**  Este archivo, que proporciona información general sobre el proyecto.
*   **`index.html`:**  La página principal del sitio web, que muestra el listado de empresas y enlaces a sus certificados.
*   **`css/styles.css`:**  Archivo CSS que contiene los estilos visuales del sitio web.
*   **`certificados/`:**  Carpeta que contiene los certificados (en formato de imagen o PDF) y las páginas HTML estáticas que simulan la validación.  Cada empresa tiene su propio archivo de certificado y su página HTML correspondiente.
*   **`img/`:**  Carpeta que contiene imágenes, logotipos e iconos utilizados en el sitio web.
*   **`js/`:** Carpeta para los archivos JavaScript (en caso de ser necesarios)

## Cómo Funciona

1.  **Generación Local:** Los certificados y las páginas de validación se generan localmente utilizando un script (Python, Node.js, etc.) y herramientas de diseño gráfico.
2.  **Subida a GitHub:** Los archivos generados se suben al repositorio de GitHub.
3.  **Despliegue en GitHub Pages:** GitHub Pages se utiliza para desplegar el sitio web estático.
4.  **Acceso a través de QR:** Los clientes acceden a la página de validación a través del código QR incluido en sus certificados.

## Limitaciones

*   **Información Estática:** La información mostrada en el sitio web y en los certificados no se actualiza automáticamente.
*   **Validación Simulada:** El sistema de validación es una simulación visual y no implica una verificación real de la información proporcionada por las empresas.
*   **Eliminación Manual:** Los certificados y las páginas de validación deben eliminarse manualmente del repositorio de GitHub cuando caducan.

## Consideraciones Legales

*   **Términos de Uso:** El sitio web incluye una página con los Términos de Uso, en la cual se especifica la naturaleza del servicio y se limita la responsabilidad del propietario del sitio web.
*   **Política de Privacidad:** El sitio web incluye una Política de Privacidad en la cual se declara que no se recopilan datos personales de los usuarios.

## Instalación

Este proyecto no requiere instalación. Simplemente clona el repositorio a tu computadora y abre el archivo `index.html` en tu navegador.

## Despliegue en GitHub Pages

1.  Crea un repositorio en GitHub.
2.  Sube los archivos del proyecto al repositorio.