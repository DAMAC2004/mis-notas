# Herramientas de Desarrollo de Aplicaciones Web

**Profesor:** `Jesus Manuel May Leon`

**Objetivo:** `Conocer diferentes herramientas de desarrollo web`

**Temario**
- 1.1 Conceptos Basicos de Ingenieria Web
- 1.2 Tipos de aplicaciones web
- 1.3 Caracteristicas de una aplicacion web
- 1.4 Arquitectura de aplciaciones web
- 1.5 Plataforma integral para el desarrollo web
- 1.6 Tipos de servidores web

---

## Clase 2025-08-18

### Cosas a investigar
- que es la ingenieria web
- que es la ingenieria del software
- que metodologia se usan para el desarrollo web
- api web con codefirst
- instalar sql managment studio 21 y similares para linux(arch)


## Clase 2025-08-20

### 1.1 Conceptos de ingenieria de software

`"La ingenieria web es el cimiento de la construccion digital"`

adapta los principios del software al dominio especifico de la web, abordando los desafios y carateristicas unicas que presatan soluciones basadas en un navegador web

la ingenieria web es la aplicacion de un enfoque sistematico, diciplinado y cuantifcable en el desarrollo, es una rama de especializacion del desarrollo de software, ambas comparten las misma dicilina base a 4 puntos importantes

- Dispoibilidad y escalabilidad
	- Las aplicaciones web deben estar disponibles 24/7
- Ciclos de desarrollo rapido
	- El entorno web es dinamico y competitivo lo que a menudo requiere ciclos de desarrollo mas cortos y entregas incrementales
- Multidiciplinar
	- involucra una fama mas amplia de perfiles inclyendo diseado interfazes de usuario
- Seguridad
	- Se concentran en la proteccion de datos y la seguirdad de la informacion, en un mundo donde la informacion es igual a dinero

**Ciclo de vida del desarrollo web**

1. Planificación y definición de requisitos
2. Análisis
3. Diseño 
4. Diseño de la arquitectura 
5. Desarrollo e implementacion
6. Pruebas
7. Despliegue
8. Mantenimiento

Todo esto puede asemejarse a las 6 D
1. Descripcion del problema
2. Definicion del seoftware
3. Diseno de la solucion
4. Desarrollo de la solucion
5. Depuracion y pruebas
6. Documentacion

### 1.2 Tipos de aplicaciones web

#### Aplicaciones web estaticas

Se componene principalmente de los 3 pilares principales, que son html, css y js, tambien son las primeras paginas web que surgieron, tecnicamente las mas seguras ya que no exponen nada por ser simples

#### Aplicaciones web dinamicas

aqui ya usan mas tecnologias, como lo son php, y generalmete son parte de un sistema cliente servidor, usan lenguaje del lado del servidor

#### APlicaciones web de pagina unica

si usan base de datos pero no ocupan recargar pagina para actualizar datos en la pagina, esto se logra mediante framework y API's para la carga de contenido de una manera mas satisfactoria, proporcionando de esta manera mas fluidez a la experiencia del usuario

#### Aplicaciones web de multiples paginas
Comunes en giros como el E-Commerce, racional y estructural en cada accion o enlace puede abrir otra instacia 

#### Aplicaciones web Progresivas(PWA)
COmbinana las carateristicas web  nativa, esto logra que no se necesite de internet para que algunas funciones puedan usarse como las notificaciones 

#### Aplicacaiones web sociales
manejo de base de dtos, notifiaciones, es necesario aclarar todo esto?

---

## Clase 2025-08-22

### 1. 

Que es una aplicacion web?

**Beneficios fundamentales de las aplicaciones web**

- Accecibilidad universal
- Desarrollo eficiente
- Estabilidad flexible

**Componentes principales de la Arquitectura web**

- Capa de presentacion
- Capa de aplicacion
- Capa de datos
- Infraestrutura y Comunicacion

**Modelos Arquitectonicos Comunes**

- Monolitica
- EN capas(3 usualemente)
- Microservicios

## Clase 2025-08-25

