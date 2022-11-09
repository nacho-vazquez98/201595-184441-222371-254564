# Iteración 1

# Índice

- [Identificación del problema a resolver](#Identificación_del_problema_a_resolver)
    - [Analisis del entorno](#Analisis_del_entorno)
        - [Entendimiento del MVP](#Entendimiento_del_MVP)
        - [Ingeniería inversa sobre aplicaciones conocidas similares](#Ingeniería_inversa_sobre_aplicaciones_conocidas_similares)
        - [Identificación de interesados](#Identificación_de_interesados)
        - [Estudio de competidores](#Estudio_de_competidores)
    - [Funcionalidades por interesado](#Funcionalidades_por_interesado)
- [Definición del problema](#Definición_del_problema)
    - [Story Map](#Story_Map)
    - [Product Backlog](#Product_Backlog)
        - [Epicas](#Epicas)
        - [Historias de usuarios](#Historias_de_usuarios)
    - [Criterios de aceptacion](#Criterios_de_aceptacion)
- [Dailys](#Dailys)
- [Sprint Planning](#Sprint_Planning)
- [Horas dedicadas](#Horas_dedicadas)
- [Retrospective](#Retrospective)
---

## Objetivos de la iteracion<a name="Identificación_del_problema_a_resolver"></a>

- Creación del Azure board.
- Creación del product backlog a partir de los requerimientos.
- Estudiar posibles competidores.
- Organizacion del equipo en roles

## Identificación del problema a resolver<a name="Identificación_del_problema_a_resolver"></a>

### Analisis del entorno<a name="Analisis_del_entorno"></a>

#### Entendimiento del MVP<a name="Entendimiento_del_MVP"></a>

El Proyecto se basa en realizar un prototipado de una aplicación enfocada en facilitar la movilidad urbana.
Para esto, nos basaremos en aplicaciones que ya son utilizadas por la mayoría de la población uruguaya.
Este MVP será un prototipo que validara el concepto planteado por los docentes, este pretende llegar a convertirse en una versión competitiva de las aplicaciones antes mencionadas, sumándole varias funcionalidades que estas no contienen y que además podrían mejorar significativamente la experiencia del usuario.

#### Ingeniería inversa sobre aplicaciones conocidas similares<a name="Ingeniería_inversa_sobre_aplicaciones_conocidas_similares"></a>

**STM Montevideo**

Las funcionalidades relevantes encontradas en esta aplicación, fueron:
-	Te muestra las paradas
-	Al seleccionar en una parada te muestra las líneas que pasan por esa parada, los horarios estimados de cada línea y te las muestra en tiempo real. 
-	Si seleccionas en una línea te muestra los horarios
-	Podes marcar una parada como favorita
-	Podes buscar una dirección, lugar de interés o lugar marcado como favorito y te muestra que líneas te podes tomas para llegar a ese lugar/dirección
-	Podes consultar todos los horarios de una línea especifica y compartirlos
-	Podes pedir que te muestre los locales STM en el mapa y te los distingue según sean solo de recarga o recarga y entrega de tarjetas.
-	Podes seleccionar una línea y que te muestre su recorrido en el mapa

Imagenes de la aplicación:
![](https://i.imgur.com/xjN7wk0.jpg) | ![](https://i.imgur.com/QAeLNy7.jpg) | ![](https://i.imgur.com/1gqUBnY.jpg) |
| --- | --- | --- |
![](https://i.imgur.com/jHM3pGj.jpg) | ![](https://i.imgur.com/zxEV26b.jpg) | ![](https://i.imgur.com/WM7CC0D.jpg) | 
![](https://i.imgur.com/EyBmDGg.jpg) | ![](https://i.imgur.com/fDYSLEY.jpg) | ![](https://i.imgur.com/3XTjSHF.jpg) | 
![](https://i.imgur.com/WT44jZe.jpg) | ![](https://i.imgur.com/FQseQ4G.jpg) |

**Movit**

Funcionalidades que existen en Moovit:
* Marcar destino y que se despliegue una lista con diferentes rutas de ómnibus para llegar al destino
* Integración con Uber para pedir uno
* Marcar parada como favorita
* Marcar ubicaciones como favoritos(Ej: Casa, Trabajo, etc)
* Marcar líneas como favorita
* Opción para marcar mejor ruta, caminar más o menos transbordos
* Opción para marcar preferencias de tipo de transporte

| ![](https://i.imgur.com/9oOm9lF.png)     | ![](https://i.imgur.com/tkOVxZH.png)     | ![](https://i.imgur.com/uZpJCdi.png)     |
| -------- | -------- | -------- |
| ![](https://i.imgur.com/oJbnSsR.png) |  ![](https://i.imgur.com/eXf4slm.png) |

**Como Ir**

Funcionalidades que existen en Como Ir que no están en nuestra aplicación:

* Ingresar punto de destino y origen, pudiendo ser el origen tu ubicacion actual, muestra las lineas/ combinacion de lineas posibles para llegar al destino, muestra tiempo estimado para la llegada del omnibus a la parada, y el tiempo de viaje.
* Se puede hacer click en una parada, para ver cuanto tiempo falta para que pasen las lineas
* Se puede guardar direcciones como favoritas
* Se puede guardar la tarjeta STM, para poder ver el saldo disponible, ultimo viaje, cantidad de viajes por mes.
* Envia notificaciones por cambios puntuales en los recorridos de las lineas, por paros.

| ![image](https://i.imgur.com/wD1XGGj.jpg)| ![image](https://i.imgur.com/ZdseMBU.jpg)| ![image](https://i.imgur.com/jmcp4uL.jpg)|
| -------- | -------- | -------- |
| ![image](https://i.imgur.com/CKneFz2.jpg)|![image](https://i.imgur.com/8xWyI4q.jpg)|![image](https://i.imgur.com/8YZxphd.jpg)| 
![image](https://i.imgur.com/Ivfj3Kb.jpg)


#### Identificación de interesados<a name="Identificación_de_interesados"></a>

En primer lugar, creemos que el MVP debería de enfocarse en el publico más fácil de alcanzar y de validar, este basado en la aplicación que queremos desarrollar sería el que cumpla con las siguientes características
* Persona entre 15 y 30 años (La edad se ampliará a medida que el MVP sea testeado)
* Sin vehículo personal
* Usuario habitual de transporte publico

#### Estudio de competidores<a name="Estudio_de_competidores"></a>

En cuanto a los principales competidores, consideramos que serian apps como STM Montevideo, Como ir o Moovit, ya que son las mas conocidas. Igualmente, existen otras apps no tan conocidas, como puede ser Nextbus Montevideo, las cuales tambien son consideradas competencia pero estas al no ser tan conocidas no las concideramos como competencia importante ya que no tienen un gran peso en el mercado.
Por otra parte, si el día de mañana nuestra app se ampliara al mercado de los omnibus interdepartamentales, una competencia posible podría ser SeguíTuBus la cual solo se dedica a los omnibus que empiezan o terminan su trayecto en la terminal de tres cruces.

### Funcionalidades por interesado<a name="Funcionalidades_por_interesado"></a>

- Usuario final

Todas las funcionales de la aplicación son pensadas para el usuario final, el cual es el cliente de la aplicación, especificado en la parte de identificación de interesados.

Dentro de los usuarios finales, estos se pueden subdividir en: conductores, pasajeros e inspectores.

- Conductores

Los conductores son los encargados de hacer que el vehiculo este en hora en cada parada, y debe respetar el recorrido preestablecido.

- Pasajeros

Los pasajeros son los usuarios principales de la aplicacion, son los que van a utilizar la aplicacion para saber en que parada esta el omnibus, y en que tiempo llegara a la parada, el recorrido de los mismos, etc.

- Inspectores

Los inspectores son los encargados de verificar que los conductores cumplan con el recorrido preestablecido, y que los vehiculos esten en hora en cada parada.


- Dueño del producto

La funcionalidad de STM al ser una funcionalidad agregada a lo que fue solicitado, 
se considera como una funcionalidad de interés para el dueño del producto.

| Funcionalidad | Conductor | Pasajero | Inspector | Dueño del producto |
| --- | --- | --- | --- | --- |
| STM | - | X | - | X |
| Usuario | - | X | - | - |
| Lineas de omnibus | X | X | X | - |
| Viajes | X | X | X | - |
| Notificaciones | - | X | - | - |

## Definición del problema<a name="Definición_del_problema"></a>

### Story Map<a name="Story_Map"></a>
* Story Points

La siguiente tabla establece el work effort realcionado a los story points. Basamos que cada integrante del grupo trabajara 5 horas por semana. Por lo tanto en un sprint de dos semanas cada uno podria hacer 10 horas de esfuerzo.

| Story Points | Work Effort | 
| -------- | -------- |
| 1     | 0.5 hours     |
| 2     | 1 hours     |
| 3     | 2 hours     |
| 5     | 5 hours     |
| 8     | 10 hours     |

![specmap-Obligatorio ISA1 - 2022-Story Map](https://user-images.githubusercontent.com/45313301/194671274-060a728e-a9ef-4bd3-91af-b762ee13c1ce.png)

### Product Backlog<a name="Product_Backlog"></a>

![image](https://i.imgur.com/HNdqTU0.png)
![image](https://i.imgur.com/wkL7Nod.png)

#### Epicas<a name="Epicas"></a>

Al momento de crear epicas, el criterio que tomamos fue primero tomar cada requerimiento funcional, y agruparlos, por ejemplo, todas las cosas referidas a usuarios, todas las cosas referidas a Lineas de Omnibus, etc. De eesta forma, llegamos a las siguientes epicas, las cuales tienen cada una sus user stories como dependientes de esta

![image](https://i.imgur.com/M45xabQ.png)

#### Historias de usuarios<a name="Historias_de_usuarios"></a>

Luego de dividir en epicas, nos tomamos el tiempo para ver que compone a cada una. Por ejemplo, la epica de usuarios se divide en iniciar sesion, registrarse, editar perfil, cerrar sesion, restaurar contraseña, y el historial de viajes. 
Aqui listamos todas las user stories que creamos (para ver la dependencia epica-historia ver imagen [Product Backlog](#Product_Backlog))
![image](https://i.imgur.com/hjr7CCb.png)
![image](https://i.imgur.com/koIzf57.png)

#### Criterios de aceptacion<a name="Criterios_de_aceptacion"></a>
Cada user story tiene su propio criterio de aceptacion, dependiendo de lo que la tarea conlleve. A continuacion se muestran dos ejemplos de las stories y sus criterios de aceptacion
![image](https://i.imgur.com/J2WmKsY.jpeg)
![image](https://i.imgur.com/csFPL2T.jpeg)

#### Priorizacion de las tareas

![image](https://i.imgur.com/r4E3QIj.jpeg)

Como se puede ver en la imagen anterior, se realizo una priorizacion de tareas por parte dle Product Owner. Tambien les dimos story points decididos entre todo el equipo de desarrollo junto con el el Product Owner.

## Dailys<a name="Dailys"></a>
### Primera Daily 23/09/2022
En esta primra daily, definimos los roles de cada uno de los integrantes, definimos cuales iban a ser las adapataciones necesaria del marco. Ademas definimos las tareas a realizar hasta la proxima daily de cada integrante. Dichas tareas fueron: para Ignacio, Joaquin y Martin, hacer ingenieria inversa de una aplicacion competidora a nuestra aplicacion. Para Juan, fue hacer el entendimiento del MVP.

### Segunda Daily 30/09/2022
Discutimos las epicas que fuimos armando a partir de las features presentadas en la letra, y la que decidimos agregar para brindar un valor adicional al producto, y user stories de las que se compone cada una, con su descripcion y criterio de aceptacion de la misma.

### Tercera Daily 02/10/2022
Priorizamos las epicas y las user stories, ademas asignamos un storie point a cada user storie. Vinculamos cada user storie con su respectiva epica.

### Cuarta Daily 07/10/22
Completamos definition of ready y definition of done, creamos el story map, y continuamos llenando la documentacion con las actividades que fuimos haciendo a lo largo de la iteracion.

## Sprint Planning<a name="Sprint_Planning"></a>
Realizamos la planning para la siguiente iteracion, en la cual priorizamos las tareas que vamos a realizar.
En primer lugar, asignamos story points a cada user story, ya que aun no habiamos tenido una instancia de valorar cada una. Luego de tener estos valores, realizamos el Story Map, el cual esta documentado anteriormente. 
En esta instancia tambien asignamos las tareas que cada integrante del equipo de desarrollo va a realizar.

## Horas dedicadas<a name="Horas_dedicadas"></a>

Cada integrante hizo aproximadamente una hora por daily ya que esta fue la duración de las mismas, y luego cada uno trabajó entre dos y dos horas y media fueras de las reuniones.

## Retrospective<a name="Retrospective"></a>
Evidencia de Retrospective:
![image](https://i.imgur.com/4A0J8XO.png)
![image](https://i.imgur.com/Z4DplZA.png)

### Reflexion y conclusiones

A partir de los sticky notes que pusieron notamos que a la hora de realizar tareas, estas se completan de forma exitosa, el mayor problema del equipo se encuentra a la hora de coordinar las reuniones y en el momento de las reuniones, ya que por un motivo u otro, nos terminamos desconcentrando y desviando el tema.

Para solucionar uno de estos problemas, lo que decidimos hacer es programar las reuniones por medios como Google Calendar, para tener un recordatorio de cuando va a ser, y de esta forma reducir las demoras por olvido. En cuanto a las distracciones durante las mismas, intentaremos mejorar esto al momento de reunirnos.

## Valor agregado a la aplicacion

Como se menciono anteriormente, el equipo decidio agregar una funcionalidad extra a las pedidas en la letra, esta siendo todo lo vinculado a la tarjeta STM. Esta idea surgio de la aplicacion competidora Como Ir, la cual permite ver la cantidad de boletos que tiene la tarjeta de alguien. Nosotros decidimos ir un paso mas y permitirle al usuario tambien poder recargar boletos por medio de nuestra aplicacion.
