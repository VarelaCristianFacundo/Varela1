# Aplicación de Ejemplo en Ionic

_Este es un proyecto de ejemplo desarrollado en Ionic con una barra de pestañas (tab bar) que incluye tres secciones: Chat, Home y un Toggle._

## Descripción

Esta aplicación demuestra cómo configurar una interfaz de usuario simple en Ionic con una barra de pestañas en la parte inferior. Incluye las siguientes pestañas:

- Home: La pantalla principal de la aplicación.
- Chat: Una sección de chat básico.
- Toggle: Una vista con un interruptor de encendido/apagado (toggle) para probar funcionalidades interactivas.

## Estructura del Proyecto

- www/: Carpeta principal que contiene los archivos HTML, CSS y JavaScript necesarios para la aplicación.
- scss/: Carpeta donde se encuentran los archivos SCSS para personalizar los estilos de la aplicación.
- resources/: Iconos y pantallas de carga (splash screens) para diferentes resoluciones de dispositivos.
- lib/: Contiene las bibliotecas de Ionic y AngularJS necesarias para ejecutar la aplicación.

## Requisitos Previos

- Node.js y npm deben estar instalados en tu sistema.
- Ionic CLI y Cordova deben estar instalados globalmente:

```bash
npm install -g @ionic/cli cordova

```

## Instalación

- Clonar el repositorio (si es necesario):

```bash
git clone https://github.com/VarelaCristianFacundo/Varela1.git
cd Varela1
```

- Instalar las dependencias:

```bash
npm install
```

- Compilar archivos SCSS y otros activos: Ejecuta Gulp para compilar los estilos y otros recursos de la aplicación.

```bash
gulp
```

## Ejecución del Proyecto

Para ver el proyecto en un servidor de desarrollo, ejecuta el siguiente comando en la carpeta www:

- Iniciar un servidor estático (si no lo tienes, instálalo con npm install -g http-server):

```bash
http-server www
```

- Accede a la aplicación: Visita http://localhost:8080 en tu navegador para ver la aplicación en funcionamiento.

## Ejecución en Dispositivos Móviles

_Para compilar y probar la aplicación en dispositivos móviles, puedes usar los siguientes comandos:_

- Para Android:

```bash
ionic cordova run android
```

- Para iOS (requiere macOS):

```bash
ionic cordova run ios
```

## Funcionalidades

- Home: La pantalla inicial de la aplicación.
- Chat: Permite al usuario interactuar en una pantalla de chat básica.
- Toggle: Incluye un interruptor de encendido/apagado para experimentar con controles interactivos.

## Estructura de Archivos

Varela1/
├── www/
│ ├── css/ # Archivos CSS generados
│ ├── img/ # Imágenes usadas en la aplicación
│ ├── js/ # Código JavaScript de la aplicación
│ ├── lib/ # Bibliotecas de Ionic y AngularJS
│ ├── templates/ # Plantillas HTML para las pestañas
│ └── index.html # Página principal de la aplicación
├── scss/ # Archivos SCSS de estilo
├── resources/ # Iconos y splash screens
├── gulpfile.js # Configuración de tareas de Gulp
└── package.json # Configuración del proyecto y dependencias

## Notas

**Este proyecto está diseñado como una demostración simple de Ionic, AngularJS y la funcionalidad de una barra de pestañas. Se puede ampliar con nuevas funcionalidades o estilos.**

## Contact

If you have any questions or suggestions, feel free to get in touch at **cvarelagarcia@gmail.com.**

## Author

- [@VarelaCristianFacundo](https://github.com/VarelaCristianFacundo)
