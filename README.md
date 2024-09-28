# Practica 3: Transformaciones en WebGL

Live en Glitch: [live](https://ig-practica-3-fjldm.glitch.me)

## Descripción
Esta práctica se centra en la implementación de transformaciones en WebGL para crear un sistema solar interactivo. El proyecto utiliza WebGL2 para renderizar objetos 2D y aplicar diversas transformaciones como traslación, rotación y escalado.

## Características
- Renderizado de un sistema solar simplificado con el sol, la Tierra, la Luna, Mercurio y Júpiter.
- Implementación de transformaciones matriciales para posicionar y animar los cuerpos celestes.
- Interfaz de usuario interactiva utilizando dat.GUI para controlar las transformaciones.
- Visualización de órbitas planetarias.

## Funcionalidades Adicionales
- Rotación en múltiples ejes (X, Y, Z) para una visualización 3D.
- Escalado para simular zoom de cámara.
- Inclusión de planetas adicionales (Mercurio y Júpiter) con sus respectivas órbitas.
- Órbitas no coplanares mediante rotaciones previas en los ejes X e Y.
- Visualización de las órbitas de todos los planetas y satélites.

## Tecnologías Utilizadas
- WebGL2
- JavaScript
- HTML5
- CSS3
- dat.GUI para la interfaz de usuario
- gl-matrix para operaciones matriciales

## Cómo Usar
1. Abra el archivo HTML en un navegador compatible con WebGL2.
2. Utilice los controles de la interfaz gráfica para:
   - Trasladar la escena (translateX, translateY)
   - Rotar la vista (rotateX, rotateY, rotateZ)
   - Ajustar el zoom (zoom)

## Estructura del Proyecto
- `index.html`: Archivo principal que contiene la estructura HTML y los scripts.
- Shaders integrados en el HTML:
  - Vertex Shader: Define las transformaciones de vértices.
  - Fragment Shader: Define el color de los fragmentos.
- JavaScript incrustado:
  - Inicialización de WebGL y shaders.
  - Definición de objetos celestiales y sus propiedades.
  - Lógica de renderizado y animación.
  - Implementación de transformaciones matriciales.

## Autor
Francisco Javier López-Dufour Morales

## Notas Adicionales
Este proyecto fue desarrollado como parte de la asignatura de Informática Gráfica, demostrando la aplicación práctica de conceptos de gráficos por computadora y programación WebGL.
