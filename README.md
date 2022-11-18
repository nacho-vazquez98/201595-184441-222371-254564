## Universidad ORT Uruguay

# Obligatorio de Ingeniería de Software Agil 1


*Estudiantes:*
- Martin Gulla - 254564
- Joaquin Sommer - 184441
- Juan Toledo - 222371
- Ignacio Vázquez - 201595

*Profesoras:*
- Fabiana Pedrini
- Analia Moreira

Entrega como requisito para la materia de : Ingenieria de Software Agil 1

---
# Indice
- [Obligatorio de Ingeniería de Software Agil 1](#obligatorio-de-ingeniería-de-software-agil-1)
- [Indice](#indice)
- [Definición del marco de trabajo<a name="Definición_del_marco_de_trabajo"></a>](#definición-del-marco-de-trabajo)
	- [Adaptaciones del marco SCRUM<a name="Adaptaciones_del_marco_SCRUM"></a>](#adaptaciones-del-marco-scrum)
	- [Definición de roles del equipo<a name="Definición_de_roles_del_equipo"></a>](#definición-de-roles-del-equipo)
		- [Product owner](#product-owner)
		- [Scrum master](#scrum-master)
		- [Developer](#developer)
		- [Definición de roles](#definición-de-roles)
	- [Politicas de trabajo<a name="Politicas_de_trabajo"></a>](#politicas-de-trabajo)
		- [Definición de los eventos Scrum<a name="Eventos-Scrum_I3"></a>](#definición-de-los-eventos-scrum)
			- [Dailys<a name="Dailys_I3"></a>](#dailys)
			- [Planning/Grooming<a name="Planning_Grooming_I3"></a>](#planninggrooming)
			- [Retro<a name="Retro_I3"></a>](#retro)
		- [Definition of Ready<a name="Definition_of_Ready"></a>](#definition-of-ready)
		- [Definition of Done<a name="Definition_of_Done"></a>](#definition-of-done)
			- [Definition of Done de los prototipos<a name="Definition_of_done_de_los_prototipos"></a>](#definition-of-done-de-los-prototipos)
	- [Repositorio del proyecto<a name="Repositorio_del_proyecto"></a>](#repositorio-del-proyecto)
		- [Flujo de trabajo con GIT<a name="Flujo_de_trabajo_con_GIT"></a>](#flujo-de-trabajo-con-git)
		- [Representacion de flujo de trabajo con git](#representacion-de-flujo-de-trabajo-con-git)
	- [Desarrollo de prototipo<a name="Desarrollo_de_prototipo"></a>](#desarrollo-de-prototipo)
- [Iteraciones<a name="Iteraciones"></a>](#iteraciones)
	- [Iteracion 1<a name="Iteracion_1"></a>](#iteracion-1)
		- [Objetivos de la iteracion<a name="Objetivos_de_la_iteracion"></a>](#objetivos-de-la-iteracion)
		- [Identificación del problema a resolver<a name="Identificación_del_problema_a_resolver"></a>](#identificación-del-problema-a-resolver)
			- [Analisis del entorno<a name="Analisis_del_entorno"></a>](#analisis-del-entorno)
				- [Entendimiento del MVP<a name="Entendimiento_del_MVP"></a>](#entendimiento-del-mvp)
				- [Ingeniería inversa sobre aplicaciones conocidas similares<a name="Ingeniería_inversa_sobre_aplicaciones_conocidas_similares"></a>](#ingeniería-inversa-sobre-aplicaciones-conocidas-similares)
				- [Identificación de interesados<a name="Identificación_de_interesados"></a>](#identificación-de-interesados)
				- [Estudio de competidores<a name="Estudio_de_competidores"></a>](#estudio-de-competidores)
			- [Funcionalidades por interesado<a name="Funcionalidades_por_interesado"></a>](#funcionalidades-por-interesado)
		- [Definición del problema<a name="Definición_del_problema"></a>](#definición-del-problema)
			- [Story Map<a name="Story_Map"></a>](#story-map)
			- [Product Backlog<a name="Product_Backlog"></a>](#product-backlog)
				- [Epicas<a name="Epicas"></a>](#epicas)
				- [Historias de usuarios<a name="Historias_de_usuarios"></a>](#historias-de-usuarios)
				- [Criterios de aceptacion<a name="Criterios_de_aceptacion"></a>](#criterios-de-aceptacion)
				- [Priorizacion de las tareas<a name="Priorizacion_de_las_tareas"></a>](#priorizacion-de-las-tareas)
		- [Dailys<a name="Dailys"></a>](#dailys-1)
			- [Primera Daily 23/09/2022<><a name="Primera_Daily"></a>](#primera-daily-23092022)
			- [Segunda Daily 30/09/2022<a name="Segunda_Daily"></a>](#segunda-daily-30092022)
			- [Tercera Daily 02/10/2022<a name="Tercera_Daily"></a>](#tercera-daily-02102022)
			- [Cuarta Daily 07/10/22<a name="Cuarta_Daily"></a>](#cuarta-daily-071022)
		- [Sprint Planning<a name="Sprint_Planning"></a>](#sprint-planning)
		- [Horas dedicadas<a name="Horas_dedicadas"></a>](#horas-dedicadas)
		- [Retrospective<a name="Retrospective"></a>](#retrospective)
			- [Reflexion y conclusiones](#reflexion-y-conclusiones)
		- [Valor agregado a la aplicacion](#valor-agregado-a-la-aplicacion)
		- [Cantidad de horas dedicadas a la iteracion por participante <a name="Cantidad_de_horas_dedicadas"></a>](#cantidad-de-horas-dedicadas-a-la-iteracion-por-participante-)
- [Iteracion 2<a name="Iteracion_2"></a>](#iteracion-2)
		- [Objetivo de la iteración<a name="Objetivo-de-la-iteracion"></a>](#objetivo-de-la-iteración)
		- [Realización de tareas del sprint<a name="Realización_de_tareas_del_sprint"></a>](#realización-de-tareas-del-sprint)
			- [Tareas realizadas<a name="Tareas_realizadas"></a>](#tareas-realizadas)
		- [Velocidad del equipo<a name="Velocidad_del_equipo"></a>](#velocidad-del-equipo)
		- [Prototipo generado hasta el momento<a name="Prototipo_generado_hasta_el_momento"></a>](#prototipo-generado-hasta-el-momento)
		- [Validación de usuarios<a name="Validacion_de_usuarios"></a>](#validación-de-usuarios)
		- [Registro Daily<a name="Registro_Daily"></a>](#registro-daily)
		- [Retrospective<a name="Retrospective"></a>](#retrospective-1)
		- [Horas dedicadas <a name="Horas_dedicadas"></a>](#horas-dedicadas-)
	- [Iteracion 3<a name="Iteracion_3"></a>](#iteracion-3)
		- [Objetivo de la iteración<a name="Objetivo-de-la-iteracion_I3"></a>](#objetivo-de-la-iteración-1)
		- [Backlog del sprint<a name="Backlog_I3"></a>](#backlog-del-sprint)
		- [Velocidad del equipo<a name="Velocidad_del_equipo_I3"></a>](#velocidad-del-equipo-1)
		- [Realización de tareas del sprint<a name="Realización_de_tareas_del_sprint_I3"></a>](#realización-de-tareas-del-sprint-1)
			- [Tareas realizadas<a name="Tareas_realizadas_I3"></a>](#tareas-realizadas-1)
			- [Prototipo final<a name="Prototipo_fina_I3"></a>](#prototipo-final)
			- [Validación de usuarios<a name="Validacion_de_usuarios_I3"></a>](#validación-de-usuarios-1)
		- [Transcripción de entrevista para validación<a name="Transcripcion_Entrevista_I3"></a>](#transcripción-de-entrevista-para-validación)
		- [Discusión de feedback<a name="Discucion_feedback_I3"></a>](#discusión-de-feedback)
		- [Registro Daily<a name="Registro_Daily_I3"></a>](#registro-daily-1)
		- [Retrospective<a name="Retrospective_I3"></a>](#retrospective-2)
		- [Horas dedicadas <a name="Horas_dedicadas_I3"></a>](#horas-dedicadas--1)
- [Iteracion 4<a name="Iteracion_4"></a>](#iteracion-4)
	- [Burndown Chart](#burndown-chart)
	- [Reflexion de aprendizajes](#reflexion-de-aprendizajes)
	- [Link a la demo](#link-a-la-demo)
 
---
      

# Definición del marco de trabajo<a name="Definición_del_marco_de_trabajo"></a>

## Adaptaciones del marco SCRUM<a name="Adaptaciones_del_marco_SCRUM"></a>

Para esta iteracion al no ser un proyecto tan demandante, las dailys las haremos cada 3 dias aproximadamente, definiendo el dia concreto en la daily anterior dependiendo del trabajo a realizar entre cada daily. Los eventos de Sprint Review y Sprint Retrospective los haremos en la ultima daily. Al ser un equipo pequeño, todos asumimos el rol de desarrolladores, y un par de integrantes tambien asumieron un rol mas (explicado debajo).

## Definición de roles del equipo<a name="Definición_de_roles_del_equipo"></a>

### Product owner
Quien tiene este rol procura que el equipo Scrum aporte valor al negocio en cuestión. Él representa a los stakeholders o a las partes interesadas.
El Product Owner en este proyecto fue el principal encargado de traducir los requerimientos a User Stories, priorizar estas stories, y de definir las tareas de cada integrante para el siguiente sprint.

### Scrum master
Es el responsable de que se sigan las prácticas y valores descritos en el modelo Scrum. Se puede comparar el papel del Scrum Master al de un coach/mentor que acompañará al equipo hacía el éxito del proyecto. En nuestro proyecto el SM fue la persona que definia cuando iba a ser la siguiente reunion y guardar un registro de la misma.

### Developer
Developer o desarrollador es la persona experta en escribir código, es decir, idear el conjunto de secuencias de órdenes que llevan a un sistema informático a realizar una acción concreta. Los developers, junto con el Product Owner, fueron los que estimaron las tareas y sus criterios de aceptacion.

### Definición de roles

El rol del Product Owner (PO) lo ocupara Martín Gulla, mientras que el rol del Scrum Master (SM) lo ocupara Ignacio Vázquez. Por ultimo para el Development Team (DT),  estara conformado por todos los miembros del equipo: Juan Toledo, Joaquín Sommer, Martin Gulla e Ignacio Vázquez.

El Product Owner fue el principal encargado de traducir los requerimientos a User Stories, priorizar estas stories, y de definir las tareas de cada integrante para el siguiente sprint.

El Scrum master fue la persona que definia cuando iba a ser la siguiente reunion y guardar un registro de la misma.

Los developers, junto con el Product Owner, fueron los que estimaron las tareas y sus criterios de aceptacion.

## Politicas de trabajo<a name="Politicas_de_trabajo"></a>

### Definición de los eventos Scrum<a name="Eventos-Scrum_I3"></a>

#### Dailys<a name="Dailys_I3"></a>

Decidimos realizar dailys cada 4 días porque la profundidad del proyecto no era suficiente para realizar dailys diarias. De esta manera teníamos tiempo para ir realizando los tickets que cada uno tenía asignado. En nuestras dailys cada uno comenta en que tickets estuvo trabajando los días anteriores y en que va a trabajar hasta la próxima daily. También comentamos si estamos bloqueados por algo.

#### Planning/Grooming<a name="Planning_Grooming_I3"></a>

Las planning las realizamos el ultimo día del sprint. Los viernes cada dos semanas. En estas reuniones estimamos y priorizamos las user stories que vamos a realizar en el próximo sprint. Al principio también asignábamos las user stories pero después nos dimos cuenta que no era correcto asignarlas en la planning y era mejor que cada uno se asignara a medida que iba haciendo.  

#### Retro<a name="Retro_I3"></a>

Las retro también las realizamos el ultimo día del sprint. Los viernes cada dos semanas. En las retro nos juntamos todo el equipo y básicamente mencionamos las cosas que funcionaron bien, las cosas que podríamos mejorar y que estuvimos haciendo mal. Luego de analizar las anotaciones anotamos las acciones que debemos hacer para mejorarlas intentando que estas sean medibles.

### Definition of Ready<a name="Definition_of_Ready"></a>

- Cada historia de usuario vista y aceptada por todos los miembros del equipo.
- Las tareas de las que depende estan completadas.
- El prototipo debe de estar listo para ser implementado, detallando los elementos que se deben de implementar.
- Las historias de usuario deben poder ser implementadas en un sprint de 2 semanas como máximo.
- Requisitos no funcionales deben de estar detallados.
- El entorno de pruebas debe de estar definido.
- El equipo conoce cual es la solución a mostrar en el prototipo

### Definition of Done<a name="Definition_of_Done"></a>

- El trabajo de todos los miembros del equipo de desarrollo debe estar completamente integrado en cada iteración.
- El trabajo de cada miembro del equipo debe ser revisado por al menos otro miembro del equipo.
- Todo el equipo cree que cada objetivo/requisito cumple con sus criterios de aceptación. 
- El producto cumple con los estándares de calidad del consumidor. 
- Debe estar todo el proceso completamente documentado.
- El propietario del producto ha aprobado y aceptado lo que se ha hecho en la iteración.

#### Definition of Done de los prototipos<a name="Definition_of_done_de_los_prototipos"></a>

- No hay una pantalla del prototipo a la cual no se pueda llegar/de la cual no se pueda salir.
- Se sigue un estilo similar entre todas las pantallas prototipadas.
- Validado con posibles usuarios si el flujo de la funcionalidad es entendible.


## Repositorio del proyecto<a name="Repositorio_del_proyecto"></a>

### Flujo de trabajo con GIT<a name="Flujo_de_trabajo_con_GIT"></a>

Para el flujo de trabajo con git, decidimos utilizar GitHub Flow con el cual solo tendremos dos ramas, nuestra rama "feature" la cual tendra el nombre de la iteración en curso (iterración 1, iteración 2, etc.) y la rama principal "master". Esta ultima sera solo para mergear las distintas ramas de features al finalizar cada iteración.


### Representacion de flujo de trabajo con git
   
![image](https://i.imgur.com/Kh3adNh.png)

En git se puede ver que no existen las ramas mostradas en la representación debido a que usamos squash and merge que elimina la rama luego del merge.

Mas alla que este flujo sea recomendado cuando las features son de duracion corta (diarias o incluso horas) y aca cada iteracion dura entre 2 a 3 semanas, consideramos que al no contar con un proyecto de código y solo ser proyecto de documentacion este tipo de flujo es el que deberiamos utilizar.

## Desarrollo de prototipo<a name="Desarrollo_de_prototipo"></a>

El prototipo será desarrollado en la herramienta de prototipado de alta fidelidad de Figma,
debido a que el equipo posee conocimientos en esta herramienta, y para los que no 
poseen conocimientos, es facil de aprender y de utilizar.

Link al <a href="https://www.figma.com/proto/n5qQQEU2xJSCWDSANcSIBM/Untitled?node-id=40%3A8&scaling=scale-down&page-id=0%3A1&starting-point-node-id=40%3A8">Prototipo</a>

https://www.figma.com/proto/n5qQQEU2xJSCWDSANcSIBM/Untitled?node-id=40%3A8&scaling=scale-down&page-id=0%3A1&starting-point-node-id=40%3A8

# Iteraciones<a name="Iteraciones"></a>

## Iteracion 1<a name="Iteracion_1"></a>
### Objetivos de la iteracion<a name="Objetivos_de_la_iteracion"></a>

- Creación del Azure board.
- Creación del product backlog a partir de los requerimientos.
- Estudiar posibles competidores.
- Organizacion del equipo en roles

### Identificación del problema a resolver<a name="Identificación_del_problema_a_resolver"></a>

#### Analisis del entorno<a name="Analisis_del_entorno"></a>

##### Entendimiento del MVP<a name="Entendimiento_del_MVP"></a>

El Proyecto se basa en realizar un prototipado de una aplicación enfocada en facilitar la movilidad urbana.
Para esto, nos basaremos en aplicaciones que ya son utilizadas por la mayoría de la población uruguaya.
Este MVP será un prototipo que validara el concepto planteado por los docentes, este pretende llegar a convertirse en una versión competitiva de las aplicaciones antes mencionadas, sumándole varias funcionalidades que estas no contienen y que además podrían mejorar significativamente la experiencia del usuario.

##### Ingeniería inversa sobre aplicaciones conocidas similares<a name="Ingeniería_inversa_sobre_aplicaciones_conocidas_similares"></a>

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


##### Identificación de interesados<a name="Identificación_de_interesados"></a>

En primer lugar, creemos que el MVP debería de enfocarse en el publico más fácil de alcanzar y de validar, este basado en la aplicación que queremos desarrollar sería el que cumpla con las siguientes características
* Persona entre 15 y 30 años (La edad se ampliará a medida que el MVP sea testeado)
* Sin vehículo personal
* Usuario habitual de transporte publico

##### Estudio de competidores<a name="Estudio_de_competidores"></a>

En cuanto a los principales competidores, consideramos que serian apps como STM Montevideo, Como ir o Moovit, ya que son las mas conocidas. Igualmente, existen otras apps no tan conocidas, como puede ser Nextbus Montevideo, las cuales tambien son consideradas competencia pero estas al no ser tan conocidas no las concideramos como competencia importante ya que no tienen un gran peso en el mercado.
Por otra parte, si el día de mañana nuestra app se ampliara al mercado de los omnibus interdepartamentales, una competencia posible podría ser SeguíTuBus la cual solo se dedica a los omnibus que empiezan o terminan su trayecto en la terminal de tres cruces.

#### Funcionalidades por interesado<a name="Funcionalidades_por_interesado"></a>

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

### Definición del problema<a name="Definición_del_problema"></a>

#### Story Map<a name="Story_Map"></a>
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

#### Product Backlog<a name="Product_Backlog"></a>

![image](https://i.imgur.com/HNdqTU0.png)
![image](https://i.imgur.com/wkL7Nod.png)

##### Epicas<a name="Epicas"></a>

Al momento de crear epicas, el criterio que tomamos fue primero tomar cada requerimiento funcional, y agruparlos, por ejemplo, todas las cosas referidas a usuarios, todas las cosas referidas a Lineas de Omnibus, etc. De eesta forma, llegamos a las siguientes epicas, las cuales tienen cada una sus user stories como dependientes de esta

![image](https://i.imgur.com/M45xabQ.png)

##### Historias de usuarios<a name="Historias_de_usuarios"></a>

Luego de dividir en epicas, nos tomamos el tiempo para ver que compone a cada una. Por ejemplo, la epica de usuarios se divide en iniciar sesion, registrarse, editar perfil, cerrar sesion, restaurar contraseña, y el historial de viajes. 
Aqui listamos todas las user stories que creamos (para ver la dependencia epica-historia ver imagen [Product Backlog](#Product_Backlog))
![image](https://i.imgur.com/hjr7CCb.png)
![image](https://i.imgur.com/koIzf57.png)

##### Criterios de aceptacion<a name="Criterios_de_aceptacion"></a>
Cada user story tiene su propio criterio de aceptacion, dependiendo de lo que la tarea conlleve. A continuacion se muestran dos ejemplos de las stories y sus criterios de aceptacion
![image](https://i.imgur.com/baDsFvN.jpg)
![image](https://i.imgur.com/7n465hQ.jpg)

##### Priorizacion de las tareas<a name="Priorizacion_de_las_tareas"></a>

![image](https://i.imgur.com/r4E3QIj.jpeg)

Como se puede ver en la imagen anterior, se realizo una priorizacion de tareas por parte dle Product Owner. Tambien les dimos story points decididos entre todo el equipo de desarrollo junto con el el Product Owner.

### Dailys<a name="Dailys"></a>
#### Primera Daily 23/09/2022<><a name="Primera_Daily"></a>
En esta primra daily, definimos los roles de cada uno de los integrantes, definimos cuales iban a ser las adapataciones necesaria del marco. Ademas definimos las tareas a realizar hasta la proxima daily de cada integrante. Dichas tareas fueron: para Ignacio, Joaquin y Martin, hacer ingenieria inversa de una aplicacion competidora a nuestra aplicacion. Para Juan, fue hacer el entendimiento del MVP.

#### Segunda Daily 30/09/2022<a name="Segunda_Daily"></a>
Discutimos las epicas que fuimos armando a partir de las features presentadas en la letra, y la que decidimos agregar para brindar un valor adicional al producto, y user stories de las que se compone cada una, con su descripcion y criterio de aceptacion de la misma.

#### Tercera Daily 02/10/2022<a name="Tercera_Daily"></a>
Priorizamos las epicas y las user stories, ademas asignamos un storie point a cada user storie. Vinculamos cada user storie con su respectiva epica.

#### Cuarta Daily 07/10/22<a name="Cuarta_Daily"></a>
Completamos definition of ready y definition of done, creamos el story map, y continuamos llenando la documentacion con las actividades que fuimos haciendo a lo largo de la iteracion.

### Sprint Planning<a name="Sprint_Planning"></a>
Realizamos la planning para la siguiente iteracion, en la cual priorizamos las tareas que vamos a realizar.
En primer lugar, asignamos story points a cada user story, ya que aun no habiamos tenido una instancia de valorar cada una. Luego de tener estos valores, realizamos el Story Map, el cual esta documentado anteriormente. 
En esta instancia tambien asignamos las tareas que cada integrante del equipo de desarrollo va a realizar.

### Horas dedicadas<a name="Horas_dedicadas"></a>

Cada integrante hizo aproximadamente una hora por daily ya que esta fue la duración de las mismas, y luego cada uno trabajó entre dos y dos horas y media fueras de las reuniones.

### Retrospective<a name="Retrospective"></a>
Evidencia de Retrospective:
![image](https://i.imgur.com/4A0J8XO.png)
![image](https://i.imgur.com/Z4DplZA.png)

#### Reflexion y conclusiones

A partir de los sticky notes que pusieron notamos que a la hora de realizar tareas, estas se completan de forma exitosa, el mayor problema del equipo se encuentra a la hora de coordinar las reuniones y en el momento de las reuniones, ya que por un motivo u otro, nos terminamos desconcentrando y desviando el tema.

Para solucionar uno de estos problemas, lo que decidimos hacer es programar las reuniones por medios como Google Calendar, para tener un recordatorio de cuando va a ser, y de esta forma reducir las demoras por olvido. En cuanto a las distracciones durante las mismas, intentaremos mejorar esto al momento de reunirnos.

### Valor agregado a la aplicacion

Como se menciono anteriormente, el equipo decidio agregar una funcionalidad extra a las pedidas en la letra, esta siendo todo lo vinculado a la tarjeta STM. Esta idea surgio de la aplicacion competidora Como Ir, la cual permite ver la cantidad de boletos que tiene la tarjeta de alguien. Nosotros decidimos ir un paso mas y permitirle al usuario tambien poder recargar boletos por medio de nuestra aplicacion.

### Cantidad de horas dedicadas a la iteracion por participante <a name="Cantidad_de_horas_dedicadas"></a>

| Nombre | Actividad | Horas |
| --- | --- | --- |
| Ignacio | Ingenieria inversa | 1 |
| Ignacio | Documentacion | 2 |
| Ignacio | Reuniones | 4 |
| Ignacio | Total | 7 |
| Juan | Documentacion | 4 |
| Juan | Reuniones | 4 |
| Juan | Total | 8 |
| Joaquin | Ingenieria inversa | 1 |
| Joaquin | Documentacion | 3 |
| Joaquin | Reuniones | 4 |
| Joaquin | Total | 8 |
| Martin | Ingenieria inversa | 1 |
| Martin | Documentacion | 2 |
| Martin | Reuniones | 4 |
| Martin | Total | 7 |

# Iteracion 2<a name="Iteracion_2"></a>
### Objetivo de la iteración<a name="Objetivo-de-la-iteracion"></a>

El objetivo de esta primera iteración del prototipado es comenzar con el desarrollo de la aplicación, por medio de prototipos creados en Figma. 
Estos prototipos seran validados por usuarios por medio de encuestas, y luego de analizar las respuestas recibidas, se pueden llegar a efectuar cambios a los prototipos ya hechos.


### Realización de tareas del sprint<a name="Realización_de_tareas_del_sprint"></a>

Como se menciono en la iteración pasada, se le asiganaron tareas a cada integrante a desarrollar en esta iteración. Cuando empezamos a ver como vincular las ventanas que hizo cada integrante, nos dimos cuenta que para poder integrar las diferentes funcionalidades, nos faltaba una pantalla principal. Esto nos llevo a crear una nueva tarea en la mitad del sprint para poder cumplir este objetivo.

![image](https://i.imgur.com/8eXdzHU.jpg)

#### Tareas realizadas<a name="Tareas_realizadas"></a>

En la iteración pasada se menciono que se habia dividido las tareas definidas para este sprint, aqui se muestran las tareas realizadas por cada integrante a lo largo de esta iteración.

![image](https://i.imgur.com/yarcNB4.jpg)

### Velocidad del equipo<a name="Velocidad_del_equipo"></a>

La velocidad del equipo (en base a story points) fue de 38, en la imagen aparecen como completadas tarde porque las marcabamos como resueltas, no completadas, debido a que no sabiamos que el azure no contaba las tasks resueltas como que estaban prontas. Cuando nos dimos cuenta de esto, las marcamos como completadas.

![image](https://i.imgur.com/ZjGsbi8.jpg)

### Prototipo generado hasta el momento<a name="Prototipo_generado_hasta_el_momento"></a>

A partir de las tareas, llegamos a el siguiente prototipo (fotos)

![image](https://i.imgur.com/ulr2mqq.jpg)
![image](https://i.imgur.com/A5pqrab.jpg)
![image](https://i.imgur.com/P706NJr.jpg)
![image](https://i.imgur.com/I3szBVo.jpg)
![image](https://i.imgur.com/vzknxEV.jpg)
![image](https://i.imgur.com/rorzg7a.jpg)
![image](https://i.imgur.com/RsprCYz.jpg)
![image](https://i.imgur.com/WI1YqSo.jpg)
![image](https://i.imgur.com/8yQdWXT.jpg)
![image](https://i.imgur.com/Gmh5K3e.jpg)
![image](https://i.imgur.com/Ar5w66z.jpg)
![image](https://i.imgur.com/t1b0ahB.jpg)
![image](https://i.imgur.com/1Eomx91.jpg)
![image](https://i.imgur.com/QlEyq2V.jpg)
![image](https://i.imgur.com/gxYsrrT.jpg)
![image](https://i.imgur.com/yo47XKs.jpg)
![image](https://i.imgur.com/ieu2be0.jpg)
![image](https://i.imgur.com/3knzwoN.jpg)

Luego de validar con los usuarios, nos dimos cuenta que no era muy intuitivo llegar a la información de una linea, esto nos llevo a cambiar ligeramente el diseño, y este quedo de la siguiente forma

![image](https://i.imgur.com/1NyFECy.jpg)
![image](https://i.imgur.com/Q0jaeTf.jpg)
![image](https://i.imgur.com/Hw2wJwB.jpg)
![image](https://i.imgur.com/thDUSUs.jpg)
![image](https://i.imgur.com/8Aw2stE.jpg)
![image](https://i.imgur.com/79mQXKA.jpg)
![image](https://i.imgur.com/mV005BR.jpg)
![image](https://i.imgur.com/wWJxJeq.jpg)
![image](https://i.imgur.com/Z5xlPkI.jpg)
![image](https://i.imgur.com/bD4hOaM.jpg)
![image](https://i.imgur.com/k48MlsJ.jpg)
![image](https://i.imgur.com/qR1oV9z.jpg)
![image](https://i.imgur.com/EYQNlei.jpg)
![image](https://i.imgur.com/c9iiYdz.jpg)
![image](https://i.imgur.com/4q9H4bs.jpg)
![image](https://i.imgur.com/GOUesom.jpg)
![image](https://i.imgur.com/aOUZwkj.jpg)
![image](https://i.imgur.com/RVvt1GT.jpg)

Los cambios son minimos (agregar un icono de información en la sección de lineas), pero creemos que va a ayudar a que los usuarios encuentren esta funcionalidad. Esto se validara en la siguiente iteración.

### Validación de usuarios<a name="Validacion_de_usuarios"></a>

<a href="https://docs.google.com/forms/d/e/1FAIpQLSdz4v2TZwRcXztKyiRj-5eYdIQNu0ji19rUhZ4PKewrkyEjaA/viewform">Encuesta de validacion</a>

| ¿En una escala del 1 al 5 qué te pareció el diseño de la aplicación en general? | ¿Qué cambios harías para mejorarlo? | ¿Le pareció una aplicación sencilla de usar? | Si respondió que no o depende de la sección, ¿Qué fue lo que lo llevo a esa respuesta? | ¿Te gustaría que tuviera alguna otra funcionalidad? | En caso de haber respondido que si en la pregunta anterior, ¿Qué funcionalidad agregaría? | ¿Le seria útil tener los datos de su tarjeta STM (Saldo actual, vencimiento de boletos, etc.) y poder recargar el saldo de la misma? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 5 | - | Si | - | Si | Calificar chófer y guarda de cada línea. Y que cada omnibus tenga su número de referencia para calificar | - |
| 3 | Cuando intente filtrar por linea no funciono bien el prototipo y no entendi que hacer | Si | - | No | - | - |
| 5 | Ninguno | Si | - | No | No | - |
| 4 | Retoques a la interfaz gráfica, sobre todo en "lineas cercanas" los rectángulos azules de las respectivas lineas. | Si | - | Si | Sería util que cuando buscás lineas, te muestre los horarios teoricos de cuando pasa cada bondi | - |
| 3 | Diseño de la información de las lineas | Si | - | Si | Poder ver el trayecto de la linea | - |
| 4 | - | Si | - | No | - | - |
| 5 | ningun cambio | Si | - | No | - | - |
| 4 | - | Si | - | No | - | Si |
| 5 | Ninguno | Si | - | Si | - | Si |
| 4 | - | Si | - | Si | Poder guardar los destinos | Si |
| 5 | - | Si | - | No | - | Si |
| 5 | - | Si | - | No | - | No |
| 3 | Se podria mejorar el diseño | Si | - | No | - | Si |

Analizando los resultados de la encuesta, podemos ver que la mayoría de los usuarios respondieron que le pareció una aplicación sencilla de usar, y que no le gustaría que tuviera alguna otra funcionalidad. Esto nos lleva a pensar que la aplicación cumple con su objetivo, que es ayudar a los usuarios a encontrar la información que necesitan de una forma sencilla y rápida.

Sin embargo, un punto que surgio un par de veces fue el tema del diseño de la aplicacion en si, esto fue algo que anticipamos de antemano ya que ninguno de los integrantes del equipo es diseñador, por lo que no nos dimos cuenta de que el diseño no era muy atractivo. Esto nos llevo a pensar que es necesario que el equipo de diseño de la aplicación se involucre en el proyecto, ya que ellos son los que mejor saben como hacer que la aplicación sea atractiva y facil de usar.

En cuanto a la funcionalidad que le agrega valor al producto, la terjeta STM, la mayoría de los usuarios respondieron que si le seria util, por lo que entendemos que es una buena funcionalidad extra que se puede implementar.

### Registro Daily<a name="Registro_Daily"></a>
![image](https://i.imgur.com/kbVxsl4.png)

Registro de daily 19/10/2022.

Por dificultades del equipo de ahora en adelante cambiaremos la daily a una modalidad de mensajes en la que se dirá, lo que se hizo, lo que se hará y los problemas en los que los miembros se encuentran trancados.


### Retrospective<a name="Retrospective"></a>

Al igual que la iteración pasada, al finalizar las tareas, hicimos una retro del sprint

![image](https://i.imgur.com/Re0bVHS.jpg)

[Información de la retro](./Retrospective/RetroIteracion2ISA1.json)

De esta retro pudimos ver que sigue el problema de la organizacion, y nos planteamos nuevas acciones a tomar.

### Horas dedicadas <a name="Horas_dedicadas"></a>

| Nombre | Actividad | Horas |
| --- | --- | --- |
| Ignacio | Aprendizaje de Figma | 2 |
| Ignacio | Prototipado | 2 |
| Ignacio | Documentacion | 4 |
| Ignacio | Reuniones | 4 |
| Ignacio | Total | 12 |
| Juan | Aprendizaje de Figma | 1 |
| Juan | Prototipado | 2 |
| Juan | Documentacion | 4 |
| Juan | Reuniones | 4 |
| Juan | Total | 11 |
| Joaquin | Aprendizaje de Figma | 2 |
| Joaquin | Prototipado | 2 |
| Joaquin | Documentacion | 4 |
| Joaquin | Reuniones | 4 |
| Joaquin | Total | 12 |
| Martin | Aprendizaje de Figma | 1 |
| Martin | Prototipado | 2 |
| Martin | Documentacion | 4 |
| Martin | Reuniones | 4 |
| Martin | Total | 11 |


## Iteracion 3<a name="Iteracion_3"></a>

### Objetivo de la iteración<a name="Objetivo-de-la-iteracion_I3"></a>

El objetivo de esta segunda iteración del prototipado es completar las feature que no estaban completas y finalizar con las que todabia no se habian comenzado, por medio de prototipos creados en Figma. 
Estos prototipos seran validados por usuarios por medio de encuestas, y luego de analizar las respuestas recibidas, se pueden llegar a efectuar cambios a los prototipos ya hechos.

### Backlog del sprint<a name="Backlog_I3"></a>

Este fue el backlog del sprint pero la foto fue sacada al final de la iteracion. Por esa razon las user stories se encuentran en estado resolved.

![image](https://i.imgur.com/sQyLsHu.png)

### Velocidad del equipo<a name="Velocidad_del_equipo_I3"></a>

El azure muestra como que nuestra velocidad promedio al finalizar la tercera iteracion (contando la segunda) fue de 38 story point por iteracion, esta velocidad se mantuvo constante respecto a la anterior, ya que decidimos intentar dividir las tareas para que haya una cantidad de story point similar entre cada sprint.

![image](https://i.imgur.com/15Rp7Im.jpg)

### Realización de tareas del sprint<a name="Realización_de_tareas_del_sprint_I3"></a>

Las tareas en este sprint se realizaron un poco diferente que a las del primer sprint. En esta iteracion no comenzamos con las user stories asignadas a diferencia de la anterior por lo tanto cada uno podia ir asignandose las que queria. Esta manera fue mejor porque las personas que terminaban rapido podian ir ayudando con las user stories que todavia no se habian empezado.

#### Tareas realizadas<a name="Tareas_realizadas_I3"></a>

Las tareas realizadas en este sprint fueron las siguientes

![image](https://i.imgur.com/y6bG8rN.png)


#### Prototipo final<a name="Prototipo_fina_I3"></a>

Luego de hacer todas las user stories y validar el prototipo con los usuarios llegamos al prototipo final (link al prototipo y fotos)

<a href="https://www.figma.com/proto/n5qQQEU2xJSCWDSANcSIBM/Untitled?node-id=40%3A8&scaling=scale-down&page-id=0%3A1&starting-point-node-id=40%3A8">https://www.figma.com/proto/n5qQQEU2xJSCWDSANcSIBM/Untitled?node-id=40%3A8&scaling=scale-down&page-id=0%3A1&starting-point-node-id=40%3A8</a>

![image](https://i.imgur.com/VmbntNz.png)
![image](https://i.imgur.com/aWfPFm0.png)
![image](https://i.imgur.com/CjPVS3O.png)
![image](https://i.imgur.com/6KpNJKs.png)
![image](https://i.imgur.com/wbyjgvS.png)
![image](https://i.imgur.com/KyUK2Vz.png)
![image](https://i.imgur.com/tdzCRgu.png)
![image](https://i.imgur.com/1OvFo24.png)
![image](https://i.imgur.com/bJgO6UF.png)
![image](https://i.imgur.com/seCnGHk.png)
![image](https://i.imgur.com/5e6tluP.png)
![image](https://i.imgur.com/70b8ISw.png)
![image](https://i.imgur.com/Zs0hvfe.png)
![image](https://i.imgur.com/aQl8thp.png)
![image](https://i.imgur.com/gHXRRsK.png)
![image](https://i.imgur.com/M3tpxuV.png)
![image](https://i.imgur.com/xO1uiI3.png)
![image](https://i.imgur.com/JHc8TzW.png)
![image](https://i.imgur.com/1P3Mlqg.png)
![image](https://i.imgur.com/M0IdfJA.png)
![image](https://i.imgur.com/HAe4v4M.png)
![image](https://i.imgur.com/gKBUuuS.png)
![image](https://i.imgur.com/EMZ6V6R.png)
![image](https://i.imgur.com/iR1lS4k.png)
![image](https://i.imgur.com/oAKvgKQ.png)
![image](https://i.imgur.com/DX40pcD.png)
![image](https://i.imgur.com/VYnOKGQ.png)
![image](https://i.imgur.com/s6HNSwo.png)

#### Validación de usuarios<a name="Validacion_de_usuarios_I3"></a>

<a href="https://docs.google.com/forms/d/e/1FAIpQLSdz4v2TZwRcXztKyiRj-5eYdIQNu0ji19rUhZ4PKewrkyEjaA/viewform">Encuesta de validacion</a>

[Resultados de Encuesta de validacion](./Encuestas/EncuestaValidacionDeUsuarios.xlsx)

### Transcripción de entrevista para validación<a name="Transcripcion_Entrevista_I3"></a>

> Encuestador: Hola buenas tardes, te envío el link de la aplicación que te comente anteriormente, para que nos puedas dar algo de feedback.

> Encuestado: si por supuesto enviame todo.

> Encuestador: Aqui te dejo el link: https://www.figma.com/proto/n5qQQEU2xJSCWDSANcSIBM/Untitled?node-id=40%3A8&scaling=scale-down&page-id=0%3A1&starting-point-node-id=40%3A8

> Encuestador: Te comento que esto es simplemente un prototipo para que el usuario pueda entender el funcionamiento final de la aplicación, por lo que esto puede y seguramente tendrá cambios.

> Encuestador: También te pido por favor que me comentes si tuviste alguna complicación con el prototipo, si la interfaz es cómoda e intuitiva y si le harias algun cambio o le agregarías algo a la aplicación final

> Encuestado: Cuando intente filtrar por línea no funcionó bien el prototipo y no entendi que hacer

> Encuestado: Retoques a la interfaz gráfica, sobre todo en "líneas cercanas" los rectángulos azules de las respectivas líneas.

> Encuestado: Calificar chófer y guarda de cada línea. Y que cada ómnibus tenga su número de referencia para calificar además sería útil que cuando buscás líneas, te muestre los horarios teóricos de cuando pasa cada bondi

> Encuestador: Te agradezco enormemente por este feedback, son un montón de puntos en los que no pensamos, mil gracias.

> Encuestado: Por nada.

### Discusión de feedback<a name="Discucion_feedback_I3"></a>

En primer lugar obtuvimos el comentario “Cuando intenté filtrar por línea no funcionó bien el prototipo y no entendí qué hacer”.
Con respecto a esto decidimos no prestar mucha atención ya que es una funcionalidad básica y que nos dio problemas por falta de conocimiento sobre figma, por lo que tomamos nota como cambio a mejorar en el prototipo pero no en la aplicación final.

Siguiente comentario: “Retoques a la interfaz gráfica, sobre todo en "líneas cercanas" los rectángulos azules de las respectivas líneas.” 
Aquí tomamos nota, y probamos un par de implementaciones para líneas cercanas, cambiamos el prototipo y será necesario un nuevo testeo.

“Calificar chófer y guarda de cada línea. Y que cada ómnibus tenga su número de referencia para calificar además sería útil que cuando buscás líneas, te muestre los horarios teóricos de cuando pasa cada bondi”

Este comentario ha sido uno de los mejores en nuestro feedback, consideramos que es algo relativamente simple de implementar y que le daría una distinción notoria a la aplicación. Sería buena idea agregar esto al sprint backlog, para una futura implementación. 


### Registro Daily<a name="Registro_Daily_I3"></a>

Finalmente decidimos seguir haciendo dailys por videollamada ya que nos parecio mas facil de cumplir que mandar un mensaje y la facilidad de comunicacion es mayor por videollamada. 

Registro de daily 25/10/2022.

![image](https://i.imgur.com/X73noC6.png)

Registro de daily 29/10/2022.

![image](https://i.imgur.com/frIDOCi.png)

Registro de daily 1/11/2022.

![image](https://i.imgur.com/Yc4BiI6.png)


### Retrospective<a name="Retrospective_I3"></a>

Al igual que la iteración pasada, al finalizar las tareas, hicimos una retro del sprint

![image](https://i.imgur.com/OFTeJrp.png)

[Información de la retro](./Retrospective/RetroIteracion2ISA1.json)

De esta retro pudimos ver que sigue el problema de la organizacion.

### Horas dedicadas <a name="Horas_dedicadas_I3"></a>

| Nombre | Actividad | Horas |
| --- | --- | --- |
| Ignacio | Prototipado | 2 |
| Ignacio | Documentacion | 4 |
| Ignacio | Reuniones | 4 |
| Ignacio | Total | 10 |
| Juan | Prototipado | 2 |
| Juan | Documentacion | 4 |
| Juan | Reuniones | 4 |
| Juan | Total | 10 |
| Joaquin | Prototipado | 2 |
| Joaquin | Documentacion | 4 |
| Joaquin | Reuniones | 4 |
| Joaquin | Total | 10 |
| Martin | Prototipado | 2 |
| Martin | Documentacion | 4 |
| Martin | Reuniones | 4 |
| Martin | Total | 10 |


# Iteracion 4<a name="Iteracion_4"></a>

## Burndown Chart 

![image](https://i.imgur.com/iiWlPHS.png)

Como se puede observar burndownchart no tiene los datos correctos, ya que a la hora de marcar como completadas la tareas realizadas la marcamos como "Resolved" y no como "Colsed" lo que causo que la grafica tenga grandes mesetas y bajadas de golpe, ya que cuando se les puso closed fue a todas juntas el mismo día causando las abruptas bajadas que tiene. El Azure para hacer estos calculos se fija en las tareas que estan "Closed" y esto no lo sabiamos al momento de ir cerrando las tareas. 

## Reflexion de aprendizajes

Una de las cosas que aprendimos fue a trabajar en equipo, ya que nunca habiamos trabajado en equipo de esta manera para hacer un obligatorio, y nos parecio muy interesante y nos sirvio para aprender a trabajar en equipo y a comunicarnos mejor. Usualmente los obligatorios son de dos o tres personas, y nunca habiamos trabajado en equipo de 4 personas, por lo que fue una experiencia muy buena porque organizarnos y comunicarnos fue algo que nos costo bastante, pero en cada iteracion fuimos mejorando y aprendiendo lo que nos funcionaba y lo que no. En los equipos de trabajo que tengamos en el futuro, nos va a servir mucho lo que aprendimos en este proyecto porque usualmente son equipos mas grandes donde hay que comunicarse y organizarse bien.

Quiza lo mas importante fue la gran experiencia de utilizar una metodologia agil para hacer el proyecto. Aprendimos a utilizarla y a utilizar las herramientas que nos brinda. Tambien aprendimos a hacer dailys, que nos permitieron comunicarnos y saber que estabamos haciendo cada uno, y que nos permitio saber que estabamos haciendo bien y que estabamos haciendo mal. Tambien aprendimos a hacer retros, que nos permitieron mejorar en cada iteracion y a mejorar la forma en la que trabajabamos. Hoy en dia casi todos los proyectos se hacen con metodologias agiles, por lo que es vital tener buenos conocimientos de todas las reglas y etapas que estas metodologias tienen. Esto nos va a permitir manejarnos bien en un equipo de trabajo. Todavia hay cosas que podemos mejorar, como por ejemplo hacer mejores user stories, pero por lo menos sabemos que tenemos que mejorar para poder hacerlo mejor en el futuro.

Tambien nos llevamos muchismos conociemientos adquiridos de distintas herramientas que usamos en el proyecto. Por ejemplo, aprendimos a usar Azure DevOps, que nos permitio tener un seguimiento de las tareas que teniamos que hacer y de las que ya estaban hechas. Tambien aprendimos a usar Figma, que nos permitio hacer el prototipo de la aplicacion y tambien la existencia de paginas como Metroretro que nos permitio hacer las retros de las iteraciones. Todas estas herramientas son de las mas utilizadas en el mundo laboral, por lo que es muy importante saber que existen y poder manejarlas a cierto nivel.

La idea de hacer una aplicacion sobre el trasporte publico en si no es nueva pero nos parecio muy facil para aplicar lo que aprendimos en la materia. Al no ser una idea nueva nos costo poder elegir que funcionalidades agregarle para lograr darle ese toque de innovacion que se pedia en el proyecto. Justamente pensando esto fue que nos dimos cuenta que el hacer un proyecto no es solo hacer lo que te piden sino que tambien hay que agregarle esa cosa distinta para sobresalir. Esto nos parecio muy interesante y nos sirvio para aprender a pensar de una manera distinta y tener otra cabeza cuando el dia de mañana tengamos que hacer un proyecto para un cliente.

## Link a la demo

Se realizo una demo del prototipo generado al finalizada la iteración 3.
<a href="https://web.microsoftstream.com/video/0a814414-a764-478c-8843-d029d27ca0b8">https://web.microsoftstream.com/video/0a814414-a764-478c-8843-d029d27ca0b8</a>


