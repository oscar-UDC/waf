# Walk & Fight

Nombre del grupo: **JUDC**

## Descripción del proyecto y funcionalidades básicas

Este proyecto está centrado principalmente en hacer que el usuario mejore sus habilidades cognitivas y motrices. Al iniciar la aplicación se mostrará en un mapa diferentes puntos que el usuario tendrá que ir alcanzando, esto se comprobará mediante la geolocalización del teléfono. Una vez llegado al lugar indicado, se mostrará un minijuego donde se pondrá a prueba la capacidad de memorizar del usuario enfrentándose a un enemigo. En los diferentes minijuegos se utilizará tanto la pantalla táctil del dispositivo, como el uso del micrófono y el acelerómetro. Según se vayan alcanzando los diferentes puntos, el usuario recibirá algún tipo de mejora o pista para encontrar el siguiente punto y en cada punto, la dificultad irá incrementando progresivamente. Finalmente, se podrá compartir la puntuación alcanzada en redes sociales para intentar llegar a más público.

#### Anotaciones

- Al final decidimos utilizar un minijuego único que agrupe todos los sensores que íbamos a utilizar. 
- No se ha implementado la funcionalidad de compartir en RRSS. 
- No se han implementado las pistas y ayudas a los usuarios.

## Miembros, roles y funcionalidades asignadas

Hemos decidido dividirnos en dos grupos para las dos principales funcionalidades.

|             Miembro           |   Rol    | Funciones y funcionalidades asignadas |
|-------------------------------|----------|---------------------------|
| Daniel Vicente Ramos          |   CEO    | Responsable principal. Coordina y representa al equipo. Se encarga de gestionar el ciclo de vida completo de la aplicación, desde la arquitectura e integración de los módulos hasta el testing y la documentación general. Formará parte del grupo que se encargará de la funcionalidad de el/los minijuego(s). |
| Jesús Senra Paz               |   COO    | Encargado de la arquitectura y validación funcional de la aplicación. Formará parte del grupo que se encargará del mapa y localización, así como de la integración de los sensores   |
| Caetán Tojeiro Carpente       |   CTO    | CEO en funciones en caso de que el principal no esté disponible. Responsable del uso de sensores, geolocalización y APIs de terceros. Para este caso práctico, será encargado de investigar, analizar y validar la integración del GPS, de la cámara, del micrófono y del acelerómetro, así como del mapa. Formará parte del grupo que se encargará del mapa y localización, así como de la integración de los sensores     |
| Ulises Jaime Soria Matamoros  |   CXO    | Responsable de la usabilidad, UI y UX de la aplicación. Encargado de la integración de funcionalidades sociales. Formará parte del grupo que se encargará de la funcionalidad de el/los minijuego(s)   |

Todos los miembros son además responsables de la documentación de su área.

---


#### Anotaciones
- Daniel: El testing se hizo de forma manual, abriendo la aplicación y probando las funcionalidades. Desarrolló el minijuego completo en Unity y su comunicación con la aplicación. 

- Jesús: Centrado más en la integración del sensor de localización. 

- Caetán: La integración y comprobación de sensores (cámara, acelerómetro, micrófono) fue realizada por Daniel en Unity. 

- Ulises: Se centró en la UI/UX y la validación de diferentes dispositivos. 

---

## Target 

###  Género, edad, estatus socioeconómico.  

Todos los géneros de cualquier edad y estatus socioeconómico, solamente.  

### ¿Quiénes van a ser los potenciales clientes/usuarios? 

Gente entre 15 y 79 años. 

###  ¿A quién pretendemos dar servicio?  

Cualquier persona. 

###  ¿Creamos valor para alguien? ¿Quiénes? 

Si, para cualquier persona que desee mejorar sus habilidades cognitivas, aumentar su actividad física y reducir el sedentarismo. 

###  ¿Nos dirigimos a un mercado de masas o a un nicho concreto? ¿Va a afectar esto a la aplicación?  

Nos dirigimos a un mercado de masas puesto que pretendemos llegar a grupos de población muy amplios. 

###  ¿Qué características tiene nuestro cliente perfecto? (Early adopters) 

