# Walk & Fight

Nombre del grupo: **JUDC**

## Descripción del proyecto y funcionalidades básicas

Este proyecto está centrado principalmente en hacer que el usuario mejore sus habilidades cognitivas y motrices. Al iniciar la aplicación se mostrará en un mapa diferentes puntos que el usuario tendrá que ir alcanzando, esto se comprobará mediante la geolocalización del teléfono. Una vez llegado al lugar indicado, se mostrará un minijuego donde se pondrá a prueba la capacidad de memorizar del usuario enfrentándose a un enemigo. En los diferentes minijuegos se utilizará tanto la pantalla táctil del dispositivo, como el uso del micrófono y el acelerómetro. Según se vayan alcanzando los diferentes puntos, el usuario recibirá algún tipo de mejora o pista para encontrar el siguiente punto y en cada punto, la dificultad irá incrementando progresivamente. Finalmente, se podrá compartir la puntuación alcanzada en redes sociales para intentar llegar a más público.


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

 

### Funcionalidades

* Minijuegos (AR Core y Unity) 

* Representación ruta en mapa 

* Crear una ruta 

* Cancelar ruta 

* Visualizar estadísticas 

* Compartir en redes sociales 

* Registro e inicio de sesión por Google 


###  Análisis de mercado 

No hay ninguna aplicación similar en el mercado y esto puede ser una oportunidad para hacerse un hueco en el mismo. Si analizamos las aplicaciones que se basan en el ejercicio físico (NEXT TRACK, ORUXMAPS GP), parten de 100.000 descargas y son aptas para todos los públicos. En cuanto a retos mentales, existen aplicaciones de puzles, como la saga PROFESOR LAYTON, que ronda las 100.000 descargas con una puntuación excelente y cuenta con PEGI 3. Finalmente, si vemos aquellas que relacionan el ejercicio físico junto con juegos (ZOMBIES RUN, POKÉMON GO) rondarían entre 1 millón de descargas y están dirigidos a un público mayor de 13 años.  

Dentro del análisis exhaustivo de las principales debilidades y fortalezas en el desarrollo de nuestro juego, hemos identificado que uno de los desafíos más significativos radica en la diversidad y la particular rigidez de nuestro público objetivo. Este grupo se muestra dividido en sus intereses y preferencias, lo que representa un obstáculo considerable, ya que pueden mostrar resistencia a la hora de explorar opciones que se desvíen de sus gustos preestablecidos. Sin embargo, al mismo tiempo, esta circunstancia se presenta como una oportunidad única. La ausencia de alternativas en el mercado que combinen de manera efectiva elementos de ejercicio físico con desafíos mentales constituye un nicho inexplorado. Esta singularidad de nuestro proyecto podría captar la atención y el interés de aquellos en busca de nuevas experiencias lúdicas, ofreciendo una propuesta innovadora que se distingue claramente de las opciones tradicionales disponibles. Por tanto, pese a los retos de la diversidad del público objetivo, la naturaleza única de nuestro juego puede generar un impacto significativo en el mercado, atrayendo a aquellos interesados en una experiencia de juego más integral y enriquecedora. 

En 2022, según el Concello de A Coruña [1], en la ciudad había 180.000 personas de entre 15 y 79 años, nuestro mercado de potenciales usuarios, personas que por las características técnicas y de la aplicación podrían descargarla y utilizarla. Según lo visto en clase, a fecha de enero de 2024 en torno a un 75% de usuarios móviles en España usan Android, por lo que, extrapolando estos datos a la ciudad de A Coruña, y que un 80% de la población tiene un smartphone tenemos en torno a un total de en torno 108.000 de usuarios Android. Con la información recogida, podemos observar que la aplicación puede recibirse bien en este mercado, esperando mínimo unas 10.000 descargas en cuanto se establezca este nuevo referente. 

 

## Diseño de la arquitectura de comunicaciones

El sistema se basará en una aplicación móvil que haga uso de sensores y características del teléfono Android. Por otra parte, el móvil deberá tener conexión a internet para poder conectarse a los servicios de la aplicación. A su vez, ciertas características de la aplicación harán uso de APIs de terceros.
 
![APM](https://github.com/DanielV-source/waf/assets/19588029/1035e6d3-4ce9-489e-896f-a0022bbee92d)

- Las líneas punteadas son conexiones a APIs externas 
- Las líneas continuas son conexiones entre la aplicación y los servicios propios en la nube de la aplicación 
- La línea con las flechas indica el uso del hardware del smartphone por parte de la aplicación 

[1] https://www.coruna.gal/descarga/1453722307416/Distribucion-de-la-poblacion-municipal-segun-sexo-y-edad.pdf 

 


