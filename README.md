# Challenge 03 - Templo Mayor

## Integrantes del equipo
- Debbimar Díaz Santiago
- Jonlier Díaz Rivera
- Jeremy Curry Romero
  
## Proceso

### Paso 1
<div align="center">
  <img src="1.png" width="50%" alt="Búsqueda de Poly Shape">
  <p><i>Se buscó Poly Shape.</i></p>
</div>

Para el primer paso, lo primero que se hizo fue instalar **ProBuilder**. Para este proyecto, lo principal que se utilizó fueron los **Poly Shapes**, ya que era más cómodo para recrear las áreas del templo y hacerlo más simétrico con el ejemplo. Primero, en las opciones de **ProBuilder**, se buscó la opción de **New Poly Shape** y, una vez agregado, se creó la forma de un cuadrado con un nivel de altura razonable para hacer el primer piso.

<div align="center">
  <img src="2.png" width="50%" alt="Base del templo">
  <p><i>Base del templo.</i></p>
</div>

### Paso 2

<div align="center">
  <img src="4.png" width="50%" alt="Modificación con Poly Shape">
  <p><i>Se modificó usando la herramienta de Poly Shape.</i></p>
</div>

Aquí, con la misma herramienta del **Poly Shape**, se agregaron unos puntos en las esquinas para hundir las puntas y recrear esa esquina peculiar que tiene el frente de cada piso del templo.

### Paso 3
<div align="center">
  <img src="5.png" width="50%" alt="Esquinas estiradas">
  <p><i>Se estiraron las esquinas.</i></p>
</div>

Con la misma herramienta del **Poly Shape** y los puntos de los vértices que ya estaban, se estiraron hacia atrás los de la esquina de arriba para crear ese relieve en el frente del piso.

### Paso 4

Este mismo proceso se repitió para los 3 pisos restantes, pero cada uno con menor tamaño para recrear esa forma de pirámide.

<div align="center">
  <img src="7.png" width="50%" alt="Formación de las capas del templo">
  <p><i>Formación de las capas.</i></p>
</div>

### Paso 5
<div align="center">
  <img src="8.png" width="50%" alt="Añadiendo objeto para casillas">
  <p><i>Se añadió otro objeto para las casillas.</i></p>
</div>

Luego de haber terminado los pisos con los **shapes** de **ProBuilder**, nos vamos a **New Shape** y elegimos la opción de **Door**. Como son dos casillas que hay que colocar arriba del Templo, pues le dimos **duplicate** para tener la idea.

### Paso 6
<div align="center">
  <img src="9.png" width="50%" alt="Formando los lados de las casillas">
  <p><i>Formación de los lados de las casillas.</i></p>
</div>

Después de tener esos **shapes** de **Door** colocados en sus respectivas posiciones, pues se fue a **Game Object** y en figuras 3D se agregó un cubo. Ese cubo, con la herramienta de escala, se aplanó y estiró al tamaño del marco y con la herramienta de mover se colocó en la esquina del marco del objeto **Door**. Se duplicó este objeto, se giró unos 90 grados y se colocó en la otra esquina. Este proceso se repitió para ambas casillas y todos los lados correspondientes, excepto el del frente.

### Paso 7
<div align="center">
  <img src="10.png" width="50%" alt="Creando los techos">
  <p><i>Creación de los techos.</i></p>
</div>

Se hizo un cubo y, con las herramientas de los vértices y esquinas, se estiró hacia arriba para hacer el efecto «techo a dos aguas» o más o menos parecido. Por último, se agregó otro cubo de los objetos 3D, el cual se estiró y se hizo un poco más corto para cubrir el marco de arriba de la casilla y así tener una entrada más pequeña. El objeto se duplicó y se colocó en la otra casilla.

<div align="center">
  <img src="11.png" width="50%" alt="Añadiendo marco superior">
  <p><i>Se añadió el marco superior de la casilla.</i></p>
</div>

### Paso 8
<div align="center">
  <img src="12.png" width="50%" alt="Vista del templo en proceso">
  <p><i>Templo Mayor en proceso.</i></p>
</div>

Luego, para no dañar nada, se puso la opción de bloquear los objetos para precaver y no mover nada de su sitio. Con las opciones de **ProBuilder** se fue a **New Shape** y elegimos un cubo. Ese cubo se estiró más o menos a la altura general del templo y con la herramienta de rotar se colocó verticalmente a unos -40 grados. Se colocó enfrente del templo, nivelado, para recrear la escalera.

<div align="center">
  <img src="13.png" width="50%" alt="Escalera del templo">
  <p><i>Creación de la escalera.</i></p>
</div>

<div align="center">
  <img src="14.png" width="50%" alt="Ajuste de la escalera">
  <p><i>Ajuste de la escalera.</i></p>
</div>