Una persona joven o de edad avanzada con tiempo libre que quiera reducir el sedentarismo de una forma divertida y retadora intelectualmente. 

#### Anotaciones
Nos centramos más en el público joven en las primeras fases de desarrollo y buscaríamos captar la atención de la gente mayor en futuras versiones con diferentes retos.

## Estudio de mercado 

### ¿Qué va a hacer que nuestra app no sea fácilmente copiable?  

Única en su género. Al ser la primera, tendremos la ventaja y la oportunidad de crear una comunidad propia alrededor de la propia aplicación a que le guste realizar hábitos más saludables. 

###  ¿Cómo nos diferenciamos de la competencia?  

Hoy en día, no se han encontrado aplicaciones que mezclen la parte física con la parte de retos mentales. Existen aplicaciones como Pokémon GO que “fomenta” la actividad física con el juego o numerosas aplicaciones que premian los pasos dados. Por otra parte, están las clásicas aplicaciones de puzles y juegos mentales como la saga del profesor Layton. 

###  ¿Cómo se va a crear una relación con los usuarios y cómo vamos a fidelizarlos? 

Se mantendrá el nivel de cada jugador, podrá visualizar sus estadísticas e intentar mejorarlas, compartirlas o ver las de otros usuarios. A mayores, si hay una distancia grande entre puntos, los minijuegos iniciales serán más sencillos e irá aumentando su complejidad cuando nos acercamos a un jefe (punto predefinido). 

###  Aplicaciones móviles con objetivos similares a los de la aplicación a desarrollar

* ZOMBIES RUN: Si necesitas sentirte en peligro o una motivación extra para moverte, deja de buscar porque esta es tu aplicación. Con ella conseguirás ponerte en forma jugando y es tan sencilla como ponerte los castos y dejarte llevar. Corre para huir de los muertos que iras escuchando a través de los auriculares y que quieren darte caza. Además, cuenta con registro de actividad y la posibilidad de escuchar también de fondo la música que elijas. 

* ORUXMAPS GP: Es una de las aplicaciones más completas para los amantes de la naturaleza. Con ella podemos obtener mapas online para planificar o seguir nuestras rutas campo a través. Si te alejas mucho del recorrido fijado, te avisa con una alarma y su sistema GPS recoge la información de nuestra ruta, pudiendo introducir nosotros mismos, fotos y puntos de interés que puedan servir de información adicional a otros usuarios. 

* NEXT TRACK: Condecoraciones, insignias, recompensas cuando acabes un ejercicio, toda motivación es poca para que pierdas peso de forma divertida y te pongas en forma. Con su enfoque de gamificación, consigue enganchar hasta a aquellos de carácter más perezoso. 

* Saga PROFESOR LAYTON: Retos mentales y puzles. Es un juego que sigue una historia, pero no requiere ningún tipo de actividad física (Figura 1). 

* POKÉMON GO: Es una aplicación basada en el juego Pokémon en donde los jugadores recorren las calles de su población en busca de criaturas peleas Pokémon. El juego requiere de actividad física pero no demanda ningún tipo de reto (Figura 2). 


