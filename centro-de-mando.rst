###############
Centro de Mando
###############

Todo capitán de una Crypto-space Ship tiene que saber cómo hacerla evolucionar, ganar batallas y surcar el crypto-espacio.


*********************
Indicadores Generales
*********************

Los siguientes indicadores están siempre presentes e informan lo siguiente:

.. image:: indicadores.png
    :width: 700px
    :alt: Recursos
    :align: center

1. Cantidad de **Energía** acumulada sobre la cantidad que puede almacenar actualmente. ( **acumulado** of **capacidad** )

2. Cantidad de **Grafeno** acumulado sobre la cantidad que puede almacenar actualmente

3. Cantidad de **Metales** acumulado sobre la cantidad que puede almacenar actualmente

4. Estado de la Crypto-space Ship. **100%** indica que se encuentra en óptimas condiciones

.. hint::
    Cuando el recurso acumulado es igual a la cantidad que la Crypto-space ship puede almacenar actualmente y la producción de cada recurso es mayor a 0, se están desperdiciando recursos. **Se recomienda gastar o de ser posible ampliar el almancen**.


********
Recursos
********

A continuación se presenta la vista de Recursos:

.. image:: resources.png
    :width: 700px
    :alt: Recursos
    :align: center

Sección Izquierda
=================

Se puede observar el nivel de:

1. Los Paneles Solares

2. Recolector de Grafeno

3. Recolector de Metales

Las barras indican la cantidad de recursos disponibles para ampliar al próximo nivel. El color amarillo representa  la energía, el color negro al grafeno y el gris a metales.

El botón intermitente **UPGRADE READY** indica que se tienen los recursos necesarios para ampliar de nivel y que no hay nada construyendo, ya que no se permiten ampliaciones simultáneas. Al presionarlo se puede observar la cantidad de recursos necesarios para la actualiación y al presionar el botón **Confirm** se envia la orden de construcción.

.. image:: upgrade.png
    :width: 400px
    :alt: Recursos
    :align: center

Una vez que se confirma, se descuentan los recursos y empieza su actualización.

Sección Derecha
===============

Sobre este espacio se puede observar:

1. **Location**: Coordenada donde se encuentra la Crypto-space Ship

2. **Production Ratio**: La producción de recursos por bloque

3. **Watch countdown**: La cuenta regresiva que muestra la cantidad de bloques restantes para terminar la actualización

Opcionalmente pueden aparecer otros botones intermintes desbloqueando ciertas características, como por ejemplo la opción de prender el conversor de recursos y la opción de convertir recursos.

.. note::
    **La unidad de medida de tiempo son los bloques**

**************
Construcciones
**************

Vista del panel de construcciones internas


.. image:: buildings.png
    :width: 700px
    :alt: Recursos
    :align: center

Sección Izquierda
=================

Al igual que en la vista de recursos, se puede observar el nivel de las siguientes estructuras:

1. Almacén

2. Hangar

3. W.O.P.R

Las barras indican la cantidad de recursos disponibles para ampliar al próximo nivel. El color amarillo representa la energia, el color negro al grafeno y el gris a metales.

El botón intermitente **UPGRADE READY** indica que se tienen los recursos necesarios para ampliar de nivel y que no hay nada construyendo, ya que no se permiten ampliaciones simultáneas. Al presionarlo se puede observar la cantidad de recursos necesarios para la actualización y al presionar el botón **Confirm** se envia la orden de construcción.

Al momento de ampliar el W.O.P.R de nivel 0 a nivel 1, además se tiene que seleccionar el rol de W.O.P.R entre:

1. Converter

2. Crypto-Ion Cannon

3. Reparer

.. image:: wopr.png
    :width: 400px
    :alt: Recursos
    :align: center


Sección Derecha
===============

En esta sección se puede encontrar infomación sobre la configuración de la flota de drones de combate (**fleet**).

1. **Fleet**: Información sobre la flota de drones

    - El número de drones que compone la flota.
    
    - Las características de la flota, es decir, puntos de ataque, defensa, distancia y carga. En el caso de que la flota esté diseñada. Al construir el hangar en nivel 1 ya aparece el botón intermintente **DESIGN FLEET** y luego que este diseñada **BUILD MORE**.

    - La otra opción que se activa dadas ciertas circunstancias es el botón intermitente **DISASSEMBLE FLEET** para destruir la flota actual.

2. **Fleet Prod. Queue**: La cantidad de drones que se encuentran en la cola de construcción.

4. **Watch countdown**: Los relojes de cuenta regresiva.

    - **BUILD**: Cuantos bloques faltan para finalizar la ampliación del almacén, hangar o wopr.

    - **FLEET**: Bloques restantes para la finalización de la construccion de la flota de drones.


***
Map
***

La sección estratégica por excelencia, donde los grandes comandantes se forjan y nacen las leyendas.

.. image:: map.png
    :width: 700px
    :alt: Recursos
    :align: center

Sección Izquierda
=================

En esta parte se puede encontrar la barra que indica la energia necesaria para poder pasas la Crypto-space Ship de modo.
Luego los distintos botones para pasar de modo, indicando con otro color el modo en que se encuentra actualmente.

Finalmente podemos poner unas coordenadas en **Map Browse** para poder explorar una posicion en el mapa.


Sección Central
===============

En esta sección encontramos el mapa estratégico de 7x7 casilleros cada uno representado por una coordenada. En el centro, de ser posible, se encuentra la Crypto-space ship que estamos comandando. 
también podemos identificar otros objetos tales como:

.. image:: centralmap.png
    :width: 400px
    :alt: Central map
    :align: center

- **Planetas**

- **Cinturones de Asteroides**

- **Otras Crypto-space ships**

