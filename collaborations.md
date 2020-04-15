# Colaboraciones

## 1. Procesamiento de imágenes

### 1.1. Introducción al procesamiento de imágenes

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

## 2. Visualización de información

### 2.1. Visualización de matrices de origen-destino

> Las encuestas de movilidad contienen la caracterización de los viajes en la ciudad en un día estándar: Hora, duración, motivo, lugares de origen y destino, medio de transporte y caracterización de las personas que hacen el viaje. El reto es como visualizar la información geográfica, demográfica y temporal de una manera intuitiva y ajustable.

* Datos: Encuesta de Movilidad Bogotá 2019. Datos bien estructurados.

### 2.2. Visualización datos de Bicicletas Públicas

> El sistema de bicicletas CitiBike hace disponible la información de todos sus viajes así como alguna información de sus usuarios. Al igual que el punto anterior, se debe visualizar información geográfica y de usuario pero con un componente temporal mucho más marcado al tener información minuto a minuto. [Algunos ejemplos](https://toddwschneider.com/posts/a-tale-of-twenty-two-million-citi-bikes-analyzing-the-nyc-bike-share-system/).

* Datos: [Disponibles acá](https://www.citibikenyc.com/system-data) y bien estructurados.

### 2.3. Visualización de modelos de enfermedad espacio-temporales

Los modelos de enfermedad se caracterizan por meta-poblaciones separadas espacialmente con distintos tipos de individuos (Susceptibles, Infectados, Expuestos, Recuperados, etc...). Al conectar varias de estas meta-poblaciones y adicionar una probabilidad de movimiento se tienen modelos más predictivos. Es necesaria la visualización de los modelos para hace un ajuste de variables. [Más información acá](https://arxiv.org/pdf/1802.03969.pdf).

* Datos: Deben ser generados.

### 2.4. Visualización de Algoritmos

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


### 4.3 Interacción en IK

> Implementar una metáfora de interacción para manipular los `targets` y/o las articulaciones de una estructura de esqueleto en IK en `nub`.

* Referencias:
    1. [Creación de una estructura de esqueleto en IK](?).
    2. [Wiki](https://github.com/sechaparroc/nub/wiki/Solving-IK-with-rotational-constraints).
    3. Hardware no convencional de interacción: [Kinect](https://en.wikipedia.org/wiki/Kinect), [Leap Motion](https://en.wikipedia.org/wiki/Leap_Motion), [SpaceNavigator](https://en.wikipedia.org/wiki/3Dconnexion) y [PoseNet con runway](https://www.youtube.com/watch?v=7btNir5L8Jc&t=438s), entre otros.

### 4.4 Rigging en IK

> Realizar un [benchmark de CPU vs GPU](https://en.wikipedia.org/wiki/Benchmark_(computing)) de algoritmos de [skinning](https://www.youtube.com/watch?v=YXDzMZaAo0U) para un estructura de esqueleto en IK.

* Referencias:
    1. [Creación de una estructura de esqueleto en IK](?).
    2. Algoritmo básico de [Linear Skinning]() de nub.
    3. [IK Fish](https://github.com/VisualComputing/nub/tree/ik/examples/ik/skinning/Fish)
    
### 4.5. Animación en IK

> Animar una malla poligonal arbitraria en [ik](https://en.wikipedia.org/wiki/Inverse_kinematics)

* Referencias:
    1. [Ejemplo](?) que emplea un Interpolator para definir una trayectoria para los `targets`.
    2. [Ejemplos](?) de [animaciones procedimentales]((https://en.wikipedia.org/wiki/Procedural_animation)) para definir e interpolar una trayectoria para los `targets`.
    3. [Generación de controles de animación](https://www.khanacademy.org/partner-content/pixar/animate).
    4. [Animation Blending](http://guillaumeblanc.github.io/ozz-animation/samples/blend/).
    
## 5. Adaptar [nub](https://github.com/VisualComputing/nub) a java-script

> Adaptar la librería [nub](https://github.com/VisualComputing/nub) como una librería de [p5js](https://p5js.org/)

* Referencias:
    1. [Tutorial de librerías de p5js](https://github.com/processing/p5.js/blob/master/contributor_docs/creating_libraries.md)
    2. [Repositorio de nubjs](https://github.com/VisualComputing/nubjs)

## 6. Migrar [https://github.com/VisualComputing](https://github.com/VisualComputing) a otro [servidor](https://en.wikipedia.org/wiki/Comparison_of_source-code-hosting_facilities)

[Back]({{ site.url }}/)