# Colaboraciones

## 1. Procesamiento de imágenes

> Introducir el análisis de imágenes/video al implementar las siguientes operaciones de análisis para imágenes/video tanto por software como por hardware (empleando shaders):

* Conversión a escala de grises: promedio _rgb_ y [luma](https://en.wikipedia.org/wiki/HSL_and_HSV#Disadvantages).
* Aplicación de algunas [máscaras de convolución](https://en.wikipedia.org/wiki/Kernel_(image_processing)).
* Conversión a ascii.
* (solo para imágenes) Despliegue del [histograma](https://en.wikipedia.org/wiki/Image_histogram).
* (solo para video) Medición de la [eficiencia computacional](https://processing.org/reference/frameRate.html) para las operaciones realizadas.

Emplear dos [canvas](https://processing.org/reference/PGraphics.html), uno para desplegar la imagen/video original y el otro para el resultado del análisis.

#### Alternativas para video en Linux y `gstreamer >=1`

Distribuciones recientes de Linux que emplean `gstreamer >=1`, requieren de [esta](https://github.com/gohai/processing-video/releases/tag/v1.0.2) versión alternativa de la librería de video.

Descomprimir el archivo `*.zip` en la caperta de `libraries` del sketchbook (e.g., `$HOME/sketchbook/libraries`).

## 2. Visualización de datos

### 2.1. 

### 2.2. Visualización de Algoritmos

> Visualizar algunos conceptos de computación visual como los [algoritmos de detección de superficies visibles](https://en.wikipedia.org/wiki/Hidden_surface_determination), las [projecciones 3D](https://en.wikipedia.org/wiki/3D_projection) o el [algoritmo de rasterización de un triángulo](https://fgiesen.wordpress.com/2013/02/06/the-barycentric-conspirac/)

* Referencias:
    1. [Algorithm Visualization: The State of the Field](https://dl.acm.org/citation.cfm?id=1821997)
    2. [Algovis](https://github.com/enjalot/algovis)
    3. [Visualizing algorithms](https://bost.ocks.org/mike/algorithms/)
    4. [Rasterization stage](https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation/rasterization-stage)
    5. [Depth-map demo](https://github.com/VisualComputing/nub/tree/master/examples/demos/DepthMap)
    
## 3. Rendering y computación gráfica

### 3.1. Renderer de [ray-tracing](https://en.wikipedia.org/wiki/Ray_tracing_(graphics)) 

> Implementar un renderer de ray-tracing usando [nub](https://github.com/VisualComputing/nub)

* Referencias:
    1. [joons-renderer](https://github.com/joonhyublee/joons-renderer)
    2. [sunflow](http://sunflow.sourceforge.net/index.php?pg=gall)
    
### 3.2. Técnicas avanzadas de iluminación

> Experimentar con técnicas avanzadas de iluminación empleando [shaders](https://visualcomputing.github.io/Shaders/) y [nub](https://github.com/VisualComputing/nub)

* Referencias
    1. [Shadow-mapping demo](https://github.com/VisualComputing/nub/tree/master/examples/demos/ShadowMapping)
    2. [Post-effects demo](https://github.com/VisualComputing/nub/tree/master/examples/demos/PostEffects)
    3. [Bokeh](https://en.wikipedia.org/wiki/Bokeh) y el correspondiente [DOF demo](https://github.com/VisualComputing/nub/blob/master/testing/src/intellij/DOF.java)

## 4. Interacción hombre-máquina

### 4.1 Navegación en 3a persona

> Desarrollar un control de cámara en 3a. persona para la navegación en ambientes virtuales
* Referencias:
    1. [A Survey of Interaction Techniques for Interactive 3D Environment](https://hal.inria.fr/hal-00789413/document)
    2. [Flock-of-boids demo](https://github.com/VisualComputing/nub/tree/master/examples/demos/FlockOfBoids)
    3. [Google cardboard](https://en.wikipedia.org/wiki/Google_Cardboard), [prueba-de-concepto uno](https://github.com/VisualComputing/nub/tree/master/testing/src/processing/VRFlockOfBoids) y [prueba-de-concepto dos](https://github.com/VisualComputing/nub/blob/master/testing/src/intellij/StereoFlock.java)

### 4.2 GUIs no convencionales

> Experimentar con [GUIs](https://es.wikipedia.org/wiki/Interfaz_gr%C3%A1fica_de_usuario) no convencionales en 2D y 3D
* Referencias:
    1. [A Survey of Interaction Techniques for Interactive 3D Environment](https://hal.inria.fr/hal-00789413/document)
    2. [Custom-node-interaction demo](https://github.com/VisualComputing/nub/tree/master/examples/demos/CustomNodeInteraction)

### 4.3. [Skinning](https://en.wikipedia.org/wiki/Skeletal_animation)

> To animate an arbitrary mesh using [ik](https://en.wikipedia.org/wiki/Inverse_kinematics)
* References:
    1. Inverse-kinematics (ik) nubjs module (url missing).
    2. [InteractiveFish](https://github.com/VisualComputing/framesjs/tree/0.1.x/examples/ik/InteractiveFish)
    
### 4.4. [Procedural Animation](https://en.wikipedia.org/wiki/Procedural_animation)

> To implement inverse-kinematics -based procedural animations in [nub](https://github.com/VisualComputing/nub)
* References:
    1. ik nub module (url missing).
    
## 5. Adaptar [nub](https://github.com/VisualComputing/nub) a java-script

> Adaptar la librería [nub](https://github.com/VisualComputing/nub) como una librería de [p5js](https://p5js.org/)

* Referencias:
    1. [Tutorial de librerías de p5js](https://github.com/processing/p5.js/blob/master/contributor_docs/creating_libraries.md)
    2. [Repositorio de nubjs](https://github.com/VisualComputing/nubjs)

[Back]({{ site.url }}/)
