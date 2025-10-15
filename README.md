# 🔍 Giphy Viewer | Búsqueda y Gestión de GIFs con Angular Signals

Este proyecto es una aplicación web de búsqueda de GIFs que utiliza la API pública de Giphy. Su principal enfoque es demostrar un manejo de estado moderno y eficiente utilizando las **Angular Signals (Señales)**, Standalone Components y una arquitectura limpia basada en RxJS y servicios.

## 🚀 Demo en Vivo

Puedes probar la aplicación directamente en el siguiente enlace:

🔗 **[VER DEMO EN NETLIFY]** - [https://aplicacionde-gifs.netlify.app/](https://aplicacionde-gifs.netlify.app/)

## ✨ Características Principales

| Icono | Característica | Descripción Técnica |
| :---: | :--- | :--- |
| ⚡ | **Manejo de Estado Reactivo** | Uso de **Angular Signals** para la gestión del estado de la aplicación (Trending Gifs, Historial de Búsqueda y Resultados), garantizando alto rendimiento. |
| 📂 | **Componentes Standalone** | El proyecto está construido íntegramente con la arquitectura moderna de **Standalone Components**, eliminando la necesidad de `NgModules`. |
| 🔍 | **Búsqueda Avanzada** | Implementación de búsquedas por texto con **debounce** a través de RxJS para optimizar las peticiones a la API. |
| 📚 | **Historial Persistente** | Almacenamiento y visualización del historial de búsquedas del usuario. |
| 🔌 | **Consumo de API** | Uso de `HttpClient` de Angular para interactuar con la **Giphy API** y mapear las respuestas de manera segura con TypeScript. |

## 🛠 Tecnologías y Herramientas

Las siguientes tecnologías clave fueron utilizadas en la construcción de este proyecto:

| Tecnología | Badge | Enfoque |
| :--- | :--- | :--- |
| **Angular** | ![](https://img.shields.io/badge/Angular-17%2B-red?style=flat-square&logo=angular) | Base del Framework con Standalone Components. |
| **TypeScript** | ![](https://img.shields.io/badge/TypeScript-4.9%2B-blue?style=flat-square&logo=typescript) | Tipado estricto para un código más robusto y escalable. |
| **RxJS** | ![](https://img.shields.io/badge/RxJS-7.0%2B-purple?style=flat-square&logo=rxjs) | Gestión avanzada de la asincronía y operadores como `tap`, `map` y `debounceTime`. |
| **HTML/CSS** | ![](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Estructura y diseño limpios y responsivos. |
| **Giphy API** | ![](https://img.shields.io/badge/Giphy-API-5C17FF?style=flat-square&logo=giphy&logoColor=white) | Fuente de datos para los GIFs. |

## 📸 Demostración Visual

Aquí puedes ver el funcionamiento de la aplicación:

\[ **Inserta una Captura de Pantalla o un GIF del funcionamiento aquí** ]

*(Tip: Un GIF animado es ideal para mostrar la interacción de la búsqueda y el historial)*

## ⚙️ Instalación y Configuración Local

Para ejecutar este proyecto en tu entorno de desarrollo local, sigue estos pasos:

### Prerrequisitos

* Tener instalado **Node.js** y el **Angular CLI**.
* Una **API Key** válida de Giphy (puedes obtenerla gratis en su sitio web).

### Pasos

1.  **Clonar el repositorio:**
    ```bash
    git clone [TU URL DE GITHUB]
    cd [NOMBRE-DE-TU-REPOSITORIO]
    ```

2.  **Configurar la API Key:**
    * Crea un archivo llamado `environment.ts` (si no existe) o modifica el existente en la carpeta `src/environments/`.
    * Asegúrate de que la API Key de Giphy esté configurada:
        ```typescript
        // src/environments/environment.ts
        export const environment = {
          production: false,
          giphyApiKey: '[TU_API_KEY_DE_GIPHY]', // <-- Reemplaza con tu clave
          giphyUrl: '[https://api.giphy.com/v1](https://api.giphy.com/v1)'
        };
        ```

3.  **Instalar dependencias:**
    ```bash
    npm install
    ```

4.  **Ejecutar la aplicación:**
    ```bash
    ng serve -o
    ```
    La aplicación estará disponible en `http://localhost:4200/`.

---

## 👨‍💻 Autor

**Nicolás Lowther**

* **GitHub:** [\@Niclow12](https://github.com/Niclow12)
* **LinkedIn:** [Tu Enlace a LinkedIn]

Este proyecto está bajo la Licencia MIT.