- **Coordenadas vacias**


Coordenedas vacias
------------------

Al inspeccionar una posición vacia, podemos obsevar infomacion sobre la misma. La densidad de recursos, tanto de grafeno como de metales; como asi tambien la distancia a la que se encuentra.
Si esta habilitada la opcion **Mode To** podemos desplazar la Crypto-space Ship hacia esa posicion.

.. image:: emptymap.png
    :width: 400px
    :alt: Empty Map
    :align: center

.. hint::
    La disponibilidad de recursos varía en las distintas posiciones, es conveniente buscar un lugar con alta densidad de recursos. Una alta densidad implica una mayor producción, una evolución más rápida hace la Crypto-space Ship más poderosa en menor tiempo.


Otras Crypto-space Ships
------------------------

Cuando se selecciona otra Crypto-space Ship, se puede observar información de la misma:

- **Name**: Representa el nombre de la otra nave, se puede enviar un mensaje al capitán de esta nave al apretar sobre el nombre.

- **Distance**: La distancia entre las dos Crypto-space ship medida en **gdu**

- **Mode**: El modo en que se encuentra la nave. Esta información es muy útil si se pretende atacarla

.. image:: shipmap.png
    :width: 400px
    :alt: Ship map
    :align: center

Para atacar a la nave seleccionada primero se deben cumplir ciertas condiciones:

1. Tener una **flota de drones**

2. La flota debe estar lista para la acción. Si la flota estuvo recientemente en acción, hay que esperar los bloques restante para su reparación y reaprovisionamiento

3. La otra Crypto-space Ship debe estar a una distancia en rango de acuerdo al diseño de la flota

Al cumplirse las condiciones anteriormente descritas, se habilitan los botones **Attack** y **Raid**. Ambas acciones realizan una acción bélica sobre la otra Crypto-space Ship pero con la diferencia que **Attack** intenta destruir todas las naves y luego robar recursos, en cambio **Raid** intenta robar recursos tratando de salvar la mayor cantidad de drones de la refriega.

**Send resources** permite enviar recursos a la otra Crypto-space Ship, se tienen que cumplir los mismos requisitos que para entablar una batalla. La cantidad que se puede enviar depende del diseño de los drones y la cantidad que conforme la flota.

.. note::
    La cantidad de bloques necesarios para el reaprovisionamiento de los drones es mucho mayor al atacar que al enviar recursos a otras Crypto-space Ships.


De acuerdo al rol seleccionado al ampliar el **W.O.P.R** se puede habilitar la opción de disparar el Crypto-Ion cannon o reparar la Crypto-space Ship, en caso de haber seleccionado **Crypto-Ion Cannon** o **Reparer**.


Al disparar el Crypto-Ion cannon, se puede elegir entre dos modos de disparo:

- **Normal**: Provocando daño a toda la Crypto-space Ship

- **Accuracy**: Provocando daño solamente a la estructura seleccionada, destruyendo los niveles correspondientes al nivel de actualización del Crypto-Ion Cannon.



Planetas
--------

Cuando se selecciona un planeta se proporcionará la información del mismo.

- El nombre con que se conoce al planeta

- La distancia a la que se encuentra

- El dueño del planeta

- Las Cryto-space Ships que se encuentran defendiéndolo

.. note::
    Los planetas son defendidos por nativos antes de la primer conquista. **Nunca subestimar su poder**.


.. image:: planetmap.png
    :width: 400px
    :alt: Planet Map
    :align: center


El botón **Attack** estará disponible en caso de que la flota de drones esté lista para el combate, y en rango de ataque. El planeta se puede atacar para intentar debilitar a los defensores o directamente intentar la conquista.


Si la intención es defender el planeta, se puede ocupar una de las 4 posiciones defensivas, es necesario contar con drones, la Crypto-space Ship debe estar en rango de movimiento y los motores listos para que **Defend** esté habilitado.


Para poder aterrizar basta con presionar el botón **Land** que se facilitará en caso de que la Crypto-space Ship esté a distancia y los motores esten listos para el siguiente movimiento.

.. node::
    Al aterrizar o defender un planeta **la producción de grafeno y metales es nula**. 

.. hint::
    No es posible atacar de ninguna manera a una Crypto-space Ship que aterrizó en un planeta. Es una buena estrategia para escapar de enemigos al acecho.


Sección Derecha
===============

- **Location** nos indica las coordenadas de la posición de la Crypto-space Ship en el mapa.

- **Hybrid**, **Predator**, **Keeper**, **Galleon** o **Interceptor** indica el tipo de drones de combate que tenemos y la cantidad disponible de los mismos. Debajo en que estado se encuentran: **Ready for battle** o **Waiting**. 

- **Action Countdown** la cantidad de bloques necesarios para:

    - **Move**: realizar un movimiento de la Crypto-space Ship. Esto se debe a que los motores se deben cargar para poder realizar el próximo salto.

    - **Mode**: poder cambiar de modo nuevamente.

    - **Fleet**: para poder utilizar nuestra flota nuevamente, ya sea para enviar recursos o para atacar una Crypto-space Ship enemiga. Hay que considerar que luego de un ataque o de un viaje, los drones necesitan reparaciones y recarga de energía.

    - **Fire** o **Repare**: La espera para poder realizar otra reparación o disparo de cañon. Este contador depende del rol elegido al momento de actualizar el WOPR a nivel 1.


********
Mensajes
********

Es la manera que tienen las Crypto-space Ship para comunicarse entre si. Al instante de escribir un mensaje el capitan de la otra Crypto-space Ship ya puede leerlo.
Solamente es necesario saber el nombre de la otra Crypto-space Ship a la hora de redactar el mensaje.



*******
Eventos
*******

