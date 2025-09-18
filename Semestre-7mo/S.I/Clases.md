# Seguridad Informática

**Profesor:** `Romel Acosta Felix`

"Si no sabes yo te ense~no,  su no puede yo te ayudo y si no quieres, pues mucho gusto"

**Objetivo:** `Desarrlloar planes de seguridad basados en normas y estandares internacionales que puedan asegurar un seguridad maxima en la medida de lo posible`

**Temario**
1. Introducción a la Seguridad Informática. 
	1. El valor de la información. 
	2. Definición de seguridad informática. 
	3. Visión Global de la Seguridad Informática 
	4. Objetivos de la seguridad informática. 
	5. Posibles riesgos. 
	6. Técnicas de aseguramiento del sistema. 
	7. Principales amenazas por internet. 
2. Directrices de Seguridad Informática. 
	1. Criptografía. 
	2. Esteganografía. 
	3. Certificados y Firmas Digitales. 
	4. Hacking ético. 
	5. Cómputo forense.
	6. IDS y IPS. 
	7. Seguridad en Linux 
	8. Seguridad en Wi-Fi. 
3. Firewalls como Herramientas de Seguridad. 
	1. Tipos de firewall: de software y de hardware. 
		1. Firewall de capas inferiores. 
		2. Firewall de capa de aplicación. 
		3. Firewall personal. 
	2. Ventajas de un firewall. 
	3. Limitaciones de un firewall. 
	4. Políticas del firewall. 
	5. Enlaces externos. 
4. Norma ISO 27001:2005. 
	1. Evolución de la familia ISO 27000. 
	2. Objetivos de control y controles. 
		1. Política de seguridad. 
		2. Organización para la seguridad de la información. 
		3. Administración de activos. 
		4. Seguridad de los recursos humanos. 
		5. Seguridad física y ambiental. 
		6. Gestión de las comunicaciones y operaciones. 
		7. Control de accesos. 
		8. Adquisición, desarrollo y mantenimiento de sistemas de información. 
		9. Gestión de incidentes de la seguridad de la información. 
		10. Gestión de la continuidad del negocio. 
		11. Cumplimiento.

**Criterios de evaluacion**

| **Criterios de evaluación**          | valor |
|--------------------------------------|-------|
| Examen                               | 30    |
| Analisis o ensayo                    | 20    |
| Mapa mental                          | 20    |
| Mapa conceptual                      | 20    |
| Participacion                        | 10    |



---

## Clase 2025-08-19

### Cosas a investigar

Investigar el valor de la información
Definición de seguridad informatica
Vision global de la seguridad informatica

## Clase  2025-08-26

1.1

La informacion es un conjunto de datos oorganizados y procesados qye tienene significado y utilidad para quien los recibe

Los datos por si mismo son simples hechos o cifras

la informacion como un recurso

Hoy en dia la informacion **es considerada un activo estrategico**, comparable con los recursos materiales, financieros o humanos de una organizacion
- Permite tomar decisiones acertadas
- aporta ventaja competitiva
- tiene valor economico y social

Carateristicas del valor de la informacion

- Confidencias
	- solo para personal autorizado
- Integra
	- sin modificaciones y completa
- Disponible
	- Accesible cuando se necesite
- Autenticidad
	- Debe poder verificarse que la informacion es confiable
- Valor temporal
	- durante que periodo es valioso

amenzas al valor de la informacion
- Acceso no autorizado - Robo de datos y espionaje
- Perdida o devolucion - fallos tecnicos, errores humanos o desastres
- alteracion maliciosa - modificaciones de archivos y fraudes
- Divulgacion indebida - filtraciones de datos privados o confidenciales

Importancia de proteger la informacion

- Evitar fraudes, robo de identidad y espionaje
- Garatizar la continuidad de operaciones
- Mantener la confianza de clientes
- Cumplir con leyes de proteccion de datos y normativas de seguridad

1.2 Definicio de seguridad informatica

La seguridad informatica es el conjunto de medidas, tecnicas y practucas destinadas a proteger la informacion, los sitemas y los recurss tecnologicas frente a amenazas riesgos y ataques

su propositos
- Se mantega la informacion segura frente a accesos no autorizados
- que los datos no sean alterados de manera indebida
- que esten disponibles para los usuarios y que sean legitimos

1.3 vision global de la seguridad informatica

1. Personas
	1. Los usuarios son el eslabon mas debil,
	2. requieren capacitacion y consiencia del entorno de seguridad
2. tecnologias
	1. Computadoras, redes, servidores, dispositivos moviles y la nube
	2. Proteccion con antiviruz firewalls cifrado y copias de seguridad
3. procesos y normativas
	1. Establecer politicas de seguridad y protocolos de acceso
	2. Cumplir con leyes de proteccion de datos
4. amenzas globales
	1. Malware
	2. Hacker maliciosos
	3. Robo de identidad y fraudes eletronicos
	4. ataques a infraestructruras criticas

1.4 Objetivos de la seguridad informática. 

el objetivo de la seguridad informatica es pues protejer datos, pero para verlo de una menera mas simple se dedica a que la informacion cumpla con los siguientes puntos conocidos como CIA

- Cofidencial
	- solo los usuarios elegidos deben poder acceder a la informacion
- integridad
	- los datos deben mantenerse completos, correctos y sin alteraciones
- disponibilidad
	- se debe asegurar que los servicios siempre deben estar accesibles cuando se requiera

algunos autores hablan de agregar

Autenticidad  - Verifica la identidad del sistema y el usuario
no repudio    - Evita que otros nieguen la accion o inaccion en un proceso

1.5 Posibles riesgos. 

hoy en dia respecto a la seguridad informatica, cualquier informacion en la web es pirateable o como minimo blanco de ataque, pero eso no implica que debas dejarla disponible para cualquiera sin embargo siempre va a haber amenzas, asi que lo mejor es conocer dichas amenzas y saber que hacer en dichas situaciones, todo usualmente va nacer cuando algo de los 3 pilares principales flaquea, es decir la confidencialidad, integridad y disponibilidad, esto se puede deber a lo siguiente:

- Error humano
	- mala configuracion de la privacidad
	- perdida de contraseña
	- descuido al manejar datos
- Por Ataques Externos
	- hackers
	- malwares
	- phishing
-  Fallas de hardware y/o Software
	- daños de discos
	- sistemas operativos mal diseñados o corruptos, entra el programa mal diseño
- Desastres naturales
	- Incendios, inundaciones, sismos que afecten los equipos

1.6 Técnicas de aseguramiento del sistema. 

hay varias tecnicas, una de ellas es la siguiente:

- Contrase~nas seguras
	- son medidadas y procedimientos deise~nados para protejer los sistemas de informacion complejas y cambios periodicos
- Control de Accesos
	- Aolo usarios con acceso a ciertos recursos
- Antivirus y antimalware
	- Deteccion y elimnacion de programas dañinos
- tokens
	- One Use Password
- Copias de seguridad
	- raespaldo de informacion regularmente para evitar perdida de datos
- Actualizacion de software
	- Mantener sistemas operativos y programas al dia para evitar vulnerabilidades
- Cifrado de datos
	- Protege la informacion durante su almacenamiento o transmicion
 1.7 Principales amenazas por internet. 

- phishing
	- Mensajes falsos que buscam obtener informacion personal o confidencial
- malware
	- viruz
	- troyano
	- rasonware
- Robo de Identidad
	- Usurpacion de datos personales para cometer fraudes
- DDoS
	- Inundacion de peticiones de servicios s un servidor
- Spyware
	- Recopilacion de datos sin concentimiento

## Clase 2025-09-04

1.1



1.2 



1.3

