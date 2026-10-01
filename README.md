# Portafolio

**Autor:** Magali Sarai Diego Revilla  
**Proyecto:** Portafolio.
**Fecha de entrega:** 30 de Septiembre de 2026.

## Descripción Breve
Este proyecto es un portafolio web personal e interactivo diseñado para mostrar mi trayectoria como estudiante de Ingeniería en Sistemas Computacionales. 
Combina una estructura profesional para la presentación de habilidades (Bases de datos, Redes, Desarrollo de Software) con una identidad visual única inspirada en la estética retro, 
el pixel art de 8-bits y las interfaces Sci-Fi.

---

## Descripción del Proyecto

El portafolio fue construido utilizando el framework **Bootstrap v5.3.3**, lo que garantiza un diseño completamente responsivo 
(adaptable a dispositivos móviles, tablets y escritorio) mediante el uso de su sistema de cuadrículas (Grid) y componentes predefinidos.

*   **Plantilla base:** Se utilizó la plantilla **"iPortfolio"** desarrollada por BootstrapMade.
*   **Enlace de descarga original:** [ThemeWagon - iPortfolio](https://themewagon.com/themes/iportfolio/?hl=es-MX)

### Secciones del Portafolio
El sitio es una *Single Page Application* (SPA) con navegación lateral estática. Está compuesto por las siguientes secciones:

1.  **Inicio (Hero):** Pantalla de bienvenida de tamaño completo (`100vh`) con un efecto de escritura automática (typing effect) que describe mis roles principales y un fondo animado de cielo estrellado en 8-bits.
2.  **Sobre Mí (About):** Breve biografía profesional, datos de contacto rápidos y mi enfoque como estudiante de ingenieria.
3.  **Habilidades (Skills):** Barras de progreso que cuantifican mi "dominio" en tecnologías clave como Java, Oracle 19c, C++, Diseño Retro UI, Ensamblador y MikroTik.
4.  **Currículum (Resume):** Línea de tiempo que detalla mi educación en el Instituto Tecnológico de Oaxaca y mi experiencia práctica "liderando" proyectos académicos.
5.  **Portafolio (Portfolio):** Galería interactiva con filtros (Web, Datos, Lógica) que muestra evidencias de mis proyectos mediante imágenes y videos integrados.
6.  **Servicios (Services):** Tarjetas informativas sobre las áreas técnicas en las que puedo aportar valor (DBA, UI/UX, Redes, etc.).
7.  **Contacto (Contact):** Formulario de contacto funcional y mapa de Google Maps geolocalizado en Oaxaca de Juárez.

---

## Proceso de Creación

La construcción de este portafolio partió de una plantilla genérica, la cual fue profundamente modificada tanto en estructura como en diseño para adaptarla a mi identidad "profesional" y gustos visuales del momento. 

**Paso 1: Traducción y Reestructuración del HTML**
*   **Qué se hizo?:** Se tradujo toda la maqueta del inglés al español. Se eliminaron secciones innecesarias (como "Testimonios") y se reemplazó el texto de relleno (Lorem Ipsum) con datos reales de mis proyectos académicos (desarrollo de modelos CFE, algoritmos en Prolog, topologías en Cisco/WinBox).
*   **Por qué?:** Para convertir un diseño genérico en un currículum técnico altamente personalizado y coherente con el perfil de Ingeniería en Sistemas.

**Paso 2: Personalización del Diseño (CSS Variables)**
*   **Qué se hizo?:** Se modificaron las variables globales en el archivo CSS original. La paleta de colores se cambió: fondo principal en azul marino (`#141A29`), acentos en rojo (`#991F23`) y textos destacados en dorado (`#F0C330`). Se reemplazó la tipografía por fuentes de Google Fonts estilo consola de comandos (`VT323` y `Press Start 2P`).
*   **Por qué?:** Quería que la interfaz reflejara mis intereses del momento en las UIs retro y el pixel art, cambiando con el aspecto "corporativo" estándar de Bootstrap.

**Paso 3: Creación de Animaciones CSS Puras (Hero Section)**
*   **Qué se hizo?:** Se eliminó la imagen estática de fondo de la portada (`hero-bg.jpg`). En su lugar, se crearon tres contenedores `<div>` superpuestos. Utilizando `radial-gradient` en CSS, se dibujaron "píxeles" simulando estrellas y se les aplicaron animaciones `@keyframes` (`twinkle-fast`, `twinkle-slow`) para que parpadearan a diferentes velocidades e intensidades.
*   **Por qué?:** Para evitar el uso de GIFs o videos pesados y optimizar el tiempo de carga de la página.

**Paso 4: Integración Multimedia Avanzada**
*   **Qué se hizo?:** En la sección "Portafolio", se modificó la estructura HTML (etiquetas `<img>` y sus contenedores) para soportar la reproducción de video nativo usando la etiqueta `<video autoplay loop muted playsinline>`.
*   **Por qué?:** Para poder mostrar demostraciones dinámicas de proyectos visuales (como la generación de fractales L-System en JavaFX) directamente en la cuadrícula de proyectos, sin que el usuario tenga que salir de la página.

---

## Capturas de Pantalla

*(Nota: A continuación se muestran las capturas del portafolio ejecutándose en el navegador web local).*

![Vista de la sección de Inicio (Hero)](img/inicio.png)
*Figura 1: Pantalla de inicio mostrando la tipografía 8-bits y el fondo animado.*

![Vista de la sección Sobre Mí y Habilidades](img/sobremi.png)
![Vista de la sección Sobre Mí y Habilidades](img/habilidades.png)
*Figura 2: Secciones de perfil, datos de contacto y barras de progreso de tecnologías.*

![Vista de la sección del Portafolio](img/proyectos.png)
*Figura 3: Cuadrícula de proyectos con filtros funcionales e integración de medios.*