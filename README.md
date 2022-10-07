## Universidad ORT Uruguay

# Obligatorio de Ingenieria de Software Agil 1


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

- [Definición del marco de trabajo](#Definición_del_marco_de_trabajo)
	- [Adaptaciones del marco SCRUM](#Adaptaciones_del_marco_SCRUM)
	- [Definición de roles del equipo](#Definición_de_roles_del_equipo)
	- [Politicas de trabajo](#Politicas_de_trabajo)
		- [Definition of Ready](#Definition_of_Ready)
		- [Definition of Done](#Definition_of_Done)
	- [Repositorio del proyecto](#Repositorio_del_proyecto)
		- [Flujo de trabajo con GIT](#Flujo_de_trabajo_con_GIT)
	- [Desarrollo de prototipo](#Desarrollo_de_prototipo)
- [Iteración 1](#Iteración_1)
	- [Identificación del problema a resolver](#Identificación_del_problema_a_resolver)
		- [Analisis del entorno](#Analisis_del_entorno)
			- [Entendimiento del MVP](#Entendimiento_del_MVP)
			- [Ingeniería reversa sobre aplicaciones conocidas similares](#Ingeniería_reversa_sobre_aplicaciones_conocidas_similares)
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
    - [Retrospective](#Retrospective)
 
---
      

# Definición del marco de trabajo<a name="Definición_del_marco_de_trabajo"></a>

## Adaptaciones del marco SCRUM<a name="Adaptaciones_del_marco_SCRUM"></a>

Para esta iteracion al no ser un proyecto tan demandante, las dailys las haremos cada 3 dias proximadamente, definiendo el dia concreto en la daily anterior dependiendo del trabajo a realizar entre cada daily. Los eventos de Sprint Review y Sprint Retrospective los haremos en la ultima daily. 

## Definición de roles del equipo<a name="Definición_de_roles_del_equipo"></a>

Para la definición de roles del equipo, nos dividimos de la siguiente manera:
El rol del Product Owner (PO) lo ocupara Martín Gulla, mientras que el rol del Scrum Master (SM) lo ocupara Ignacio Vázquez. Por ultimo para el Development Team (DT), al se un equipo pequeño, este estara conformado por todos los miembros del equipo: Juan Toledo, Joaquín Sommer, Martin Gulla e Ignacio Vázquez.

## Politicas de trabajo<a name="Politicas_de_trabajo"></a>

### Definition of Ready<a name="Definition_of_Ready"></a>

- Cada historia de usuario vista y aceptada por todos los miembros del equipo
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


## Repositorio del proyecto<a name="Repositorio_del_proyecto"></a>

### Flujo de trabajo con GIT<a name="Flujo_de_trabajo_con_GIT"></a>

Para el flujo de trabajo con git, decidimos utilizar GitHub Flow con el cual solo tendremos dos ramas, nuestra rama "feature" la cual tendra el nombre de la iteración en curso (iterración 1, iteración 2, etc.) y la rama principal "master". Esta ultima sera solo para mergear las distintas ramas de features al finalizar cada iteración.
Mas alla que este flujo sea recomendado cuando las features son de duracion corta (diarias o incluso horas) y aca cada iteracion dura entre 2 a 3 semanas, consideramos que al no contar con un proyecto de código y solo ser proyecto de documentacion este tipo de flujo es el que deberiamos utilizar.

## Desarrollo de prototipo<a name="Desarrollo_de_prototipo"></a>

El prototipo será desarrollado en la herramienta de prototipado de alta fidelidad de Figma,
debido a que el equipo posee conocimientos en esta herramienta, y para los que no 
poseen conocimientos, es facil de aprender y de utilizar.


# Iteración 1<a name="Iteración_1"></a>

## Identificación del problema a resolver<a name="Identificación_del_problema_a_resolver"></a>

### Analisis del entorno<a name="Analisis_del_entorno"></a>

#### Entendimiento del MVP<a name="Entendimiento_del_MVP"></a>

El Proyecto se basa en realizar un prototipado de una aplicación enfocada en facilitar la movilidad urbana.
Para esto, nos basaremos en aplicaciones que ya son utilizadas por la mayoría de la población uruguaya.
Este MVP será un prototipo que validara el concepto planteado por los docentes, este pretende llegar a convertirse en una versión competitiva de las aplicaciones antes mencionadas, sumándole varias funcionalidades que estas no contienen y que además podrían mejorar significativamente la experiencia del usuario.

#### Ingeniería reversa sobre aplicaciones conocidas similares<a name="Ingeniería_reversa_sobre_aplicaciones_conocidas_similares"></a>

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

Todas las funcionales de la aplicación son pensadas para el usuario final,
el cual es el cliente de la aplicación, especificado en la parte de identificación de interesados.


- Dueño del producto

La funcionalidad de STM al ser una funcionalidad agregada a lo que fue solicitado, 
se considera como una funcionalidad de interés para el dueño del producto.


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

## Retrospective<a name="Retrospective"></a>
Evidencia de Retrospective:
![image](https://i.imgur.com/4A0J8XO.png)
![image](https://i.imgur.com/Z4DplZA.png)