Los clientes hacen peticiones de información al servidor a partir del protocolo conocido como http y el servidor le devuelve la información en html estático puro

dentro de esta lógica existen muchas metodologías, conceptos e información de por medio para que esto ocurra

por ejemplo aquí podemos hablar de lo siguiente:

- Backend
	- hablamos de cosas como el servidor, donde este puede estar sostenido mediante Apache o IIS
	- puede contar con módulos como lo son php, asp, BD, Mysql, oracle
- Frontend
	- Frameworks
	- protocolos de peticion de informacion
-  Tipos de peticiones HTTP
	- GET
	- PUT
	- POST
	- DELETE

- Arquitectura Horizontal
	- Caracterizado por una estrctura smple y plana
	- Se plasma en una sola pagina
	- No es escalable
- Arquitectura jerarquica
	-  Estrutura ramificada con secciones
	- hace que la info sea mas facil de encontrar
	- ayuda a los motores de busqueda a entender la relevancia de los contenidos
- Arquitectura Silo
	- Hace referencia a una estructura web que tiene el propósito de unificar y agrupar el contenido  por temáticas únicas de forma estructurada y ordenada
	- El contenido se organiza en _silos_ de palabras clave para ayudar a incrementar la visibilidad de estas keywords.

---
## Clase 2025-08-29

UN servidor web es un software que recibe peticiones htttp

**Servidores**

- Apache
	- es un software que sirve para recibir peticiones de los navegadores y responder con otras paginas web y /o recursos
	- Carateristicas
		- codigo abierto
		- multiplataforma
		- basado en modulos
		- muy usado en hosting
		- compatibilidad con multiples lenguajes
	- como funciona?
		- no alcanzo
- Ngix
	- Funciona similar que apache, pero hecho para ser mas ligero y rapido que apache
	- Caratristicas
		- ALto rendimiento
		- ligero
		- servidor proxy
		- Balanceador de carga
		- compatibilidad de pagina estaticas y dinamicas
	- Como funciona
		- Peticion hhtp
		- recibe peticion
		- si es estatico se entrega directo pero si es dinamico, envia la peticion a otro servicio y lo devuellve
		- cliente recibe pagina web
- Internet Information services
	- z
	- Carateriticas
		- Desarrollado por microsoft
		- integracion con Microsoft
		- SOporte de multiples protocolos
		- Gestion sencilla
		- Escalabilidad
	- Funciona
		- peticion http
		- iis recibe solicitud
		- si es estatico es directo, si es dinamico para la peticion al motor correspondiente y pasa la respuesta
		- El cliente recibe la pagina
- OpernRsty
	- Es un servidor web con una arquitectura basada en eventos, hecho para contrui aplicaciones y servicios web escalables
	- Carateristicas
		- Arquitectura basada en eventos
		- Alto rendimiento
		- Alta concurrencia
	- Como funciona
		- Basada en Ngix
		- Procesamiento de solicitudes: cuando un cliente envia una solicitud htto, ngix la recibe y la pasa atraves de serie de fases de procesamiento
		- lenguaje de programacion lua
		- ejecucion de codigo lua
- Gws
	- Seejecutan en sistemas operativus basados en Unix
- Servidor Node.JS
	- El servidor escucha solicitudes http
	- recibe la peticion, ejecuta codigo y devuelve la pagina

## Clases 2025-09-05

exposicion

## Clases 2025-09-17

Podemos decir que la IA desde que llego, ha cambiado la formas de trabao como se conoce, permite anlaizar patrones de uso, mejorar la experiencia de usaurio y optimizar el renfimmiento de los sitios

Su aplicacion combina creatuvudad analisis de datos y automatizacion

IA en el diseño de interfaces

- genera de manera automartica de prototipos y diseños
- Soporte para UX/UI con pruebas automaticas de usabilidad
- Creacion de interfaces personalizadas segun las necesidades del usuario
- Estudia el comportamiento de los usuarios

Algunas plataformas son:
- figma
- adobe sensei

la ia es una herramienta clave que empezaemos a usar mas y mas, asi que hay que integrar estas herramientas
