 # BurguerQueen 


## Descripción del proyecto

Construir una interfaz para un restaurante de comida rápida donde se puedan tomar pedidos usando una tablet.

## Entendimiento del problema

Seguramente conoces algún restaurante de comida rápida, basta con un paseo por alguna calle concurrida del centro y podrás notar la existencia de varios. La principal característica de un negocio de este tipo es que los alimentos se preparan y se sirven para ser consumidos rápidamente. Así, el fundamento es la rapidez. Este recurso lo tenemos que mantener en mente para accionar las soluciones. 

<a href="https://ibb.co/4NL5xnM"><img src="https://i.ibb.co/j4Y1FPG/MCC.png" alt="MCC" border="0"></a><br/>

Para conocer cómo se realizan los pedidos y las necesidades del personal de atención al público, acudimos a las instalaciones de HotDogs Ramírez, un local ubicado en la Glorieta de Insurgentes de la CDMX. Fuimos atendidas por el cajero del turno matutino y él nos explicó sobre el funcionamiento del local; también, nos habló de las dificultades para utilizar el software y las repercusiones en su trabajo. Nos compartió los recibos que expiden y que se entregan al cliente, a cocina y registro de caja.

<a href="https://ibb.co/8dC6bwq"><img src="https://i.ibb.co/D8J5YFh/Recibos.png" alt="Recibos" border="0"></a><br/>


Decídimos unir los hallazgos con el de las compañeras de squad para obtener una visión amplia de la situación a enfrentar. Para este punto, elaboramos un Benchmark.

<a href="https://ibb.co/pfg7Sj5"><img src="https://i.ibb.co/jydNSks/benchmark-locales.png" alt="benchmark-locales" border="0"></a><br />

Para seguir con este apartado, entrevistamos a una compañera que trabajó en Domino´s pizza. Agrego algunas notas de la charla.

<a href="https://ibb.co/kqWvy97"><img src="https://i.ibb.co/DwSTb8J/entrevista-dominos.jpg" alt="entrevista-dominos" border="0"></a><br />

Con la información recabada, construimos dos elementos para concentrar los pains y gains detectados. El primero un Storytelling y el segundo un mapa de empatía. Comparto el siguiente: 

1. Storytelling 
> Hoy es el primer día de trabajo de Diana, es una joven de 25 años con la secundaria terminada. Llegó a Burguer Queen por recomendación de una amiga, después de un proceso corto de selección y cinco horas de capacitación. Estaba contenta porque el trabajo le permitiría pagarse la escuela, aunque no tenía otra opción. Llegó a registrarse, primero en el sistema del gerente y después, se fue a su área a realizar otro, en su máquina.

> Aparece el primer cliente en el mostrador;  ella se pone nerviosa, mira la pantalla, hay muchos botones; el cliente, le pregunta por las promociones, Diana revisa su máquina no las encuentra, pregunta a sus compañeros, no obtiene respuesta y le señalan un menú de papel. El cliente se muestra paciente, piensa mucho, le pregunta sobre las opciones. 
Diana, no las encuentra, se calma y logra dar respuesta: -tenemos sencilla y doble. - El cliente se va por una doble,  el pedido continúa.

> Diana no distingue en el primer vistazo la opción de las carnes, pues todos los botones tienen el mismo color; por fin encuentra beef (res). Ella busca la opción de acompañamientos, se encuentra con una pantalla con claves pf y or. Supone que pf es de papas a la francesa y la selecciona. Diana olvida decirle al cliente que el precio incrementa $15 pesos por acompañamiento.

> El cliente indeciso, decide hacer un cambio de último momento, prefiere una sencilla. Ahora Diana, busca la opción de regresar para cancelar, no la encuentra, elige el único botón rojo que ella asocia con cancelar, un enorme mensaje de error aparece y no dice porqué . Llama al gerente, éste tarda, pues atiende otros asuntos. Diana, le pide unos minutitos al cliente. Él la mira y le pide que se apure. Ella solo sonríe, espera e informa al gerente sobre la situación. Éste último reinicia el sistema, se disculpa con el cliente y termina el pedido. Diana, avergonzada anota en unas hojas lo que el gerente hizo para resolver el asunto.