### Paso 9
<div align="center">
  <img src="15.png" width="50%" alt="Bordes de las escaleras">
  <p><i>Bordes de las escaleras.</i></p>
</div>

Luego se duplicó ese mismo cubo y con la herramienta de escala se encogió el ancho para hacer los bordes. Se colocó un borde y luego se duplicó para el del centro y la otra esquina.

### Paso 10

Una vez teníamos la mayor parte del templo hecho, se va a objetos 3D y se agrega un terreno. Al terreno se le colocan las medidas de 250 en ancho, largo y altura, también un **heightmap resolution** de 257x257. Luego, en internet, se buscó una imagen que cumpliera con el área respectiva en donde se encontraba este templo en sus tiempos; era más o menos tierra, fango y un poco de pasto. La imagen se importó en el área de **paint texture**, dentro del inspector del terreno, se creó un **layer** y, luego de agregar esa nueva pintura, se aplicó.

<div align="center">
  <img src="17.png" width="50%" alt="Terreno pintado">
  <p><i>Se añadió el terreno y se pintó.</i></p>
</div>

## Historia

### Donde la Guerra y la Lluvia se Encontraron

Huitzilin e Itzcoatl eran amigos desde pequeños. Siempre estuvieron unidos y jugaban a ser guerreros en los alrededores de la pirámide del Templo Mayor. A medida que fueron creciendo, su vínculo se fortalecía cada vez más, al punto de parecer hermanos. Pero en su adolescencia, la vida les trajo un gran desafío: ambos se enamoraron de Itzel, una joven hermosa que vivía cerca del templo y que, sin darse cuenta, se volvió el centro de sus corazones.

Cuando Itzel descubrió que los dos la amaban, decidió poner a prueba su valentía. Les propuso que se enfrentaran y que el vencedor no solo ganaría su amor, sino también el honor de demostrar su fuerza. Huitzilin e Itzcoatl, confiados en su amistad y en su propio coraje, aceptaron el reto. Al caer la tarde, ambos se encontraron frente a la sagrada pirámide, y en su cima Itzel aguardaba para presenciar el enfrentamiento.

Justo cuando sus miradas se cruzaron, algo imposible ocurrió. Una energía ancestral cayó sobre la pirámide y ambos quedaron envueltos en un resplandor cegador. Huitzilin sintió el espíritu de la guerra en su alma y, ante los ojos de Itzel, se transformó en el dios de la guerra. Itzcoatl, a su vez, sintió la fuerza de las tormentas y de sus manos brotaron relámpagos. La lucha entre ambos estremeció la tierra durante días, causando lluvias torrenciales, vientos huracanados y rugidos que quedaron grabados en la memoria de todos. Aquel enfrentamiento no solo decidiría un amor, sino que marcaría para siempre el mito del Templo Mayor, donde la guerra y la lluvia se encontraron en un combate eterno.*

## Gameplay

En este juego, el jugador tiene la opción de utilizar a uno de los dos protagonistas, Huitzilin o itzcoatl. Cada uno recorre un camino propio, lo que le permite al jugador vivir esta historia desde perspectivas opuestas. La historia de Huitzilin destaca la guerra y el honor, mientras que la de Itzcoatl destaca la fuerza de las tormentas y la conexion con la naturaleza. Al completar ambos recorridos, el jugador podra experimentar como concluye la historia de ambos protagonistas y como se veria sus respectivas vidas luego de la gran batalla.


## Experiencia Ganada
**Debbimar** - "Haciendo este **challenge** por primera vez, utilicé la opción de **Poly Shape** y me encantó. Es una herramienta muy útil, ya que era bastante sencilla y podía acomodarlo o transformarlo de la forma que quisiera sin tener que escoger la opción y sin «restricciones». Con esto me refiero a que tenía la libertad de transformar un bloque de mil formas de manera sencilla. Fue interesante hacer este **challenge**, ya que justamente en una clase de literatura estábamos hablando de este tema del Popol Vuh y Texcoco."

**Jonlier** - "Este tercer reto me puso a sacarle jugo a Unity. Son increíbles e impresionantes las funciones y gráficos que tiene este programa. A mí, me fascinó crear este Templo Mayor. La parte creativa fue mi parte favorita. Le puse empeño para que quedara así como se muestra en la foto. Me hubiese gustado añadirle más cosas al juego, pero sé que en los próximos retos tendré la oportunidad de añadirlas. En fin, ¡reto tres superado!"

**Jeremy** - "Este challenge me gustó mucho porque no solo me permitió aplicar los conocimientos adquiridos en clase, sino que también, al investigar información sobre la pirámide, pude aprender más acerca de la cultura de México. Descubrí datos importantes sobre sus tradiciones y su historia ancestral, lo que despertó mi curiosidad por conocer y valorar otras culturas más allá de la puertorriqueña."