![Sin título1](https://github.com/DanielV-source/waf/assets/19588029/10bd4918-8355-4b87-8db3-d221c1433802)

 Figura 1: Profesor Layton                                               


![Sin título](https://github.com/DanielV-source/waf/assets/19588029/d2e0f445-8e05-4216-bd7e-7be8d8d8a373)

 Figura 2: Pokémon GO                          

###  Análisis de mercado 

No hay ninguna aplicación similar en el mercado y esto puede ser una oportunidad para hacerse un hueco en el mismo. Si analizamos las aplicaciones que se basan en el ejercicio físico (NEXT TRACK, ORUXMAPS GP), parten de 100.000 descargas y son aptas para todos los públicos. En cuanto a retos mentales, existen aplicaciones de puzles, como la saga PROFESOR LAYTON, que ronda las 100.000 descargas con una puntuación excelente y cuenta con PEGI 3. Finalmente, si vemos aquellas que relacionan el ejercicio físico junto con juegos (ZOMBIES RUN, POKÉMON GO) rondarían entre 1 millón de descargas y están dirigidos a un público mayor de 13 años.  

Dentro del análisis exhaustivo de las principales debilidades y fortalezas en el desarrollo de nuestro juego, hemos identificado que uno de los desafíos más significativos radica en la diversidad y la particular rigidez de nuestro público objetivo. Este grupo se muestra dividido en sus intereses y preferencias, lo que representa un obstáculo considerable, ya que pueden mostrar resistencia a la hora de explorar opciones que se desvíen de sus gustos preestablecidos. Sin embargo, al mismo tiempo, esta circunstancia se presenta como una oportunidad única. La ausencia de alternativas en el mercado que combinen de manera efectiva elementos de ejercicio físico con desafíos mentales constituye un nicho inexplorado. Esta singularidad de nuestro proyecto podría captar la atención y el interés de aquellos en busca de nuevas experiencias lúdicas, ofreciendo una propuesta innovadora que se distingue claramente de las opciones tradicionales disponibles. Por tanto, pese a los retos de la diversidad del público objetivo, la naturaleza única de nuestro juego puede generar un impacto significativo en el mercado, atrayendo a aquellos interesados en una experiencia de juego más integral y enriquecedora. 

En 2022, según el Concello de A Coruña [1], en la ciudad había 180.000 personas de entre 15 y 79 años, nuestro mercado de potenciales usuarios, personas que por las características técnicas y de la aplicación podrían descargarla y utilizarla. Según lo visto en clase, a fecha de enero de 2024 en torno a un 75% de usuarios móviles en España usan Android, por lo que, extrapolando estos datos a la ciudad de A Coruña, y que un 80% de la población tiene un smartphone tenemos en torno a un total de en torno 108.000 de usuarios Android. Con la información recogida, podemos observar que la aplicación puede recibirse bien en este mercado, esperando mínimo unas 10.000 descargas en cuanto se establezca este nuevo referente. 

#### Anotaciones
- Las estadísticas globales y personales se implementarían en futuras versiones.

## Funcionalidades

* Minijuegos (AR Core y Unity) - Daniel y Ulises

* Representación ruta en mapa - Caetán y Jesús 

* Crear una ruta - Caetán y Jesús 

* Cancelar ruta - Caetán y Jesús 

* Visualizar estadísticas - grupal

* Compartir en redes sociales - Ulises

* Registro e inicio de sesión por Google - Daniel

#### Anotaciones
- Minijuego (Unity) - Daniel.

- No hay un botón específico para cancelar ruta, pero si es posible iniciar una nueva desde el botón “Empezar aventura”. 

- La visualización de estadísticas se implementaría en futuras versiones.

- La integración con RRSS se implementaría en futuras versiones. 

- Además, la gestión del perfil fue implementada por Ulises.

## Diseño de la arquitectura de comunicaciones

El sistema se basará en una aplicación móvil que haga uso de sensores y características del teléfono Android. Por otra parte, el móvil deberá tener conexión a internet para poder conectarse a los servicios de la aplicación. A su vez, ciertas características de la aplicación harán uso de APIs de terceros.
 
![APM](https://github.com/DanielV-source/waf/assets/19588029/1035e6d3-4ce9-489e-896f-a0022bbee92d)

- Las líneas punteadas son conexiones a APIs externas 
- Las líneas continuas son conexiones entre la aplicación y los servicios propios en la nube de la aplicación 
- La línea con las flechas indica el uso del hardware del smartphone por parte de la aplicación 

[1] https://www.coruna.gal/descarga/1453722307416/Distribucion-de-la-poblacion-municipal-segun-sexo-y-edad.pdf 

#### Anotaciones
- No se utilizó AR Core, debido a su complejidad y falta de tiempo. En cambio, se optó por una aproximación 2D más interactiva.

- No se ha implementado un backend para la aplicación.

- No se ha implementado todavía la integración con RRSS.

## Mockups

![image](https://github.com/DanielV-source/waf/assets/19588029/e3adcdff-6607-4b65-991d-1764d803ad42)

### Versión digital para móviles y tablets

#### Versión claro
![APM-Pantallas-claro](https://github.com/DanielV-source/waf/assets/79198704/d87d161b-28b6-46ce-a023-f23803cd7979)
#### Versión oscuro
![APM-Pantallas-oscuro](https://github.com/DanielV-source/waf/assets/79198704/7f393363-1a28-47c2-a81b-fc34f0684aaf)

### Flujo de pantallas

#### Versión claro
![APM-Flujo-de-pantallas-claro](https://github.com/DanielV-source/waf/assets/79198704/c3af518b-8796-4f36-a0b1-227beae32bb9)
#### Versión oscuro
![APM-Flujo-de-pantallas-oscuro](https://github.com/DanielV-source/waf/assets/79198704/0efc6377-0b75-457b-b1bb-b544bd6824ef)

### Diseño de pantallas con editor UIs

![Temp](https://github.com/DanielV-source/waf/assets/79198704/b8bdc112-8d56-4780-b177-82feeccf81ae)

#### Anotaciones
- El minijuego se ha implementado con otra lógica, pero manteniendo la idea original. 

- La alerta por llegada a un punto de batalla no será tan prominente y consistirá en la aparición de un simple botón con el texto "Fight!".

## Arquitectura

### ¿Qué se pretende implementar como una actividad?  

Tan solo habrá actividades para los componentes básicos de la aplicación. Estas actividades harán uso de fragments para la representación completa de la aplicación de una manera óptima. A continuación, se enumeran todas las actividades: 

- MainActivity: En esta actividad se implementa la pantalla de inicio de sesión y es el punto de entrada a la aplicación. En ella se implementa la gestión del inicio de sesión y el cierre de sesión. 
- InitMenuActivity: Esta actividad implementará el fragment MainFragment, así como la toolbar y fragment lateral ProfileFragment. 
- FightActivity: Esta actividad gestiona el servicio de Unity, permitiendo la comunicación del motor con la aplicación. 


### ¿Qué se va a implementar como un servicio?  

Se implementará el servicio oculto de “escucha” para registrar los logs de Unity y poder comunicar el progreso del reto con los datos del usuario en la aplicación y viceversa. 


### ¿Qué se va a implementar con fragments?  

Se implementará la toolbar que se añadirá en las pantallas requeridas, donde se muestre un logo y un menú desplazable lateral. Esta toolbar se situará en la parte superior y dispondrá de un botón de despliegue y ocultación con el nombre de usuario, un botón para volver a la pantalla inicial y un botón para cerrar la sesión. 

- MainFragment: Esta es la pantalla inicial de la aplicación una vez que el usuario ha iniciado la sesión. Desde ella es posible comenzar una nueva aventura, continuar una aventura ya iniciada y visitar las estadísticas. Dependiendo de la opción elegida se reemplazará este fragment por el indicado. 
- MyStatisticsFragment: En este fragment se implementa la pantalla que recopila las opciones para ver las diferentes estadísticas en vista a una futura extensión de estas. Para esta primera versión esta pantalla solo mostrará la opción de ver las estadísticas globales y la de volver a la pantalla inicial. Las estadísticas globales se representan con un fragment que reemplazará a MyStatisticsFragment. 
- RankingFragment: En este fragment se implementa la pantalla donde se muestran las estadísticas de todos los jugadores de la aplicación. 
- OSMFragment: Este fragment representa el mapa. En él se implementa la localización del usuario mediante su GPS y se detecta cuando este esté próximo a un punto concreto donde se encuentra un reto. Cuando esto sucede, se mostrará un botón sobre el mapa para lanzar el reto. Esto reemplazará el fragment por el del reto, llamado FightFragment. 
- FightFragment: Este fragment gestiona el reto y lanza la actividad FightActivity para gestionar el servicio de Unity. Una vez terminado el reto, se reemplaza por el fragment correspondiente dependiendo del resultado del reto y del tipo de rival. 
- WinnerFragment: En este fragment se implementa la pantalla que muestra las estadísticas del reto y se permite al usuario compartirlo en redes sociales o volver a la pantalla de inicio. En caso de continuar y siempre y cuando el reto no sea un reto final, este fragment será substituido por OSMFragment. En caso de elegir la opción de retornar al menú principal, se substituirá por el fragment MainFragment. 
- LoserFragment: En este fragment se implementa la pantalla que muestra las estadísticas del reto y se permite al usuario volver a intentar el reto o volver a la pantalla de inicio. En el primer caso, se reemplazará el fragment por OSMFragment. En caso de elegir la opción de retornar al menú principal, se substituirá por el fragment MainFragment. 
- ProfileFragment: Se implementa la barra lateral del menú desplegable con la toolbar y tendrá un botón para volver a la pantalla inicial y un botón para cerrar la sesión. 
 

### ¿Quién lanza a quién y quién hace uso de los fragments o los servicios? 

Para el servicio, este será lanzado por la el fragment FightFragment. Cuando el usuario se encuentre próximo al punto requerido, aparecerá en la pantalla un botón con el texto Fight. Haciendo tap en el botón, el servicio para que el reto y la aplicación se comuniquen con Unity será lanzado. Este servicio será intrgrado en FightActivity. 

Para los fragments: 
- MainFragment será cargado por MainActivity 
- MainFragment será reemplazado por OSMFragment 
- MainFragment será reemplazado por MyStatisticsFragment 
- MyStatisticsFragment será reemplazado por MainFragment 
- MyStatisticsFragment será reemplazado por RankingFragment 
- OSMFragment será reemplazado por FightFragment 
- FightFragment será reemplazado por LoserFragment  
- FightFragment será reemplazado por WinnerFragment 
- LoserFragment será reemplazado por OSMFragment 
- LoserFragment será reemplazado por MainFragment 
- WinnerFragment será reemplazado por MainFragment 
- WinnerFragment será reemplazado por OSMFragment  
- ProfileFragment será usado en caso de navegación 
 

Debido a la operabilidad y naturaleza de nuestra aplicación, su uso se restringe a dispositivos smartphone, no tablets ni pantallas grandes, por lo que la aplicación tendrá las mismas apariencias y distribución de pantallas a excepción de los retos ya mostrados. 

Esta restricción se debe a que la aplicación necesita conectividad de datos móviles, GPS y ciertos sensores más, algo que solo es posible asegurar en dispositivos móviles smartphones. Además, la usabilidad de una pantalla grande en los desplazamientos y en la manera de completar los retos se antoja poco manejable. 


### Definición de las necesidades de tareas en segundo plano. 

A modo de recordatorio, se pasa a definir los términos clave:

- _Activities_: Representan una única pantalla con una interfaz de usuario, cada actividad es independiente y se puede iniciar otras actividades. Las aplicaciones suelen tener varias actividades que interactúan entre sí. 
- _Services_: Se puede realizar operaciones de larga duración sin proporcional una interfaz de usuario. 
- _Corrutinas_: Se utilizan para ejecutar tareas asíncronas en _threads_ ligeros

A continuación, se enumeran las diferentes actividades en segundo plano que tendrá la aplicación:
- Geolocalización / Open Street Maps: Es necesario seguir la posición del usuario en todo momento para que cuando su ubicación se encuentre dentro del rango de un punto se lanza la actividad del reto.  La geolocalización será de tipo _geofencing_ ya que necesitamos lanzar un evento basado en la ubicación de un usuario, es decir, cuando su ubicación se encuentre dentro del rango de distancia definido al punto del reto. 
- Unity: Este servicio es necesario para obtener y controlar el estado del juego en todo momento, así como saber si el usuario ha superado la prueba o no (con su consecuente pantalla de victoria o derrota. 

Además, como corrutina se implementa también la llamada a la API de openrouteservice (https://api.openrouteservice.org/v2) para la obtención de los puntos intermedios de la ruta, es decir, los puntos donde se encuentran los retos. 


### Servicios de Google

En este caso se implementan 2 servicios de Google/Android. 

- *Autenticación*: Se hace uso del paquete _signin_ de Google. Esta autenticación se hace con la integración de Firebase, siendo este el que almacena los tokens de acceso y admite o deniega el acceso de los usuarios. 
- *Geolocalización*: Se hace uso del paquete _location_ de Android para acceder al GPS y obtener así la ubicación del usuario. La ubicación de la que se hace uso es la ubicación más precisa (_ACCESS_FINE_LOCATION_) y también se solicita siempre la ubicación actual, no la última ubicación conocida. En este caso se está haciendo uso de Open Street Maps en lugar de Google Maps para representar la ubicación del usuario en un mapa. Cabe recordar que se hará uso de una estrategia de _geofencing_. Además, para lanzar el evento del reto, el usuario puede estar en un radio de 20 metros alrededor del punto en el que se ubica el reto.  

En este caso, además de obtener la ubicación del usuario mediante el GPS del dispositivo, también se puede obtener de la red que use para aquellos dispositivos independientemente de GPS, así que permitimos la usabilidad de la aplicación en diferentes dispositivos con o no sensor GPS.

### Almacenamiento 

Para este proyecto, el almacenamiento necesario es básico. Por una parte, se necesita hacer uso del almacenamiento interno para poder comunicar ciertos datos entre los diferentes componentes. En este caso, y como los datos no son críticos ni confidenciales, se hace uso de _SharedPreferences_ para poder tener acceso a las coordenadas en el mapa. Estas coordenadas serán guardadas en _SharedPreferences_ al inicializar el mapa y podrán ser usadas en cualquier lugar de la aplicación. En este caso, en los diferentes _handlers_ que gestionan las ubicaciones del mapa. La puntuación actual de la partida también será guardada en el _SharedPreferences_, así como la dificultad y el punto actuales en el que tiene que luchar, para poder recuperar la partida mientras la aplicación no se cierre. 

El resto de información sobre el usuario, como el nombre, el correo, etc. se obtendrá directamente de _Firebase_. 

Trabajo futuro: 

- Implementación de un almacenamiento externo para los rankings globales y personales del usuario, así como el punto de la partida en el que el usuario está de forma no volátil, para permitir al usuario recuperar la partida en cualquier momento. 
- Implementación de dificultad dinámica según los resultados que vaya teniendo el usuario durante la partida. 

### Usabilidad y UX

Aplicando la guía de referencia de _Material Design_ (https://m2.material.io/design/material-theming/overview.html#material-theming) aplicaremos un cambio en el color de fondo de los botones del menú principal. 

* Se identificarán los botones primarios con el color primario de referencia (código hexadecimal #6200EE) 

#### Contactar con responsables de UX de otros grupos para probar y dar _feedback_ de las _apps_

1. Contactamos con Alejandro Rodríguez de la aplicación "SwimChrono". 

    * Aumentar el tamaño del título inicial de la aplicación "Walk and Fight". 
    * Aumentar el tamaño de los botones y las letras del menú. 
    * Ajustar el _fragment_,  reducir el tamaño y cambiar el color.  
    * Los botones del menú están bien colocados. 
    * Antes de que se inicie el juego, poner la descripción de la actividad en el cuadro que arroja la flecha azul. 
    * El _Sign in_ con Google, se ve bien al inicio. 

2. Contactamos con Diego López de la aplicación "ScapeTheAds". 

    * Modificar el color de rojo a rojo más oscuro. 
    * Modificar el botón de "Fight" en el mapa, ubicándolo más abajo. 
    * Cambiar el color de los botones del menú principal. 
    * Colocar información en _Profile_. 
    * Ajustar el _fragment_,  reducir el tamaño y cambiar el color. 
    * El _Sign in_ con Google, se ve bien al inicio. 

De estos feedback, el equipo ha acordado e implementado las siguientes recomendaciones: 

* Aumentar el tamaño de los botones y las letras del menú. 
* Modificar el botón de "Fight" en el mapa, ubicarlo más abajo. 
* Cambiar el color de los botones del menú principal. 
* Colocar información en _Profile_. 

## Modelo de negocio

### Lean canvas

![image](https://github.com/DanielV-source/waf/assets/56442137/167f6c86-3cc6-4ced-972f-02d5a751458a)