La historia concentra algunos de los malestares más comunes entre los empleados de caja:
* No hay capacitación para el uso de los softwares.
* Cancelar un pedido es complicado, en ocasiones se requiere de la asistencia de otra persona para resolverlo.
* La interfaz es confusa, pues los productos no están clasificados, los colores no apoyan en la identificación de secciones y se requiere hacer una búsqueda para encontrar las secciones deseadas.
* Tardan un mes en aprender a utilizar la herramienta para los pedidos. Lo cual, lleva a los empleados a desarrollar sus estrategias, como: realizar notas en libretas o descargar manuales de uso.

## Reto

La información recabada nos llevó a delimitar el siguiente perfil:

### Perfil del cajero de BurgerQueen
* Edad:18-35.
* Escolaridad: secundaria terminada.
* Sexo: indistinto.
* Sin experiencia.
* Trabajar de lunes a domingo.
* De preferencia trabajar cerca de la sucursal.
* Con excelente actitud, comprometido, responsable.

### Responsabilidades
* Atención al cliente.
* Conocimiento del menú.
* Órdenes (tomar pedidos, entregar las peticiones de los clientes, asegurarse que esté presentada adecuadamente.
* Atender quejas.
* Limpieza.

* Entender cómo se realizan los pedidos en un restaurante similar a BQ y cuáles son las necesidades del personal de cocina y del personal de atención al público (meser@s y cajer@s).
* Ideal si dentro de la investigación toman fotos de las formas en que se toman pedidos actualmente.
* Diseñar la versión para tablets de esta aplicación, teniendo en cuenta el modo de uso de esta tablet (por ej. El uso de la pantalla táctil) y los distintos tipos de usuarios.
* El diseño se debe adaptar a dos tamaños de tablets 9.7 y 7 pulgadas.
* Crear un ícono para poder agregar la pantalla al home de la tablet. Puedes usar appicon y agregar las especificaciones para el equipo de desarrollo.
* El estado actual del pedido siempre visible mientras tomamos un pedido.
* Necesitamos hacer una web app, así será accesible y funcionará bien en tablets iOS y Android.
* Testear e iterar los diseños con personal de restaurantes similares a BQ.
* Entregar las especificaciones de diseño al equipo de desarrollo en Figma, Zeplin ó XD.
* Hacer seguimiento y QA a la implementación realizada por el equipo de desarrollo.
* Realizar pruebas de usabilidad de la aplicación web al final de cada entrega del equipo de desarrollo.

# Objetivo de BurgerQueen

> Somos Burguer Queen, una cadena de comida rápida 24hrs.

> Nuestra propuesta de servicio 24hrs ha tenido muy buena acogida, y para expandirnos necesitamos un sistema que nos ayude a tomar los pedidos de los clientes.

> Tenemos 2 menús: uno para el desayuno, que es bien sencillo:

> **Desayuno**

> |Item|Precio|
> |:---|:---:|
> |Café Americano|$20|
> |Café con Leche| $28 |
> |Sandwich de Jamón y Queso| $35 |
> |Jugo Natural| $15 |


Y un menú para el resto del dia:

> **Diario**

> |Hamburguesas|Precio|Acompañamientos|+$15|Bebidas|Precio|
> |:---|:---:|:---|:---:|:---|:---:|
> |Sencilla|$40|Papas a la Francesa||Refresco|$15|
> |Doble| $55 |Onion Rings||Agua|$10|

> Los clientes pueden escoger entre hamburguesas de res, de pollo, o vegetariana. Y por $15 MXN pueden agregarle queso o huevo.

> Nuestros clientes son bastante indecisos, por lo que es muy común que cambien el pedido varias veces antes de finalizarlo.




